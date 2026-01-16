# leetcode-learning

A personal LeetCode study repository collecting solved problems and reference solutions. Each problem is stored as a Markdown file (problem number + slug) with one or more solution approaches implemented in languages such as C#, Python, SQL, and shell.

Quick link to the repository search (may show more files): https://github.com/huiyufeng-hyf/leetcode-learning/search?q=path%3A%2F

## What this repo contains
- Exercise Problems: Markdown files for individual LeetCode problems, typically named `NNNN.title.md` (for example `0069.sqrtx.md`).
- Each problem file usually includes:
  - A link to the LeetCode problem
  - One or more solution implementations (C#, Python, SQL, shell, etc.)
  - Short explanation or notes where helpful

## Languages and tools
- Primary languages used in solutions: C#, Python
- Other snippets/styles: SQL (T-SQL), shell commands (awk/sed), and general pseudocode in Markdown
- Most solutions are standalone code blocks that can be run on LeetCode, or executed locally after minor wrapping (e.g., placing C# code into a .NET console project or running Python scripts directly).

## Repository structure (example)
- Exercise Problems/
  - 0001.two-sum.md
  - 0069.sqrtx.md
  - 0195.tenth-line.md
  - ...
- (Feel free to add directories for categorized problems, tags, or language-specific folders if desired.)

## How to use
1. Browse the `Exercise Problems/` directory and open the Markdown file for a problem you want to study.
2. Solutions are provided inline in code blocks. For Python, run the code with:
   - python3 <script>.py (you may need to convert the snippet to a runnable file and add I/O or test harness)
3. For C# snippets:
   - Paste the solution class into LeetCode's editor
   - Or create a small .NET project (dotnet new console) and adapt the code into a test harness to run locally
4. SQL and shell snippets typically show concise commands or queries — run them in the appropriate environment (DB client, shell).

## Quickstart example
- Read the file `Exercise Problems/0069.sqrtx.md` for different implementations of `mySqrt`.
- To test a Python solution locally:
  1. Copy the code into a file, e.g. `0069_sqrtx.py`
  2. Add a small test harness or call the function with sample inputs.
  3. Run `python3 0069_sqrtx.py`.

## Contribution guidelines
- Add new problems to `Exercise Problems/` using the naming convention: `NNNN.slug.md`
  - Include the LeetCode problem link at the top
  - Provide one or more solution blocks with language labels (```python / ```csharp / ```sql / ```bash)
  - Add a short explanation or complexity analysis if helpful
- If adding runnable projects (language-specific), consider creating subfolders per language (e.g., `python/`, `csharp/`) with a README describing how to run tests.
- Keep code examples small and focused; prefer clear, idiomatic solutions.

## Suggested improvements
- Add a top-level README (this file) — done.
- Add a CONTRIBUTING.md with preferred formatting & example templates.
- Add a LICENSE file to clearly define reuse permissions.
- Optionally add tags or a JSON/CSV index mapping problem numbers to languages implemented and difficulty for easier navigation.

## License
- No license included in this README. If you want this repository to be reusable, add a LICENSE file (MIT, Apache-2.0, etc.) and I can help create one.

## Contact
- Repo owner: huiyufeng-hyf
- If you'd like, I can:
  - Generate a CONTRIBUTING.md template
  - Convert a subset of problems into runnable Python or C# projects
  - Add badges for build/CI or language stats

(Notes: I reviewed several problem files in `Exercise Problems/` to build this summary; search results used may be incomplete — view more with the repo search link above.)
