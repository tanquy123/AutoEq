# AKG K3003 High Boost Filter

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -4.7dB
GraphicEQ: 21 0.0; 23 2.4; 25 1.9; 28 1.3; 31 0.8; 34 0.4; 37 0.1; 41 -0.3; 45 -0.7; 49 -1.1; 54 -1.5; 60 -2.0; 66 -2.4; 72 -2.9; 79 -3.2; 87 -3.5; 96 -3.8; 106 -4.1; 116 -4.3; 128 -4.6; 141 -4.7; 155 -4.9; 170 -4.9; 187 -4.9; 206 -4.8; 227 -4.6; 249 -4.3; 274 -4.1; 302 -3.7; 332 -3.2; 365 -2.8; 402 -2.3; 442 -2.0; 486 -1.6; 535 -1.2; 588 -0.7; 647 -0.2; 712 0.0; 783 0.4; 861 0.3; 947 0.2; 1042 -0.2; 1146 -0.4; 1261 -0.7; 1387 -0.8; 1526 -1.2; 1678 -1.7; 1846 -1.8; 2031 -1.7; 2234 -1.5; 2457 -1.5; 2703 -1.5; 2973 -1.5; 3270 0.3; 3597 4.0; 3957 3.9; 4353 -1.3; 4788 -6.2; 5267 -5.7; 5793 -4.4; 6373 0.4; 7010 2.1; 7711 0.2; 8482 -4.5; 9330 -10.2; 10263 -10.0; 11289 -2.4; 12418 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`AKG K3003 High Boost Filter GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-46**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `AKG K3003 High Boost Filter ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-2.9dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 19 Hz    | 1.18 | 3.3 dB   |
| Peaking | 158 Hz   | 0.51 | -5.1 dB  |
| Peaking | 5259 Hz  | 3.55 | -10.4 dB |
| Peaking | 6888 Hz  | 0.95 | 5.6 dB   |
| Peaking | 9648 Hz  | 3.26 | -15.2 dB |
| Peaking | 801 Hz   | 1.97 | 1.5 dB   |
| Peaking | 2654 Hz  | 0.89 | -2.8 dB  |
| Peaking | 3817 Hz  | 3.82 | 6.9 dB   |
| Peaking | 4601 Hz  | 9.4  | -3.4 dB  |
| Peaking | 12009 Hz | 7.5  | 2.3 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/AKG%20K3003%20High%20Boost%20Filter/AKG%20K3003%20High%20Boost%20Filter.png)