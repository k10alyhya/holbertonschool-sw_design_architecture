# UML Intro

## Description

This project introduces UML (Unified Modeling Language) as a tool to model software systems. Working from a textual problem description, the goal is to identify system components and represent them using:

- a **class diagram**, describing the static structure of the system
- a **sequence diagram**, describing how objects interact for a specific use case

Both diagrams are written in [Mermaid](https://mermaid.js.org/) syntax and represent a **Library Loan System**, where a library manages books, users, and loans.

## Learning Objectives

- Extract classes, attributes, and methods from a textual description
- Model relationships between classes (association, aggregation, composition)
- Determine multiplicity from system rules
- Represent a system using UML class diagrams
- Model interactions using UML sequence diagrams
- Use Mermaid syntax to express diagrams

## Requirements

- Ubuntu 20.04
- Mermaid-compatible renderer
- Diagrams use Python-style data types (`str`, `bool`, etc.)
- All names match exactly those used in the problem statement
- No additional elements beyond what is described in the problem

## Files

| File | Description |
| --- | --- |
| `0-class_diagram.mmd` | Class diagram modeling the structure of the Library Loan System: `Library`, `Book`, `User`, and `Loan`, their attributes, methods, and relationships |
| `1-sequence_diagram.mmd` | Sequence diagram modeling the interaction when a user borrows a book, from the initial request to the final loan confirmation |

## Problem Overview

A small library needs to manage its books and users, and to create a loan whenever a user borrows a book. Borrowing a book marks it as unavailable; closing a loan makes the book available again.

## Author

Khaled Al-Yahya
