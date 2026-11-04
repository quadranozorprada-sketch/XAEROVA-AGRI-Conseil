XAEROVA Agri Intelligence — prototype V3

Lancement :
1. Décompresser le ZIP.
2. Ouvrir le dossier dans VS Code.
3. Dans le terminal : py -m http.server 8000
4. Ouvrir http://localhost:8000

Fonctionnalités de démonstration :
- Écran d'accueil avec deux chemins : onboarding et compte prérempli.
- Profil fictif Atlantic Pineapple Estate, à Bonoua (Sud-Comoé).
- Superficie affichée : 250 acres = environ 101,2 hectares.
- Carte Leaflet avec fond satellite Esri et fond plan OpenStreetMap.
- Polygone de ferme et marqueurs de blocs fictifs.
- Météo actuelle et prévisions récupérées en direct via Open-Meteo pour les coordonnées de Bonoua.
- Heure locale Africa/Abidjan.
- Onboarding guidé en 4 étapes.

IMPORTANT — limites :
- L'entreprise, le domaine, les parcelles, les limites GPS, surfaces de blocs et alertes sont fictifs.
- Le polygone est une géométrie de démonstration, pas un relevé cadastral / GPS réel.
- Les cartes satellite sont des tuiles cartographiques externes, pas des photos drone XAEROVA.
- Les panneaux d'imagerie aérienne sont des visuels stylisés de démonstration.
- Les données météo viennent d'un modèle météo géographique pour Bonoua, pas d'une station météo installée sur la parcelle. L'API Open-Meteo est appelée directement depuis le navigateur pour ce prototype.
- Pas de connexion utilisateur, base de données, sauvegarde multi-appareils, intégration drone, analyse IA, ni sécurité de production.
- Les tuiles de carte et l'API météo nécessitent une connexion Internet.
- Vérifier les conditions d'utilisation et tarifs des fournisseurs avant usage commercial en production.

Coordonnées de référence : Bonoua 5.2720, -3.6010 (approximation de démonstration).
Conversion : 250 acres ≈ 101,17 hectares.
