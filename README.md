# Mujai — Card Readings + Merit (Demo)

A single-page demo: Tarot, Lenormand and Oracle readings, daily check-in, coins, history and a merit (donation) section.

- `index.html` — English version
- `th.html` — Thai version

## Run locally
Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Notes
- Outside claude.ai, AI readings use a built-in fallback text (card meanings) instead of live AI.
- Coins, history and check-ins are saved in the browser (localStorage) on that device only.
- Payments, QR codes and foundations are simulated / fictional.
