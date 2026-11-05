# Plateforme UIP Burkina Faso (prototype)

Prototype de démonstration de la plateforme de l'Unité d'Information Passagers (UIP) prévue par le projet de décret portant conditions de traitement des RPCV (API) et des DDP (PNR) au Burkina Faso.

**Toutes les données (compagnies, passagers, listes, notices) sont fictives et générées dans le navigateur. Ne saisir aucune donnée réelle : le décret impose un hébergement sur infrastructures nationales (art. 15).**

## Modules
- Flux en direct selon la méthode push (les transporteurs envoient, l'UIP ne va jamais chercher les données), avec accusés de réception
- Scénarios de ciblage composés (2 critères ou plus, validation par un second profil, revue à 6 mois)
- Coopération internationale : instruction des demandes des UIP partenaires et envoi de demandes (simulation)
- Recherche rapide (Ctrl + K), export CSV, impression de fiche, thème clair ou sombre
- Salle de veille : vols OUA et BOY, état des transmissions H-48, H-24, H-30 min et fermeture du vol (art. 7 et 8)
- Vols et manifestes, fiche passager (annexes 1 et 2), aperçu dépersonnalisé (art. 19)
- Réception et lecture de messages UN/EDIFACT PAXLST (API) et PNRGOV (PNR), avec suppression des codes religion et santé à l'intégration (art. 11)
- Analyse des liens entre voyageurs (même réservation, téléphone, carte, courriel) avec graphe, et historique des voyages
- Dossiers d'enquête avec synthèse exportable
- Profils (analyste, superviseur, délégué à la protection des données, administrateur) et double validation des transmissions
- Statistiques d'activité et de qualité du ciblage
- Règles de ciblage réglables, listes de surveillance, file d'alertes avec décision motivée
- Interconnexions simulées : INTERPOL (documents volés ou perdus, notices), liste nationale, MIDAS, agence de l'immigration
- Recherche encadrée (finalité et référence obligatoires)
- Conformité des transporteurs et procédure d'amende (art. 21 et 22)
- Protection des données : filtre des données sensibles (art. 11), journal d'audit (art. 14)

## Utilisation
Ouvrir `index.html` dans un navigateur, ou consulter la version publiée via GitHub Pages. Aucune installation, aucun serveur. Les décisions et dossiers sont gardés dans le navigateur du visiteur (bouton « Réinitialiser la démo » dans le bandeau).
