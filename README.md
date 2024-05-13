# PCB-Design-Application
# Aim


# Software required
Eagle

# Procedure
1.Open a new schematic file within your project.</br>
2.Use the libraries provided in EAGLE or create custom libraries if necessary.</br>
3.Place components onto the schematic sheet by using the 'Add' tool.</br>
4.Connect the components using the 'Net' tool.</br>
5.Label nets appropriately to ensure clarity</br>
6.Once routing is complete, perform a ERC to ensure there are no errors and save the schematic.</br>
7.Click on the 'Generate/Switch to Board' icon to create a board from your schematic.</br>
8.EAGLE's board layout editor allows you to place components, route traces, and define board shapes.</br>
9.Arrange components on the board to optimize space usage and minimize signal interference.</br>
10.Route traces to connect components according to your schematic.</br>
11.Use the various routing and editing tools provided by EAGLE to ensure proper routing and avoid design rule violations.</br>
12.Once routing is complete, perform a design rule check (DRC) to ensure there are no errors and save the board layout.</br>
13.Go to File > CAM Processor and set up CAM jobs to generate Gerber files for your PCB layers.</br>
14.Verify generated files to ensure they contain all necessary information.</br>
15.Save the generated manufacturing files.</br>

# Theory
This very easy project uses the 555 timer IC which works as a monostable multivibrator Its working principle is based on the electronic microphone. When there is a sound, the microphone catches that sound and sends it to the transistors. Transistors amplify those signals and send them to the 555 timer IC. The IC then drives the load accordingly. Make this circuit on a PCB and control your appliances through just one clap.

### Working 
Sound Detection: The microphone picks up sound signals, including claps.

Signal Amplification: The signal from the microphone is amplified to ensure even quiet sounds are detected.

Signal Processing: The amplified signal is processed to distinguish clap sounds from background noise.

Threshold Comparison: The processed signal is compared to a predefined threshold level.

Switching Action: If the signal exceeds the threshold, indicating a clap, a switching action is triggered to turn a device or light on or off.

Feedback Indication: Optionally, an LED or indicator provides feedback when a clap is detected.

Reset Mechanism: Some designs include a reset mechanism to prevent rapid switching in response to multiple claps.

# Circuit Diagram

![Screenshot 2024-05-13 115730](https://github.com/ssaranya27/PCB-Design-Application/assets/148853824/3675bed4-c16c-430d-9b37-5a30ed357b54)

# Output
### Schematic diagram

![ex05-output-sche](https://github.com/ssaranya27/PCB-Design-Application/assets/148853824/171e6fe4-790d-48b1-a424-30ecaef708fa)


### Layout diagram

![ex05-output-layout](https://github.com/ssaranya27/PCB-Design-Application/assets/148853824/56b8cc43-c783-417f-ba6f-8da415879800)


# Result
Thus, the clap switch circuit's schmetic diagram and layout diagram is designed successfully by using the Eagle software.

