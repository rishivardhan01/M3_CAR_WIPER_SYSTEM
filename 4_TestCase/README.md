## High Level Test Cases
   | Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | OUTPUT |
   |---------|:------------|:--------|:--------|:-----------|:-------------|
   | H_01 | check if the SWITCH is pressed  | program execution | Engine starts | RED LED ON | PASS |
   | H_02 | check if the SWITCH is pressed  | program execution | Wiper starts  | BLUE LED ON | PASS |
   | H_03 | check if the SWITCH is pressed  | program execution | Wiper starts  | GREEN LED ON | PASS |
   | H_04 | check if the SWITCH is pressed  | program execution | Wiper starts  | ORANGE LED ON | PASS |
   | H_05 | check if the SWITCH is pressed  | ----------------- | Engine stop | LED OFF | PASS |

   
   
   
## Low Level Test Plan
   | Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | OUTPUT |
   |---------|:------------|:--------|:--------|:-----------|:-------------|
   | L_01 | check if the SWITCH is pressed  | program execution | Engine starts | RED LED ON | PASS |
   | L_02 | check if the SWITCH is pressed again | program execution | Wiper starts and runs at 35 percent  | BLUE LED ON | PASS |
   | L_03 | check if the SWITCH is pressed again | program execution | Wiper starts and runs at 70 percent | GREEN LED ON | PASS |
   | L_04 | check if the SWITCH is pressed again | program execution | Wiper starts and runs at 100 percent | ORANGE LED ON | PASS |
   | L_05 | check if the SWITCH is pressed again | ----------------- | Engine stop | LED OFF | PASS |
