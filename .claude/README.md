# Configuration Claude Code

Ces fichiers proviennent de la marketplace officielle
[claude-plugins-official](https://github.com/anthropics/claude-plugins-official)
d'Anthropic. Ils sont copiés directement dans le dépôt plutôt qu'installés via
`/plugin`, afin de fonctionner aussi dans les sessions distantes (Claude Code
sur le web), où le système de plugins n'est pas disponible.

## Contenu

| Chemin | Source | Rôle |
|---|---|---|
| `skills/frontend-design/` | plugin `frontend-design` | Se charge automatiquement lors du travail sur l'interface : direction artistique, typographie, choix visuels non génériques. |
| `commands/commit.md` | plugin `commit-commands` | `/commit` — crée un commit à partir des changements en cours. |
| `commands/commit-push-pr.md` | plugin `commit-commands` | `/commit-push-pr` — commit, push, puis ouverture d'une pull request. |
| `commands/clean_gone.md` | plugin `commit-commands` | `/clean_gone` — supprime les branches locales dont la branche distante a disparu. |

Les licences d'origine sont conservées (`LICENSE`, `LICENSE.txt`).

## Mise à jour

Ces fichiers sont une copie figée. Pour récupérer une version plus récente,
reprendre les fichiers correspondants depuis le dépôt source.
