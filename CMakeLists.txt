project (ttftobmp)


add_executable(ttftobitmap main.cc)

target_link_libraries (ttftobitmap SDLmain)
target_link_libraries (ttftobitmap SDL)
target_link_libraries (ttftobitmap SDL_ttf)
