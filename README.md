# Pack de campagne — Dr Mohamed Fawzi Bendimerad · Liste 14 · Zone 6

Kit de mobilisation (GOTV) pour les législatives du **2 juillet 2026**, diaspora **Zone 6 (Golfe / Asie / Océanie)**, cible prioritaire **Golfe**, langues **AR + EN**.

⏱️ **Urgent** : le vote à l'étranger s'étale sur plusieurs jours et se termine le 2 juillet. En France il commence le 27 juin — pour le Golfe, **confirmer la fenêtre exacte auprès des consulats** et diffuser dès maintenant.

## Contenu du dossier
| Fichier | Quoi | Usage |
|--------|------|-------|
| `index.html` | Page web unique bilingue (programme + comment voter + partage) | **À héberger**, c'est LE lien à diffuser |
| `messages-whatsapp.md` | Messages prêts à coller (3 phases + statut) | Copier-coller dans les groupes |
| `script-video.md` | Scripts micro-vidéos AR/EN avec timing | À filmer par le candidat |
| `story.svg` | Visuel story/statut 9:16 (1080×1920) | Exporter en PNG |
| `post.svg` | Visuel post carré (1080×1080) | Exporter en PNG |
| `badge-profil.svg` | Cadre photo de profil "Vote 14" | Exporter en PNG |

## 1. Mettre la page en ligne (3 min)
La page est **un seul fichier autonome** (aucune dépendance).
- **Le plus simple** : glisser `index.html` (+ `fawzi.jpg`) sur [netlify.com/drop](https://app.netlify.com/drop) → lien instantané.
- **Ou** Vercel / GitHub Pages / l'hébergement de ton choix.
- Mets une **photo du candidat** nommée `fawzi.jpg` dans le même dossier (sinon la page s'affiche proprement sans photo).
- Une fois en ligne, copie l'URL dans `[LIEN]` des messages WhatsApp.

## 2. Exporter les visuels SVG → PNG
- **Sans rien installer** : ouvre le `.svg` dans Chrome → capture, ou utilise [cloudconvert.com](https://cloudconvert.com/svg-to-png).
- **En ligne de commande** (si `rsvg-convert` ou Inkscape installé) :
  ```
  rsvg-convert -w 1080 -h 1920 story.svg -o story.png
  rsvg-convert -w 1080 -h 1080 post.svg  -o post.png
  rsvg-convert -w 1080 -h 1080 badge-profil.svg -o badge-profil.png
  ```
- Les SVG référencent `fawzi.jpg` ; place-la dans le dossier avant export pour qu'elle apparaisse.

## 3. Diffuser
Suis l'ordre de `messages-whatsapp.md` : message d'info → comment voter → rappel jour J. Le **partage individuel** (chacun renvoie à ses contacts) est plus efficace que les gros groupes.

---

## ⚠️ À VÉRIFIER avant diffusion (ne pas diffuser une erreur)
Ces points sont fondés sur les règles nationales ANIE, mais **à confirmer auprès des consulats du Golfe** :
1. **Numéro de liste = 14** : confirmé par l'affiche, mais re-vérifier que c'est bien le n° officiel sur le bulletin de la Zone 6.
2. **Dates et horaires exacts du vote** par consulat (Riyad, Djeddah, Abou Dhabi, Dubaï, Doha, Koweït…). La fenêtre « plusieurs jours jusqu'au 2 juillet » est la règle ; l'horaire précis est consulaire.
3. **Couverture Bahreïn / Oman** : vérifier de quelle ambassade dépendent ces pays (peuvent être rattachés à une mission voisine).
4. **Pièces acceptées** : passeport / carte d'identité nationale / carte consulaire + inscription sur la liste électorale consulaire — confirmer le libellé exact côté consulat.

Source règles de vote : ANIE / guides consulaires des législatives du 2 juillet 2026.

## Idées bonus (si tu as le temps)
- QR code de l'URL imprimé sur un visuel → partage hors-ligne (mosquée, association).
- Liste de 10–15 « relais » par ville chargés de réinjecter le lien dans leurs groupes.
- Story « rappel J-1 » programmée la veille au soir.
