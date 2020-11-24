OBJETOS=HolaMundo.o ../FUNCION1/funcion1.o 
CFLAGS=-I../FUNCION1 

HolaMundo: $(OBJETOS) 
	cc $(OBJETOS) -o HolaMundo 

../FUNCION1/funcion1.o: ../FUNCION1/funcion1.c 
	cc -c ../FUNCION1/funcion1.c -o ../FUNCION1/funcion1.o 
	
HolaMundo.o: HolaMundo.c ../FUNCION1/funcion1.h
	cc -c -I../FUNCION1 HolaMundo.c -o HolaMundo.o
