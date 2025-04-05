# harmonicClustering

Harmonic Clustering is a research-driven project that applies **network science techniques** to uncover **listener communities** from large-scale music streaming logs. Using the **LFM-1b Last.fm dataset**, we build user-user graphs based on temporal playlist overlaps and apply **community detection algorithms** to find natural clusters of music taste.

---

## Motivation

In the era of personalized streaming, users often discover and consume music in unique but overlapping patterns. This project explores how these overlaps can form the basis of **organic music communities**, uncovering hidden listener groups who share similar track interests over time.

---

## Dataset

We use the [LFM-1b Dataset](https://www.cp.jku.at/datasets/LFM-1b/) which contains over 1 billion listening events from Last.fm users.

- Subsampled to ~1 million rows for efficiency.
- Weekly pseudo-playlists are created for each user.
- User similarity is computed via Jaccard index on track overlap.

---

## Methods

- Preprocessing with pandas and NumPy
- Constructing pseudo-playlists from weekly listening history
- Creating a user-user graph based on shared tracks

- Applying **Louvain** or **Label Propagation** for community detection
- Visualizing with NetworkX and matplotlib
---

## Goals

- Understand how music consumption patterns form community structures
- Provide an open-source framework for analyzing music graphs
- Contribute a concise research paper that demonstrates the effectiveness of this approach

---

## Example Visualization

_Coming soon!_ We'll visualize clusters of users and their top shared tracks.

---

## Status

&#x2611; Preprocessing <br>
&#x2612; Similarity matrix + graph construction <br>
&#x2612; Community detection <br>
&#x2612; Graph visualization <br>
&#x2612; Research paper writing

---

## License

This project is under the [MIT License](LICENSE).

---

## 🙌 Contributions

Feel free to fork, contribute, or reach out with ideas and improvements!
