# node-red-type-21-master-command-flow-example
A Node-RED flow example to set sensor type and sensor range for Differential Bidirectional Pressure Sensor

## Instructions
1) Open the flow.json file and copy the raw JSON code.
2) In Node-RED, open the main menu and click on Import.
3) Paste the JSON code into the text box and click the Import button.
4) Navigate to the newly imported flow named 'Type 21 - Set Range'.
5) Configure the serial device by double-clicking on the Wireless Gateway node and selecting the correct port from the drop-down menu. /dev/ttymxc2 for Gateway
6) Click the Done button.
7) Double-click on the Settings node (yellow node) to set your desired values for the Sensor Type and Sensor Range.
8) Click the Done button.
9) Click the Deploy button (in the top right corner) to save and apply your changes.
10) Press and release the physical Reset button on your device to force it to transmit a SYNC or FLY message.
11) Wait a moment for the sensor configuration to complete.

## Sensor Type Options
<img width="171" height="125" alt="sensor_type" src="https://github.com/user-attachments/assets/678490fb-69af-441e-995e-7fb5d41c3249" />

## Sensor Range Options
<img width="222" height="578" alt="options_1" src="https://github.com/user-attachments/assets/0b3fee1a-aaf6-4d4e-9ebc-d7aa1ae6beee" />
<img width="222" height="651" alt="options_2" src="https://github.com/user-attachments/assets/931a1466-c2a0-4693-914d-de7cde19d9fc" />
<img width="222" height="721" alt="options_3" src="https://github.com/user-attachments/assets/d2113eff-8d67-424a-9cc3-3f8776c64a79" />

