

# Digital Stopwatch Project

A micro-project for the course **22ECT31 - Digital Electronics**, implemented using **IC 555 Timer**, **IC 4026 Counter**, and **7-segment displays**. This stopwatch can count seconds from **00 to 59**, featuring **Start/Stop** and **Reset** buttons.

## 📁 Project Files

| File | Description |
|------|-------------|
| `Report.pdf` | Detailed report of the project including methodology, design, simulation, and results |
| `DE Output.pdf` | Output observations and implementation outcomes |
| `DE PPT.pptx` | PowerPoint presentation for the project |
| `StopWatch Circuit Diagram.jpg` | Hand-drawn circuit diagram |
| `IC 555 Pinout.png` | Pin configuration of the 555 Timer |
| `IC 4026 Pinout.png` | Pin configuration of the 4026 Counter IC |

## 🛠️ Components Used

- IC 555 (Timer)
- IC 4026 (x2 – Counter and Display Driver)
- 7-Segment Displays (x2)
- Push Buttons (Start/Stop, Reset)
- Resistors, Capacitors, Potentiometer (50k)
- 5V DC Power Supply

## ⚙️ Working Principle

1. **Clock Pulse Generation**: IC 555 in astable mode generates a 1Hz clock pulse.
2. **Counting**: Clock pulses feed into the first IC 4026, which counts 0-9. On the 10th pulse, it carries to the second IC 4026 to increment tens.
3. **Display**: Both ICs drive 7-segment displays showing elapsed time.
4. **Controls**:
   - **Start/Stop**: Enables/disables clock pulses.
   - **Reset**: Clears counters to 00.

## ✅ Output

   [DigitalStopwatch.mp4](https://github.com/user-attachments/assets/fca4d497-cc74-4aa5-a369-9a526c9ae2f8)

- Accurately counts from **00 to 59 seconds**
- Smooth rollover to 00 after 59
- Fully tested in **Proteus simulation** and **hardware implementation**

## 🔮 Future Scope

- Extend time count to **minutes** by adding another IC 4026
- Add **buzzer/alarm** for specific time events
- Migrate from dot board to **PCB**
- Optional: Upgrade to **microcontroller (e.g., Arduino)** for features like lap timing

## 👨‍💻 Team Members

- Hariprasad M (23ECR068)
- Kishorekumar S (23ECE117)
- Prasath R (23ECL255)

## 📜 License

This project is intended for **educational use**. Feel free to use and modify with credit.

