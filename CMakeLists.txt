project (IOT)
add_executable(main main.cpp)
TARGET_LINK_LIBRARIES(main cgicc wiringPi pthread crypt rt wiringPi)
