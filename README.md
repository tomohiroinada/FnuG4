# FnuG4

You need to install tomohiroinada/Fedra (or simple Fedra) with this repositiry as well.
Also you need to place Fedra and this repository in parallel (i.e. the same level). (e.g. virtualrec/Fedra and virtualrec/FnuG4)
Otherwise, you need to specify your Fedra path in rootlogon.c.

First, you need to install Fedra and set pathes, (see detail in Readme of Fedra repository.)
Here you can create FnuG4_C.so file to run virtualrec.c as follow.

-bash-4.2$ root -l -b
root [0] .L FnuG4.C++

Then, you can run virtualrec.c by root simply.

-bash-4.2$ root -l -b virtualrec.c

Output in the first trial was saved as run_virtualrec.log.


