---
layout: pattern
title: Naked Objects
folder: naked-objects
permalink: /patterns/naked-objects/
pumlid: LSX15i8W30N0g-W187jlaq9igH1uoO_r-BfrDs_kJKkFAc7zTW3B7qJ6LzuRZjZ2nSfKY2ANEQZrk1XiTFARKnLlkwR5W9Ww3VOVIFabDStjb08dGVcVz6mVX4aE6td5w5y0
categories: Architectural
tags:
 - Java
 - Difficulty-Expert
---

## Intent
The Naked Objects architectural pattern is well suited for rapid
prototyping. Using the pattern, you only need to write the domain objects,
everything else is autogenerated by the framework.

![alt text](./etc/naked-objects.png "Naked Objects")

## Applicability
Use the Naked Objects pattern when

* you are prototyping and need fast development cycle
* an autogenerated user interface is good enough
* you want to automatically publish the domain as REST services

## Real world examples

* [Apache Isis](https://isis.apache.org/)

## Credits

* [Richard Pawson - Naked Objects](https://isis.apache.org/resources/thesis/Pawson-Naked-Objects-thesis.pdf)
