
CC = g++
CFLAGS = -g -fsanitize=address
TARGET = main
# -g -Wall -D_GLIBCXX_DEBUG -D_GLIBCXX_DEBUG_PEDANTIC -ggdb -Wall -Wextra -Wshadow -Wconversion
all = $(TARGET)

objects = main.o
$(info $$CFLAGS = $(CFLAGS))

$(TARGET): $(TARGET).cpp
		$(CC) $(CFLAGS) $(TARGET).cpp -o $(TARGET)

.PHONY: clean
clean:
	rm -f $(TARGET)
