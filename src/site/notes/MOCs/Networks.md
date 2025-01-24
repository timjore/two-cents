---
{"dg-publish":true,"permalink":"/mo-cs/networks/","tags":["MOC"]}
---

# Networks

The “rigorous language for the description of networks is found in graph theory, a field of mathematics that can be traced back to the pioneering work of Leonhard Euler in the eighteenth century.”[^1] 

## Foundational concepts and terminology of Graph Theory

- **network** (or *graph*): a set of elements (*nodes*) with a set of connections between pairs of nodes (*links*). A network is characterized by the total number of nodes *N* and total number of links (*L*). 
- **links:** represent the presence of a relation between the nodes (e.g., social, p;hysical, communication, geographic, conceptual, chemical, biological, etc.)
- **neighbors:** two nodes that are *connected* (or *adjacent*) by a link between them.

## Kinds of Networks

- **Directed network** (or *digraph*): links are called *directed links* and the order of the nodes in a link reflects the direction (from *source* node to *target*).
- **Undirected network:** links are bi-directional and the order of the two nodes in a link does not matter.
- **Weighted network:** links have associated weights.
- **Unweighted network:** all links are the same weight.
- **Network size:** *N* is the *size* of the network because it identifies the number of distinct elements composing the system.
- **Network density:** the fraction of possible links that actually exist (i.e., the fraction of pairs of nodes that are connected).

## Classes of Networks

- **Bipartite networks:** have two groups of nodes such that links only connect nodes from different groups and not nodes from the same group. (e.g., movie-star, artist-song, class-student, product-customer, etc.)
- **Multiplex networks:** have multiple types of links. (e.g., movie-star with added links showing actors/actresses who are married to each other.)
- **Complete network:** a network with the maximum number of links, in which all possible pairs of nodes are connected by links. A complete network has maximal density: 1.
- **Sparse network:** a network with a much lower (e.g., orders of magnitude) network density than 1.

## Subnetworks

- **Subnetwork** (or *subgraph*): a subset of the nodes of a network and all the links among these nodes.
- **Clique:** a complete subnetwork where all pairs of nodes in the network are connected.
- **Ego network:** the subnetwork consisting of a given node (*ego*) and its neighbors. 
- **Node degree**: The number of neighbors (links) of a given node. A node with no neighbors is a *singleton*.
- **Network degree:** of a network is denoted by $(k)$ and is directly proportional to its density.



| File                                                                                                                                                  | Total Links |
| ----------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- |
| [[Complex networks have unique topological features\|Complex networks have unique topological features]]                                           | 18          |
| [[Liquid Networks foster innovation\|Liquid Networks foster innovation]]                                                                           | 17          |
| [[Power Law distributions\|Power Law distributions]]                                                                                               | 12          |
| [[Simple rules tame complexity\|Simple rules tame complexity]]                                                                                     | 11          |
| [[Kinds of networks\|Kinds of networks]]                                                                                                           | 7           |
| [[Networks at scale increase the number of links more than nodes\|Networks at scale increase the number of links more than nodes]]                 | 7           |
| [[Flexibility, simplicity and adaptability are simple rules of movements\|Flexibility, simplicity and adaptability are simple rules of movements]] | 6           |
| [[All-Channel Networks can function without hierarchies\|All-Channel Networks can function without hierarchies]]                                   | 5           |
| [[Globalization is a complex system\|Globalization is a complex system]]                                                                           | 5           |
| [[Metcalfe's Law defines network effects\|Metcalfe's Law defines network effects]]                                                                 | 5           |
| [[Scale-free patterns are fractal\|Scale-free patterns are fractal]]                                                                               | 2           |

{ .block-language-dataview}


[^1]: Unless noted otherwise, all defintions are from [[References/A First Course in Network Science – Menczer, et. al. (2020)\|A First Course in Network Science – Menczer, et. al. (2020)]].