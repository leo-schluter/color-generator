# 🎨 Générateur de Couleurs

Une application web interactive et élégante pour générer des couleurs aléatoires avec un design moderne et des animations fluides.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Fonctionnalités

- 🎲 **Génération aléatoire** de couleurs hexadécimales
- 🌈 **Changement dynamique** du fond d'écran avec dégradé
- 💾 **Affichage du code hexadécimal** pour faciliter la copie
- 🔄 **Aperçu visuel** de la couleur générée
- ✨ **Animations fluides** et transitions élégantes
- 📱 **Design responsive** adapté aux mobiles et tablettes
- 🎯 **Interface moderne** avec effets de survol et interactions

## 🚀 Installation

### Prérequis

Aucun prérequis particulier ! Il vous suffit d'avoir un navigateur web moderne.

### Étapes d'installation

1. **Cloner le dépôt**
   ```bash
   git clone <url-du-depot>
   cd test-claude
   ```

2. **Ouvrir l'application**

   Il suffit d'ouvrir le fichier `index.html` dans votre navigateur préféré :

   - Double-cliquez sur `index.html`, ou
   - Faites un clic droit → "Ouvrir avec" → votre navigateur, ou
   - Depuis le terminal :
     ```bash
     # Sur macOS
     open index.html

     # Sur Linux
     xdg-open index.html

     # Sur Windows
     start index.html
     ```

### Installation avec serveur local (optionnel)

Pour une expérience optimale, vous pouvez utiliser un serveur local :

```bash
# Avec Python 3
python -m http.server 8000

# Avec Python 2
python -m SimpleHTTPServer 8000

# Avec Node.js (si npx est installé)
npx http-server

# Avec PHP
php -S localhost:8000
```

Puis ouvrez votre navigateur à l'adresse `http://localhost:8000`

## 📖 Usage

### Utilisation basique

1. Ouvrez `index.html` dans votre navigateur
2. Cliquez sur le bouton **"Générer une Couleur"**
3. La couleur de fond change instantanément
4. Le code hexadécimal de la couleur s'affiche au centre
5. Un aperçu circulaire de la couleur est visible

### Copier le code couleur

Pour copier le code hexadécimal d'une couleur générée :
1. Sélectionnez le code affiché (ex: `#A3C4F3`)
2. Copiez-le avec `Ctrl+C` (ou `Cmd+C` sur Mac)
3. Utilisez-le dans vos projets CSS, design, etc.

## 🛠️ Technologies utilisées

- **HTML5** - Structure de la page
- **CSS3** - Styles, animations et transitions
  - Flexbox pour le centrage
  - Animations CSS natives
  - Media queries pour le responsive
  - Effets de glassmorphism
- **JavaScript Vanilla** - Logique de génération de couleurs
  - Aucune dépendance externe
  - Aucun framework requis

## 📁 Structure du projet

```
test-claude/
├── index.html          # Application principale (HTML + CSS + JS)
├── .gitignore         # Fichiers à ignorer par Git
└── README.md          # Documentation du projet
```

## 🎨 Personnalisation

### Modifier la couleur initiale

Dans `index.html`, ligne 178, modifiez la valeur hexadécimale :

```javascript
colorCode.textContent = '#667eea';  // Changez cette valeur
```

### Ajuster la vitesse des animations

Dans la section `<style>`, modifiez les durées de transition :

```css
body {
    transition: background 0.5s;  /* Changez 0.5s */
}
```

### Personnaliser les couleurs du conteneur

Modifiez le dégradé de fond dans la section `body` du CSS :

```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

## 🌐 Compatibilité navigateurs

| Navigateur | Version minimale |
|-----------|------------------|
| Chrome    | 60+             |
| Firefox   | 60+             |
| Safari    | 12+             |
| Edge      | 79+             |
| Opera     | 47+             |

## 📝 Améliorations futures

- [ ] Copier le code couleur en un clic
- [ ] Historique des couleurs générées
- [ ] Export de palette de couleurs
- [ ] Modes de couleurs (RGB, HSL, etc.)
- [ ] Génération de couleurs complémentaires
- [ ] Dark mode / Light mode toggle
- [ ] Raccourcis clavier (ex: Espace pour générer)

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :

1. Fork le projet
2. Créer une branche (`git checkout -b feature/amelioration`)
3. Commit vos changements (`git commit -m 'Ajout de fonctionnalité'`)
4. Push vers la branche (`git push origin feature/amelioration`)
5. Ouvrir une Pull Request

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 👤 Auteur

Créé avec ❤️ par Claude Code

## 🙏 Remerciements

- Design inspiré par les tendances modernes du web design
- Animations CSS basées sur les meilleures pratiques
- Palette de couleurs initiale inspirée par les dégradés populaires

---

**Note:** Ce projet est un exemple éducatif pour démontrer les capacités du HTML, CSS et JavaScript vanilla.
