# Gemini CLI – Assistant IA de Google pour le terminal

## Introduction

Gemini CLI est un agent d’intelligence artificielle open source développé par Google, conçu pour fonctionner directement dans votre terminal. Il permet d’analyser, générer, déboguer et automatiser du code ou des workflows, en s’appuyant sur les modèles Gemini 2.5 Pro. Il intègre des outils avancés comme la gestion de projets, la génération multimédia, la recherche web native et des capacités d’automatisation via MCP.

Grâce à Gemini CLI, les développeurs peuvent interagir avec une IA puissante pour accélérer le développement, l’automatisation ou la documentation, tout en profitant d’une interface simple et efficace.

---

## Préambule

Ce projet est hébergé sur GitHub : **[google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli)**.

Gemini CLI est conçu pour être multiplateforme (Windows, macOS, Linux) et s’intègre naturellement dans votre environnement de développement. Il est distribué sous licence open source et propose un accès gratuit généreux (jusqu’à 1 000 requêtes par jour) avec un compte Google personnel.

---

## Prérequis

Avant d’installer Gemini CLI, assurez-vous d’avoir :

- **Node.js** version 18 ou supérieure installé sur votre machine
- **Un terminal** (PowerShell, Terminal Windows, Terminal macOS, ou terminal Linux)
- **Un compte Google** pour l’authentification

---

## Installation détaillée

### 1. Installer Node.js

- **Windows** : Téléchargez l’installateur officiel sur [nodejs.org](https://nodejs.org/) et suivez les instructions.
- **macOS** : Utilisez Homebrew :

  ```bash
  brew install node@22
  ```

  ou téléchargez l’installateur officiel.
- **Linux** (Ubuntu/Debian) :

  ```bash
  sudo apt update
  sudo apt install nodejs npm
  ```

Vérifiez l’installation avec :

```bash
node -v
npm -v
```

---

### 2. Installer Gemini CLI

Vous avez deux options : exécuter Gemini CLI sans installation ou l’installer globalement.

#### Option 1 : Exécuter sans installation (pour tester)

```bash
npx https://github.com/google-gemini/gemini-cli
```

Cette commande lance Gemini CLI sans l’installer sur votre système[1][3][4].

#### Option 2 : Installer globalement (recommandé)

```bash
npm install -g @google/gemini-cli
```

Sur Windows, il peut être nécessaire d’exécuter PowerShell ou le Terminal Windows en tant qu’administrateur[1][2][5].

---

### 3. Lancer Gemini CLI

Après l’installation, tapez simplement :

```bash
gemini
```

Suivez les instructions pour choisir un thème et vous authentifier avec votre compte Google. Une fenêtre de navigateur s’ouvrira pour la connexion[3][4][5].

---

### 4. Authentification

- **Compte Google** : Par défaut, l’authentification via votre compte Google personnel vous donne accès à 60 requêtes par minute et 1 000 requêtes par jour.
- **Clé API** (usage avancé) : Pour des besoins professionnels ou des quotas accrus, vous pouvez utiliser une clé API obtenue via Google AI Studio. Configurez-la ainsi :

  ```bash
  export GOOGLE_GENAI_API_KEY="votre-clé-api"
  ```

  Ajoutez cette ligne à votre `.bashrc`, `.zshrc` ou configurez-la dans les variables d’environnement Windows[1][4][5].

---

## Premiers pas

- **Saisissez vos prompts** dans le terminal Gemini CLI.
- **Utilisez les commandes internes** (ex : `/help`, `/chat save`, `/memory add`, `/stats`).
- **Incluez des fichiers** dans vos prompts avec `@` (ex : `@src/ analyse l’architecture`).
- **Exécutez des commandes shell** avec `!` (ex : `!git status`)[1].

---

## Fonctionnalités principales

- **Analyse et génération de code**
- **Gestion de projets et automatisation**
- **Génération multimédia (images, vidéos)**
- **Recherche web native**
- **Intégration MCP pour workflows avancés**
- **Accès gratuit généreux avec un compte Google**

---

## Support et documentation

- **Documentation officielle** : [github.com/google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli)
- **Forum d’aide** : [Issues GitHub](https://github.com/google-gemini/gemini-cli/issues)

---

## Licence

Gemini CLI est distribué sous licence open source (Apache 2.0).

---

## Sources

```text
[1] Gemini CLI - L'IA de Google directement dans votre terminal <https://korben.info/gemini-cli-google-terminal-ia.html>
[2] Gemini CLI: A comprehensive guide to understanding, installing ... <https://www.reddit.com/r/GoogleGeminiAI/comments/1lkol0m/gemini_cli_a_comprehensive_guide_to_understanding/>
[3] Free Gemini 2.5 Pro Access + 1000 Daily Requests <https://apidog.com/blog/gemini-cli-setup-guide/>
[4] Google Gemini/gemini-cli: An open-source AI agent that ... <https://github.com/google-gemini/gemini-cli>
[5] Google Gemini CLI Tutorial: How to Install and Use It (With ... <https://dev.to/auden/google-gemini-cli-tutorial-how-to-install-and-use-it-with-images-4phb>
[6] Google dévoile Gemini CLI : l'IA dans votre terminal <https://www.it-connect.fr/google-devoile-gemini-cli-une-ia-gratuite-directement-dans-votre-terminal/>
[7] Gemini CLI: your open-source AI agent <https://blog.google/technology/developers/introducing-gemini-cli-open-source-ai-agent/>
[8] Gemini CLI - How to Install, Setup and Use Tutorial <https://www.youtube.com/watch?v=6izVe1KtW_c>
[9] Google releases Gemini CLI with free Gemini 2.5 Pro <https://www.bleepingcomputer.com/news/artificial-intelligence/google-releases-gemini-cli-with-free-gemini-25-pro/>
[10] Gemini CLI brings Google's AI agent to your terminal for free <https://9to5google.com/2025/06/25/google-gemini-cli/>
```
