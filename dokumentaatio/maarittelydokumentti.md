Määrittelydokumentti kurssille Tietorakenteiden harjoitustyö

Toteutan työvuorosuunnittelua suorittavan ohjelman. Työssä toteutetaan Ford-Fulkerson -algoritmi.

Ratkaisen työvuorojen suunnitteluun liittyvää ongelmaa, jossa pyrkimyksenä on työvuorojen mahdollisimman tasainen jakautuminen joukolle työntekijöitä. Valitsin algoritmiksi Ford-Fulkersonin algoritmin, koska maksimivirtaus tuntui aiheena kiinnostavalta.

Ohjelma saa syötteenä työntekijöiden määrän, sekä työvuorojen joukkoja. Ohjelma luo työntekijöiden tekemien työvuorojen perusteella muodostetuista työvuorohistorioista verkkoja työntekijöiden ja työvuorojen välille. Tämän jälkeen ohjelma löytää halutunlaisen kombinaation työntekijöistä ja työvuoroista.

Ford-Fulkerson -algoritmin aikavaativuus on Wikipedian[1] mukaan O(Ef), missä E on verkon kaarien määrä ja f on maksimivirtaus. Eräs variaatio Ford-Fulkersonin algoritmista on Edmonds-Karpin algoritmi[2], jonka aikavaativuus on O(VE²), missä V on verkon solmujen määrä ja E on verkon kaarien määrä. Tässä työssä toteutetaan toinen näistä algoritmeista.

Työssä käytetään lähteinä Antti Laaksosen kirjoittamaa Tirakirjaa, https://github.com/pllk/tirakirja/raw/master/tirakirja.pdf, teosta Introduction to Algorithms (Cormen et al.), sekä Wikipediaa.



[1] https://en.wikipedia.org/wiki/Ford–Fulkerson_algorithm

[2] https://en.wikipedia.org/wiki/Edmonds%E2%80%93Karp_algorithm
