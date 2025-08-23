---
layout: post
title: "topics in probability and statistics for machine learning"
date: 2025-08-23
categories: [probability, statistics]
tags: [random variables]
---

# random variables: discrete and continuous
In probability and statistics, a **random variable** is a variable whose possible values are outcomes of a random phenomenon. Understanding random variables is essential for many machine learning concepts, from probability distributions to statistical modeling.

## discrete random variable
A **discrete random variable** can take on a countable number of distinct values, often integers. For example:
- the number of heads when flipping 3 coins.
- the number of customers arriving at a store in an hour.

**key points:**
- Probability Mass Function (PMF): Assigns a probability to each possible value.
- Probabilities sum to 1.

**example:**
Flipping a fair coin twice, let \(X\) be the number of heads:
|   X  |  0  |  1  |  2  |
|------|-----|-----|-----|
| P(X) | 1/4 | 1/2 | 1/4 |

## continuous random variable
A **continuous random variable** can take on any value within a range (interval) of real numbers. For example:
- height of students in a class.
- time taken to run a mile.

**key points:**
- Probability Density Function (PDF): Defines the relative likelihood of values.
- Probabilities are computed over intervals, not exact values.

**example:**
The probability that a student’s height is between 160 cm and 170 cm is the **area under the PDF curve** in that interval.

### summary:
- Discrete random variables → countable outcomes, PMF.
- Continuous random variables → infinite outcomes, PDF.

Understanding these distinctions is fundamental for probability distributions, expectations, and variance calculations in machine learning.
