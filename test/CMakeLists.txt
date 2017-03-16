include_directories(${CMAKE_SOURCE_DIR}/src)
include_directories(${CMAKE_SOURCE_DIR}/third_party/catch)

add_executable(simple_factory_test simple_factory/client_test.cc)
add_executable(strategy_test strategy/client_test.cc)
add_executable(decorator_test decorator/client_test.cc)
add_executable(proxy_test proxy/client_test.cc)
add_executable(builder_test builder/client_test.cc)
add_executable(observer_test observer/client_test.cc)
