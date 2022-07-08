
INCLUDE=-I./


redis: redis.cpp redis.h
	g++ -g $(INCLUDE)  redis.cpp -o redis -L/usr/local/lib/ -lhiredis -w

clean:
	rm -f redis.o redis
