# ⚖️ TravailLex 2026 — Code du Travail

Interface juridique IA pour le Code du travail français 2026, hébergée sur **GitHub Pages** (zéro serveur, zéro coût).

## 🚀 Utilisation

Ouvrez l'URL GitHub Pages de votre repo.  
Au premier lancement, une fenêtre vous demande votre **clé API Anthropic**.

### Obtenir la clé API (gratuit pour démarrer)
1. Allez sur [console.anthropic.com](https://console.anthropic.com/api-keys)
2. → **API Keys** → **Create Key**
3. Copiez la clé (commence par `sk-ant-api03-…`)
4. Collez-la dans la fenêtre de l'application

La clé est stockée **uniquement dans votre navigateur** (localStorage).  
Elle n'est jamais envoyée à un tiers — l'appel va directement de votre navigateur vers `api.anthropic.com`.

## 📦 Déploiement sur GitHub Pages

```bash
# 1. Créer un repo GitHub (ex: travaillex-2026)
# 2. Pousser ce dossier
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/VOTRE-USERNAME/travaillex-2026.git
git push -u origin main

# 3. Activer GitHub Pages
# → Settings > Pages > Source : main branch / root
# → Votre URL : https://VOTRE-USERNAME.github.io/travaillex-2026/
```

## ✨ Fonctionnalités

- 📋 **Articles** — 17 articles du Code du travail avec analyse IA live
- ⚖️ **Jurisprudences** — Arrêts 2025-2026 + actualisation temps réel
- 📊 **Chiffres clés** — SMIC, cotisations, plafonds 2026
- 🤖 **Assistant IA** — Chat juridique avec web search activé
- ⛶ **Plein écran** — Bouton + touche F11
- ⬛ **Vue double** — IA + lien Légifrance côte à côte

## ⚠️ Avertissement

Outil fourni à titre informatif uniquement. Ne constitue pas un avis juridique.  
Consultez toujours un juriste qualifié ou [Légifrance](https://legifrance.gouv.fr) pour les textes officiels.

## 💰 Coût

- **Hébergement** : 0 € (GitHub Pages)
- **API Anthropic** : environ 0,01-0,05 € par question (selon longueur)
  - Les 5 premiers dollars sont offerts sur les nouveaux comptes Anthropic
