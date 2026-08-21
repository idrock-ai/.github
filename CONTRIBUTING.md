# Contributing to IDROCK repositories

Thanks for your interest in our work! This page covers both external
contributions and the standards every IDROCK repository follows.

## For external contributors

- Open an issue before large changes so we can discuss the approach.
- Pull requests should be focused: one change per PR, with a clear description.
- By contributing, you agree that your contribution is licensed under the
  repository's license.

## Lab repository standards

Every repository in the `idrock-ai` organization follows these rules:

1. **License from day one.** Default **Apache-2.0** for code, **CC-BY-4.0**
   for data, unless the project requires otherwise. No unlicensed repos.
2. **Metadata at creation time.** Every repo gets a one-sentence description,
   a homepage link (project page, paper, or idrock.uz), and 3–6 topics.
3. **README skeleton for paper/model repos:**
   logo → badge row (license, arXiv, Hugging Face) → one-paragraph pitch that
   names the lab with a link to [idrock.uz](https://idrock.uz) →
   copy-paste install/quickstart → checkpoint table with per-item Hugging Face
   links → dated `## News` → `## Citation` with BibTeX.
4. **Citation files.** Public research repos include a `CITATION.cff`
   (see [CITING.md](CITING.md)) so GitHub shows the "Cite this repository"
   button.
5. **Naming.** Lowercase-hyphen for tools (`prompt-optimization-audit`),
   product-case for models (`piyola`). Name repos after the system, never the
   paper title.
6. **Lifecycle honesty.** Archive dead repos. When a repo is superseded, add a
   notice at the top of its README pointing to the successor.
7. **Models ship with code.** Every model released on
   [huggingface.co/idrock](https://huggingface.co/idrock) has a corresponding
   GitHub repo with training/eval/inference code, cross-linked with the model
   card.
