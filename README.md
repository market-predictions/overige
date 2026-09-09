# Overige

General-purpose repository for standalone Control work that does not belong to another governed project repository.

## Control intake

Use this repository only for work whose authoritative output can live here.

Supported chat conventions:

```text
[control] task overige: <task description>

[control] sequence overige:
1. <step>
2. <step>
3. <step>
```

Control translates each accepted instruction into governed Mission work and then uses the existing Control V4 Mission → refresh → canonical queue → canonical Runner path.

This repository does not own a scheduler, queue, workflow engine, retry system, or Control runtime state.
