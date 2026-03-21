### iBERT: Interpretable BERT

Accepted to the Main Proceedings (Oral) of [EACL 2026](https://2026.eacl.org/).

---
- Project Page: [ibert.io](https://ibert.io)

- Deck: [ibert-deck.pdf](https://ibert.io/ibert-deck.pdf)

- Paper: [aclanthology.org/2026.eacl-long.65.pdf](https://aclanthology.org/2026.eacl-long.65.pdf)

- Code and model will be released in April 2026.

---

Citation:
```
@inproceedings{anand-etal-2026-ibert,
    title = "i{BERT}: Interpretable Embeddings via Sense Decomposition",
    author = "Anand, Vishal  and
      Alshomary, Milad  and
      McKeown, Kathleen",
    editor = "Demberg, Vera  and
      Inui, Kentaro  and
      Marquez, Llu{\'i}s",
    booktitle = "Proceedings of the 19th Conference of the {E}uropean Chapter of the {A}ssociation for {C}omputational {L}inguistics (Volume 1: Long Papers)",
    month = mar,
    year = "2026",
    address = "Rabat, Morocco",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2026.eacl-long.65/",
    pages = "1413--1429",
    ISBN = "979-8-89176-380-7",
    abstract = "We present iBERT (interpretable-BERT), an encoder to produce inherently interpretable and controllable embeddings - designed to modularize and expose the discriminative cues present in language, such as semantic or stylistic structure. Each input token is represented as a sparse, non-negative mixture over k context-independent sense vectors, which can be pooled into sentence embeddings or used directly at the token level. This enables modular control over representation, before any decoding or downstream use.To demonstrate our model{'}s interpretability, we evaluate it on a suite of style-focused tasks. On the STEL benchmark, it improves style representation effectiveness by {\textasciitilde}8 points over SBERT-style baselines, while maintaining competitive performance on authorship verification. Because each embedding is a structured composition of interpretable senses, we highlight how specific style attributes get assigned to specific sense vectors. While our experiments center on style, iBERT is not limited to stylistic modeling. Its structural modularity is designed to interpretably decompose whichever discriminative signals are present in the data {---} enabling generalization even when supervision blends semantic or stylistic factors."
}
```
