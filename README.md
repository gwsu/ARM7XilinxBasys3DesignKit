# ARM7XilinxBasys3DesignKit

This a kind of Educational Kit for Computer Engineering Students .


Its an ARM7 single cycle like (same architecture) processor with only seven main instructions: add,sub,and,orr,ldr,str and b . It too supports ands,orrs,adds and subs, besides the usefuk arm conditions like beq or addeq for example.


The source cames from of the book Computer Design Arm Edition of Harris and Harris .


Before starting, you are supposed to install, in RWindo$ OS, the free versio of  Vivado (webpack) , MDK Keil and Mdk Keil Legacy Support form ARM7 

After the installation, you are ready to go:

1. Open the myarm7code.uvproj mdk keil project in folder Software . Remember using only the seven implemented instructions and its derivations . Type F7 for compiling and automatically generating the system verilog implemented code memory imem.sv .

2. Open ARMSOC_1.xpr vivado project in Xilinx folder. You can Simulate or generate bit stream and download it to Basys 3 Artix 7 based board from digilent inc .

You have a few code examples in software folder. Creative solutions are needed , because you dont have mov or BL instructions. Look at the examples .

If you want to learn how to add more instructions, please, look lab 9 at https://booksite.elsevier.com/9780128000564/content/labs_companion.zip .
