# Raw simulation data

Download Tau5_bAIes_review_raw_data.zip from this repository’s Releases page.

SHA-256: `7bc464513a9aa845b9bc68dcae778200d8fae16b58dad065473eb6a9a69997ea`

Includes all saved WT/AA trajectory segments, topology, parameters, checkpoints, portable states, logs, force field/CMAP, and the actual runner. Binary CPU checkpoints require a compatible platform; use XML states across hardware. The GPU runner uses single precision. Scripts preserve original absolute paths as provenance; adapt them to the extraction location before reuse. Ignore transfer_unused.xtc, if present: it was produced by the zero-step state-export operation and is not a trajectory segment.
