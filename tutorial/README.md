# My "Let's Build a Compiler" journey

Stored within  will be snapshots  of code  and notes accumulated  from my
exploration of the "Let's Build a Compiler" tutorial by Jack Crenshaw.

The tutorial, as I encountered it, was found at:

  * https://compilers.iecc.com/crenshaw/

I have downloaded the tutorial in the various formats available from this
site, storing them all in the `tutorial/` subdirectory here.

I extracted the text file archive, placing the pertinent tutorial section
in the appropriate subdirectory along with any code generated. Notes will
be recorded in the `README.md` file in each directory.

## My intentions

At the outset, here are my intentions:

I stumbled  across https://github.com/DoctorWkt/acwj, involving  making a
compiler. I read through several  of the modules, getting more interested
along the  way. I  also discovered,  from it  and other  google searches,
similar efforts,  be they  other compilers, or  even compiler  tools like
**qbe**.

A "wouldn't  it be nice" sort  of desire I've had  is to create my  own C
compiler for the Vircon32 fantasy console. Specifically, one that doesn't
have  one-off syntax  for  arrays,  and supports  some  of the  currently
missing  things in  its  compiler, like  ternary  operators, unions,  and
function pointers.

Understanding that  this would be quite  an undertaking, and while  I did
make some initial attempts, I quickly hit walls, not seeing where and how
to  translate some  assembly  emissions due  to  platform differences  or
conceptual obstacles.

This tutorial was the first where I felt the vibe was closer to my way of
thinking.  Plus it  offered  me  the fun  challenge  of translating  from
pascal; a language I've not really used  for over 25 years, yet can still
largely read.

So:  following the  tutorial  but  instead targeting  C  and  bash as  my
implementation languages.

And: the ultimate,  long-term goal of making a C  compiler. We'll see how
far I get.

NOTE: I am  looking to maintain TWO simultaneous  implementations with my
approach here.  One written  in C,  another written in  bash. The  aim is
for  both  to  output  identically,  even though  the  details  of  their
implementations necessarily differ.

Why bash,  one might ask? It  is one of those  "terrible"-y awesome ideas
that popped  into my  head. There's  no business for  any compiler  to be
written in a scripting language. And therein was the allure: it is crazy,
but at the same time offers some unique challenges to think through how I
might implement some of the needed logic.

So far, I have enjoyed the drastic  detail extremes both C and bash offer
me: C being incredibly low-level,  bash being incredibly high-level. Both
offer ease and annoyance with their various strengths.

C and bash have been my go-to  languages for years. The bulk of code I've
written  has been  in one  of these  two languages.  I have  familiarity,
enough to feel comfortable using them in conjunction with my explorations
of this tutorial.

Again: while there is a "would be  nice" final result I'd love to achieve
(a working C  compiler targeting the Vircon32 fantasy  console), I should
emphasize  this is  primarily  a learning  and  exploratory endeavour.  I
might  not  actually finish.  Compiler  Construction  was an  elective  I
unfortunately missed  out on  in my undergraduate  studies, and  for some
reason now,  21 years after graduating,  I feel inspired enough  to close
that gap.

If  this  provides  value  to  anyone  other  than  me,  that  is  purely
accidental, although not unwelcome. Just:  don't expect me or this effort
to divert from my above-stated intentions.
