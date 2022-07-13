# Algorithms & Data structures ( need cleaning )

# Analysis

[Analysis](Algorithms%20&%20Data%20structures%20(%20need%20cleaning%20)%2050e89a8ce8b2493292373810e38986af/Analysis%2033d0554a18df41f5a469f1d1ac94aea2.md)

# Algorithms

### Sorting & Searching

[Searching ](Algorithms%20&%20Data%20structures%20(%20need%20cleaning%20)%2050e89a8ce8b2493292373810e38986af/Searching%20c87fa88835b44585ac22b58e92df9f88.md)

[Sorting ](Algorithms%20&%20Data%20structures%20(%20need%20cleaning%20)%2050e89a8ce8b2493292373810e38986af/Sorting%2007042beb8ab740ac9d013442d04a0041.md)

### Graph

### Greedy

> choose what best at current moment
> 

### Dynamic Programming

> break into subproblems and cache result
> 

[fib memoization](Algorithms%20&%20Data%20structures%20(%20need%20cleaning%20)%2050e89a8ce8b2493292373810e38986af/fib%20memoization%20f9be5b35debc40d093741149f8602c80.md)

[Gridtraveler memoization ](Algorithms%20&%20Data%20structures%20(%20need%20cleaning%20)%2050e89a8ce8b2493292373810e38986af/Gridtraveler%20memoization%2039a09c10d8204629ab2d421aefefbad3.md)

![Untitled](Algorithms%20&%20Data%20structures%20(%20need%20cleaning%20)%2050e89a8ce8b2493292373810e38986af/Untitled.png)

[https://www.youtube.com/watch?v=oBt53YbR9Kk](https://www.youtube.com/watch?v=oBt53YbR9Kk)

# Data structures

### Concepts

- pointers
    
    ### Void pointer
    
    > points to many types
    > 
    
    ![Untitled](Algorithms%20&%20Data%20structures%20(%20need%20cleaning%20)%2050e89a8ce8b2493292373810e38986af/Untitled%201.png)
    
    → Use for malloc and calloc (which return void pointer) which can associate with any data types 
    
    ### Null pointer
    
    > points to non existing ( after freed) memory
    > 
    
    ![Untitled](Algorithms%20&%20Data%20structures%20(%20need%20cleaning%20)%2050e89a8ce8b2493292373810e38986af/Untitled%202.png)
    
    → initialize, handle error
    
    ### Dangling pointer
    
    > points to non existent memory
    > 
    
    ![Untitled](Algorithms%20&%20Data%20structures%20(%20need%20cleaning%20)%2050e89a8ce8b2493292373810e38986af/Untitled%203.png)
    
    ### Wild pointer
    
    > pointer grab trash values
    > 
    
    ![Untitled](Algorithms%20&%20Data%20structures%20(%20need%20cleaning%20)%2050e89a8ce8b2493292373810e38986af/Untitled%204.png)
    
- memory
    
    ## Static
    
    > defined run time, cant change
    > 
    
    ![Untitled](Algorithms%20&%20Data%20structures%20(%20need%20cleaning%20)%2050e89a8ce8b2493292373810e38986af/Untitled%205.png)
    
    ## Dynamic
    
    > can change size
    > 
    
    ![Untitled](Algorithms%20&%20Data%20structures%20(%20need%20cleaning%20)%2050e89a8ce8b2493292373810e38986af/Untitled%206.png)
    
    - memory chart
        
        ![Untitled](Algorithms%20&%20Data%20structures%20(%20need%20cleaning%20)%2050e89a8ce8b2493292373810e38986af/Untitled%207.png)
        
    
    ## Calloc & Malloc
    
    ```c
    1. Malloc allocate mem
    - Take trash value 
    - Only 1 argument size_each_block
    2. Calloc allocate many 
    - Initialized as zero 
    - 2 arguments: number_of_blocks, size_each_block
    ```
    

### Trees

[Trees (1)](Algorithms%20&%20Data%20structures%20(%20need%20cleaning%20)%2050e89a8ce8b2493292373810e38986af/Trees%20(1)%2004e4f9a042bd45f5b80a2bc3893348d5.md)

[Stack, Linked List, Doubly Linked List, , Binary Heap](Algorithms%20&%20Data%20structures%20(%20need%20cleaning%20)%2050e89a8ce8b2493292373810e38986af/Stack,%20Linked%20List,%20Doubly%20Linked%20List,%20,%20Binary%20H%204c6971bc51df4f9ca1688b4ced27f613.md)

- recommend
    1. def
    2. examples / use case
    3. operations (coding) 

# Sources

[https://github.com/TheAlgorithms/Rust](https://github.com/TheAlgorithms/Rust)