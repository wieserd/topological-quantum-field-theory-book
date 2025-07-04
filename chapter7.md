# Chapter 7: Other Examples of QTFTs (Brief Overview)

## 7.1 BF Theory

While [Chern-Simons theory](/BOOK/glossary/chern_simons_theory.md) stands out as a prominent example of a [Quantum Topological Field Theory (QTFT)](/BOOK/glossary/quantum_topological_field_theory.md), it is by no means the only one. There are other fascinating topological field theories that offer different perspectives and applications. One such theory is **BF theory**, which is a topological field theory that can be defined in any dimension. Its simplicity and generality make it a valuable tool for understanding [topological invariants](/BOOK/glossary/topological_invariants.md) and their connections to geometry. Think of BF theory as a very general framework for describing topological properties, almost like a blank canvas that can be specialized to different dimensions and contexts.

### The BF Action

BF theory is characterized by its [action](/BOOK/glossary/action.md), which involves a 2-form field `B` and a connection 1-form `A` (similar to the [gauge field](/BOOK/glossary/gauge_field.md) in [Chern-Simons theory](/BOOK/glossary/chern_simons_theory.md)). The [action](/BOOK/glossary/action.md) is given by:

S_BF = ∫_M Tr(B ∧ F)

where:
*   `M` is the spacetime [manifold](/BOOK/glossary/manifold.md) of arbitrary dimension.
*   `B` is a Lie algebra-valued 2-form field.
*   `F` is the curvature 2-form of the connection `A`, defined as `F = dA + A ∧ A`.
*   `Tr` denotes a trace over the Lie algebra indices.
*   `∧` denotes the wedge product of [differential forms](/BOOK/glossary/differential_forms.md).

Similar to [Chern-Simons theory](/BOOK/glossary/chern_simons_theory.md), the BF [action](/BOOK/glossary/action.md) is purely topological, meaning it does not depend on a metric. This implies that the classical equations of motion for BF theory are also topological, and the theory is invariant under continuous deformations of the [manifold](/BOOK/glossary/manifold.md). The fields `B` and `A` are not dynamical in the conventional sense; their equations of motion simply enforce topological constraints.

### Properties and Significance

BF theory is significant for several reasons:

*   **Generality:** It can be defined in any dimension, making it a versatile framework for studying topological properties in various contexts.
*   **Connection to Gravity:** In certain dimensions and with specific gauge groups, BF theory can be related to theories of gravity. For example, in 4 dimensions, BF theory can be seen as a precursor to general relativity, where the `B` field is related to the tetrad and the `A` field to the spin connection.
*   **[Topological Invariants](/BOOK/glossary/topological_invariants.md):** The observables of BF theory are [topological invariants](/BOOK/glossary/topological_invariants.md) of the [manifold](/BOOK/glossary/manifold.md), such as intersection numbers or linking numbers. This makes it a powerful tool for probing the topological structure of spacetime.
*   **Simplicity:** Its relatively simple structure makes it a good starting point for understanding more complex topological field theories.

## 7.2 Gravity in 2+1 Dimensions

One of the most intriguing applications of [Quantum Topological Field Theory](/BOOK/glossary/quantum_topological_field_theory.md) is in the study of **gravity in 2+1 dimensions** (two spatial dimensions and one time dimension). Unlike 3+1 dimensional general relativity, which is a highly complex and non-renormalizable theory, gravity in 2+1 dimensions is a much simpler, yet still insightful, theory that turns out to be purely topological. This makes it a valuable toy model for understanding quantum gravity. Imagine a world where gravity isn't about the curvature of spacetime, but about its fundamental connectivity and holes, much like the difference between drawing on a flat piece of paper versus drawing on the surface of a donut.

### Einstein Gravity in 2+1 Dimensions

In 2+1 dimensions, the Einstein-Hilbert [action](/BOOK/glossary/action.md), which describes general relativity, simplifies considerably. The Riemann curvature tensor, which describes the curvature of spacetime, can be expressed in terms of the Ricci tensor and scalar curvature. Crucially, in 2+1 dimensions, there are no propagating gravitational degrees of freedom. This means that gravitational waves, which are a key feature of 3+1 dimensional gravity, do not exist in 2+1 dimensions. The only non-trivial solutions to Einstein's equations in vacuum are flat spacetime or spacetimes with conical singularities (points with deficit angles).

### Connection to Chern-Simons Theory

The remarkable connection is that 2+1 dimensional Einstein gravity with a cosmological constant can be formulated as a **[Chern-Simons theory](/BOOK/glossary/chern_simons_theory.md)** with a specific gauge group. For a positive cosmological constant, the gauge group is SO(3,1) or SO(2,2), and for a negative cosmological constant, it is SO(2,1) x SO(2,1). This formulation was pioneered by Edward Witten and highlights the topological nature of gravity in this lower dimension.

This means that the quantum theory of gravity in 2+1 dimensions is a [topological quantum field theory](/BOOK/glossary/quantum_topological_field_theory.md). Its observables are [topological invariants](/BOOK/glossary/topological_invariants.md), and the theory is exactly solvable. This solvability makes it an excellent laboratory for exploring conceptual issues in quantum gravity, such as the nature of spacetime at the quantum level, the role of topology, and the emergence of geometry from a more fundamental topological structure.

### Implications for Quantum Gravity

While 2+1 dimensional gravity is a simplified model, it offers valuable insights into the challenges and potential approaches to a full theory of quantum gravity. It suggests that topology might play a more fundamental role in quantum gravity than previously thought. The fact that a theory of gravity can be purely topological in lower dimensions raises questions about whether similar topological structures might underlie gravity in higher dimensions, perhaps in a more subtle way.

Furthermore, the connection to [Chern-Simons theory](/BOOK/glossary/chern_simons_theory.md) provides a concrete example of how a theory of gravity can be quantized and how its quantum states can be understood in terms of [topological invariants](/BOOK/glossary/topological_invariants.md). This has inspired various approaches to quantum gravity, including loop quantum gravity and string theory, which also emphasize the role of discrete structures and topological properties.

## 7.3 Exercises

1.  **BF Theory Concepts:**
    *   Explain the key features that make BF theory a topological field theory. How does its [action](/BOOK/glossary/action.md) differ from that of conventional field theories?
    *   Discuss the significance of BF theory's generality, i.e., its ability to be defined in any dimension. How does this make it a versatile tool for studying topological properties?
    *   In what ways can BF theory be related to theories of gravity? Provide an example.

2.  **Gravity in 2+1 Dimensions:**
    *   Why is gravity in 2+1 dimensions considered a purely topological theory, unlike gravity in 3+1 dimensions?
    *   Explain the connection between 2+1 dimensional Einstein gravity and [Chern-Simons theory](/BOOK/glossary/chern_simons_theory.md). What are the implications of this connection for understanding quantum gravity?
    *   Discuss how the solvability of 2+1 dimensional quantum gravity makes it a valuable toy model for exploring conceptual issues in quantum gravity.

3.  **Comparison of QTFTs:**
    *   Compare and contrast [Chern-Simons theory](/BOOK/glossary/chern_simons_theory.md) and BF theory. What are their similarities and differences in terms of their actions, dimensions, and primary applications?
    *   Both [Chern-Simons theory](/BOOK/glossary/chern_simons_theory.md) and BF theory are examples of [topological quantum field theories](/BOOK/glossary/quantum_topological_field_theory.md). What common characteristics do they share that define them as QTFTs?