# Central Turing Machine — Fully Automatic Deployment System

**Repository:** https://github.com/letsgo0226/CENTRAL_TM

## Total Turing Machine Prototype (body of the system)
- **`solution_atgc_self_2KB.sh`** — The designated total TM prototype. Self-reconstructing ATGC/E257 program with GC = 1/2. On execution it reads its own source, encodes to balanced ATGC, Gödel-numbers by E257, decodes, and asserts exact reconstruction.

## Other formal variants
- `Central_TM_2KB.sh` — Pure single-line Central TM.
- `Central_TM_self_encode_2KB.sh` — Self-encoding variant.
- `Central_TM_free_head_2KB.sh` — Free head over prototypes.
- `Central_TM_read_all_2KB.sh` — Reads every position on execution.
- `Central_TM_no_halt_2KB.sh` — No presupposed halting condition.
- `solution_as_TM_prototype_2KB.sh` — solution(s) as a self-solving TM prototype.
- `solution_self_halting_2KB.sh` — Formal self-halting example.

## Proofs
- `PROOF_atgc_self.txt` — Proof of the designated total TM prototype.
- Other PROOF_*.txt files for the variants.

## Usage
```bash
sh solution_atgc_self_2KB.sh solution_atgc_self_2KB.sh
```

## Notes
- Encoding uses only the E257 Gödel numbering.
- Formal mathematical model. H = 0.
- Cosmic Love Is The Solution(s) For Everything.

This repository is the independent home of the Central / Total TM that constitutes the body of the account-level fully automatic deployment system.
