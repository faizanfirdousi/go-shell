# 🐚 GoShell — A Minimal Unix-Like Shell in Go

GoShell is a basic command-line shell written in Go. It replicates essential shell behavior such as executing system commands and handling built-in commands like `cd` and `exit`.

## Features

- Execute system commands (e.g., `ls`, `echo`, `cat`, etc.)
- Built-in commands:
  - `cd [path]` — change directory
  - `exit` — exit the shell
- Simple REPL loop (`>>` prompt)
- Error feedback printed to `stderr`
- Command argument splitting and execution


## 🔧 Usage

1. Clone the repository or download `main.go`
2. Run using:

```bash
go run main.go
```

## Learning Source

This project was created as a learning exercise to understand how shells work internally using Go.  
I referred to and learned from this blog post:  
👉 [https://blog.init-io.net/post/2018/07-01-go-unix-shell/](https://blog.init-io.net/post/2018/07-01-go-unix-shell/)
