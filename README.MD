# Rotary Encoder Explainer

A Python script that plots the signals seen by a microcontroller when a rotary encoder is turned. A bunch of parameters can be changed. Useful to design the low-pass filter and see the shape of your pulses.

## Usage

1) Activate the virtual environment

2) Start the Bokeh server (the `--dev` flag is optional, in case you want to see changes in the code as they are saved)

```bash
bokeh serve src\PulseGraph.py --dev
```

3) Open your browser and head to `http://localhost:5006/PulseGraph`