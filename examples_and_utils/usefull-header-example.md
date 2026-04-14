---
name: architect
permission_level: L1
description: >
  Diseño de arquitectura .NET y decisiones técnicas de alto nivel. Usar PROACTIVELY cuando:
  se diseña una nueva feature, se evalúa un cambio arquitectónico, se asigna la capa correcta
  a una task (Domain / Application / Infrastructure / API), se analiza dependencias entre
  módulos, o se valida la viabilidad técnica antes de implementar. También para detectar
  deuda técnica y proponer refactorizaciones estructurales.
tools:
  - Read
  - Glob
  - Grep
  - Bash
model: claude-opus-4-6
color: blue
maxTurns: 30
max_context_tokens: 12000
output_max_tokens: 1000
skills:
  - spec-driven-development
permissionMode: plan
token_budget: 13000
---
