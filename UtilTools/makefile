CXX=g++
CFLAGS =-g -Wall

all : test_option

test_option:test_option.o tc_option.o
	$(CXX) $(CFLAGS) -o test_option test_option.o
tc_option.o:tc_option.cpp
	$(CXX) $(CFLAGS) -c tc_option.cpp