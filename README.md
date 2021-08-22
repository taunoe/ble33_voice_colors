# ble33_voice_colors

Häälkäsklusega värvi määramine

## Installida Nodejs

## Installida Arduino CLI

## Installi Edge Impulse CLI

    npm install -g edge-impulse-cli

## Lae Edge Impulse firmware

Viia Arduino Nano33Ble alglaadimis reziimi: reset nuppu vajutada kiiresti kaks korda. Kollane tuli hakkab vilkuma.

Kataloogis [edge_impulse_firmware/arduino-nano-33-ble-sense/](./edge_impulse_firmware/arduino-nano-33-ble-sense/)

    ./flash_linux.sh

![Edge Impulse firmware](./img/Ekraanipilt%202021-08-22%2018-35-35.png)

## Andmete kogumine

Käivitada Edge Impulse daemon:

    edge-impulse-daemon

![Edge Impulse daemon](./img/Ekraanipilt%202021-08-22%2018-39-39.png)

Lisaks tundmatute sõnade ja müra jaoks:

* [Keyword spotting dataset](https://docs.edgeimpulse.com/docs/keyword-spotting)