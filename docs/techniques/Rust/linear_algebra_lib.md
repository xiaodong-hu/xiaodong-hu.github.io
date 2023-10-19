---
layout: default
title: Linear Algebra in Rust
parent: Techniques
---

The huge mememory consumption of julia code for our project of **fractional Chern insulator** once pushed me to rust. The smooth conversion between these two languages really surprise me, probably due to the modern desgin of rust syntax. 

However, I have to say that playing with complex numbers and tensors in rust is almost a nightmare, due to the ugly design of the interfraces for the current implementation of linear algebra libs, including 

- [nalgebra](https://crates.io/crates/nalgebra)
- [ndarray-linalg](https://crates.io/crates/ndarray-linalg)

I really want a user-friendly linear algebra like julia (which I assume to be the best among all programming languages, particularly far exceeding the famous `numpy`), so want to desgin one myself.