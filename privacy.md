# 🔐 Politique de confidentialité — AlphaSecurity

**Dernière mise à jour : 18 septembre 2026**

AlphaSecurity est un bot Discord conçu pour la protection, la modération, la sécurité et la gestion des serveurs Discord.

La présente Politique de confidentialité explique quelles informations peuvent être traitées lors de l'utilisation d'AlphaSecurity, dans quel but elles sont utilisées et comment elles sont gérées.

---

## 1. Responsable du service

Le service AlphaSecurity est exploité par son équipe de développement.

Pour toute question concernant la confidentialité, les données ou le fonctionnement du bot, vous pouvez contacter l'équipe à :

📧 **[contact.louisspeedy55@ikmail.com](mailto:contact.louisspeedy55@ikmail.com)**

---

## 2. Quelles données peuvent être traitées ?

AlphaSecurity peut traiter certaines données nécessaires à son fonctionnement.

Les données réellement traitées dépendent des fonctionnalités utilisées sur le serveur.

### 👤 Informations Discord

AlphaSecurity peut traiter :

* L'identifiant Discord d'un utilisateur (`User ID`)
* L'identifiant d'un serveur (`Guild ID`)
* L'identifiant des salons
* L'identifiant des rôles
* Le pseudonyme ou nom d'utilisateur Discord
* Les rôles nécessaires à la gestion des permissions
* Les informations nécessaires à l'identification des propriétaires et membres du staff

Ces informations permettent notamment de vérifier les permissions et la hiérarchie des rôles, d'appliquer les sanctions et de faire fonctionner les différentes fonctionnalités du bot.

---

## 3. Données liées à la modération

Lorsqu'une action de modération est effectuée avec AlphaSecurity, certaines informations peuvent être enregistrées.

Cela peut notamment comprendre :

* L'utilisateur concerné
* Le serveur concerné
* Le type d'action effectuée
* La raison indiquée
* L'auteur de l'action
* La date de l'action
* L'identifiant d'un avertissement ou d'une sanction lorsqu'il est généré

Les avertissements peuvent être conservés afin de permettre leur consultation et leur gestion ultérieure.

---

## 4. Signalements

La fonctionnalité de signalement permet aux utilisateurs de transmettre un rapport à l'équipe de modération.

Un signalement peut contenir :

* L'utilisateur signalé
* L'utilisateur ayant effectué le signalement
* Le motif du signalement
* Des preuves
* Des liens ou pièces jointes transmis comme preuves

Les preuves sont utilisées afin de permettre aux membres du staff de vérifier et de traiter le signalement.

Les signalements en attente peuvent être conservés par AlphaSecurity.

---

## 5. Alertes SOS et RAID

Les commandes d'alerte permettent de transmettre des informations au staff lorsqu'une situation nécessite une intervention.

Les informations associées à une alerte peuvent notamment comprendre :

* L'utilisateur ayant déclenché l'alerte
* Le serveur concerné
* Le type d'alerte
* Le message ou les détails fournis
* L'état de traitement de l'alerte

Les alertes SOS et RAID non résolues peuvent être conservées afin de permettre leur suivi.

---

## 6. Messages et système `snipe`

Certaines fonctionnalités d'AlphaSecurity nécessitent le traitement temporaire de messages Discord.

Le système `snipe` peut notamment conserver temporairement le dernier message supprimé d'un salon, avec son contenu et, lorsque disponible, une image.

Cette mémoire est limitée à **500 salons maximum**.

Les messages peuvent également être analysés temporairement par le système anti-raid afin de détecter certains comportements tels que le spam ou la répétition excessive de messages.

---

## 7. Système anti-raid

AlphaSecurity dispose d'un système automatique de protection contre certains comportements suspects.

Il peut notamment détecter :

* Le spam
* La répétition d'un même message
* Les arrivées massives de membres
* La suppression ou création rapide de salons
* La suppression ou création rapide de rôles
* Les bannissements multiples
* Les expulsions ou timeouts multiples
* Certains motifs associés aux arnaques et au phishing

Ces systèmes utilisent les informations nécessaires à la détection et à l'application des protections.

Lorsqu'une détection entraîne une sanction ou une alerte, les informations nécessaires peuvent également être enregistrées dans les systèmes de logs ou de modération.

---

## 8. Blacklist et preuves

AlphaSecurity possède un système de blacklist permettant de gérer des utilisateurs ou des serveurs considérés comme incompatibles avec le service.

Pour un utilisateur blacklisté, le système peut conserver :

* L'identifiant de l'utilisateur
* La raison de la blacklist
* L'auteur de la blacklist
* La date
* Les preuves associées

Les preuves peuvent notamment être des photographies ou autres éléments transmis dans le cadre de la blacklist.

AlphaSecurity peut également conserver une blacklist de serveurs.

---

## 9. Whitelist

AlphaSecurity peut conserver des informations relatives aux utilisateurs ou éléments placés en whitelist.

La whitelist est utilisée notamment pour exclure certaines personnes des protections anti-raid.

Les utilisateurs présents dans la whitelist peuvent ainsi être exemptés de certains mécanismes automatiques.

---

## 10. Suggestions

La commande de suggestion permet aux utilisateurs de proposer des idées à la communauté.

Les suggestions peuvent être conservées afin de permettre :

* Leur publication
* Le vote de la communauté
* Leur acceptation ou leur refus par l'équipe du serveur

---

## 11. Logs

Les commandes et actions effectuées avec AlphaSecurity peuvent être envoyées dans des salons de logs configurés sur le serveur.

Les logs peuvent notamment être séparés selon plusieurs catégories :

* Logs utilisateurs
* Logs fondateurs
* Logs staff
* Logs staff administrateur

Ces logs permettent aux responsables du serveur de suivre les actions effectuées avec le bot.

L'accès à ces informations dépend des permissions configurées sur le serveur Discord.

---

## 12. Données de configuration

AlphaSecurity conserve également les informations nécessaires à sa configuration et à son fonctionnement.

Cela peut notamment comprendre :

* Les identifiants des propriétaires
* Les identifiants des super-propriétaires
* Les identifiants des serveurs
* Les identifiants des salons
* Les identifiants des rôles
* Les paramètres de configuration du serveur
* Les informations nécessaires au fonctionnement du système de support

Le token Discord du bot peut également être présent dans la configuration technique du service. **Ce token est une donnée strictement technique et confidentielle et n'est pas destiné à être communiqué aux utilisateurs.**

---

## 13. Où les données sont-elles stockées ?

AlphaSecurity utilise notamment des fichiers JSON et une base de données SQLite.

Les fichiers utilisés comprennent notamment :

* `reports.json`
* `manual_alerts.json`
* `suggestions.json`
* `staff_cache.json`
* `grades_cache.json`
* `antiraid_disabled.json`
* `pending_update.json`

Une base SQLite nommée `blacklist.db` est également utilisée pour certaines données telles que :

* Les blacklists
* Les propriétaires
* Les whitelists
* Les avertissements
* Les informations liées aux raids
* Les blacklists de serveurs
* La configuration des serveurs

---

## 14. Finalités

Les données traitées par AlphaSecurity servent notamment à :

* Assurer la sécurité des serveurs
* Détecter les raids et le spam
* Effectuer les actions de modération
* Conserver les avertissements
* Traiter les signalements
* Traiter les alertes SOS et RAID
* Gérer les blacklists et whitelists
* Assurer le fonctionnement des systèmes de staff
* Conserver les configurations nécessaires au bot
* Permettre le suivi des commandes et actions
* Améliorer la sécurité et l'administration du service

---

## 15. Partage des informations

AlphaSecurity n'a pas pour finalité de vendre les données des utilisateurs.

Les informations peuvent être accessibles aux personnes disposant des permissions nécessaires sur le serveur, notamment les administrateurs et membres du staff, lorsque les fonctionnalités utilisées le prévoient.

Par exemple, un signalement peut être transmis dans un salon réservé au staff.

Les informations envoyées directement dans Discord restent également soumises au fonctionnement et aux règles de Discord.

---

## 16. Responsabilité des administrateurs

Les administrateurs des serveurs utilisant AlphaSecurity sont responsables de la configuration du bot sur leur serveur.

Ils déterminent notamment :

* Les permissions accordées au bot
* Les salons de logs
* Les rôles utilisés
* Les membres du staff ayant accès aux informations
* Les systèmes de modération activés

AlphaSecurity ne contrôle pas les permissions accordées par les administrateurs.

---

## 17. Sécurité

AlphaSecurity met en œuvre des mesures techniques destinées à protéger les informations nécessaires à son fonctionnement.

Toutefois, aucun système informatique ou service en ligne ne peut garantir une sécurité absolue.

Les utilisateurs sont invités à ne pas transmettre d'informations personnelles inutiles dans les signalements, preuves ou alertes.

---

## 18. Durée de conservation

Les données sont conservées aussi longtemps que nécessaire au fonctionnement de la fonctionnalité concernée.

Certaines informations peuvent être conservées tant qu'elles sont nécessaires à la sécurité, à la modération, à la gestion d'une blacklist ou à la configuration d'un serveur.

Les durées exactes peuvent varier selon le type de donnée et la fonctionnalité concernée.

---

## 19. Suppression et demande d'information

Pour toute question concernant les informations traitées par AlphaSecurity, ou pour toute demande relative à vos données, vous pouvez contacter l'équipe :

📧 **[contact.louisspeedy55@ikmail.com](mailto:contact.louisspeedy55@ikmail.com)**

Toute demande sera étudiée en fonction de la nature des données concernées et des contraintes techniques ou légales applicables.

---

## 20. Modifications

Cette Politique de confidentialité peut être modifiée lorsque le fonctionnement d'AlphaSecurity évolue.

La date de dernière mise à jour est indiquée en haut de cette page.

Nous recommandons aux utilisateurs de consulter régulièrement cette page afin de prendre connaissance des éventuelles modifications.

---

## 21. Contact

Pour toute question concernant la confidentialité, les données ou AlphaSecurity :

📧 **[contact.louisspeedy55@ikmail.com](mailto:contact.louisspeedy55@ikmail.com)**

---

**AlphaSecurity — Protection, modération et sécurité Discord.**
