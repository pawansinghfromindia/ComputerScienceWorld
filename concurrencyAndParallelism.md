# Concurrency and Parallelism

Hey bro, Concurrency and Parallelism are same, right?
- No bro, **Concurrency is not parallelism!**

| Concurrency                                     | Parallelism |
|-------------------------------------------------|----------------------------------------------------|
|Composition of multiple independent processes    | Parallelism is simulatenous Execution of processes |
| It's about dealing with a lot of things at once | It's about doing a lot of things at once |
| Concurrency is a way to structure the things so that you can may be use parallelism to do better job| Parallelism goal is not concurency,
Concurrency goal is **Parallelism** |

Analogy of it :

Concurrency : Mouse, Keyboard, Display, Disk Drive
- If there is one processor or core, at a time you can run one processess ideally. But we have a concurrency models for I/O devices.
- It doesn't need to do parallelism. Like Context Switch between the processes
- Todays we have 8 Core, 16Core Processors etc
  
Parallelism : Vector Dot Products
- Break the thing  and execute separately

**[Lecture by Rob Pike](https://www.youtube.com/watch?v=oV9rvDllKEg) See [Slides](https://talks.golang.org/2012/waza.slide)**
