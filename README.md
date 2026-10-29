# Lane Line

A phone app for league bowling. It does your targeting math at the lane, tells you where to stand for any spare, and keeps a log of every league night on your phone.

- **Line:** pick your break point and arrow; get your start, slide, and lay down boards.
- **Moves:** try a 2 and 1, 3 and 2, or any feet and eyes move and see where the break point lands.
- **Spares:** tap the pins left standing; get your stand board, target, and where to hit.
- **Body:** setup checklists for strike shots and both sides of the lane.
- **Log:** save each shot. Every league night keeps its shots, lanes, notes, strike %, spare %, and drift.
- **My numbers:** your drift, layoff, and spare spots, plus a board and pin reference lane.

Everything runs in one file (`index.html`). There is no server and no account.

## Where your data lives

Your numbers and logs save on your phone, in the browser's local storage, every time you change something. Nothing leaves the phone.

- Install Lane Line to your home screen (steps below) and always open it from there. On iPhone, the home screen app keeps its own storage, separate from Safari tabs.
- The app asks the browser to protect its storage from automatic cleanup. The Log tab tells you whether that worked.
- Use **Log > Backup > Save backup file** now and then. **Restore backup** brings it back on a new phone, and it merges nights without duplicating them.

## Add it to your phone

- **iPhone (Safari):** open the link, tap **Share**, then **Add to Home Screen**.
- **Android (Chrome):** open the link, tap the menu, then **Install app** or **Add to Home screen**.

After the first open, it works with no signal, which helps in bowling centers with bad reception.

## Sources

The targeting math and spare system come from:

- [Improve Your Targeting By Understanding The Math](https://www.youtube.com/watch?v=eoEDaYzhH3Y), Bald Brothers Bowling
- [How To Shoot Spares Like A Pro](https://www.youtube.com/watch?v=FXIeYKWzZmI), Darren Tang
- [How To Shoot Spares In Bowling](https://www.youtube.com/watch?v=kCIXAlB55RQ), Luis Napoles
