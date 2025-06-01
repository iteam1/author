# author

For the purpose of grammar development

```
                 ┌────────┐
                 │  Code  │
                 └───┬────┘
                     │
                     ▼
                ┌──────────┐
                │  Parser  │
                └────┬─────┘
                     ▼
           ┌──────────────────┐
           │  AST / CST Tree  │
           └────┬──────┬──────┘
                │      │
                │      └──────────────┐
                ▼                     ▼
         ┌────────────┐        ┌───────────────┐
         │ Formatter  │        │   Validator   │
         └────┬───────┘        │ (syntax/sem.) │
              │                └──────┬────────┘
              ▼                       ▼
     ┌────────────────┐     ┌────────────────────┐
     │ Formatted Code │     │  Detailed Report   │
     └──────┬─────────┘     └────────────────────┘
            │
            ▼
        ┌────────┐
        │Visitor │
        └────┬───┘
             ▼
       ┌────────────┐
       │  Insights  │
       └────────────┘

```

## References

- [Language Development](https://www.antlr.org/)
- [](g)