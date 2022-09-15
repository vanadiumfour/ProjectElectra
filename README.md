# Project Electra

Project Electra is a rather complex multifaceted project dealing with, most simply put, electrical and electrochemical measurements. There are three Sub-Projects to Project Electra, however, only the first two will be made open-source and publicly available for a variety of reasons including the third's complexity, multi-field integration, primarily its potential for in its completed state to be a revolutionary commercial product, as well as a few other reasons. I would not suggest trying to devise what sub-project 3 is as it is ridiculously unlikely that even given Sub-Projects 1 & 2 knowledge Sub-Project 3 is related tangentially and non-linearly. 

## Project Electra Sub-Project One

Sub-Project One is by and far the most simple. It is a battery cycler project that can perform cycling using the constant current method (CC) or constant current constant voltage method (CC/CV) during battery testing. 

## Project Electra Sub-Project Two

Sub-Project Two is considerably more complex than Sub-Project One. To Start, it integrates several independent instruments and uses them in concert with one another. These instruments (or Sub-Systems) are the following:
Keithley 2400 High Accuracy Multimeter as well as either a Current or Voltage Source.
Keithley 2182A NanoVoltmeter
Keithley 6517A Electrometer / High Resistance Meter
Solartron 1260 Impedance Gain-Phase Analyzer
Solartron 1287 ElectroChemical Interface
Maccor Battery Cycler Model MC-4
Thermal Products Solutions Tenney Model TJR Thermal Isolation Chamber
Potentially Keithley 2700 Multimeter, Current or Voltage Source, and Data Acquisition Device

Other hardware and networking utilized includes the following:
<table border="0">
    <tr>
        <td>
            <ul>
                <li>Ethernet Hardware</li>
                    <ul>
                        <li>Managed Switch; Ethernet Networking</li>
                        <li>Wiring/Cabling</li>
                        <li>Ethernet to GPIB Adapter</li>
                    </ul>
                <li>GPIB Networking</li>
                <li>Thermocouples >= 2</li>
                    <ul>
                        <li>Type K</li>
                            <ul>
                                <li>Range:        -200&deg;C to 1350&deg;C</li>
                                <li>Sensitivity:  41&mu;V/C</li>
                            </ul>
                        <li>Type T</li>
                            <ul>
                                <li>Range:        -200&deg;C to 350&deg;C</li>
                                <li>Sensitivity:  43&mu;V/C</li>
                            </ul>
                        <li>Type E</li>
                            <ul>
                                <li>Range:        -110&deg;C to 140&deg;C</li>
                                <li>Sensitivity:  68&mu;V/C</li>
                            </ul>
                        <li>Most Likely Type Chosen is Type T</li>
                    </ul>
            Strain Gauge
                Precise
                Sensitive
                Detect Small (&mu;m or smaller changes is goal)
            Microcontroller and assorted electrical components including:
                Operational Amplifiers
                    Standard
                    Instrumental
                    Rail to Rail
                    Precision
                    JFET
                    Low Noise
                    Low Power
                    Type Combination
                Resistors
                    Low Accuracy
                    High Accuracy
                    Low Wattage/Current
                    High Wattage/Current
                Inductors
                    Standard
                    Wire Coils
                    Toroid
                Capacitors
                    General
                    Ceramic
                    Electrolytic
                    Polymer
                    Tantalum
                    Etc.
                Transistors
                    General
                        NPN
                        PNP
                    FET
                        NPN
                        PNP
                    MOSFETT 
                        NPN
                        PNP
                    IGBT
                    UJT
                4 x Analog to Digital Converter (ADC) >= 16bit
                PIR Motion Detector
                Potentiometers, varying resistance ranges
                Interface Electronics
                    Buttons
                    Switches
                    Rotary encoders
                    Display elements
                    LEDs
                    Etc. 
                Transformers
                    Standard
                    Tapped
                Diodes
                    General
                    Signal Diodes
                    Zerner Diodes
                    Rectifier Diodes
        </td>
        <td>
            Voltage Regulators
                Negative Voltage
                Positive Voltage
            Current Regulators
                Negative Current
                Positive Current
            Multiple Fuses
            Oscillators
                Crystal
                Other
            Relays
            Logic ICs
                AND
                OR
                NAND
                NOR
                XOR
                Inverter
            Flip Flops
                D Type
                JK Type
                SR Type
            555 Timers
            Counter
                Binary
                    Up
                    Down
                Decade
                    Up
                    Down
                Decimal
                    Up
                    Down
                Octal
                    Up
                    Down
            EEPROM(s)
            Register(s)
            Multiplexers
            DeMultiplexers
            Encoders
            Decoders
            TPM
            Register
                General
                8 Bit Shift
                4 Step Shift
                8 Step Shift
                64 Step Shift
                Quad D Type
                32 Stage Shift
                4 Bit Right / Left Shift
            Comparator
            Toroid Inductors
            Triacs
            Thyristor
            Optocouplers
            Rectifiers
                Full Wave Bridge Rectifier
            Thermistors
                NTC Type
                PTC Type
            Relays
                Mechanical
                Solid State
                Optical
            Real Time Clock or RTC
            Analog Switch IC
            Phase Locked Loop
            Monostable MultiVibrator
            Astable MultiVibrator
        </td>
    </tr>
</table>

Hardware Interface for Initialization, Activation, Simple Configuration, and Simple/Basic Control.
Computer and Software Interface for System Use, Control, Data Collection, Data Retrieval, Analysis, Sub-System Management, etc. 
Atmospheric Hygrometer / Humidity Sensor
Atmospheric Barometric Pressure Sensor
Pressure Transducer
Altimeter
Vibration Sensor
3 Axis Gyroscope
Thermal Camera

