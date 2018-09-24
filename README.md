# dir-digester
A simple GoLang program to get md5 checksum of all files in a local directory.

This is a practice project to play with advance concurrency features of GoLang.

## Concepts used -

* **Goroutines** - async functions 
* **Channels** - communication between goroutines
  * **Data Channels** - to pass data between goroutines
  * **Error Channels** - to communicate errors occured in any running goroutine
  * **Done Channels** - to signal running goroutines to stop 
* **Wait Groups** - to keep a track of all running goroutines and wait untill each one has gracefully completed their job
* **Bounded Parallelism** - to limit the number of goroutines running in parallel to control the usage of machine resources by the program 
