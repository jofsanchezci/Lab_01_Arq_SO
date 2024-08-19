
# Laboratory Design: Digital Logic Circuits

## Objective:
The objective of this laboratory is to understand and implement basic digital logic circuits using fundamental logic gates (AND, OR, NOT). Students will learn how to construct truth tables, analyze logic circuits algebraically, and implement circuits based on Boolean expressions.

## Materials:
- Breadboard
- Logic gate ICs (e.g., 7400 series for NAND, NOR, AND, OR, NOT gates)
- Connecting wires
- Power supply (5V DC)
- Multimeter
- LEDs for output display
- Push buttons or switches for inputs

## Laboratory Tasks:

### Task 1: Truth Tables
- **Objective**: Construct truth tables for basic logic gates.
- **Procedure**:
  1. Connect an OR gate (e.g., 7432 IC) on the breadboard.
  2. Apply all possible combinations of inputs (00, 01, 10, 11) using push buttons.
  3. Record the output for each combination to construct the truth table.
  4. Repeat the procedure for AND (e.g., 7408 IC) and NOT gates (e.g., 7404 IC).
- **Expected Outcome**: Students should be able to fill out the truth tables for OR, AND, and NOT gates.

### Task 2: Operation OR with OR Gates
- **Objective**: Understand and demonstrate the OR operation using OR gates.
- **Procedure**:
  1. Connect two inputs to an OR gate.
  2. Vary the inputs (0 and 1) and observe the output using an LED.
  3. Verify that the LED lights up when at least one of the inputs is high (1).
- **Expected Outcome**: Students should observe that the OR gate output is high (LED on) when at least one input is high.

### Task 3: Operation AND with AND Gates
- **Objective**: Understand and demonstrate the AND operation using AND gates.
- **Procedure**:
  1. Connect two inputs to an AND gate.
  2. Vary the inputs (0 and 1) and observe the output using an LED.
  3. Verify that the LED lights up only when both inputs are high (1).
- **Expected Outcome**: Students should observe that the AND gate output is high (LED on) only when both inputs are high.

### Task 4: Operation NOT
- **Objective**: Understand and demonstrate the NOT operation using a NOT gate.
- **Procedure**:
  1. Connect a single input to a NOT gate.
  2. Apply a high (1) and low (0) input, and observe the output using an LED.
  3. Verify that the LED lights up when the input is low and turns off when the input is high.
- **Expected Outcome**: Students should observe that the NOT gate inverts the input.

### Task 5: Description of Logic Circuits in Algebraic Form
- **Objective**: Analyze and describe a given logic circuit algebraically.
- **Procedure**:
  1. Build a circuit using a combination of AND, OR, and NOT gates (e.g., `X = A · B + C`).
  2. Analyze the circuit and write down the Boolean expression representing it.
  3. Compare the algebraic expression with the actual behavior of the circuit.
- **Expected Outcome**: Students should be able to derive the correct Boolean expression from the circuit and verify its accuracy by testing the circuit.

### Task 6: Evaluation of Logic Circuits
- **Objective**: Evaluate the output of a logic circuit for different input combinations.
- **Procedure**:
  1. Construct a more complex logic circuit (e.g., `X = \overline{(A + B)} \cdot C`).
  2. Create a truth table for the circuit by varying the inputs.
  3. Compare the truth table with the expected output from the Boolean expression.
- **Expected Outcome**: Students should be able to evaluate the circuit’s output and ensure it matches the predicted behavior from the truth table.

### Task 7: Implementation of Circuits from Boolean Expressions
- **Objective**: Implement a logic circuit based on a given Boolean expression.
- **Procedure**:
  1. Given a Boolean expression (e.g., `Y = (A + B) \cdot \overline{C}`), design the circuit on paper.
  2. Implement the circuit on the breadboard using the appropriate gates.
  3. Test the circuit for all possible input combinations and record the output.
- **Expected Outcome**: Students should successfully build the circuit corresponding to the Boolean expression and verify its functionality.

## Evaluation:
Students will be evaluated on the following criteria:
- Correctness of truth tables.
- Ability to construct and analyze basic logic gates (AND, OR, NOT).
- Accuracy in describing circuits algebraically.
- Ability to implement and evaluate circuits based on Boolean expressions.
- Proper use of laboratory equipment and adherence to safety protocols.

## Report:
Each student should submit a report including:
- Constructed truth tables.
- Boolean expressions derived from circuit analysis.
- Observations from each task, including any discrepancies between expected and actual outputs.
- Answers to any questions provided in the lab manual.

This lab is designed to provide hands-on experience with digital logic circuits, reinforcing theoretical knowledge through practical application.
