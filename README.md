# Awesome Diff Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A collaborative list of great tools that show differences between files and folders. Feel free to contribute to this list.

## Contents

- [Source Code](#source-code)
  - [Standard Tools](#standard-tools)
  - [Semantic Diffs](#semantic-diffs)
  - [Diff Enhancers](#diff-enhancers)
- [Other Text Formats](#other-text-formats)
- [Databases](#databases)
- [PDF](#pdf)
- [Binary Data](#binary-data)
- [Folder Comparison](#folder-comparison)

## Source Code

### Standard Tools

The most commonly used tools to display changes between two versions of a source code.

- [GNU Diffutils](https://www.gnu.org/software/diffutils/) - Popular set of tools to compute unified diffs between files, supports two-way and three-way diffs.
- [git (diff)](https://git-scm.com/) - Popular version control system, can compute unified diffs between commits, workings trees, branches, etc.

### Semantic Diffs

Programming language aware diffs that provide additional features like hiding syntax-only changes.

- [diffsitter](https://github.com/afnanenayet/diffsitter) - Terminal utility to generate unified diffs, hides style changes, but doesn't detect moved code.
- [difftastic](https://github.com/Wilfred/difftastic) - Terminal utility to generate side-by-side diffs, hides style changes and supports many languages, but doesn't detect moved code.
- [gumtree](https://github.com/GumTreeDiff/gumtree) - Web/GUI/Text frontend to generate side-by-side diffs, hides style changes and detects moved code.
- [SemanticDiff](https://semanticdiff.com) - VS Code extension/GitHub App to generate side-by-side diffs, hides style changes, detects moved code blocks and simple refactorings.
- [zograscope](https://github.com/xaizek/zograscope) - Terminal utility to generate side-by-side diffs, hides style changes, mostly focused on C/C++.

### Diff Enhancers

Wrappers that enhance the output of an existing diff tool.

- [delta](https://github.com/dandavison/delta) - Pager for (git) diff, adds syntax highlighting, inline and side-by-side view, support for git blame and merge conflicts.
- [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) - Pager for (git) diff, changes colors and highlights inline changes, various options to customize output format.
- [diffr](https://github.com/mookid/diffr) - Pager for git diff, changes colors and highlights inline changes.
- [dunk](https://github.com/darrenburns/dunk) - Postprocesses the output of git diff to generate side-by-side diffs, supports syntax highlighting and highlights inline changes.
- [git-split-diffs](https://github.com/banga/git-split-diffs) - Pager for (git) diff, displays changes like GitHub split diffs (side-by-side diffs) with syntax highlighting.
- [icdiff](https://github.com/jeffkaufman/icdiff) - Standalone application for side-by-side diffs with syntax highlighting.
- [riff](https://github.com/walles/riff) - Wrapper around (`git`) `diff` highlighting which parts of lines that changed.
- [ydiff](https://github.com/ymattw/ydiff) - Pager for git diff, supports unified and side-by-side view, highlights inline changes.


## Other Text Formats

Diff utilities for non-code based text formats.

- [daff](https://github.com/paulfitz/daff) - Library for comparing tables format such as csv files.
- [dyff](https://github.com/homeport/dyff) - Pager for git diff (or standalone) for YAML/JSON, enhances display of changes and their location.
- [Graphtage](https://github.com/trailofbits/graphtage) - Semantic diff for JSON, JSON5, XML, HTML, YAML, CSV.
- [jd](https://github.com/josephburnett/jd) - Creates diffs for JSON/YAML files, also supports patching.
- [JSON Diff](https://www.jsondiff.com/) - Online tool to compute a semantic diff for JSON files.
- [nbdime](https://nbdime.readthedocs.io/en/latest/) - Diffing and merging of Jupyter Notebooks.
- [OpenAPI-diff](https://github.com/OpenAPITools/openapi-diff) - Utility for comparing two OpenAPI specifications.
- [prettier-diff](https://github.com/josephfrazier/prettier-diff) - Wrapper around git diff for JavaScript/JSON, preprocesses the data with a prettifier.
- [xcdiff](https://github.com/bloomberg/xcdiff) - Terminal utility to find differences between two .xcodeproj project files.

## Databases

Diff utilities to compare the schema or content of databases.

- [Another PostgreSQL Diff Tool](https://github.com/fordfrog/apgdiff) - Compares the schema of PostgreSQL dumps.
- [migra](https://github.com/djrobstep/migra) - Compares the schema of PostgreSQL databases and generates migrations.

## PDF

Diff utilities to compare the content of PDF files.

- [diff-pdf](https://vslavik.github.io/diff-pdf/) - Generates a PDF file with visually highlighted differences based on the input PDFs.
- [DiffPDF](https://www.qtrac.eu/diffpdf.html) - Interactive GUI for comparing two PDF files.

## Binary Data

Diff utilities to compare binary data.

- [diffuse](https://github.com/JakeWharton/diffuse) - Compares the content of APKs, AABs, AARs, and JARs.
- [multidiff](https://github.com/juhakivekas/multidiff) - Utility to diff multiple binary objects or streams of data.
- [VBinDiff](https://www.cjmweb.net/vbindiff/) - Side by side comparison of binary data in hex and ascii format.

## Folder Comparison

Diff utilities that can compare the content of whole directories.

- [WinMerge](https://winmerge.org) - Supports code (with syntax highlighting), text, image and CSV files.
- [Meld](https://meldmerge.org/) - Supports text based files, also integrates with version control systems.

## Contributing

Contributing is greatly welcomed! Please read the [Contribution Guidelines](Contributing.md) before taking any action.
