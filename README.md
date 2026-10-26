# Aboutprime — Prime Number Animator

An interactive mathematics project for visualizing prime numbers, exploring prime gaps, and observing patterns in the Ulam spiral.

**Live demo:** https://mdshakibuzzaman.github.io/Aboutprime/

## Overview

Aboutprime is a browser-based mathematics visualization tool designed to make selected properties of prime numbers easier to explore.

Instead of presenting prime numbers only as a list, the application provides visual representations of algorithms and numerical patterns.

## Features

### 1. Sieve of Eratosthenes
Visualize how composite numbers are eliminated to identify primes. Step through the process and observe why the algorithm begins crossing out multiples of each prime at its square.

### 2. Ulam Spiral
Explore a spatial arrangement of consecutive integers in which prime numbers are highlighted. Observe the diagonal patterns that emerge as the spiral grows.

### 3. Prime Gaps
Visualize differences between consecutive prime numbers and explore twin-prime pairs and record gaps within a selected range.

### Interactive controls
- Play, pause, step, and reset the animation.
- Adjust the number range.
- Control animation speed.
- Use the responsive, canvas-based interface.
- Support light and dark color schemes.

## Mathematical Background

A prime number is an integer greater than 1 whose only positive divisors are 1 and itself.

The project explores three related ideas:

- **Prime generation:** The Sieve of Eratosthenes identifies primes by eliminating multiples of smaller primes.
- **Spatial patterns:** The Ulam spiral arranges integers geometrically to reveal patterns in the locations of primes.
- **Prime gaps:** If \(p_n\) denotes the \(n\)-th prime, the gap between consecutive primes is \(g_n=p_{n+1}-p_n\).

These visualizations help generate questions and build intuition. Observing a pattern in a finite range does not, by itself, establish a general mathematical theorem.

## Technology

- HTML5
- CSS3
- JavaScript
- HTML Canvas API

The application runs directly in a modern web browser without requiring a separate installation.

## Getting Started

1. Open the live demo linked above.
2. Select a visualization mode.
3. Adjust the number limit and animation speed.
4. Use the controls to explore the visualization.

To inspect the implementation, browse `index.html` in this repository.

## Future Development

Potential improvements include:

- More detailed prime-gap statistics and plots.
- Clearer explanations of the algorithms.
- Automated tests for mathematical correctness.
- Additional investigations into prime-number patterns.
- Improved accessibility and mobile usability.

## Author

Created by Md Shakibuzzaman as an independent mathematics and programming project.

The goal is to build interactive tools that encourage mathematical exploration and help make abstract ideas more accessible.
