# Athlete Testing Kit

A portable, low-cost system for measuring vertical jump height and sprint split times for track and field athletes, built with an ESP32, IR break-beam sensors, and 3D-printed mounts.

## Why I Built This

I'm a mechanical engineering student and a high jumper/triple jumper. Commercial jump and timing systems are expensive, so I wanted to build a student friendly alternative and measure how accurate it is.

## Planne features

1. Vertical jump tester: adjustable height beam on a notched metal rod with an audible tone and LED when broken
2. Sprint timing gates: split times between two gates, with first-break, reconnect, and flying-start modes
3. Data logging: every trial saved to CSV with Python, with plots
4. Wired or wireless gates, compared against a video reference
5. Further reach goals: solar-powered gates, camera-based triple jump measurement

## Milestones

1. Single-beam trigger with buzzer and LED
2. Serial logging to CSV with Python
3. Three-beam array with "latch and report highest" logic
4. Full beam array (6-8 beams) on notched rod
5. Wired timing gates
6. Wireless (ESP-NOW) timing gates
7. Validation testing and write-up

## Goals and accuracy

1. get a reading close to a quarter inch for the vertical jump test (verified with a standard issue vert tester)
2. Get a reading of .5 for the dash (verified with hand times and video fram by frame recording)

## Hardware

| Part | Purpose | Approx. cost |
|------|---------|--------------|
| [ESP32 dev board] | Microcontroller | [$] |
| [IR break-beam sensor pairs] | Beam detection | [$] |
| [Passive buzzer + LEDs] | Audio/visual feedback | [$] |
| [3D-printed mounts] | Sensor and gate holders | [$] |

Total cost: [$]

## Repository Structure

- `firmware/`: ESP32/Arduino code
- `python/`: logging and plotting scripts
- `cad/`: CAD files (STEP/STL) for mounts and gate posts
- `docs/`: photos, wiring diagrams, and notes
- `data/`: sample test data and validation results

## Setup

1. [Wiring diagram or photo]
2. [How to upload the firmware]
3. [How to run the Python logger]

## Results

[Fill in after testing: measured timing error vs. video reference, jump height resolution vs. tape measure, repeatability across trials, and 2-3 graphs.]

## What I Learned

[Challenges, design iterations, and what I'd change.]

## Next Steps

[Future improvements.]

## Author

Ola, Mechanical Engineering, Montgomery College