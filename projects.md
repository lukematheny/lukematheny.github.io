## Projects

| [Home](index.md) | [Projects](projects.md) | [Resumé](resume.md) | [Skills/Passions](skills.md) |

### Slideman -- Electronic 15-puzzle

I’ve been part of the niche speedsliding community, and all the good slide puzzles were only on computers, so I created a handheld slide puzzle, fixed with mechanical buttons for tactile feedback.​

In the span of the two weeks between my internship and the fall semester of school, I built the entire machine, having to learn how to solder electrical connections and design schematics based on part datasheets. Waiting for parts to be shipped, I programmed the puzzle from scratch, itching to debug the code when I could finally test it.

<img src="images/image.png" alt="Slideman autopsy" width="300"/>

With my knowledge of Solidworks and 3D printing, I designed a chassis with perfect tolerances to secure the circuit board in place and accommodate every feature of the final design.​

### Battery Temperature Data Collection

The problem I was faced with was getting several accurate temperature measurements on batteries simultaneously. The lab I worked in over Summer 2022 wanted to test the limits of battery cycling rates, but the data collection system had no way of gauging temperatures.​

I found thermocouple units online, and to organize them and the Arduino for temperature data collection, I designed in Solidworks a model, accounting for PCB tolerances, that could integrate the parts.​

The data collected from the Arduino was separate from the rest of the battery data, so I had to use Python to generate the desired data, merge the instances together, accounting for time mismatch, and get useful results by data visualization.​

<img src="images/temptest.png" alt="Temperature tester" width="500"/>