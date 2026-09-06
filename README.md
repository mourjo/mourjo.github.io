# mourjo.me

Source for [mourjo.me](https://mourjo.me) — personal website of Mourjo Sen.

## Setup

After cloning, configure git to use the project's commit hooks:

```bash
git config core.hooksPath .hooks
```

This enables a **pre-commit hook** that automatically regenerates `slides.html` with the current contents of the `slides/` directory whenever you commit.
