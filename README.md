# public-lab

Bac à sable public. Expérimentations, mini-outils et prototypes sans lien avec un projet client.

## Ce qui a le droit d'être ici

- code d'exemple autonome, qui tourne seul
- bricolages personnels, démos, outils génériques
- tout ce que je suis à l'aise de voir publié sous mon nom de compte

## Ce qui n'y jamais entrera

- données clients, prospects, emails, chiffres d'affaires
- identifiants, clés d'API, tokens, `.env`
- code ou documents appartenant à un projet privé d'un client
- toute production d'un projet sous contrat

Un crochet de pré-commit bloque les patterns évidents de secrets (`sk-`, `ghp_`, clés privées, mots de passe en dur).
Il est utile, ce n'est pas une garantie : la relecture avant un `git push` reste obligatoire.

## Démarrer

```bash
git clone https://github.com/yleporcher/public-lab.git
cd public-lab
git config core.hooksPath .githooks   # active le contrôle des secrets
```

## Licence

MIT — voir [LICENSE](LICENSE).
