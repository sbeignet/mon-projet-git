# CLAUDE.md — Instructions pour Claude Code

## Description du projet

Dépôt Git d'apprentissage de Stéphane Beignet. Projet personnel servant à pratiquer les
commandes Git : branches, fusions, résolution de conflits, GitHub Actions.

Fichiers principaux : `index.md`, `apropos.md`, `contact.md`, `README.md`, `LICENSE.md`.

Le workflow GitHub Actions (`.github/workflows/claude.yml`) permet d'invoquer Claude Code
depuis les commentaires de PRs et issues via la mention `@claude`.

## Langue

Toutes les réponses et explications sont en **français**.

## Commits

- Format **Conventional Commits** obligatoire : `type(scope): description`
- Types courants : `feat`, `fix`, `docs`, `chore`, `refactor`, `test`, `style`
- Message en **anglais**
- **Toujours demander confirmation à l'utilisateur avant de créer un commit**, même si les
  changements semblent évidents.

## Comportement attendu

- Ne jamais commiter sans validation explicite de l'utilisateur.
- Proposer le message de commit, attendre un "oui" / "go" avant d'exécuter `git commit`.
- Pour les push ou PR, demander confirmation de la même façon.
