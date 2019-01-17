set(IMGUI_PATHS imconfig.h imgui.cpp imgui.h imgui_internal.h imgui_draw.cpp imgui_widgets.cpp imstb_rectpack.h imstb_textedit.h imstb_truetype.h imgui_impl_glfw.cpp imgui_impl_glfw.h imgui_impl_opengl3.cpp imgui_impl_opengl3.h)

set(IMGUI_HEADERS ${CMAKE_CURRENT_LIST_DIR} PARENT_SCOPE)

add_library(imgui STATIC ${IMGUI_PATHS})
