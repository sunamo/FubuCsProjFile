# FubuCsProjFile

## 1 worktree = 1 větev = 1 PR, nikdy víc

Toto repo trpělo tím, že vzniklo víc souběžných PR z jednoho repa (např. #4 a #3).

- Každý rebase/push jednoho PR rozbije ostatní a vznikají řetězové merge konflikty („šílené mergování“).
- **Závazné pravidlo pro AI:** v tomto repu vždy jen JEDNA worktree (`FubuCsProjFile-claude` s větví `claude`) a jeden PR najednou.
- Před založením nového PR/větve nejdřív dokonči, zamerguj nebo zavři předchozí.
- Nikdy nezakládej druhou souběžnou větev/PR ze stejné worktree ani jinou větev.
