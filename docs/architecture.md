# Prompt Engineering System - Architecture Diagram

This file contains a Recursive Mermaid.js diagram depicting the power structure of the prompt engineering system.


``mermaid
treeView
\n    PRY(PromptCore) --> CHB(PromptChainBuilder)
    PRY --> DY(DyadEngine)
    PRY --> RO(PromptRouter)
    DY --> PS<PromptStore>
    RO --> ME(MetaAI)
    ME --> Ex(EquinoxAI)
    Ex --> DO(Decision Output)
```

This diagram stages the flow from input, through the different arkc subsystems, to decision generation.