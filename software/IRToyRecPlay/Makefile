SRC_FILES=bin.c  kbhit.c  main.c  ols.c  queue.c  serial.c  txt.c
OBJ_FILES=$(SRC_FILES:.c=.o)
TARGET=IrToyRecPlay

all: $(TARGET)

$(TARGET): $(OBJ_FILES)
	gcc -o $@ $?

clean:
	rm -rf $(TARGET) $(OBJ_FILES)
