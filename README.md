# 🧰 MC88 Web Tools — Suite de création de sites sans code

Trois outils 100 % gratuits, légers et **sans aucune installation** pour créer des pages web complètes sans écrire une seule ligne de code.  
Tous les outils fonctionnent **entièrement dans votre navigateur** (aucun serveur, aucune connexion Internet après le premier chargement).

---

## 📦 Contenu du dépôt

| Fichier | Description |
|---------|-------------|
| `tft-mc88.html` | Transforme du texte brut en HTML sémantique propre. |
| `styleme-mc88.html` | Permet de styliser visuellement n'importe quel élément HTML (CSS généré automatiquement). |
| `scriptme-mc88.html` | Bibliothèque de fonctionnalités JavaScript prêtes à l'emploi (menus, sliders, popups…). |

---

## 🚀 Démarrage rapide

1. **Téléchargez** les trois fichiers `.html` dans un même dossier sur votre ordinateur.
2. **Double-cliquez** sur le fichier souhaité pour l'ouvrir dans votre navigateur.
   - Pas besoin d'Internet, pas de serveur, pas de compilation.
3. Utilisez les outils dans l'ordre recommandé :
   1. **TFT MC88** → écrivez votre contenu et exportez le HTML.
   2. **STYLEME MC88** → importez ce HTML et personnalisez les couleurs, effets, textes.
   3. **SCRIPTME MC88** → ajoutez des interactions (menu, modale, slider…) en copiant ou téléchargeant le code.

---

## 🧩 TFT MC88 — Texte → HTML

### Objectif
Écrire du contenu de manière simple, puis obtenir un fichier HTML prêt à l'emploi.

### Utilisation
1. **Tapez ou collez** votre texte dans la zone de gauche.
2. **Sélectionnez** un morceau de texte.
3. **Cliquez sur un outil** dans la barre supérieure :
   - Titre, sous‑titre, paragraphe
   - Gras, italique
   - Liste, citation
   - Lien, image, bouton, vidéo, audio, séparateur
4. Le **panneau de droite** affiche l'aperçu en temps réel.
5. **Exportez** :
   - bouton **Copier** → copie le HTML brut
   - bouton **Télécharger** → enregistre un fichier `.html` complet

> 💡 **Astuce** : le fichier téléchargé peut être renommé `index.html` et déposé tel quel sur un hébergeur.

---

## 🎨 STYLEME MC88 — Studio CSS visuel

### Objectif
Donner du style à une page HTML existante (ou créée avec TFT) sans écrire de CSS.

### Utilisation
1. **Ouvrez** `styleme-mc88.html`.
2. Une page de démonstration s'affiche déjà.
   - Pour importer **votre propre HTML**, cliquez sur **« Import »** et collez‑le.
3. **Cliquez sur n'importe quel élément** dans l'aperçu (titre, bouton, carte…).
   - Un cadre violet apparaît autour de l'élément sélectionné.
4. Utilisez les **panneaux du bas** pour modifier :
   - **Couleur** : palette rapide, couleur de fond, couleur de texte
   - **Effets** : arrondi, ombre portée, opacité, animations (15 effets)
   - **Texte** : taille, graisse, alignement
   - **Page** : fond, couleur de texte, espacement global
5. **Exportez** le CSS généré :
   - Bouton **« Export »** → télécharge `styleme-export.css`
   - Liez ce fichier à votre HTML avec `<link rel="stylesheet" href="styleme-export.css">`

> ✅ Chaque élément reçoit automatiquement un identifiant unique pour éviter les conflits.

---

## ⚙️ SCRIPTME MC88 — Bibliothèque de fonctionnalités JavaScript

### Objectif
Ajouter des interactions prêtes à l'emploi à votre site, sans connaître JavaScript.

### Utilisation
1. **Ouvrez** `scriptme-mc88.html`.
2. Parcourez les **14 fonctionnalités** classées par catégories :
   - Navigation (menu mobile, défilement fluide, retour en haut)
   - Contenu (onglets, accordéon, slider d'images)
   - Interaction (popup, mode sombre, copie presse‑papiers, validation de formulaire)
   - Feedback (compteur animé, apparition au défilement, notifications toast, effet machine à écrire)
3. **Cliquez sur une carte** pour ouvrir le détail :
   - **Aperçu en direct** de la fonctionnalité
   - Onglets **HTML / CSS / JS** avec le code complet
   - Onglet **« How to use »** expliquant en français simple où coller chaque partie
4. **Copiez** le code ou **téléchargez** un fichier HTML autonome de la fonctionnalité.

> 🔧 Chaque fonctionnalité est autonome : il suffit de coller le HTML, le CSS et le JS aux bons endroits de votre page.

---

## 🔗 Les trois outils ensemble

1. **TFT MC88** → générez le contenu et la structure.
2. **STYLEME MC88** → importez le HTML de TFT et personnalisez l'apparence.
3. **SCRIPTME MC88** → choisissez une fonctionnalité (ex. menu mobile) et collez son code dans la page stylée.

Le résultat est un site complet, responsive et moderne, sans aucune connaissance en programmation.

---

## 🛠️ Dépannage

### Problème 1 : Les fichiers ne s'ouvrent pas
- **Cause** : certains navigateurs bloquent les fichiers locaux.
- **Solution** : double‑cliquez à nouveau, ou faites un clic droit → « Ouvrir avec » → choisissez Chrome, Edge, Firefox ou Safari.

### Problème 2 : Le bouton « Copier » ne fonctionne pas
- **Cause** : l'API presse‑papiers peut être bloquée en mode local.
- **Solution** : utilisez le bouton « Télécharger » à la place, ou ouvrez la page via un petit serveur local (par exemple avec l'extension VS Code « Live Server »).

### Problème 3 : STYLEME n'importe pas mon HTML
- **Cause** : le HTML contient des scripts ou des attributs non sécurisés.
- **Solution** : collez uniquement le contenu du `<body>` (sans les balises `<script>`). STYLEME supprime automatiquement les éléments dangereux.

### Problème 4 : Les modifications de STYLEME ne sont pas sauvegardées
- **Cause** : le stockage local est désactivé ou la navigation privée est active.
- **Solution** : utilisez la navigation normale, ou exportez régulièrement votre CSS.

### Problème 5 : SCRIPTME affiche une erreur dans l'aperçu
- **Cause** : certaines fonctionnalités nécessitent un navigateur moderne.
- **Solution** : mettez à jour votre navigateur, ou testez une autre fonctionnalité.

---

## 📄 Copyright

**© 2026**  
📧 mohamed005cheikh@gmail.com  
Créé par **MC88**  
Tous droits réservés.

---

## 🔗 Fichiers associés

- `tft-mc88.html` — lien direct (si hébergé)
- `styleme-mc88.html` — lien direct
- `scriptme-mc88.html` — lien direct

**Bonne création ! 🚀**
