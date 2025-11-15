PID: unique process ID, /proc/<pid>/… for info, used for control.

Environment: each process has environment variables; can be read/manipulated via getenv, setenv, environ.

Signals: asynchronous interrupts; must decide to catch/ignore/default; special rules for SIGKILL/SIGSTOP; threads complicate things; handlers must be reentrant.
