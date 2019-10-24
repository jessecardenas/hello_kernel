# hello_kernel
This is a simple minimal kernel module  
From [https://www.thegeekstuff.com/2013/07/write-linux-kernel-module/](https://www.thegeekstuff.com/2013/07/write-linux-kernel-module/) 

To compile:
> make  

To install:
> insmod hello.ko  
> dmesg | tail  
> rmmod hello.ko  

To clean compiled files:
> make clean  

