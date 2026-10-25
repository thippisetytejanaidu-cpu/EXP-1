
# EXP-1: Verification of Kirchhoff's Laws (KVL and KCL)

## AIM

a. To verify Kirchhoff's Voltage Law (KVL) for the given circuit.

b. To verify Kirchhoff's Current Law (KCL) for the given circuit.

## APPARATUS REQUIRED

| S. No. | Components | Range/Value | Quantity |
|---|---|---|---|
| 1 | Resistor | As per circuit diagram | 3 |
| 2 | Voltmeter (DC) | 0-30 V | 3 |
| 3 | Ammeter (DC) | 0-200 mA | 3 |
| 4 | Breadboard | - | 1 |
| 5 | Regulated Power Supply (RPS) | 0-30 V | 1 |
| 6 | Connecting wires | As required | As required |

## THEORY

### a. Kirchhoff's Voltage Law (KVL)

Kirchhoff's Voltage Law states that the algebraic sum of all voltages around any closed loop in an electrical circuit is zero.

**Formula:**

V - V1 - V2 - V3 = 0

Therefore,

V = V1 + V2 + V3

### b. Kirchhoff's Current Law (KCL)

Kirchhoff's Current Law states that the algebraic sum of all currents entering and leaving a node is zero. The total current entering a junction is equal to the total current leaving the junction.

**Formula:**

I1 = I2 + I3

## PROCEDURE

### a. KVL

1. Connect the circuit as shown in the KVL circuit diagram.
2. Check whether the RPS voltage is set to zero.
3. Check all the meters for zero reading.
4. Switch on the RPS.
5. Set the input voltage to the required value.
6. Record the voltmeter readings across each resistor.
7. Repeat the procedure for different input voltages and tabulate the readings.
8. Verify that the sum of the voltage drops across the resistors equals the supply voltage.

### b. KCL

1. Connect the circuit as shown in the KCL circuit diagram.
2. Check whether the RPS voltage is set to zero.
3. Check all the meters for zero reading.
4. Switch on the RPS.
5. Set the input voltage to the required value.
6. Record the current readings in the different branches using the ammeters.
7. Repeat the procedure for different input voltages and tabulate the readings.
8. Verify that the current entering the junction equals the sum of the currents leaving the junction.

## CIRCUIT DIAGRAM
<img width="1920" height="1080" alt="Screenshot 2026-10-14 170702" src="https://github.com/user-attachments/assets/d0e9a39a-28ef-4297-9521-22f357e615f2" />
<img width="1920" height="1080" alt="Screenshot 2026-10-14 170633" src="https://github.com/user-attachments/assets/6dece8f5-8076-471c-9b62-0816a6c2695f" />

### a. KVL

The KVL circuit consists of a 100 V battery and three resistors connected in series.

- R1 = 30 ohms
- R2 = 50 ohms
- R3 = 100 ohms

The voltmeters are connected in parallel across each resistor.

### b. KCL

The KCL circuit consists of a 100 V battery, with R1 in series with a parallel combination of R2 and R3.

- R1 = 30 ohms
- R2 = 100 ohms
- R3 = 50 ohms

The ammeters measure the total current and the currents in the two branches.

## CALCULATIONS

### a. KVL

**Given:**

R1 = 30 ohms

R2 = 50 ohms

R3 = 100 ohms

Supply voltage V = 100 V

**Total resistance:**

RT = R1 + R2 + R3

RT = 30 + 50 + 100

RT = 180 ohms

**Circuit current:**

I = V / RT

I = 100 / 180

I = 0.556 A

**Voltage across R1:**

V1 = I x R1

V1 = 0.556 x 30

V1 = 16.67 V

**Voltage across R2:**

V2 = I x R2

V2 = 0.556 x 50

V2 = 27.78 V

**Voltage across R3:**

V3 = I x R3

V3 = 0.556 x 100

V3 = 55.56 V

**Verification of KVL:**

V = V1 + V2 + V3

V = 16.67 + 27.78 + 55.56

V = 100.01 V

Therefore, the total voltage drop is approximately equal to the supply voltage of 100 V.

Hence, KVL is verified theoretically.

### b. KCL

**Given:**

R1 = 30 ohms

R2 = 100 ohms

R3 = 50 ohms

Supply voltage V = 100 V

**Equivalent resistance of the parallel branch:**

RP = (R2 x R3) / (R2 + R3)

RP = (100 x 50) / (100 + 50)

RP = 5000 / 150

RP = 33.33 ohms

**Total resistance:**

RT = R1 + RP

RT = 30 + 33.33

RT = 63.33 ohms

**Total current:**

I1 = V / RT

I1 = 100 / 63.33

I1 = 1.579 A

**Voltage across the parallel branches:**

VP = I1 x RP

VP = 1.579 x 33.33

VP = 52.63 V

**Current through R2:**

I2 = VP / R2

I2 = 52.63 / 100

I2 = 0.526 A

**Current through R3:**

I3 = VP / R3

I3 = 52.63 / 50

I3 = 1.053 A

**Verification of KCL:**

I1 = I2 + I3

I1 = 0.526 + 1.053

I1 = 1.579 A

Therefore, the total current entering the junction is approximately equal to the sum of the branch currents leaving the junction.

Hence, KCL is verified theoretically.

<img width="750" height="1280" alt="WhatsApp Image 2026-10-25 at 12 46 37 PM" src="https://github.com/user-attachments/assets/35a3fe74-5576-4bc5-981c-e9aaf5c3dd7a" />

<img width="770" height="1280" alt="WhatsApp Image 2026-10-25 at 12 46 38 PM" src="https://github.com/user-attachments/assets/e02136ae-e8a2-41ec-93e6-04f9f70936bc" />


## TABULATION

### a. KVL - Observed Readings

| S. No. | Resistor | Resistance | Voltage |
|---|---|---|---|
| 1 | R1 | 30 ohms | 16.67 V |
| 2 | R2 | 50 ohms | 27.78 V |
| 3 | R3 | 100 ohms | 55.56 V |
| 4 | Total voltage drop | - | 100.01 V |
| 5 | Supply voltage | - | 100 V |

**Note:** These KVL values are calculated from the supply voltage and resistor values shown in the screenshot. They are not confirmed exact meter readings.

### b. KCL - Observed Readings

| S. No. | Branch | Current |
|---|---|---|
| 1 | Total current (I1) | 1.58 A |
| 2 | Current through R2 (I2) | 0.53 A |
| 3 | Current through R3 (I3) | 1.05 A |
| 4 | Sum of branch currents (I2 + I3) | 1.58 A |

**Verification:**

I1 = I2 + I3

1.58 = 0.53 + 1.05

1.58 = 1.58 A

Therefore, KCL is verified using the displayed readings.

## RESULT

Thus, Kirchhoff's Laws were verified for the given circuits.

- **KVL:** The sum of the voltage drops around a closed loop is approximately equal to the supply voltage.
- **KCL:** The total current entering a junction is equal to the sum of the currents leaving the junction.






