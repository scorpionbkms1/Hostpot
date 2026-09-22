BKMS HOTSPOT V2
================

Cette version est préparée pour l'intégration au HotSpot MikroTik RouterOS.

FICHIERS
- login.html   : portail de connexion
- status.html  : statut de session et statistiques
- logout.html  : déconnexion
- style.css    : design commun

INSTALLATION SUR MIKROTIK (LORSQUE TU AURAS LE ROUTEUR)
1. Dans WinBox, ouvre Files.
2. Ouvre le dossier hotspot (ou le dossier HotSpot utilisé par ton serveur).
3. Sauvegarde les anciens fichiers avant remplacement.
4. Envoie login.html, status.html, logout.html et style.css.
5. Vérifie le profil HotSpot et la page de login configurée.

VARIABLES MIKROTIK UTILISÉES
- $(link-login-only)
- $(link-orig)
- $(username)
- $(uptime)
- $(session-time-left)
- $(bytes-in-nice)
- $(bytes-out-nice)
- $(ip)
- $(link-logout)
- $(link-login)

IMPORTANT
Les prix affichés sont des exemples. Ils ne déclenchent aucun paiement.
La création réelle des tickets et les profils (1h, 3h, 24h, 7j) se fera côté MikroTik/User Manager/RADIUS ou via un système externe.

TEST LOCAL
Les pages sont conçues pour être servies par MikroTik. Ouvertes directement dans Chrome, les variables $(...) ne seront pas remplacées par RouterOS.
