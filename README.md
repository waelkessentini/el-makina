# El Makina · المكينة

A Tunisian bluffing card game for the browser. Play against bots, or with up to three friends online, each on their own phone.

**Play:** https://waelkessentini.github.io/el-makina/

## Playing with friends
1. Open the link, open the menu (☰) and choose **العب مع صحابك**.
2. Type your name and tap **نحلّ طاولة** (host a table).
3. Send your friends the 5-letter code, or tap **ابعث الرابط** to share the invite link.
4. Friends open the link, type a name and tap **ندخل** (join).
5. Choose the response time and bot level, then tap **ابدا الجولة** (start). Empty seats are played by bots.

The host's browser runs the table, so keep it open. A friend who drops out is replaced by a bot and can rejoin with the same link. Online play needs an internet connection; the browsers connect directly and a free public PeerJS server only introduces them. Solo play works offline.

Every player's browser runs the same game, so this is a game between friends: someone using the browser's developer tools could see hidden cards.

The whole game is the single file `index.html`.
