KDIR?=$(OK6410KDIR)
PWD:=$(shell pwd)
obj-m+=buzzer.o

default:
	make -C $(KDIR) M=$(PWD) modules
