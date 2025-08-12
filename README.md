# Bonjour Nga

Le blog de mes 4 voyages au Vietnam, présenté comme une série TV (4 saisons), avec photos, vidéos et itinéraires.

## Aperçu

- **Blog personnel** sur le Vietnam, façon série TV : 4 saisons = 4 voyages.
- Hébergé gratuitement sur **GitHub Pages**.
- Thème : Minimal Mistakes Jekyll (moderne, responsive).

## Structure

- `index.md` : accueil, liens vers chaque saison
- `saison-1.md`, `saison-2.md`, etc. : une page par voyage
- `_pages/about.md` : à propos
- `_data/navigation.yml` : navigation principale
- `assets/images/` : tes photos et visuels

## Installation locale

1. Installe [Ruby](https://www.ruby-lang.org/fr/) et [Bundler](https://bundler.io/).
2. Clone le dépôt :
   ```sh
   git clone https://github.com/francknga/bonjournga.git
   cd bonjournga
   ```
3. Installe les dépendances :
   ```sh
   bundle install
   ```
4. Lance le serveur local :
   ```sh
   bundle exec jekyll serve
   ```
5. Ouvre [http://localhost:4000](http://localhost:4000)

## Déploiement

Le site se déploie **automatiquement** sur chaque push sur la branche `main` grâce à GitHub Actions.

## Domaine personnalisé

- Le fichier `CNAME` est déjà prêt avec `bonjournga.com`
- Configure ce domaine dans les paramètres GitHub Pages du dépôt (voir [aide GitHub](https://docs.github.com/fr/pages/configuring-a-custom-domain-for-your-github-pages-site)).

## Ajouter ton contenu

- Remplace les textes, photos, vidéos dans chaque page de saison.
- Pour les images : place-les dans `assets/images/saisonX/` puis lie-les dans tes pages Markdown.
- Pour les cartes : exemple avec Leaflet dans `saison-1.md`.

---

> Pour toute question, édite ce dépôt ou contacte-moi sur GitHub !