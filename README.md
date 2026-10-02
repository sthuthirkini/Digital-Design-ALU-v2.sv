# Digital-Design-ALU-v2.sv
Dealing with overflows that ALU v1 could not handle.
//The first alu just focussed on operations, now we see how the operations can effect the bigger system ,if an overflow occurs,how it can be dealt with for accurate and safe operations.

Our ALU uses 4-bit two's-complement representation for signed arithmetic.
It has already been established while doing the subtraction A-B=A+1~B

Acceptable range: -8 to +7


