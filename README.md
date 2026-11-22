# Monitoraggio Milestone – aggiornamenti

Pacchetti firmati per l'aggiornamento automatico dei server video (canale **test**).
Ogni notte i server leggono `manifest.json`, controllano la firma `manifest.sig` con la chiave pubblica
installata e, se la versione è nuova, scaricano lo zip e ne controllano l'SHA256.

Versione attuale: **1.1.8** (2026-11-22).
