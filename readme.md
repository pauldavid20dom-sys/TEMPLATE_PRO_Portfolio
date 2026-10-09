# Minimalist Developer Portfolio — HTML & Tailwind CSS Template

Un template de portfolio moderne, conçu spécifiquement pour les développeurs, designers et créateurs tech. Construit avec **HTML5** et **Tailwind CSS** (via CDN), il est prêt à l'emploi et ne nécessite aucune configuration complexe ou installation de Node.js.

---

## ✨ Fonctionnalités

- **Design Moderne  :** Une esthétique professionnelle axée sur la mise en valeur des projets.
- **Mode Sombre / Clair Natif :** Basculement instantané entre le thème sombre et clair (sauvegardé via `localStorage`).
- **100% Responsive :** Parfaitement adapté aux mobiles, tablettes et ordinateurs de bureau.
- **Prêt à l'emploi :** Pas d'outil de build (*bundler*) requis. Il suffit d'ouvrir le fichier dans un navigateur ou de le déployer directement.
- **Code Propre & Documenté :** Des sections clairement identifiées pour faciliter la personnalisation.

---

## 📂 Structure des Fichiers

```text
portfolio-template/
├── index.html       # Le fichier source unique contenant tout le code
└── README.md        # Guide d'utilisation et documentation
```

---

## 🚀 Guide de Démarrage Rapide

1. Télécharge et décompresse le fichier zip du template.
2. Ouvre le dossier dans ton éditeur de code favori (comme *VS Code*).
3. Double-clique sur le fichier `index.html` pour l'ouvrir dans ton navigateur web et le tester en local.

---

## 🛠️ Personnalisation

Il est très facile de s'approprier ce template en modifiant quelques lignes de texte directement dans le fichier `index.html` :

### 1. Modifier le nom et les textes d'introduction
Recherche les balises contenant `[Votre Nom]` dans le fichier `index.html` et remplace-les par ton nom ou ton identifiant professionnel.

### 2. Mettre à jour les projets
Dans la section `<section id="projects">`, tu trouveras 3 cartes de projets. Pour chaque projet :
- Remplace le texte de substitution `[Image Projet X]` par une véritable image ou capture d'écran (en modifiant la balise ou en insérant une balise `<img>`).
- Modifie les titres, descriptions et tags technologiques selon tes besoins.

### 3. Configurer le formulaire de contact
Par défaut, le formulaire utilise un événement préventif (`onsubmit="event.preventDefault();"`). Pour le rendre pleinement fonctionnel, tu peux :
- Utiliser un service externe gratuit comme [Formspree](https://formspree.io/) ou [Web3Forms](https://web3forms.com/).
- Remplacer l'attribut `action` de la balise `<form>` par l'URL fournie par ton service.

---

## 🌐 Déploiement

Tu peux publier ce site en quelques secondes sur des plateformes d'hébergement statique gratuites :
- **GitHub Pages**
- **Vercel**
- **Netlify**

Glisse simplement ton dossier ou connecte ton dépôt Git, et le site sera en ligne instantanément.

---

## 📄 Licence
Ce template est vendu sous licence standard pour un usage personnel ou commercial (selon la plateforme d'achat). Merci de ne pas revendre ou redistribuer le code brut tel quel sur les plateformes de templates.