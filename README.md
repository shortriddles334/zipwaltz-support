# zipwaltz-support
Public support and privacy information for Zipwaltz

## Duel page (`/duel/`)
`duel/index.html` is the browser duel page: a Zipwaltz duel link (`…/duel/#duel=…`) opens here and plays the
duel with no install; the App Store and Google Play buttons show on the title. It is generated from the game
repository (`shortriddles334/slingshot-planet`) with `node tools/build-duel-page.cjs OUT_DIR`; do not edit it by
hand. Built from slingshot-planet `d86f1bd`.

## Party invite page (`/party/`)
`party/index.html` is the Orbit Party invite page. A room invite (`…/party/?room=CODE`) shows a party link preview
("Join my Orbit Party"), then opens the duel page beside it with the same query, where the room screen opens with the
code filled in. It is under 2 KB and loads nothing. It is generated from the game repository with
`node tools/build-party-page.cjs OUT_DIR`; do not edit it by hand. Built from slingshot-planet `663f87e`.
