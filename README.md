# Math club lab

Interactive proofs, demos and games for a middle-school MathCounts club.

Live site: https://proofs-without-words.phfhung.workers.dev/

## How it works

- Everything the site serves is in `public/`. Each page is one self-contained HTML file with no build step.
- `public/index.html` is the directory. Add a card there when you add a page.
- Pushing to `main` deploys to Cloudflare automatically (`wrangler.jsonc` tells Cloudflare to serve `public/`).

## Pages

| File | What it is |
|---|---|
| `pythagoras.html` | Five visual proofs of the Pythagorean theorem |
| `heron.html` | Heron's formula in pictures |
| `euclid.html` | Euclid's algorithm for the GCF |
| `bezout.html` | Bézout's identity: frog jumps and a clock |
| `vieta.html` | Vieta's formula, step by step |
| `parabola.html` | Folding a parabola from paper |
| `jugs.html` | The Die Hard jug puzzle |
| `vernier.html` | Reading a vernier caliper, why it works, and a bonus tab on when clock hands meet |
| `newton.html` | Square roots by guess and average (Heron and Newton) |
| `catalan.html` | Catalan numbers: five pictures of one count, the reflection proof, and the recurrence |
| `brackets.html` | Signs and brackets between numbers to hit a target; every bracketing drawn as a tree |
| `derangements.html` | Secret Santa: derangements by sorting every draw, inclusion and exclusion as a running count, the recurrence with arrows, and 1/e |
| `necklaces.html` | Fermat's little theorem by sorting bead strings into necklaces; which numbers pass the test; the test as hops round a clock |
| `squares.html` | Factoring by a difference of two squares: cut and slide, then grow the square until the corner piece is a perfect square |
| `nim.html` | Nim (take 1, 2 or 3): play the computer, see why rows of four win, and the game in 14 lines of Python |
| `prime-sprint.html` | Prime-tapping speed game |

## Trying a change locally

Open any file in `public/` in a browser. No server is needed.
