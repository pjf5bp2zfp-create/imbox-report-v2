# IMBOX Report v2.0

Nouvelle interface (2026) du rapport de maintenance IMBOX — CAPS Group France STC Nord.
Mêmes fonctionnalités et même PDF officiel que la v1 (pdf-lib + `imbox-officiel-modele.pdf`), plus un Agenda local (import de planning).

Site statique : `index.html` (mobile + desktop responsive), `desktop.html` (copie), `pdf-lib.min.js`, `imbox-officiel-modele.pdf`.
Les données de planning restent uniquement sur l'appareil (localStorage) — aucun planning n'est publié ici.

## Nouveautés
- **Sauvegarde / restauration** (onglet Agenda, en bas) : export de toutes les données `imbox.v2.*` en `imbox-sauvegarde-AAAA-MM-JJ.json` (partage iPhone ou téléchargement), restauration avec « Remplacer » ou « Fusionner » (doublons ignorés par id).
- **Historique** (onglet 🗂️) : toutes les interventions, recherche + filtres mois/statut, « Modifier » / « Supprimer ».
- **Rapport du mois** (bouton en haut de l'Historique) : compte par type, détail, total gagné, export `rapport-imbox-AAAA-MM.pdf` / `.csv`.
