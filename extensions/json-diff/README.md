<div align="center">
  <img src="assets/extension-icon.png" width="128" alt="JSON Diff" />
  <h1>JSON Diff</h1>
  <p>Paste two JSON snippets and instantly see what changed — right from Raycast.</p>
</div>

## Getting Started

1. Open Raycast and search for **Compare JSON**
2. Paste your original JSON in the first field
3. Paste the modified JSON in the second field
4. Hit Compare to see the diff ✨

The diff view highlights added and removed lines with color-coded syntax, collapses unchanged regions for readability, and shows a summary of total changes.

## Features

- 🔴🟢 **Color-coded diff** — Added lines in green, removed lines in red
- ⚡ **Real-time validation** — Syntax errors appear inline as you type, so you catch issues before comparing
- 🔍 **Compact diff view** — Only changed lines are shown with surrounding context, keeping large diffs readable
- ✨ **Format JSON** — Auto-format both inputs with `Cmd+Shift+F`
- 🔄 **Swap inputs** — Reverse the comparison direction with `Cmd+Shift+S`
- 📋 **Paste from clipboard** — Paste directly into either field with `Cmd+Shift+1` or `Cmd+Shift+2`
- 📤 **Copy results** — Copy the full diff, compact diff, or either formatted JSON from the result view

## How It Works

JSON Diff uses the [Myers diff algorithm](https://en.wikipedia.org/wiki/Diff#Myers_algorithm) to compute the minimal edit distance between two pretty-printed JSON documents. The result is displayed as a compact, syntax-highlighted diff with surrounding context — similar to `git diff` output.

🔒 All processing happens locally.
