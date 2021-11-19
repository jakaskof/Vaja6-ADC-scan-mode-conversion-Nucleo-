# Vaja6-ADC-scan-mode-conversion-Nucleo-

Odgovori na vprašanja:
Določite in aktivirajte tri analogne vhode za kanale IN1, IN2 in IN3 za zunanje potenciometre kot Single-ended vhod. To bodo pini ____PC1______, _PC2________ in ___PC0_______. 
Izbrani pini naj bodo vsi v isti grupi/skupini! Katera skupina je to? ___skupina C_.
Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pinov? ___ADC1_IN1______, _ADC_IN2________ in __ADC_IN3______.
V oknu Configuration ADC pretvorbe V Parameter settings izberite ločljivost pretvorbe na 8-bitno, torej je območje vrednosti od 0 ÷ 255. Clock Prescaler nastavite tako, da bo izračunana frekvenca vzorčenja 4 MHz. Koliko bo izbrana vrednost parametra? __Izbrana vrednost je 4__________.
Koliko je privzeta vrednost paramtera Number of Conversion? __1____ .
Čas vzorčenja Sampling Time izberite 92.5 cikla. Koliko je čas vzorčenja v mikro sekundah? _______26,125 mikrosekund______. Enačba za izračun: tvz = (tvz_cik + 12) / ftakta_pretvorbe
V zavihku DMA Settings kliknite Add in v nastalem polju »select« izberite možnost ADC1. Dolžina podatka pretvorbe bo 1 Byte, zato ustrezno popravite izbirno polje Data Width: ____byte________ (tako za Peripheral in Memory). 
Kaj pomeni kratica DMA?______Direct memory access___.


Komentar:
Ob dolgem poškušanju programiranja nama je naposled uspelo. Največ težav nama je povzročalo prikazovanje vrednosti v oknu Live expression. Ta vaja se nama je zdela bolj zahtevna kot prejšnje, vendar jo ocenjujeva kot uspešno zaključeno.

Avtorja: Svit Pravdič in Jaka Škof
