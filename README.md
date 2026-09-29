# sandbox-metrics-oauth

Pages statiques de relais OAuth pour l'add-on Google Sheets **Sandbox Metrics** (aucun secret ici).

- `/tiktok/` : TikTok limite l'URL de redirection à 100 caractères ; cette page renvoie vers le callback Apps Script
  en conservant la query string (`auth_code`, `state`).
