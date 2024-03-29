# message(FATAL_ERROR "请修改 stbiw/CMakeLists.txt！要求生成一个名为 stbiw 的库")
add_library(stbiw STATIC stb_image_write.cpp) # 构建子模块
target_include_directories(stbiw PUBLIC .) # 添加头文件搜索目录