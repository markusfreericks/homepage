## Observations

### “You can have a second computer once you’ve shown you know how to use the first one.”

- Frank McSherry, Michael Isard, Derek G. Murray: [Scalability! But at what COST?](https://www.usenix.org/system/files/conference/hotos15/hotos15-paper-mcsherry.pdf)
-- whenever we do anything in parallel, or on distrubuted machines, we have to compare it to a competent single-threaded/single-machine implementation, and ask: at what number of threads/machines are we getting faster?
-- COST is an acronym: "Configuration that Outperforms a Single Thread"
- see also: https://adamdrake.com/command-line-tools-can-be-235x-faster-than-your-hadoop-cluster.html
-- he gives an example where an analysis task on a 1.75GB data set completed in 12 seconds with shell command line tools (find | xargs mawk | mawk), vs. 26 minutes with a a hadoop cluster

### Conways Law

- https://www.melconway.com/Home/pdf/committees.pdf
-- the structure of a software design reflects the structure of the teams that developed it
-- example from the paper: "A contract research organization had eight people who were to produce a COBOL and an ALGOL compiler. After some initial estimates of difficulty and time, five people were assigned to the COBOL job and three to the ALGOL job. The resulting COBOL compiler ran in five phases, the ALGOL compiler ran in three. "
-- discussed e.g. https://www.youtube.com/watch?v=5IUj1EZwpJY&t=701s

