# Text Embedding Interface

This is a fork of Huggingface open-sourced embedding model inference server, written in Rust. 
Sphere features are built on top of it.
This repo should be regularly synced with upstream.

## Sync with upstream

```bash
git remote add upstream https://github.com/huggingface/text-embeddings-inference.git

git fetch upstream
git checkout main
git merge upstream/main
```