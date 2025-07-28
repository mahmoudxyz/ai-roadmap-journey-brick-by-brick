# Derivatives

Derivatives are the foundation of machine learning optimization. Every time a neural network learns, it's using derivatives to figure out how to adjust its parameters.

## Resources
**Same as previous page**

I recommend watching only Professor Leonard	 and study and solve all problems Calculus I with integrated Precalculus book

| Resource | Type | Cost | Link | Notes |
|----------|------|------|------|-------|
| 3Blue1Brown Calculus | Video Series | Free | <a href="https://youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr" target="_blank">YouTube</a> | Best intuitive introduction available |
| Khan Academy Calculus | Interactive Course | Free | <a href="https://khanacademy.org/math/calculus-1" target="_blank">khanacademy.org</a> | Solid practice problems and explanations |
| MIT OCW 18.01 | Full Course | Free | <a href="https://ocw.mit.edu/courses/18-01-single-variable-calculus-fall-2006/" target="_blank">ocw.mit.edu</a> | Rigorous treatment with problem sets |
| Paul's Online Math Notes | Reference | Free | <a href="https://tutorial.math.lamar.edu/Classes/CalcI/CalcI.aspx" target="_blank">tutorial.math.lamar.edu</a> | Great for quick lookups and examples |
| Professor Leonard | Video Lectures | Free | [YouTube](https://youtube.com/playlist?list=PLF797E961509B4EB5&si=MCBEJh3w6u4DtXM1) |
| Calculus I with integrated Precalculus | Book | Paid | [Book link](https://a.co/d/5bpuEcg) |

## The Core Concept

A derivative measures how much a function changes when you change its input by a tiny amount. If f(x) is your function, f'(x) tells you the slope of the curve at point x.

In ML terms: if your loss function is L(w) where w is a weight, then L'(w) tells you how much the loss increases or decreases when you change that weight slightly.

## Essential Rules

<a href="https://tutorial.math.lamar.edu/pdf/calculus_cheat_sheet_derivatives.pdf" target="_blank">Calculus Cheat Sheet derivatives</a>

## Why This Matters

When you hear "gradient descent," that's just following derivatives downhill to minimize a function. When you see "backpropagation," that's computing derivatives using the chain rule through a network.

Understanding derivatives geometrically (as slopes) and algebraically (as limits) gives you the intuition to debug optimization problems and understand why learning algorithms work the way they do.
