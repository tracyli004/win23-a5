CC = gcc
CFLAGS = -Wall

TARGET = calculator
SRCS = main.c addition.c subtraction.c multiplication.c division.c
OBJS = $(SRCS:.c=.o)


all: $(TARGET)

$(TARGET): $(OBJS)
	$(CC) $(CFLAGS) -o $(TARGET) $(OBJS)

%.o: %.c
	$(CC) $(CFLAGS) -c $< -o $@


