# A real-time implementation of Gang Scheduling on embedded platforms.

This repository contains the pdf version of my thesis on "A real-time implementation of gang scheduling on embedded platforms".

Bachelor’s Degree in Computer Science at the Univerity of Trento, Italy. 

By Valeria Grotto.


## Abstract

This thesis describes the implementation and testing of a process scheduler that enforces a gang scheduling policy for PSE53, a novel real-time operative system developed by Huawei.
This work was carried on during an internship at the Huawei’s Research Center in Pisa, Evidence S.r.l. The internship lasted 4 months, from February to June 2022.


Gang scheduling is a scheduling algorithm that schedules a set of threads to run in parallel
on different cores. Usually, a real-time operating system implements single-core scheduling
policies to avoid task interference and deadline misses. However, the gang policy allows the
user to benefit from the multicore infrastructure while still avoiding interference. In fact, one of
the main advantages of gang scheduling is the possibility to form a gang with only tasks that
cooperate and do not hinder the others.
Moreover, the gang algorithm allows synchronizing tasks with busy-waiting, reducing the
delay provoked by context switching.
``` 
Keywords: gang scheduling, real-time, parallel, scheduling, interference, busy-waiting
```

[A-real-time-implementation-of-gang-scheduling-on-embedded-platforms.pdf](https://github.com/valegr8/a-real-time-implementation-of-gang-scheduling-on-embedded-platforms/blob/main/A_real_time_implementation_of_gang_scheduling_on_embedded_platforms.pdf
)
