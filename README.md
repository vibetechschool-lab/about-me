# Portfolio · Khalil Bergaoui

Site personnel de **Khalil Bergaoui**, fondateur de **LavaCode**, développeur Full-Stack et formateur en informatique.

- Trilingue : français, anglais, arabe (bouton FR / EN / عربي, mise en page RTL pour l'arabe)
- Style LavaCode : fond sombre, dégradé orange « lava »
- 100 % statique : un seul `index.html` + le dossier `assets/`, aucune installation

## Structure

```
index.html                  la page (HTML, CSS et JavaScript)
assets/khalil-bergaoui.jpg  photo
assets/lavacode-icon.png    icône LavaCode (favicon)
assets/lavacode-logo.jpg    logo LavaCode
.nojekyll                   indique à GitHub Pages de servir les fichiers tels quels
```

## Mise en ligne

### GitHub Pages
1. Envoyer ces fichiers dans un dépôt **public** (par exemple `portfolio`).
2. **Settings → Pages → Deploy from a branch → `main` / `(root)` → Save**.
3. Le site est disponible sur `https://<organisation>.github.io/portfolio/` après 1 à 2 minutes.

### Vercel ou Netlify
Importer le dépôt, choisir **Other / aucun framework**, laisser la commande de build vide et le dossier de sortie à la racine.

## Modifier le contenu
- Textes français : directement dans `index.html`.
- Textes anglais et arabes : objet `T` en bas de `index.html` (clés `en` et `ar`).
- Coordonnées : section `id="contact"`.
