OBJS = demo_app.o
CC = $(CROSS_COMPILE)gcc
OUT_BIN = demo_app
dep_file = .$@.d
all: $(OBJS)
	$(CC) $(LDFLAGS) -g -o $(OUT_BIN) $^

%.o:%.c
	$(CC) $(CFLAGS) -Wp,-MD,$(dep_file0 -c -o $@ $<
clean:
	rm -rf *.o
	rm -rf $(OUT_BIN)
	rm -f $(shell find -name "*.d")

