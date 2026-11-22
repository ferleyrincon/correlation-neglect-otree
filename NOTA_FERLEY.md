# Note on this fork

**This is not original work of this account.** It is an unmodified copy (fork) of

> **[duarte-rlp/parents](https://github.com/duarte-rlp/parents)** — oTree code by **Rafael Duarte**.

The copy exists only so that a working paper by Ferley Rincón can cite a stable, citable snapshot
of the code that was used in the field. All credit for the code belongs to its author. No file of
the original code and no commit of its history has been modified in this fork; the only file added
is this note.

## What the code is

The oTree implementation of the correlation-neglect field experiment run in Brazil. Screens are in
Portuguese (pt-BR). Session config `general` chains the apps `home`, `training`,
`real_effort_numbers`, `checker1`, `choice`, `choice_2`, `couple`, `real`, `payoff_choice`,
`survey` and `final`.

## Why this snapshot

- Fork point: commit [`2620c82`](https://github.com/duarte-rlp/parents/commit/2620c82) ("Text
  changes", 5 March 2024), the tip of the original `master`.
- Field work: 35 sessions between February and 3 April 2024; the treatment started on 4 March 2024.
- A 2026 check of the two field exports found that they contain exactly the apps of the `general`
  session and that **every** variable in the data is defined in this code. An earlier pilot
  (October 2023) used a different survey that is no longer in the code.

<!-- TODO (Ferley): pedir a Rafael Duarte que confirme que `2620c82` estuvo en el servidor durante
     todo el trabajo de campo (hubo commits de texto en febrero de 2024). -->

## Where to report issues or send improvements

Open issues and pull requests in the original repository,
**https://github.com/duarte-rlp/parents**, not here.

## Licence

Whatever licence the original repository carries applies to all of its files. This note is the only
file added by this account and is released under the MIT licence.
