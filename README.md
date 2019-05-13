This project is implemented with a goal of understanding threads and gain an understanding of the concurrency control mechanism in operating system.

This contains the implementation of following algorithms:
1. Mutex for thread synchronization consists of following functionalities: 

    ```Lock()```   : Acquire the mutex if free, otherwise wait until the mutex is free and then get it.

    ```Unlock()```: Release the mutex.  If other threads are waiting, then wake up the oldest one and give it the lock.

    ```Init()```: Each mutex must be initialized.

    ```IsHeldByCurrentThread()```: Return TRUE iff the current (invoking) thread holds a lock on the mutex.

1. Producer-Consumer/Bounded buffer problem: A multi-process synchronization problem.

2. Dining-Philosopher problem: A classic concurrency problem dealing with synchronization.