# Pattes au chaud

Guides d'achat pour les propriétaires d'animaux au Québec, avec liens d'affiliation Amazon.ca.

- **Site** : https://lattendu1987-dev.github.io/pattes-au-chaud/
- **Plan** : [`docs/PLAN.md`](docs/PLAN.md)
- **Contenu** : tout est dans [`config/site.toml`](config/site.toml) (guides, identifiant Amazon).

```bash
python -m pattes site          # génère le site dans public/
python -m pattes affiliation   # simulation des commissions
python -m unittest discover -s tests -t .
```

Chaque mise à jour de `main` régénère le site et le publie sur la branche `gh-pages`.
