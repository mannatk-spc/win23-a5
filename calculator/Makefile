CC=gcc
CFLAGS=-Wall -g

calculator: main.c addition.c subtraction.c multiplication.c division.c
	$(CC) $(CFLAGS) -o calculator main.c addition.c subtraction.c multiplication.c division.c

clean:
	rm -f calculator