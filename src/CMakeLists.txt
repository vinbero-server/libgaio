add_library(gaio SHARED gaio.c)
set_target_properties(gaio PROPERTIES PUBLIC_HEADER "gaio.h")
install(TARGETS gaio DESTINATION /usr/local/lib/
	PUBLIC_HEADER DESTINATION /usr/local/include/)