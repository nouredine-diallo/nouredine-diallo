# 👋 Hello, Nouredine Diallo 

###  Étudiant & Builder | Passionné d'Automatisation & IA

Bienvenue sur mon portfolio !
Je suis étudiant en Informatique (L2) , et développeur de projets 
Ce qui me motive ? **Passer de l'idée au produit fini.**
Pour y arriver, j'utilise les nouvelles decouverte (LLMs, Automation, No-Code) pour construire des systèmes plus ambitieux par rapport a la vitesse de developpement , tout en apprenant l'architecture logicielle et en connaissant les limites de ses outils 

 **Ma recherche :** Je cherche une **Alternance**  pour Septembre 2026  afin de mettre cette énergie au service d'une vraie équipe technique.

---

###  Transparence & Curiosité :

Je crois en une utilisation **honnête et maîtrisée mais a une certaine limite ** de l'IA pour des fonction / script qui ne touche pas a la logique pur du projet ou en lui donnnat les etapes de developpment 
* **Je ne suis pas une "boîte noire" :** Si j'utilise l'IA pour générer du code, je le relis, je l'audite et je le comprends.
* **60/40 :** J'utilise l'IA pour le "boilerplate" et l'exécution, mais je garde la main à 100% sur l'architecture, la sécurité et la logique métier.
* **Apprentissage continu :** Je me forme chaque jour (Google, DeepLearning.ai) pour comprendre ce qui se passe sous le capot (RAG, Embeddings, Vecteurs) , videos youtube pour la culture par rapport à ces themes ...

---

###  Mes Projets 

 Voici mes réalisations concrètes :

#### ⚡ [SparkFlow_LAND] - SaaS de Gestion de Contenu (En vente sur actuellement Microns et d'autre plateforme , avec un influenceur qui l'utilise régulierement pour ses script ou plannification )
*Un outil pour aider les créateurs à scripter et planifier.*
* **Ce que j'ai fait :** J'ai conçu toute l'architecture RAG pour générer des scripts pertinents sans "hallucinations" pour video virale sur reseau sociaux . J'ai utilisé des *System Prompts* complexes pour guider l'IA et à chaque étape elle génere des rapports .
* **Le défi technique :** Sécuriser l'application. J'ai construit des agents "copilotes" qui analysent le code généré pour détecter les failles d'injection ( je peux vous montrer leur sytem prompt ) , mettre en place les convention de clean code et optimisation / robustesse et mise en place d'un cache pour les nombreux appel api  avant la mise en prod.
* **Stack :** React, Supabase, OpenAI API , netlify ......

#### [Agent Prompt RAG] - Générateur de Prompts Sécurisé
*Un agent intelligent qui m'aide à écrire de meilleurs prompts.*
* **Mon approche :** J'ai codé manuellement les 60% critiques (l'ingestion , l'embedding , e stockage dans chromaDb et la realisation de la tache finale ) et supervisé l'IA pour générer les 40% restants ( comme creer une page streamlit un peu plus esthetique , verifier certains bug .... ) en lui détaillant toutes les etapes de création et en utilisant des technique de context engerring pour éviter toute hallucination , duplication de code , chose que j'ai remarquer dans le premier projet l'ia fais souvent 
* **Architecture :** Pipeline en 4 étapes (Comprendre -> Chercher -> Construire -> Valider) connecté à une base de connaissances technique (ArXiv, Docs).
* **Stack :** Python, ChromaDB, LangChain, Validation JSON stricte , FASTAPI , LM 

####  [Alchimist Labs] - Expérience "100% IA"
*Un défi personnel : jusqu'où peut-on aller sans coder manuellement tout en lui donnat des indication précise comme comment les fonction doivent etre defini , le processus pour atteindre la video , l'architecure .... ?*
* **L'expérience :** J'ai voulu tester les limites du Prompt Engineering pur en créant un pipeline vidéo complet (30 vidéos/mois) , projet que j'ai documenter quotidiennement sur linkedin 
* **Apprentissage :** Ce projet m'a appris à gérer les coûts (FinOps) en préférant des modèles locaux ou Vertex AI plutôt que GPT-4 pour tout. C'était un exercice de rigueur dans le prompt.
* **Stack :** Vertex AI, Python Scripts, FFmpeg.

#### [Auto-Clipper] - Workflow Hybride / de base est complementaire au projet sparkflow 
*Automatisation de la découpe vidéo.*
* **Le setup :** 2  scénario **Make** (configuré manuellement par moi meme  de A à Z) qui orchestre un script Python de découpe (FFmpeg) avec un triiger qui surveille airtable pour voir la video ajoutée , assembly qui donnera une transcription au scenario ce qu'on utilisera plus tard avec les timestamp .......
* **Résultat :** Transformation automatique de vidéos longues en clips courts avec sous-titres et posts réseaux sociaux.

---

### 📚 Mon Parcours d'Apprentissage

Je combine la rigueur universitaire avec une soif d'apprendre par la pratique.

* **🎓 Université Lyon 1 (L2 Informatique) :**
    * Apprentissage des fondamentaux : C++, Algorithmique, Structures de données.
    * *Projet notable :* Développement d'un jeu Snake en C++ (Gestion mémoire, Pointeurs).
    *                   * Developpement en c++ d'un mode 3d en utilisant les maillages ...
    *                  * Second semestre à venir projet d'une web app avec sql , python

* **🏅 Auto-Formation Certifiante (Niveau Avancé) :**
    * J'ai mis en place mon propre programme de formation assisté par IA, validant chaque compétence par des labs pratiques "Go/No-Go".
    * **Certifications Validées :**
        * *DeepLearning.ai :* Building and Evaluating Advanced RAG.
        * *Google Cloud :* Prompt Design in Vertex AI.
    * **Compétences acquises :** Triade RAG (TruLens), Masquage de données sensibles (PII), Optimisation vectorielle.

---

### 🛠️ Ma Boîte à Outils

| Domaine | Ce que je maîtrise / J'utilise |
| :--- | :--- |
| **Automation** | **Make.com** (Avancé), **Webhooks** (Intégration API) |
| **IA & GenAI** | **Prompt Engineering** ( Avancé), **RAG Concepts**,**finetuning** , **Vertex AI**, **OpenAI API** |
| **Code** | **Python** (Scripting pour l'IA & APIs), **C++** (Bases universitaires), **SQL** (Base universitaires/Supabase) |
| **Outils Dev** | **VS Code**, **Git/GitHub** |
| **En Apprentissage** | Python Avancé, n8n (Transition depuis Make prévue), Docker |
---

### 📫 Travaillons ensemble !

Je suis un étudiant curieux, travailleur et passionné  et en constante apprentissage par l'impact de l'IA sur nos métiers.
Si vous cherchez quelqu'un qui ne se contente pas d'exécuter, mais qui cherche toujours à optimiser et automatiser les process, discutons-en !
n'hesitez pas a explorer mes projets ou de venir à moi pour plus d'informations 
* 📧 nourredinediallo@gmail.com

<!--
**nouredine-diallo/nouredine-diallo** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
