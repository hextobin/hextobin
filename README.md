### Small ML experiments, answered plainly

I run quick, cheap experiments on ideas I'm curious about, then write each one up
as a question and an answer, with enough detail to reproduce it.

<!-- One row per published experiment, newest first. Keep the question and the
answer to one line each, matching the repo README's Question/Answer. -->
| Question | Answer | Repo |
|---|---|---|
| Does planning each clause with a discrete "concept" code help a small story model predict arcs? | No: the codes lowered word loss but didn't pay for themselves | [concepts](https://github.com/hextobin/concepts) |
| Can a polynomial equation solved by Newton replace GELU in a transformer? | No: worse than GELU, barely better than no activation | [polydeq](https://github.com/hextobin/polydeq) |

Each run costs a few dollars on a rented GPU that sets itself up, saves its
results to git and deletes itself when done.
