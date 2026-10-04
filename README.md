# Frontend Platform Engineering — A Working Reference

A single-page reference for the areas a frontend platform engineer is expected to reason about:
web protocols and security, core web platform concepts, performance and bundling, and testing.

**Read it here → https://ravichaudhary8434.github.io/frontend-platform-reference/**

## What's in it

15 sections, ~100 topics, 14 hand-drawn SVG diagrams. Every topic follows the same shape:

- **What it is** — the definition, stated precisely enough to survive a follow-up
- **Example** — code, a header, or a config fragment
- **Trade-offs** — what you give up, and when you'd choose otherwise
- **Follow-ups** — the questions that come next

### Sections

| | |
| --- | --- |
| 2. JavaScript core | execution context, event loop, closures, prototypes, GC |
| 3. TypeScript | structural typing, discriminated unions, runtime validation, monorepo scale |
| 4. Browser internals | critical rendering path, layout/paint/composite, main thread vs compositor |
| 5. Rendering & React | CSR/SSR/SSG/ISR/streaming/islands, hydration, fiber, hooks, state |
| 6. Web protocols | DNS, TCP vs QUIC, TLS, HTTP/1.1–3, idempotency, realtime transports |
| 7. Caching & storage | cache headers, CDN layers, browser storage, service workers |
| 8. Security | XSS, CSP, CORS, CSRF, headers, OAuth/PKCE/JWT, supply chain |
| 9. Performance | Core Web Vitals, measurement, loading, runtime, compression, budgets |
| 10. Bundling | modules, tree shaking, code splitting, bundler comparison, build speed |
| 11. Platform architecture | design systems, packages, monorepos, micro-frontends, edge routing |
| 12. Testing | the trophy, mocking, contract, visual, a11y, flake management |
| 13. Operations | CI/CD, progressive delivery, observability, SLOs, incidents |
| 14. A11y & i18n | WCAG, ARIA patterns, i18n architecture, RTL |
| 15. Applying it | a design framework and worked scenarios |

### Diagrams

Event loop · critical rendering path · rendering-strategy timeline · React render vs commit ·
round trips before first byte · HTTP/1.1 vs 2 vs 3 head-of-line blocking · cache layer stack ·
CORS preflight · OAuth PKCE sequence · Core Web Vitals timeline · chunk graph ·
Module Federation · testing trophy · CI/CD pipeline.

All inline SVG — vector, themeable, and they print cleanly.

## Notes

`index.html` is fully self-contained: no CDN, no build step, no JavaScript dependencies.
It works offline, adapts to your system's light/dark setting, and `Cmd/Ctrl+P` produces a
clean PDF with sensible page breaks.

MIT licensed. Corrections welcome.
