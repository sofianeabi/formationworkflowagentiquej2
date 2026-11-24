# Workflow agentique : jour 2

Ressources de la formation « Développer avec l'IA » (Amiltone), jour 2. Rien d'autre que ce dont vous avez besoin aujourd'hui.

## Contenu

| Fichier | Quoi |
|---|---|
| `notes-de-frais.zip` | Le chantier du jour (API de notes de frais), ses cartes de mission et le contrôle automatique |
| `Cartes_de_mission.pdf` | Les cartes de la journée à lire ou imprimer (même contenu que le dossier `cartes/` du zip) |

## Mise en route (5 minutes)

Prérequis : Node.js 20 ou plus, Git, Claude Code à jour (`claude update`). Sous Windows, utilisez Git Bash (installé avec Git for Windows) ou PowerShell 7.

1. Téléchargez `notes-de-frais.zip` et décompressez-le.
2. Dans un terminal :

```bash
cd notes-de-frais
npm install
npm run controle -- doctor
```

3. Les 8 lignes du diagnostic doivent être vertes. Sinon, écrivez la ligne rouge dans le chat Teams.

Ensuite, suivez les cartes dans l'ordre. Chaque carte donne un objectif, un livrable et le contrôle à lancer : `npm run controle -- check <n>`.

## Règles de sécurité du jeu

- Ne lisez jamais le dossier `controle/recettes/` et interdisez-le à votre IA.
- Ne modifiez pas le dossier `controle/`.
- Jamais de mode « bypass permissions ».
- Aucun `git push` : tout reste sur votre poste.
