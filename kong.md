```
➤ ssh -l username kong.njit.edu

kong-1 username>: ls
AFS_HOME@  UCS-README
kong-2 username>: ssh phi.njit.edu
phi-1 username>: exit
logout

kong-3 username>: which python
/usr/bin/python
kong-4 username>: python
kong-5 username>: R
R: Command not found.
kong-6 username>: matlab
kong-7 username>: ssh phi.njit.edu
phi-2 username>: matlab
phi-3 username>: python
Python 3.5.2 |Anaconda custom (64-bit)| (default, Jul  2 2016, 17:53:06)
[GCC 4.4.7 20120313 (Red Hat 4.4.7-1)] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> exit()
phi-4 username>: python2
Python 2.7.12 |Anaconda 4.0.0 (64-bit)| (default, Jul  2 2016, 17:42:40)
[GCC 4.4.7 20120313 (Red Hat 4.4.7-1)] on linux2
Type "help", "copyright", "credits" or "license" for more information.
Anaconda is brought to you by Continuum Analytics.
Please check out: http://continuum.io/thanks and https://anaconda.org
>>> exit()
phi-5 username>: qsub                 
qsub: Command not found.   ##this is similar to sbatch
```
