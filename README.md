# Greece 8

8 allenamenti corpo libero da 30-40 minuti, pensati per casa o per le vacanze.

Funziona completamente offline una volta aggiunto alla schermata Home.

## Installazione su iPhone / iPad

1. Apri **https://fmondora.github.io/greece8/** su Safari
2. Tocca **Condividi** (quadrato con freccia)
3. Scorri in basso e scegli **Aggiungi alla schermata Home**

## Timer supportati

- EMOM
- AMRAP
- For Time
- Intervalli (lavoro / recupero)
- Rounds con recupero automatico

## HRV / FC (nuovo)

- Misurazione Fotocamera (PPG dito su lente posteriore + flash, simile a HRV4Training)
- Misurazione Bluetooth (Web Bluetooth, Polar H10 ecc. — IBI diretti, massima precisione)
- Calcolo RMSSD, SDNN, HR — prontezza vs baseline personale
- Tutto locale, offline, salvato nel browser
- Utile per decidere intensità sessioni Greece 8

Per la fotocamera: copri completamente flash+lente con polpastrello, pressione leggera, 60-120s a riposo.

## Sviluppo locale

```bash
python3 -m http.server 8765
```

Poi apri http://localhost:8765

## Provalo live

**https://fmondora.github.io/greece8/**

Aggiungilo alla schermata Home per usarlo offline come PWA (funziona anche senza connessione dopo il primo caricamento).

## Deploy

Deploy automatico su GitHub Pages dal branch `main` (root del repo).
