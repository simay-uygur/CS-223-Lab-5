# CS-223-Lab-5
This is an assignment given by Bilkent University in the CS 223 Digital Design course.


In a community, people need stop signs and trac lights to organize the traffic flow. If there were no traffic lights or stop signs, people's lives would be in danger from divers going too fast. These devices also play a role in road safety. While accidents still occur at intersections, these crashes may be been prevented by the drivers yielding to the traffic lights and improving the traffic lights timings. To reduce danger at the intersections, time for switching red light to green light and green light to red light should be regulated carefully. Studies show if the both lights are red for 3 seconds before either light turns green again prevent huge amount of accidents in traffic.


* SystemVerilog module for the state machine and a testbench for it to verify functionality.


A BCD counter stores the counted seconds directly in BCD format and handle the necessary transitions without doing division and modulo arithmetic. The operations of BCD counter are:
 When Enable = 1 and Load = 0, the count Q[3:0] is incremented on the rising edge of the clock.
 When Enable = 1 and Load = 0 and Q[3:0] = 4′b1001, the count Q[3:0] rolls back to 4′b0000 on the rising
edge of the clock.
 When Enable = 1 and Load = 1, the input D[3:0] is loaded to the output Q[3:0] ← D[3:0] on the rising edge of the clock.
 When Enable = 0, the output Q[3:0] remains the same Q[3:0] ← Q[3:0] on the rising edge of the clock.


* SystemVerilog module for a single-digit BCD counter with enable signal that resets after reaching the number nine using the up-counter designed before.
* SystemVerilog module for a two-digit BCD counter using the single-digit BCD counter that was implemented in the previous step. The count should automatically roll back to 0 after 99. 
