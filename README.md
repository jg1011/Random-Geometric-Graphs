# Roadmap 

The current plan and scope for these notes is to cover the following material. 

- Elementary theory of random geometric graphs, courtesy of Penrose's blue book (and perhaps some red book 
stuff where I deem appropriate). 
- Introduction to the sphere packing problem, the trivial bound 
- Probabilistic lattice packings, courtesy of Minkowski-Hlawka 
- Campos's breakthrough bound

And for some possible appendices / probabilistic ingredients, 

- Concentration inequalities
- Poisson point processes (can I assume my reader knows about these?)
- Geometric ingredients (convex sets and some measure theory)
- Algebraic ingredients (probably not worth, but some lattice theory for Minkowski-Hlawka)

Where appropriate I will deviate from these, but for now this is a good roadmap (and achievable in a week or so). 


# To-Do

### Penrose's Red Book

### Penrose's Blue Book
- Exercise 2.2 :(
- Type up proofs in chapter 3, getting good w/ Mecke's is mandatory. 

### Pach & Agarwal's Combinatorial Geometry
All Todos are on CH7, the chapter of primary interest to me
- Figure out that one line of magic in Davenport & Roger's result, ask Penrose? 
- Learn Hlawka's theorem proof (already read once but go beyond surface)
- Make jump to Minkowski-Hlawka theorem 

It is worth noting this chapter takes a lattice approach to sphere packing, something likely to not 
be optimal (or at least probably not beat Campos2023) but is of independent interest. 

### Campos 2023
Campos & Co approach bounding sphere packing densities in high dimensional space with random geometric graphs & a new bound on the maximal independent set of a (fixed) graph. The first 3 steps in the methodology (of the proof of thm 1.1) were quite literally exactly what I had in mind. The advent of theorem 1.3 to bound the large independent set was creative, and I believe this proof, while being left temporarily, is of independent interest. 

The methodology is as follows: 
- Consider a PPP with carefully chosen intensity (one that will work nicely with our other results)
- Remove points of high degree / codegree 
- Bound the independent set of the geometric graph left over (where the radius is just double the radius of the unit-volume $d$-sphere)

Various TO-DOs:

- Understand sharpness argument for theorem 1.3, seen in the 2nd paragraph page 4. 
- Prove the univariate Mecke, either directly or as a special case of Penrose (blue book) Mecke. 
- Improve your Poisson tail bound and ideally arive at their bound. Note on this in pdf
- Verify $t = \Delta^{-1/3} - \Delta^{-1}$ algebra bash. $\Delta(t+1) = \Delta(1+\Delta^{-1/3}) - 1$ to be applied to RHS of $(\dagger)$ is fine, just the bound.
- Finish bounding of rightmost term in sum (lemma 2.30) $\mathbb{E}|\{y \in X \setminus B_x(\log d) : I_{x,y} \geq \eta \Delta - 1\}|$
- Look into remarks 2.31, 2.32 & 2.33

Notes are currently up to (but not including) the proof of theorem 1.3. I'd like to understand this tool, particularly on the relevance of random graph theory vs just graph theory. Rödl nibble is cool :)
    - Not particularly geometric, but a very nice application of the probabilistic method in combinatorics (in particular the method of alteration). 

### Misc
- Fix claimcount numbering and devise a better system for the remaining counts


