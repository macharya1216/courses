# Propositional Logic Overview

## Core Components of Propositional Logic

### 1. **Propositions (Atomic Statements)**
- Simple declarative statements that are either true or false
- Examples: "It is raining", "2 + 2 = 4", "The door is open"
- Usually represented by variables: P, Q, R, etc.

### 2. **Logical Connectives (Operators)**
- **Negation (¬)**: "NOT" - flips truth value
- **Conjunction (∧)**: "AND" - true only when both parts are true
- **Disjunction (∨)**: "OR" - true when at least one part is true
- **Implication (→)**: "IF...THEN" - false only when premise is true and conclusion is false
- **Biconditional (↔)**: "IF AND ONLY IF" - true when both parts have same truth value

### 3. **Truth Tables**
- Systematic way to show all possible truth value combinations
- Used to define how operators work
- Essential for evaluating complex expressions

### 4. **Logical Equivalences**
- **De Morgan's Laws**: ¬(P ∧ Q) ≡ ¬P ∨ ¬Q
- **Distributive Laws**: P ∧ (Q ∨ R) ≡ (P ∧ Q) ∨ (P ∧ R)
- **Identity Laws**: P ∧ True ≡ P
- **Absorption Laws**: P ∧ (P ∨ Q) ≡ P

### 5. **Logical Forms**
- **Tautologies**: Always true (P ∨ ¬P)
- **Contradictions**: Always false (P ∧ ¬P)
- **Contingencies**: Sometimes true, sometimes false

### 6. **Inference Rules**
- **Modus Ponens**: If P→Q and P, then Q
- **Modus Tollens**: If P→Q and ¬Q, then ¬P
- **Hypothetical Syllogism**: If P→Q and Q→R, then P→R

### 7. **Applications**
- **Logic Circuits**: Computer hardware design
- **Programming**: Conditional statements, boolean logic
- **Mathematical Proofs**: Foundation for reasoning
- **Philosophy**: Analyzing arguments
- **AI/Expert Systems**: Decision making

## Key Characteristics
- Deals only with truth values (true/false)
- No quantifiers (unlike predicate logic)
- Compositional: meaning of complex statements depends on parts
- Decidable: can always determine if a statement is true/false

## Basic Truth Tables

### Negation (¬P)
| P | ¬P |
|---|----| 
| T | F  |
| F | T  |

### Conjunction (P ∧ Q)
| P | Q | P ∧ Q |
|---|---|-------|
| T | T | T     |
| T | F | F     |
| F | T | F     |
| F | F | F     |

### Disjunction (P ∨ Q)
| P | Q | P ∨ Q |
|---|---|-------|
| T | T | T     |
| T | F | T     |
| F | T | T     |
| F | F | F     |

### Implication (P → Q)
| P | Q | P → Q |
|---|---|-------|
| T | T | T     |
| T | F | F     |
| F | T | T     |
| F | F | T     |

### Biconditional (P ↔ Q)
| P | Q | P ↔ Q |
|---|---|-------|
| T | T | T     |
| T | F | F     |
| F | T | F     |
| F | F | T     |

## Important Logical Equivalences

### De Morgan's Laws
- ¬(P ∧ Q) ≡ ¬P ∨ ¬Q
- ¬(P ∨ Q) ≡ ¬P ∧ ¬Q

### Distributive Laws
- P ∧ (Q ∨ R) ≡ (P ∧ Q) ∨ (P ∧ R)
- P ∨ (Q ∧ R) ≡ (P ∨ Q) ∧ (P ∨ R)

### Identity Laws
- P ∧ True ≡ P
- P ∨ False ≡ P
- P ∧ False ≡ False
- P ∨ True ≡ True

### Absorption Laws
- P ∧ (P ∨ Q) ≡ P
- P ∨ (P ∧ Q) ≡ P

### Double Negation
- ¬¬P ≡ P

### Implication Equivalence
- P → Q ≡ ¬P ∨ Q

## Common Inference Patterns

### Modus Ponens
```
Premise 1: P → Q
Premise 2: P
Conclusion: Q
```

### Modus Tollens
```
Premise 1: P → Q
Premise 2: ¬Q
Conclusion: ¬P
```

### Hypothetical Syllogism
```
Premise 1: P → Q
Premise 2: Q → R
Conclusion: P → R
```

### Disjunctive Syllogism
```
Premise 1: P ∨ Q
Premise 2: ¬P
Conclusion: Q
```

This forms the foundation for more advanced logic systems like predicate logic, modal logic, and formal reasoning systems.
