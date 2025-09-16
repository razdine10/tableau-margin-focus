# Margin Focus: At-Risk Sub-Categories 2024–2025

This project analyzes the evolution of profitability ratio between 2024 and 2025. It highlights at-risk sub-categories such as Binders and Tables, which show increased sales but declining margins. The analysis also reveals regional disparities (Central, East, South, West) to help guide strategic business decisions.

- Dashboard: https://public.tableau.com/app/profile/razdine.said/viz/MarginFocusAt-RiskSub-Categories20242025/Tableaudebord1?publish=yes

## Files
- Margin Focus_ At-Risk Sub-Categories 2024–2025.twbx: Tableau workbook package.

## Procédure: récupérer le fichier depuis GitHub et l’ouvrir dans Tableau

- **Option 1 — Téléchargement (simple)**
  1. Ouvrez la page du dépôt GitHub.
  2. Cliquez sur `Code` > `Download ZIP`.
  3. Décompressez le ZIP; vous verrez le fichier `.twbx`.

- **Option 2 — Cloner le dépôt (recommandé si vous allez republier)**
  1. Copiez l’URL HTTPS du dépôt.
  2. Dans le Terminal:

```bash
cd "/Users/razdinesaid/Desktop"
git clone https://github.com/<votre-username>/margin-focus-at-risk-sub-categories-2024-2025.git
cd margin-focus-at-risk-sub-categories-2024-2025
```

- **Ouvrir dans Tableau Desktop / Tableau Public (app Desktop)**
  - Double-cliquez sur le fichier `.twbx` OU ouvrez Tableau > `File` > `Open` et sélectionnez le fichier.
  - Le `.twbx` contient les sources packagées; vous pouvez modifier feuilles, dashboards et calculs.
  - Pour publier: `File` > `Save to Tableau Public As…`, puis ajoutez titre/description.

- **Ouvrir via Tableau Public (web)**
  1. Connectez-vous sur Tableau Public.
  2. `Créer` > `Téléverser un classeur` (Upload a workbook).
  3. Sélectionnez le `.twbx`, puis cliquez sur `Modifier` pour travailler dans le navigateur.
  4. Enregistrez; le tableau de bord sera disponible sur votre profil.

- **Re-pousser vos changements sur GitHub (si vous avez cloné)**

```bash
git add "Margin Focus_ At-Risk Sub-Categories 2024–2025.twbx"
git commit -m "Mise à jour du classeur"
git push
```

- **Notes**
  - Si le `.twbx` > 100 Mo, utilisez Git LFS ou allégez le classeur.
  - Si certaines connexions sont "live", vérifiez qu’elles sont packagées ou reconnectez-les après ouverture.
