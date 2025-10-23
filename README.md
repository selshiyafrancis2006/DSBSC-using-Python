<h1>DSBSC USING PYTHON</h1>
EX NO: 2 DSB-SC-AM MODULATOR AND DEMODULATOR USING PYTHON

AIM:

To write a program to perform DSBSC modulation and demodulation using COLAB and study its spectral characteristics.

EQUIPMENTS REQUIRED

• Computer with i3 Processor • CO LAB.

Note: Keep all the switch faults in off position

Algorithm:

Define Parameters: • Fs: Sampling frequency. • T: Duration of the signal. • Fc: Carrier frequency. • Fm: Frequency of the message signal. • Amplitude: Maximum amplitude of the message signal.
Generate Signals: • Message Signal: A sinusoidal signal that will be modulated. • Carrier Signal: A high-frequency sinusoidal signal used for modulation.
DSBSC Modulation: • Modulated Signal: Multiply the message signal by the carrier signal to produce the DSBSC signal.
DSBSC Demodulation: • Multiplication: Multiply the modulated signal by the carrier signal to get the product of the message signal with itself (i.e., the original message signal plus high-frequency components). • Low-pass Filtering: Apply a Butterworth low-pass filter to remove the high- frequency components and recover the original message signal.
Visualization: Plot the message signal, carrier signal, DSBSC modulated signal, and the recovered signal after demodulation. PROCEDURE
• Refer Algorithms and write code for the experiment. • Open SCILAB in System • Type your code in New Editor • Save the file

• Execute the code • If any Error, correct it in code and execute again • Verify the generated waveform using Tabulation and Model Waveform

Model Waveform

image
Program:

<img width="509" height="518" alt="image" src="https://github.com/user-attachments/assets/afc7018c-e917-4f1a-8186-fcb86f4fe675" />

Output Graph: 

<img width="890" height="600" alt="image" src="https://github.com/user-attachments/assets/283fe6d9-5bd8-42e9-a54a-e134d09a766f" />


Tablular Column:

<img width="1559" height="932" alt="image" src="https://github.com/user-attachments/assets/810b491f-88b8-4117-836c-185815a01a35" />

Result:

Thus the DSB-SC-AM Modulation and Demodulation using python is generated.
