# GuitarPro dataset of classical guitar studies

Includes both `.gpx`, `.gp5` and `MIDI` files for **Brouwer's 20 Estudios Sencillos** and **Villa-Lobos 12 Études**. Annotations include dynamics and guitar fingerings. 

Folder `dada` includes both encoded and decoded versions using [dadaGP](https://github.com/dada-bots/dadaGP), created from the files in `.gp5` format. Differences between `.gpx` and `.gp5` include the removal of text (e.g. piece title, dynamic indications) and repetitions using specific symbols (e.g. *da Coda*, *da Segno*), for these raised conflicts during the process of encoding/decoding (special text characters caused the encoding process to fail; repetition symbols interrupted the decoding phase). 


