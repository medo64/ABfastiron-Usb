# A-BFastiron SS-305MP USB Board

## Parts

| #  | Name                            | RefDes   | DigiKey                  |
|---:|---------------------------------|----------|--------------------------|
|  1 | C 10uF X5R 50V (1206)           | C1       | 1276-6736-1-ND           |
|  1 | C 22uF X5R 25V (0805)           | C2       | 311-1903-1-ND            |
|  1 | DS LED (0805)                   | DS1      | 732-4984-1-ND            |
|  1 | F 500mA 25V (1206)              | F1       | 507-1803-1-ND            |
|  1 | J USB A 2.0 Vertical (4w)       | J1       | 2987-CU01SAV1S00-ND      |
|  1 | R 3.3K 5% 0.125W (0805)         | R1       | RMCF0805JT3K30CT-ND      |
|  1 | VR VXO7805-1000 (SIP-3)         | VR1      | 102-4258-ND              |
|  1 | W JST-XH 100mm (2w)             | -        | -                        |
|  2 | H Screw M3x8mm                  | -        | -                        |

## Notes

Please check polarity of DC-DC voltage regulator. There are two common pinouts;
one using 7805-like setup while other has the same pinout in reverse. VXO7805
listed here is one of those and silk-screen is adjusted for it. If you have one
of regulators with "proper" pinout, just rotate it and mount it slightly off the
board - there's enough space either way and, as long as pin 1 matches, there
will be no impact to circuit.
