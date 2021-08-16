# Kliento mintys

- norim galeti ikurtam kaleimui `new Jail()` suteikti pavadinima ir ji veliau keisti;

- ikurus kaleima, turi buti nurodomas jo dydis pagal kamerose laikymu kaliniu kieki, pvz, reikalingas metodas, muriame nurodysime kameros dydi ir kiek tokiu kameru yra;

- atvezus kalinius, jie visu pirma yra sutalpinami i didziausia apimti turimas kameras;

- reikia galimybes isleisti kalinius i laisve;

- reikia galimybes atlaisvinti kamera ir jeigu joje buvo kaliniu, tai juos privalu perkelti i kitas kameras;

- reikia metodo, kuris isspausdintu visu kameru, pagal dydi, uzimtuma, t.y.

```
============================================================
"XXX" kaleimas
============================================================
Vietu: 1; viso: 10; uzimtos pilnai: 3; uzimtos ne pilnai: 0;
Vietu: 3; viso: 10; uzimtos pilnai: 2; uzimtos ne pilnai: 1;
Vietu: 8; viso: 20; uzimtos pilnai: 5; uzimtos ne pilnai: 2;
============================================================
Viso vietu: 200; kaliniu: 70;
============================================================
```
