Tested on MATLABR2023a

How to run:
candidate_script(n) or candidate_script()

If you don't give the parameter 'n', a preset 'n==1200' will be chosen.
Wait a couple of seconds for output. On my machine with 'n==1200' the output is:


Created 1200 Matrices in 1.3717 seconds.(via a class with preallocation)
Created 1200 Matrices in 4.7203 seconds. (without class but second file, with preallocation)
Created 1200 Matrices in 4.4823 seconds. (without class in same file, with preallocation)
Created 1200 Matrices in 1.7062 seconds.(via a class without preallocation)
Created 1200 Matrices in 3.9131 seconds. (without class but second file, without preallocation)
Created 1200 Matrices in 4.1159 seconds. (without class in same file, without preallocation)






In general, the second_method.m script _could_ be run, but you'd need some more knowledge of how to.