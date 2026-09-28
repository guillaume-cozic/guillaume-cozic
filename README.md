# Guillaume Cozic — Product Engineer

**Le produit et le code, du cadrage à la mise en production.**

Développeur PHP / TypeScript depuis 2014, je porte aussi la casquette produit : je cadre avec le métier, je challenge le besoin, je livre en TDD et je transforme chaque retour utilisateur en itération.

Le Pradet (83) · [LinkedIn](https://www.linkedin.com/in/guillaumecozic/) · [Malt](https://www.malt.fr/profile/guillaumecozic) · [guillaume.cozic@gmail.com](mailto:guillaume.cozic@gmail.com)

---

## Ma façon de travailler

| | |
|---|---|
| **01 · Challenger le besoin** | Cadrer avec le métier, questionner la valeur, découper en incréments livrables. |
| **02 · Livrer sans dette** | Architecture hexagonale + TDD, assisté par l'IA (Claude Code) : un code prêt à pivoter avec le produit. |
| **03 · Itérer** | Transformer chaque retour utilisateur en évolution, vite et en confiance. |

---

## Projets phares

### [ZouriteBnb](https://github.com/guillaume-cozic/zouritebnb) · [www.zouritebnb.com](https://www.zouritebnb.com)
Marketplace de location de logements pour l'île Rodrigues, conçue et développée de bout en bout.

- **Produit** : recherche sur carte, calendrier de disponibilité, réservation (demande ou instantanée), paiement Stripe, annulation avec politique de remboursement, avis croisés, messagerie, wishlist, co-hôtes, back-office.
- **Tech** : PHP 8.4 / Symfony / API Platform en architecture hexagonale, React 19 / Redux Toolkit / TypeScript, blog Astro.
- **Qualité** : TDD, tests d'intégration et E2E, tests de contrat OpenAPI entre API et front, tests de mutation (Infection), règles d'architecture vérifiées par PHPArkitect.
- **Ops** : Docker, déploiement Ansible, JWT + refresh tokens, Symfony Messenger.

### Assistant conversationnel LLM
Un chat en langage naturel qui pilote un site de réservation (recherche + réservation) via un LLM et des outils exposés en MCP.

- **Produit** : réserver un logement sans quitter la conversation ; brancher n'importe quel site cible sans toucher au cœur.
- **Tech** : orchestrateur NestJS (Fastify) en architecture hexagonale, LangGraph, serveur MCP générique + « domain packs », streaming SSE.
- **LLM interchangeable** : Claude via le Claude Agent SDK pour le POC, LLM open source auto-hébergé (Ollama / vLLM) en cible — un simple adapter.
- **Évaluation** : traces Langfuse, scoring LLM-as-judge, comparaison de runs entre versions.

---

## Stack

- **Back** : PHP 8, Laravel, Symfony, API Platform, NestJS
- **Front** : React, Redux, TypeScript
- **Data** : PostgreSQL, MySQL, Elasticsearch, Redis
- **Ops** : Docker, Ansible, Kong, GitHub Actions, Jenkins
- **IA** : Claude Code, Claude Agent SDK, LangGraph, MCP, Langfuse
- **Méthodes** : TDD, DDD, CQRS, architecture hexagonale

---

## Parcours en bref

| Période | Où | Rôle |
|---|---|---|
| 2024 → auj. | MaxiCoffee | Développeur backend Laravel — monolithe modulaire, CQRS, TDD |
| 2022 → 2023 | IAD | Développeur backend Symfony — diffusion d'annonces immobilières |
| 2019 → 2022 | Teddilab | Développeur backend Laravel — e-learning aéronautique |
| 2017 → 2018 | Boostmyshop | Lead technique — 40 M de repricings par semaine |
| 2014 → 2017 | Aicom | Responsable technique — 8 sites en production |

Ingénieur informatique, ISEN Toulon (2008 – 2013).
