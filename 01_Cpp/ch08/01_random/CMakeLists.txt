
cmake_minimum_required(VERSION 2.8)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -W -O2 -std=c++11")

add_executable(01_random_device                         01_random_device.cpp)
add_executable(02_seed_seq                              02_seed_seq.cpp)
add_executable(03_default_random_engine                 03_default_random_engine.cpp)
add_executable(04_uniform_int_distribution              04_uniform_int_distribution.cpp)
add_executable(05_uniform_real_distribution             05_uniform_real_distribution.cpp)
add_executable(06_uniform_int_distribution_for_cards    06_uniform_int_distribution_for_cards.cpp)
add_executable(07_standard_uniform_distribution         07_standard_uniform_distribution.cpp)
add_executable(08_normal_distribution                   08_normal_distribution.cpp)
add_executable(09_normal_distribution_histogram         09_normal_distribution_histogram.cpp)
add_executable(10_lognormal_distribution                10_lognormal_distribution.cpp)
add_executable(11_lognormal_distribution_histogram      11_lognormal_distribution_histogram.cpp)
add_executable(12_discrete_distribution                 12_discrete_distribution.cpp)
add_executable(13_piecewise_constant_distribution       13_piecewise_constant_distribution.cpp)
add_executable(14_piecewise_linear_distribution         14_piecewise_linear_distribution.cpp)
add_executable(15_poisson_distribution                  15_poisson_distribution.cpp)
add_executable(16_geometric_distribution                16_geometric_distribution.cpp)
add_executable(17_exponential_distribution              17_exponential_distribution.cpp)
add_executable(18_other_random_engine                   18_other_random_engine.cpp)
add_executable(19_shuffle                               19_shuffle.cpp)
