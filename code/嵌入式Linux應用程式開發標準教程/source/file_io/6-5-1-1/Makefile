EXEC = standard_io
OBJS = standard_io.o
HEADERS = 

CC = gcc
INC = -I.
CFLAGS = ${INC} -g 

all:${EXEC}
${EXEC} : ${OBJS}
	${CC} ${CFLAGS} ${LDFLAGS} -o $@ ${OBJS} 

${OBJS} : ${HEADERS}

.PHONY : clean
clean :
	-rm -f ${OBJS} ${EXEC}