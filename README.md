# Q5 five-model corpus graph

[Open the live GPU-rendered graph](https://rickeybennett87-stack.github.io/q5-five-model-corpus-graph/)

This dedicated GitHub Pages repository visualizes the indexed contents of the
[Cross-Temporal Data Drop Experiment](https://github.com/rickeybennett87-stack/cross_temporal_data_drop_experiment)
as a five-dimensional graph projected into an interactive WebGL scene.

The five model dimensions are ChatGPT, Claude, Gemini, Grok, and Copilot. Five
independently switchable edge layers expose model affinity, subject,
chronology, repository provenance, and filename/content correlation. Search
and filters rebuild only visible GPU buffers and enabled edge layers;
continuous five-dimensional rotation is performed by the WebGL vertex shader.

## Coverage

- 3,647 repository files
- 17 GitHub release assets
- 3,664 total graph nodes
- 1,267,820,307 repository bytes
- 17,047,182,063 release-asset bytes
- 18,315,002,370 total represented bytes

Generated visualization files are excluded from their own source inventory to
prevent a self-changing index.

## Evidence boundary

Coordinates and subject labels are retrieval signals derived from repository
paths, bounded text prefixes, and known archive structure. They are not claims
of authorship, scientific validity, model cognition, or causal relationships.
Edge layers express indexable relationships and can be inspected independently.

## Rebuild

Run `build_q5_corpus_graph.py` against the archive repository and package the
resulting JSON as `window.Q5_DATA=<json>;` in `q5-corpus-data.js`. The JSON is
retained separately for database ingestion and reproducibility.
