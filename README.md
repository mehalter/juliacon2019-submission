# SemanticModels.jl: A Julia Package for Scientific Model Augmentation

[![status](https://submissions.juliacon.org/papers/33aac8bcc9f413f18cc1cb3894ad7b57/status.svg)](https://submissions.juliacon.org/papers/33aac8bcc9f413f18cc1cb3894ad7b57)

`SemanticModels.jl` is a package that takes advantage of meta-modeling and
meta-programming to automate model augmentation and creation. We chose Julia for
our project because of the powerful type system, the efficient internal abstract
syntax tree (AST), and the embedded domain specific languages (DSL) that emerge
as a result through the multiple dispatch mechanism for all libraries in the
Julia ecosystem. The dynamic type inference and method generation has
significant and powerful downstream effects which enables dynamic model
manipulation with efficient code generation. These DSLs allow for strong
theoretical category definitions and classifications of models to define
conceptually sound universal rewrite rules for any given model class.
