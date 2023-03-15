![VPong Pic](/vpong.png)
# VPong

This is my first dabbing into programming the Vectrex. If you examine the sources – they start of with the comment: “; this game was written on 08.02.1998”

That is one very specific date! – I remember, that the complete VPong was exactly written on that day. I did not start befor that and I never changed anything after. It was a Sunday and I wanted to write a test program for DVE (DOS Vectrex Emulator), I wanted to explore what was needed to add development tools to the emlation package.

I new my way around the Vectrex before that day – as I had put myself in charge of DVE. I also knew about the 6809 processor, since emulating it was part of DVE – but before that I did not program any 6809 code (I am pretty certain, that I did not even have a a Vectrex back than).

I certainly new my way around computers and programming in general, made my way thru several computers:
– ZX81 (BASIC)
– C64 (BASIC and a bit 6510 Assembler)
– AMIGA (C and 68000 Assembler)
– PC (C and x86 Assembler)
– many other languages in university… (C++, PASCAL, EIFEL, LISP, COBOL to name but a few)

But until that day – I think I never wrote a single line of 6809 code.

VPong was a testcase.
I wanted it to include:

- vector lists
- moveable objects
- joystick input
- sound

... and a single player “Pong” variant was the easiest thing I could think of.

While being a small game – and one that never really was intended to be distributed – in hindsight I am astonished, as to what small things I put into it:

- it has a title page + intro music (internal ROM music)
- it features a score, a ball count and a “touch” count
- different sounds for paddle, wall and out of bounds
- animated effects if you lose a ball or game over
- game over screen (including score display)
- increasing difficulty (every 5 paddle touches, the ball gets faster)
- different angles for paddle touches, depending on the position of the touch

Apart from that the source is fully(!) documented!
The source doesn’t use many “make my life easier” features a decent assembler offers and which I only learned much later – but it is well readable and structured.
