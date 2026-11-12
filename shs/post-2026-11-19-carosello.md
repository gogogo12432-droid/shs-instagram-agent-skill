# Post 2: carosello di giovedì 19 novembre, 19:00

BOZZA da approvare. Non pubblicato. Tipo: Teach (fiducia). Formato:
carosello di 7 slide, 1080 x 1350 px (4:5), nessuna persona.

L'idea: dire in anticipo le cose che l'ospite scopre solo all'arrivo (niente
cucina, colazione non inclusa, tassa di soggiorno). Chi legge sa cosa
aspettarsi e chi scrive ARENA è già convinto.

## Slide

| n. | foto | testo a schermo (IT / EN) |
| --- | --- | --- |
| 1 (copertina) | `piazza-bra.jpg`, taglio sull'Arena | 5 cose da sapere prima di prenotare a Verona. / 5 things to know before booking in Verona. |
| 2 | `ingresso-1.jpg` (verticale, senza il quadro) | Check-in dalle 15:00, check-out entro le 11:00. Ti accogliamo di persona. / Check-in from 3 pm, check-out by 11 am. We welcome you in person. |
| 3 | `ingresso-2.jpg` o `ingresso-3.jpg` (da scegliere) | Ascensore, secondo piano. / Elevator, second floor. |
| 4 | `soggiorno-1.jpg` | Tassa di soggiorno: si paga all'arrivo, in contanti. Bambini fino a 14 anni esenti. / Tourist tax: paid on arrival, in cash. Children up to 14 are exempt. |
| 5 | `soggiorno-2.jpg` o `soggiorno-3.jpg` (angolo caffè, se c'è) | Niente cucina, colazione non inclusa. C'è l'angolo caffè: Nespresso, tè e tisane. / No kitchen, breakfast not included. There is a coffee corner: Nespresso, tea and herbal teas. |
| 6 | `camera-1.jpg` | 4 posti letto per appartamento. Culla gratuita per neonati, su richiesta. / 4 beds per apartment. Free cot for babies, on request. |
| 7 | `piazza-bra.jpg` | Sul nostro sito il prezzo è più basso che sulle piattaforme. Commenta ARENA. / Our website has a lower price than the booking platforms. Comment ARENA. |

Tutti i dati vengono dal sito sweethomesuites.eu o dall'annuncio Airbnb
(vedi `templates/voice-shs.md`). Le foto di `ingresso-2/3` e `soggiorno-2/3`
non le ho guardate: scegli quella dove si vede meglio (e senza persone).

## Caption in italiano

```
5 cose da sapere prima di prenotare le nostre suite a Verona.

Check-in dalle 15:00 e check-out entro le 11:00, con accoglienza di persona. Ascensore e secondo piano. La tassa di soggiorno si paga all'arrivo, in contanti: i bambini fino a 14 anni sono esenti. Niente cucina e colazione non inclusa, ma c'è l'angolo caffè con Nespresso, tè e tisane. Quattro posti letto per appartamento e culla gratuita per i neonati, su richiesta.

Non accettiamo animali né feste di addio al celibato o nubilato.

Sul nostro sito il prezzo è più basso che sulle piattaforme. Commenta ARENA e ti mandiamo il link per chiedere il prezzo per le tue date. Cancellazione gratuita fino a 7 giorni prima dell'arrivo.

#verona #arenadiverona #piazzabra #veronaitaly #sweethomesuites
```

## Caption in inglese

```
5 things to know before booking our suites in Verona.

Check-in from 3 pm and check-out by 11 am, with a personal welcome. Elevator and second floor. The tourist tax is paid on arrival, in cash, and children up to 14 are exempt. There is no kitchen and breakfast is not included, but you get a coffee corner with Nespresso, tea and herbal teas. Four beds per apartment and a free cot for babies, on request.

We do not accept pets or bachelor and bachelorette parties.

Our own website has a lower price than the booking platforms. Comment ARENA and we will send you the link to request a price for your dates. Free cancellation up to 7 days before arrival.
```

## Confermato dal titolare (12 novembre)

1. Cancellazione "gratuita fino a 7 giorni prima dell'arrivo": ok.
2. Tassa di soggiorno: **senza cifra** (come nella bozza).
3. Niente animali e niente feste di addio: valgono anche dal sito.
4. Ascensore e secondo piano: dati corretti.

## Cosa resta da fare

- Scegliere le foto per le slide 3 e 5 (`ingresso-2/3`, `soggiorno-2/3`): non
  le ho guardate, controlla che non ci siano persone.
- **Controlli del repo:** `caption.py` (prima riga intera in 61 caratteri, 5
  hashtag sotto la riga) e `detect.py` (nessun termine da IA, nessun carattere
  invisibile). Segnala "nessun invito all'azione": è un falso allarme, lo
  strumento non riconosce "Commenta".
