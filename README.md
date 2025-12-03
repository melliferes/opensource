# Automatisations offertes par Mellifères

> 🐝 **La mission de Mellifères est d'accélérer les projets écologiques.**

Ce dépôt contient une collection d'automatisations open-source développées par [Melliferes.ca](https://melliferes.ca) pour soutenir les projets écologiques et l'autonomie alimentaire du Québec au sens large. Ces automatisations sont conçues pour simplifier les tâches administratives ou gagner en visibilité.


## 📦 Automatisations disponibles

### 1. Analyse et téléverse une facture sur Google Drive venant d'un courriel

Cette automatisation analyse automatiquement les factures reçues par courriel et les téléverse sur Google Drive avec un nom de fichier structuré généré par l'IA.

**Fichier** : [`1-analyze-and-upload-invoices-on-google-drive.json`](automations/n8n/1-analyze-and-upload-invoices-on-google-drive.json)

**Fonctionnalités** :
- Surveillance automatique de la boîte Gmail
- Analyse d'images de factures avec GPT-4o
- Génération intelligente de noms de fichiers structurés
- Téléversement automatique sur Google Drive

**Prérequis** :
- Compte n8n (cloud ou self-hosted)
- Compte OpenAI avec accès API
- Compte Google Workspace (Gmail + Google Drive)

**Documentation** : Voir les instructions dans le workflow n8n ou consulter la documentation n8n pour plus de détails.

---

## 🚀 Démarrage rapide

### Prérequis généraux

Pour utiliser ces automatisations, vous aurez généralement besoin de :

- **Une instance n8n** : [n8n cloud](https://n8n.io) ou installation self-hosted
- **Comptes de services** : Selon l'automatisation (OpenAI, Google Workspace, etc.)
- **Accès aux APIs** : Les automatisations utilisent diverses APIs pour fonctionner

### Installation d'une automatisation

1. **Importez le workflow** dans votre instance n8n :
   - Ouvrez votre instance n8n
   - Cliquez sur "Import from File" ou utilisez l'import depuis URL
   - Sélectionnez le fichier JSON de l'automatisation souhaitée

2. **Configurez les identifiants** :
   - Connectez les services requis (Gmail, Google Drive, OpenAI, etc.)
   - Suivez les tutoriels de configuration dans n8n si nécessaire

3. **Configurez les paramètres** :
   - Modifiez les nœuds de configuration selon vos besoins
   - Personnalisez les instructions IA si applicable

4. **Activez le workflow** :
   - Activez l'automatisation dans n8n
   - Testez avec des données réelles

---

## 🤝 Contribution

Nous vous invitons chaleureusement à contribuer à ce projet ! Que vous soyez développeur, utilisateur ou simplement intéressé par l'autonomie alimentaire, votre contribution est la bienvenue.

### Comment contribuer

- 🐛 **Signaler des bugs** : Aidez-nous à améliorer la qualité des automatisations
- 💡 **Proposer des améliorations** : Partagez vos idées pour de nouvelles fonctionnalités
- 📝 **Améliorer la documentation** : Rendez les automatisations plus accessibles
- 🔧 **Développer de nouvelles automatisations** : Créez des outils pour la communauté
- 🌱 **Partager vos besoins** : Dites-nous quels problèmes vous aimeriez voir résolus

### Proposer une nouvelle automatisation

Si vous avez développé une automatisation utile pour les projets d'autonomie alimentaire, n'hésitez pas à :
1. Créer une issue pour discuter de votre idée
2. Soumettre une pull request avec votre automatisation
3. Documenter votre automatisation clairement

---

## 💝 Soutien

Si vous souhaitez soutenir notre mission et accélérer le développement de nouvelles automatisations, vous pouvez faire une contribution consciente par paiement Interac à **equipe@melliferes.ca**.

Votre soutien nous permet de :
- Développer de nouvelles automatisations
- Améliorer les outils existants
- Maintenir et documenter le projet
- Accélérer les projets écologiques dans votre communauté

---

## 📚 Ressources utiles

- [Melliferes.ca](https://melliferes.ca) - Site web principal
- [Documentation n8n](https://docs.n8n.io) - Guide complet pour utiliser n8n
- [n8n Community](https://community.n8n.io) - Communauté et support

---

## 📄 Licence

Ce projet est open-source et disponible sous licence libre. Vous êtes libre d'utiliser, modifier et distribuer ces automatisations selon vos besoins.

---

## 📧 Contact

Pour toute question, suggestion ou collaboration :

**Email** : equipe@melliferes.ca

Nous sommes toujours heureux d'échanger avec la communauté et d'entendre vos retours !

---

## 🌟 Vision à long terme

Notre objectif est de créer un écosystème complet d'automatisations qui couvrent tous les aspects opérationnels des projets d'autonomie alimentaire :

- **Gestion administrative** : Factures, comptabilité, documents légaux
- **Suivi de production** : Inventaires, récoltes, ventes
- **Communication** : Relations clients, réseaux sociaux, newsletters
- **Gestion des ressources** : Planification, optimisation, reporting
- **Intégration** : Connexion entre différents outils et plateformes

Ensemble, construisons des outils qui libèrent du temps pour l'essentiel : créer un avenir plus durable et autonome.

---

*Dernière mise à jour : Décembre 2025*
