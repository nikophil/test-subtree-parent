# test-subtree-parent

Monorepo de test. Le contenu de `packages/child/` est synchronisé (split en lecture seule)
vers le repo [`nikophil/test-subtree-child`](https://github.com/nikophil/test-subtree-child)
à chaque push sur `main`, via `danharrin/monorepo-split-github-action`.
