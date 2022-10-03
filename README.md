# Multithread Web Server
This repository is implemented by following tutorial in [Chapter 20, Rust book](https://doc.rust-lang.org/book/ch20-00-final-project-a-web-server.html).

## Detail
* ThreadPool and communication between them (mpsc::channel + Arc + Mutex)
* Simple web server listen for TCP connection, parse simple HTTP request and repsonse
