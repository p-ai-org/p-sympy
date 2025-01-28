# p-sympy

## Project Overview

Have you ever wanted to contribute to open source software? Join my project and gain the opportunity to do just that! My goal is to enhance the performance of the assumptions module in SymPy, a widely-used Python-based computer algebra system (think WolframAlpha, but in Python). As an expert in SymPy’s new assumption system, I’ve guided newcomers in contributing to it, drawing from my experience as a contributor during Google Summer of Code 2023.

SymPy's assumption system allows users to query properties (or "assumptions") about symbols and expressions, such as whether a symbol represents a positive, real, or integer value. Its primary purpose is to enable more simplifications and manipulations of mathematical expressions. See here for more details about SymPy’s assumptions.

SymPy actually has two different assumption systems—the “old” and “new” assumptions. For more than a decade, there has been an effort to transition the new assumption system which allows for more types of queries (e.g. reasoning about inequalities). However, the new assumptions are much slower, so it’s the goal of my project to do what we can to improve their speed. See here for a blog post I’m writing which contains additional details. 

## Project members

- Tilo Reneau-Cardoso

## Purpose of this fork

Ideally, no one has to use this fork; it's a lot more straightforward to just use your own fork of SymPy. However, in case members of the same subprojects want to work asynchronously, they can make PRs from this repo and push commits to it.
