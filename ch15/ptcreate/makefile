SRC_FILES = ptcreate.c
OBJ_FILES = $(patsubst %.c, %.o, ${SRC_FILES})
a   : ${OBJ_FILES}
	gcc -o  a ${OBJ_FILES}

%.o:%.c
	gcc -c -o $@ $<

clean:
	rm *.o a
