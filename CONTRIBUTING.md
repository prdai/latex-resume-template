# Contributing

Thanks for taking the time to contribute! Here's how to get involved.

## Ways to Contribute

- **Bug fixes** — spotted a broken macro, misaligned spacing, or a LaTeX compilation error? Open an issue or submit a fix.
- **Template improvements** — layout tweaks, new section variants, better defaults.
- **Documentation** — clearer instructions, examples, or additional guidance in `GUIDELINES.md`.
- **Compatibility** — testing with different LaTeX distributions (TeX Live, MiKTeX, Overleaf) and reporting results.

## Getting Started

1. Fork this repository.
2. Create a feature branch from `main`:
   ```bash
   git checkout -b feature/your-change
   ```
3. Make your changes.
4. Verify the template compiles cleanly:
   ```bash
   pdflatex template.tex
   ```
5. Open a pull request against `main` with a clear description of what changed and why.

## Pull Request Guidelines

- Keep PRs focused — one change per PR is easier to review.
- If you're changing the layout, attach a compiled PDF preview so reviewers can see the result.
- Update `README.md` or `GUIDELINES.md` if your change affects usage or best practices.

## Reporting Issues

Open a GitHub Issue and include:
- What you expected to happen.
- What actually happened.
- Your LaTeX distribution and version.
- A minimal reproduction snippet if relevant.

## Code Style

- Use consistent indentation (two spaces for LaTeX source).
- Keep placeholder text in `[square brackets]` so it's easy to grep and replace.
- Avoid adding packages that are not available in a standard TeX Live installation.

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).
