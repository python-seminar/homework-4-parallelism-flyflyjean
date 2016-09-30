# homework-4-parallelism-flyflyjean
homework-4-parallelism-flyflyjean created by GitHub Classroom
Jing Dai (SID: 26915093)

Before running the program, IPython controller and four IPython engines should be started by typing (ipcluster start -n 4) in terminal

Plot illustration:
The trends of multiprocessing and ipyparallel are very similar. When the dart number is small, both of them need a longer time for execution than the one without parallelism.  That is probably because of the overhead. There is extra time required for the parallelization, such as initiating the process and passing the functions and arguments, which can not be compensated by the reduced time of computing.  The curve also showed that ipyparallel has a longer overhead than multiprocessing. With the increase of the dart number, the execution time is more computation dependent, meaning the speed-up in computing is truly playing a role. The increase of simulation rate finally levels off at around10^6 darts, which validates the same idea. Though multiprocessing has a shorter overhead, the two parallelization methods end up with almost the same rate and execution time.

