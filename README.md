# Convex Java Client

A JNI wrapper around the Convex Rust client for use in Java projects

![GitHub](https://img.shields.io/github/license/varunsingh87/convex-java)

[Convex](https://convex.dev) is a backend application platform that abstracts away database management and backend software engineering by providing functions to the frontend that use network sockets to constantly communicate database updates and easily mutate data in the database. It has official support for Python, Rust, JavaScript, and React Native clients. This project uses a JNI wrapper on the Rust client to support Convex in a project using a Java frontend. 

The goal of this project is to provide the same functionality that the JavaScript (React) client provides through the React hooks and Convex functions, in a Java project when this package is imported. 

## Quick Reference

https://docs.rs/jni/latest/jni/
https://docs.rs/convex/latest/convex/?ref=blog.convex.dev
