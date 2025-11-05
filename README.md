# AEMT-OSCP
An Automated Evolutionary Modularization Technique for Optimized Sequential Software Source Code Parallelization

graph TD
    A[Source Code Input] --> B[AST Parser]
    B --> C[Code Model Builder]
    C --> D[Dependency Analyzer]
    D --> E[DTMC Model Builder]
    E --> F[Execution Time Estimator]
    F --> G[Genetic Algorithm Optimizer]
    G --> H[Constraint Handler]
    H --> I[Performance Predictor]
    I --> J[Optimized Modularization Output]
    
    K[User Constraints] --> H
    L[Configuration] --> G
    L --> E
    L --> F
    
    style A fill:#e1f5fe
    style J fill:#e8f5e8
    style K fill:#fff3e0
    style L fill:#f3e5f5
