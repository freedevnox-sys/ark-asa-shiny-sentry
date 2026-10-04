# 🌈 ARK: ASA Shiny Sentry

Surveille à ta place les **dinos Shiny** d'ARK: Survival Ascended annoncés par **L'indic** sur le Discord **[FR] France Ark**, et te prévient dès qu'un Shiny qui t'intéresse apparaît.

Disponible sur **PC Windows** et sur **Android** (le téléphone fait tout seul, sans PC).

> **Téléchargement** : page [Releases](https://github.com/freedevnox-sys/ark-asa-shiny-sentry/releases)
> — les versions **`V…`** sont pour **PC** (`ARK_ASA_Shiny_Sentry.exe`), les versions **`A…`** pour **Android** (`ShinySentry-x.y.z.apk`).

---

## ✨ Fonctions

- **Surveillance automatique** du salon Shiny de L'indic, map par map, à intervalle régulier.
- **Alertes** (notification Windows ou Android) pour les nouveaux Shinies uniquement, jamais deux fois le même.
- **Filtres** : créatures, types de Shiny et couleurs, combinables en **ET / OU** — ou tout recevoir, ou rien.
- **Liste des Shinies présents** avec recherche, tri, coordonnées **Lat / Lon** à copier en un clic.
- **Fiche taming** de chaque créature (KO, passif, œuf…) avec lien Dododex.
- **Historique** des Shinies détectés sur 7 jours.
- **Cartes des recensements de tribus** (plugin TribeRegistry) : une carte par map avec les bases principales 🏠, avant-postes 📍 et déménagements 🚚, zoomable. Mise à jour **une fois par jour** ou à la demande, pour ton cluster ou n'importe quel autre. Depuis la fiche d'un Shiny, **« Tribus sur <map> »** ouvre la carte de sa map avec **la position du Shiny repérée** : tu vois tout de suite s'il est près d'une base.
- **Glitches de Genesis 1** : les 150 glitches (biomes, histoire, anecdotes) à cocher une fois réparés, avec leur **position sur la carte** de Genesis (ou celle que tu notes en jeu) et ta progression.
- **Santé du scanner** : une map qui échoue plusieurs fois est mise en pause et signalée, puis reprise automatiquement ; écran **Diagnostic** exportable.
- **Mises à jour intégrées** : l'application propose elle-même les nouvelles versions, vérifiées avant installation.

Côté PC uniquement : **Status serveur** (joueurs connectés par map) et rappel du **vote Top-Serveurs**.
Côté Android : surveillance **en arrière-plan et écran éteint**, import de la configuration PC.

---

## 💻 Installation PC (Windows 10 / 11, 64 bits)

1. Télécharge `ARK_ASA_Shiny_Sentry.exe` depuis la dernière release **`V…`**.
2. Lance-le. Windows SmartScreen peut afficher « Windows a protégé votre ordinateur » : **Informations complémentaires → Exécuter quand même**.
3. **Activation** : l'écran « Activation requise » affiche ton **ID d'installation** → **Copier l'ID** et envoie-le à **Nox** (voir [Contact](#-contact)). Colle la clé reçue puis **Activer et démarrer**.
4. **Première configuration** (assistant) :
   1. **Ouvrir Discord** : un navigateur Chromium dédié s'ouvre.
   2. **Connecte-toi à Discord** dans ce navigateur.
   3. **Canal Shiny** : trouvé **automatiquement** (salon Shiny de L'indic et post des cartes), tu confirmes. Sinon **🔍 Détection automatique**, ou ouvre le salon et colle son adresse (`https://discord.com/channels/…`). Plus tard, **⚙ Configuration → 🔍 Détecter** (à côté de l'adresse du salon) relance la recherche.
   4. **Sources des dinos** : liste ASA officielle, plus les mods de ton cluster si besoin.
5. Choisis tes filtres dans **⚙ Configuration**, puis **Démarrer**.

Le scan ne démarre jamais tout seul, et une seule fenêtre de l'application peut être ouverte à la fois. Chromium reste ouvert entre deux surveillances pour garder ta session Discord. Il est lancé en français : Discord y affiche l'âge des Shinies comme L'indic l'attend (l'anglais est aussi compris).

## 📱 Installation Android (Android 8 ou plus)

1. Sur le téléphone, télécharge `ShinySentry-x.y.z.apk` depuis la dernière release **`A…`** et ouvre-le (autorise l'installation depuis cette source si Android le demande).
2. **Activation** : envoie l'**ID d'installation** affiché à **Nox** (bouton d'envoi intégré, ou voir [Contact](#-contact)), puis colle la clé reçue.
3. Autorise les **notifications**.
4. **Discord** → **Connexion** → connecte-toi à Discord dans l'application.
5. Les salons de L'indic (salon Shiny et post des cartes) sont **trouvés automatiquement** : confirme avec **Enregistrer**. Sinon **🔍 Détection auto**, ou va dans le salon Shiny puis **Utiliser ce salon**.
6. **Configuration** : ton cluster (Boosté par défaut) et tes filtres, puis **Démarrer la surveillance**.

Pour que la surveillance continue application fermée et écran éteint, autorise **« Afficher par-dessus les autres applis »** et retire l'**optimisation de batterie** pour Shiny Sentry (l'écran principal te guide).

---

## 🗺 Cartes des recensements

Les cartes viennent du post **« Panel de recensement des tribus »** (forum *recensements-auto* du Discord), celui qui a le bouton **« Carte des recensements »**. Il est **trouvé automatiquement** avec le salon Shiny (recherche rapide de Discord, vérification du bouton, confirmation avant d'enregistrer). Sinon :

- **PC** : vue **🗺 Cartes** → **« 🔍 Détecter »**, ou ouvre ce post dans le Chromium de Shiny Sentry → **« Utiliser l'onglet Discord actuel »** (ou colle son lien).
- **Android** : écran **Discord** → **« 🔍 Détection auto »**, ou ouvre ce post → **« Utiliser pour les cartes »**.

La détection ne fait qu'ouvrir et lire des pages Discord : aucun clic, rien n'est publié.

Ensuite, les cartes de ton cluster se mettent à jour **une fois par jour** (entre deux cycles de surveillance, dans un onglet séparé sur PC) ; **Actualiser** les met à jour à la demande. Le sélecteur **Cluster** permet de consulter Omega, Chaos, Classique… Une map en échec garde sa dernière carte connue.

**Position du Shiny** : depuis la fiche d'un Shiny, **« Tribus sur <map> »** affiche sa carte avec une **cible jaune** à ses coordonnées Lat / Lon, et son nom. Sur PC, la vue à 100 % s'ouvre centrée sur lui ; sur Android, la carte s'ouvre zoomée dessus (double tap : carte entière).

**Tous les Shinies de la map** : les autres Shinies présents apparaissent en **cibles roses** sur la carte ; un clic (PC) ou un toucher (Android) ouvre leur fiche.

## 🏠 Tes bases

Pose ta base sur la carte d'une map : **clic droit** sur la carte (PC) ou **appui long** (Android, à partir de la 1.1.0), puis « Ma base ici ». Ensuite :

- les alertes des Shinies de cette map indiquent **la distance et la direction** : « 🏠 à 12 de ta base (nord-est) » (distance en unités GPS, 0 à 100) ;
- un **rayon d'alerte** optionnel (vue Cartes sur PC, ligne « 🏠 Mes bases » sur Android) ne garde que les Shinies proches de tes bases ; les maps où tu n'as pas de base ne sont pas filtrées. 0 = alertes partout.

## 🧩 Glitches de Genesis 1

Bouton **🧩 Glitches Gen 1** (PC) ou menu **⋮ → Glitches de Genesis 1** (Android) : les 150 glitches du wiki (36 de biome, 40 d'histoire, 74 anecdotes).

- **Coche** un glitch une fois réparé (PC : clic dans la colonne ✔, double-clic ou Espace) ; ta progression s'affiche par type.
- Filtres **À réparer / Réparés**, par type, par biome, et recherche (« siphon », « volcan »…).
- Choisis un glitch : il apparaît en **cible jaune** sur la carte de Genesis du recensement, les autres glitches en pastilles **vertes** (réparés) ou **orange** (à réparer). Seuls les glitches sont affichés : ni ressources, ni autres points d'intérêt. Coordonnées Lat / Lon à copier (PC).
- Les positions sont celles du wiki, converties pour ASA (Genesis est agrandie en ASA). Les **30 glitches de l'océan** n'ont pas de position connue en ASA : à toi de la noter.
- **📍 Noter la position** (PC : bouton ou clic droit sur la carte ; Android : **📍 Position** ou appui long sur la carte) : place un glitch là où tu l'as trouvé en jeu, ou corrige une position fausse. Ta position (notée) remplace celle du wiki ; « Oublier » la retire. Celles notées sur le PC passent sur le téléphone avec **Configuration → ⋮ → Importer une config…** (config.json du PC).
- La carte vient du recensement : ouvre une fois **🗺 Cartes → Actualiser** sur un cluster qui a Genesis.

## 🔄 Mises à jour

L'application vérifie les mises à jour **à chaque démarrage** — sur PC, le lien **« ⟳ Mises à jour »** sous le titre relance la vérification à la demande. Une nouvelle version est téléchargée depuis ces releases et **installée seulement si son empreinte SHA-256 correspond** à celle publiée. Tes réglages, ta licence et ta session Discord sont conservés.

Après chaque mise à jour, une fenêtre **« ✨ Nouveautés »** présente une fois les changements des deux dernières versions. Pour la revoir : lien **« ✨ Nouveautés »** sous le titre (PC), ou menu **⋮ → Nouveautés** (Android).

---

## 🔒 Confidentialité

- Tout reste **sur ton appareil** : configuration, mémoire des Shinies, historique, cartes et session Discord (PC : `%LOCALAPPDATA%\ARK_ASA_Shiny_Sentry\`).
- L'application **ne publie jamais rien** sur Discord et n'envoie aucune commande au bot en ton nom : elle lit les réponses de L'indic comme tu le ferais, et clique uniquement sur ses boutons de consultation.
- L'export **Diagnostic** est nettoyé : ni clé de licence, ni lien de salon, ni session Discord.

## 🆘 En cas de souci

- **« Connexion Discord requise »** : reconnecte-toi dans le Chromium de Shiny Sentry (PC) ou via l'écran Discord (Android).
- **Une map reste en pause** : **Diagnostic → Retester les maps en pause**.
- **Cartes vides** : vérifie que le post du panel est bien choisi (voir ci-dessus) et que Discord est connecté.
- Pour signaler un problème, joins l'export **Diagnostic** (PC : bouton Diagnostic ; Android : menu ⋮ → Diagnostic → Exporter).

## 📬 Contact

- **Discord** : **noxly**
- **E-mail** : [free.dev.nox@gmail.com](mailto:free.dev.nox@gmail.com)

Pour une clé d'activation, une question ou un bug (avec l'export Diagnostic si possible).

---

*ARK: ASA Shiny Sentry — BY Nox. Outil de joueur non officiel, sans lien avec Studio Wildcard ni avec [FR] France Ark.*
