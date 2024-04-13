# 🚀 ft_irc - Internet Relay Chat

Create your own IRC server to understand and implement standard network communication protocols.

## 📚 Table of Contents

- [Introduction](#introduction)
- [General Rules](#general-rules)
- [Mandatory Part](#mandatory-part)
- [Final Rendering](#final-rendering)

## 📖 Introduction

ft_irc involves creating an IRC server that communicates via the Internet using TCP/IP protocols. It supports real-time public and private messaging through a client-server architecture.

## ✨ General Rules

- No program crashes; handle all errors gracefully.
- C++ 98 compliance; compile with `-std=c++98`.
- Use a Makefile with `NAME`, `all`, `clean`, `fclean`, `re`.
- No external libraries; focus on using pure C++ features.

## 🚀 Mandatory Part

### Features

- Handle multiple client connections simultaneously without blocking.
- Use non-blocking I/O operations with a single `poll()` or equivalent.
- Support basic IRC commands and real-time message broadcasting to channels.

### Technical Requirements

- Develop the server in C++ 98.
- Execute the server with `./ircserv <port> <password>`.
- Include commands for user authentication, nickname, username, channel operations, and private messaging.

## 🔍 Final Rendering

### Chatting with multiple persons
![image](https://github.com/wayzeek/IRC/assets/112975047/a29b4ab6-7087-4e75-bd3a-5b44818abc39)

## 🏆 Credits

This project was completed by [jprofit](https://github.com/JohanPrft), [amontalb](https://github.com/Tonisos) and [myself](https://github.com/wayzeek) as part of the curriculum at École 42.
