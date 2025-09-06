# Weenix Kernel — Demonstration

This repository showcases the results of my work on **Weenix**, a Unix-like toy kernel.  
The source code is not included (per course policy), but here you can find screenshots, recordings,  
and explanations of the kernel features we (Group of 4) implemented as part of the semester long Kernel project of the course CSCI402 at USC.
The kernel was divided into three parts each focusing on a part of the kernel.

---

## Features Implemented

- **Processes & Threads**

  - Full process lifecycle
  - Thread scheduling, synchronization
  - Mutexes & wait queues

- **Virtual File System (VFS)**

  - System calls: `open`, `close`, `read`, `write`
  - File descriptor tables per process
  - Support for device files

- **Virtual Memory**
  - Page fault handler
  - `mmap()` and `brk()` implementations
  - Copy-on-write and full `fork()` pipeline

---

## Demo

#### User Shell

![User Shell](images/user_shell.jpeg)

#### User Shell `help` command

![User Shell Help](images/help.jpeg)

#### User Shell `cat` command

![User Shell cat](images/cat.jpeg)

#### Kernel Shell `help` command

![K Shell kshell_help](images/kshell_help.jpeg)

#### User Shell `ls` command

![User Shell ls](images/ls.jpeg)

#### User Shell `stat` command

![User Shell stat](images/stat.jpeg)

#### User Shell `faber thread tests`

![User Shell cat](images/faber_thread_tests.gif)

#### User Shell `fork-and-wait`

![User Shell fork](images/fork_and_wait.jpeg)

#### `forkbomb` test - Upto 250 child threads

![User Shell forkbomb250](images/forkbomb250.gif)

#### `forkbomb` test - Upto 500 child threads

![User Shell forkbomb500](images/forkbomb500.gif)

#### `memtest`

![User Shell memtest](images/memtest.jpeg)

#### `stresstest`

![User Shell stress](images/stress.gif)
