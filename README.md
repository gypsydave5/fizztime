FIZZTIME
========

A timer, written in bash, for keeping track of how fast you're getting (or not in my
case) at the Fizzbuzz challenge. It writes a 'fizzbuzz_times_log.txt' with the
time an date you started and the time taken.

To run, either place the 'fizztimer' file in the directory you're working in
or (for the daring) symlink it to '/usr/local/bin' and use it whenever. It
even works for things other than Fizzbuzz (surprisingly...)

The program will the shell on running, which can then be broken out of with
a return. If you don't like this behaviour you could either run it as
a background process with '&' or just have it in a different terminal window
when doing the challenge.

Or just use a watch and a piece of paper...