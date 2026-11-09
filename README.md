# Thomas Shanahan

I build automated LiDAR archaeology: detectors that find burial mounds and other earthworks in airborne terrain
data, evaluated against fixed, pre-set rules. I work by directing AI coding agents. Claude Code writes
and runs the code; Codex reviews and checks it; I set the questions, the rules and what counts as evidence. The code
in my repositories is written by agents under my direction.

Based in New Jersey, open to relocating.

## LiDAR archaeology (since September 2026)

- **Confirmed new sites.** Qualified heritage professionals confirmed 4 site locations in Lower Saxony, Germany, as
  previously unknown archaeology. One is a barrow field. These are desk assessments; nothing has been excavated.
- **Record additions.** 16 additions to heritage records and inventories in England, France and Germany. These
  overlap with the 4 above; a record addition is not the same as a discovery. One English county Historic Environment
  Record names me as the source for three mounds first noted on LiDAR.
- **Sealed Dutch test against the public baseline.** I adapted the public ADAF barrow detector (Kostovska et al. 2025,
  [doi:10.5281/zenodo.15848663](https://doi.org/10.5281/zenodo.15848663)). On 1,641 km² of Dutch terrain, at the same
  review workload, my adapted model found 623 of 932 registered barrows and ADAF found 516: +11.5 points
  (simultaneous 95 % interval +7.4 to +15.5). The protocol was frozen before the test data were fetched, scored once
  and recounted independently. This measures recall of registered monuments, not discovery precision.
- **Denmark.** On 171 unseen areas, a later two-checkpoint adapted system (S_D + PROX) found 84.2 % of 5,273 protected barrows, against 72.2 % for
  plain ADAF. Again, recall of known sites.
- **Where it fails.** A temporal holdout showed the detector is nearly blind to one survey campaign's overploughed
  mounds as seen on the Danish elevation model (1 of 242, ADAF 17 of 242). On mounds described as clear on the relief
  map its observed recovery was similar to ADAF's (22 vs 20 of 68). My first summary of this test was too broad because a parser defect let in
  some records; the corrected account is the one above.
- **Work in progress.** Maya, hollow-way and field-dike detectors are development-grade. The Maya results were judged
  by AI model readers, not by archaeologists.

## Public outputs

- Preprint, Nov 2026 (not peer reviewed): [doi:10.5281/zenodo.23874293](https://doi.org/10.5281/zenodo.23874293)
- Preprint, Oct 2026 (not peer reviewed): [doi:10.5281/zenodo.23352619](https://doi.org/10.5281/zenodo.23352619)
- Model weights, CC BY-SA 4.0: [doi:10.5281/zenodo.23862470](https://doi.org/10.5281/zenodo.23862470)
- Code and frozen protocols, Apache-2.0: [tee-20190/ndsbarrow-adapt](https://github.com/tee-20190/ndsbarrow-adapt)
- Two-minute check, no install: [aggregate-results verification demo](https://github.com/tee-20190/ndsbarrow-adapt/tree/main/demo)
  recomputes the Dutch and Danish headline numbers from released files (it does not run detection)

## How I work with agents

- Fix the question, the data, the comparison and the pass/fail rule before running anything, and record them with
  file hashes.
- Keep test terrain sealed until the protocol is frozen; report failures and corrections next to the wins.
- Have a second agent or an independent script recount every number that matters.
- Ask the people who hold the records, and count only their confirmations as confirmations.

## Other work

AI-agent work and self-employment since February 2026: research and data projects for small businesses, including
compliance lead lists built from public records and an acquisition-research package with a ranked target list and a
scenario-tested financial model, and candidate-outreach lists for a recruiting agency. Head freshman baseball coach at
a public high school in New Jersey.
