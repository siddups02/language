# sudo yum install glibc-static
all:
	\g++ -g -std=c++11 ex1.cpp -pthread -lboost_thread -lboost_system -o ex1  
	\g++ -g -std=c++11 ex2.cpp -pthread -lboost_thread -lboost_system -o ex2

run:
	LD_LIBRARY_PATH=/usr/local/lib  ./ex2

