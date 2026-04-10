include(FetchContent)

FentchContent_Declare(
eigen
GIT_REPOSITORY https://gitlab.com/libeigen/eigen.git
GIT_TAG        3.4.0
GIT_SHALLOW    TRUE
)
FetchContent_MakeAvailable(eigen)
