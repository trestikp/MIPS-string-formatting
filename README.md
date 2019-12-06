# MIPS-string-formatting
Simple string formatting in MIPS. More in README

ukol2.s
As said above. Is a simple program which prompts the user to add a string and then modify it
with the use of instructions d and i.
Instruction d<position> - deletes char at <position>.
Instruction i<position><char> - inserts <char> at <position>.
!! <position> is an index of said char! not its number.
i.e. input = "hello"
instr: d1 -> "hllo"
instr: i1e -> "hello"

This program isn't completely fool proof and almost certainly has bugs and things to improve.
It was more or less my first time writing a program in assembly and it probably looks that way.
There is probably a lot of improvements possible on the code, but maybe it can help another 
noob like me.

ukol1.circ
Is a circuit done in Logism. It only simulates simple 5 state automat.
It's just my backup for the whole subject so it's there.
