# CMakeList.txt : CMake project for CMakeProject01, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (CMakeProject01 "CMakeProject01.cpp" "CMakeProject01.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET CMakeProject01 PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
