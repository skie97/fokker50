# Fokker 50 Hot Poops!
Unsual Attitude Recoveries
``` mermaid
---
title: UA Recovery
---
flowchart TD
A([Id UA Type])--Nose High-->B
A--Nose Low-->C
B("GA
T/O Detent")--"< 30°NU"-->D
D("Roll wings level + Ease nose to horizon")-->F
F{Speed?}--"< 120KIAS"-->G("≅10°ND
T/O Detent")-->F
F--"≥ 120KIAS"-->H("S&L Flight")
B--"≥ 30°NU"-->E
E("Accept AOB + Ease nose to horizon")--Speed pass 100KIAS-->I
I("Roll Wings Level")-->F
C("Flt Idle
Roll wings level
Pitch @ Max G")-->J{"Speed?"}
J--">180KIAS"-->K("≅10°NU")
K-->J
J--"≤180KIAS"-->H
H-->L{"Gears
or Flaps
Overstress?"}
L--Yes-->M("Leave down")
L--No-->N("All Good!")
```
