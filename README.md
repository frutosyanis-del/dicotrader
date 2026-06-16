# DICOTRADER

> Le lexique du marché, du mot le plus simple au jargon de pro.

Dictionnaire de trading interactif, en français. Une page web autonome avec recherche instantanée et filtres par branche — du vocabulaire de base aux concepts de structure de marché, crypto, forex et quant.

**[→ Voir en ligne](https://TON-PSEUDO.github.io/dicotrader)** *(à remplacer par ton URL GitHub Pages ou Netlify)*

---

## Pourquoi

La plupart des glossaires de trading sont soit incomplets, soit payants, soit éparpillés entre l'anglais et le franglais. DICOTRADER rassemble 119 termes au même endroit, en français clair, dans une interface qui se cherche au clavier — pensée d'abord comme un outil d'apprentissage personnel, librement réutilisable.

## Fonctionnalités

- **Recherche instantanée**, insensible aux accents et à la casse — cherche dans les termes *et* les définitions.
- **12 branches** filtrables : marchés, styles, vocabulaire de base, ordres, analyse technique, structure de marché, risque & psycho, macro, crypto, forex, quant, slang.
- **Surlignage** du texte recherché dans les résultats.
- **Zéro dépendance, zéro build** — un seul fichier HTML, JavaScript natif. Ça s'ouvre dans n'importe quel navigateur.
- **Responsive**, lisible sur mobile comme sur desktop.

## Utilisation

Ouvre simplement `index.html` dans ton navigateur. C'est tout.

## Ajouter ou modifier un terme

Tout le contenu vit dans un seul tableau `DATA` à l'intérieur du fichier `index.html`. Pour ajouter un terme, ajoute une ligne :

```js
{ t: "Nom du terme", c: "categorie", d: "La définition, courte et concrète." }
```

Le champ `c` doit correspondre à l'un des identifiants de catégorie suivants :

`marches` · `styles` · `base` · `ordres` · `at` · `structure` · `risque` · `macro` · `crypto` · `forex` · `quant` · `slang`

Aucune compilation nécessaire : tu enregistres, tu rafraîchis la page.

## Hébergement

Deux options gratuites, sans configuration :

- **Netlify Drop** — glisse le dossier sur [netlify.com/drop](https://app.netlify.com/drop), URL immédiate.
- **GitHub Pages** — Settings → Pages → branche `main`. L'URL devient `ton-pseudo.github.io/dicotrader`.

## Contribuer

Les corrections de définitions et les nouveaux termes sont bienvenus. Ouvre une *issue* ou une *pull request* en éditant le tableau `DATA`. Garde les définitions courtes (une à deux phrases) et neutres — pas de conseil en investissement.

## Avertissement

Contenu éducatif uniquement. Rien ici ne constitue un conseil financier ou en investissement. Le trading comporte un risque de perte en capital.

## Licence

[MIT](./LICENSE) — fais-en ce que tu veux.
