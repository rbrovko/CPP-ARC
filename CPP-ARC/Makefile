CXX=g++ -std=c++0x -Wall -Werror
BUILD_DIR=./build

default: arc_example

main.o: main.cpp 
	$(CXX) -c $^

arc_example: main.o
	$(CXX) $^ -o $@
	rm -f main.o
	./arc_example

clean:
	rm -f arc_example
