# Graph Forge

### A visual playground for graph traversal and path search.

**HTML · CSS · JavaScript** &nbsp;·&nbsp; **Engineering lab** &nbsp;·&nbsp; **Inspect, run, learn**

---

## Why this project matters

A functional standalone, offline-capable browser application, built without vendor API keys or a backend. Open `index.html` locally or deploy the repository as a static website.

The repository is intentionally small enough to read through, with the runtime behavior and design choices visible in the source files.

## Getting started

```bash
python -m http.server 8000
```

Open **http://localhost:8000/**.

## Read the implementation

| Path | Role |
|--|--|
| [`README.md`](./README.md) | Background and documentation |
| [`app.js`](./app.js) | Core implementation |
| [`index.html`](./index.html) | Web application entry point |
| [`style.css`](./style.css) | Responsive visual styling |

## A good way to explore it

1. Run the example using the instructions above.
2. Change a controlled input or simulated condition.
3. Compare what you observe with the source and existing tests.

## Scope

This is an illustrative, local engineering project rather than an independently audited production service. Synthetic data and test scenarios are for learning; do not rely on them for real-world operational guarantees.

<details>
<summary><strong>Detailed original notes and commands</strong></summary>

# Graph Forge

A functional standalone, offline-capable browser application, built without vendor API keys or a backend. Open `index.html` locally or deploy the repository as a static website.

## Engineering notes
- Actual algorithms run inside the browser.
- Sample/generated data is explicitly described as a simulation; uploaded local data stays on-device.
- Accessibility: keyboard-operated controls and readable status output.
- No tracking, cookies, CDN dependencies, or hardcoded credentials.

Run: `python -m http.server 8080` from this directory.

</details>

---

<sub>From [Sharanya Pal's engineering projects](https://github.com/sharanyapal?tab=repositories).</sub>
