if (NOT MINGW_BUILD)
  add_subdirectory(Common/)
  add_subdirectory(Linux/)
  add_subdirectory(Tools/)
endif()
