AJAX

Kun lähetä painiketta painetaan selain lähettää datan
palvelimelle-> Kyseessä on HTTP POST-pyyntö jonka mukana myös täytetty data esim kirjain "a" lähtee palvelimelle. Pal-
velin vastaa koodilla 302 eli uudelleenohjaa palvelime
tekemään GET- pyynnön osoitteeseen notes-> selain lataa 
uudelleen muistiinpanojen sivun ja samalla lähtee 3 muuta
HTTP pyyntöä css, javascript, ja data.json tiedostojen
lataamiseen-> Lisätty data esim kirjain "a" näkyy sivulla

SPA

Selain lähettää pyynnön serverille->
Serveri palauttaa HTML tiedoston->
Tiedoston sisällä on JavaScriptiä jossa on koodia
joka noutaa dataa palvelimelta ja rakentaa uuden
HTML sivun/tiedoston käyttäjälle esim verkkokaupan
ostosokorin
