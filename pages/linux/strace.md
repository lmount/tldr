# strace

> Trace system calls and signals.

- Basic tracing:

`strace {{command}}`

- Attach to a process:

`strace -p {{pid}}`

- Log output to a file:

`strace -o {{logfile}} {{command}}`

- Trace following children:

`strace -f {{command}}`

- Trace all open and read calls:

`strace -e trace={{open,read}} {{command}}`
