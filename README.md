# T1024 MSA Explorer

Interactive, static dashboard for the Clustal Omega multiple sequence alignment of CASP14 target **T1024 (LmrP)** plus nine selected homologs.

## Included
- Interactive colored MSA
- Conservation plot
- Gap-frequency plot
- Sequence logo
- Consensus sequence
- Adjustable conserved-region finder
- Pairwise sequence-identity matrix
- Mapping from alignment columns back to T1024 residue numbers
- Downloadable per-column CSV from the browser

## Data summary
- Sequences: 10
- Alignment columns: 420
- Fully conserved columns: 82
- Source alignment: `clustalo-1024_align.aln-clustal_num`
- Alignment method: Clustal Omega 1.2.4
  No package installation, server, build step, or external JavaScript library is required.

## Metric definitions
**Conservation score** = `(1 - H/log2(20)) × occupancy`, where `H` is Shannon entropy over non-gap amino acids and occupancy is the non-gap fraction in the column.

**Pairwise identity** = identical amino acids divided by alignment columns in which both sequences are non-gap.

**Sequence logo information** = `(log2(20) - H) × occupancy`, with each amino-acid letter receiving height proportional to its frequency.
