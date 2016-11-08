GTEST_LL = -I /usr/include/gtest/ -l gtest -l gtest_main -pthread

all: iterators stl

iterators: iterators.cpp
	g++ -g -Wall -o iterators iterators.cpp

stl: stl.cpp
	g++ -g -Wall -o stl stl.cpp $(GTEST_LL)