# Targeted Individual Simulator (v0.1.2)

## ⚠️ Disclaimer

This project is an **interactive simulator** inspired by real testimonies from individuals who identify as *Targeted Individuals*.  
It is designed **not** to assert the objective truth of these claims, but to **model the experience** as reported — for research, education, and system design testing.

The simulator explores how a **hypothetical bi-directional BCI** could influence perception, behavior, and cognition in real-time, using known computing paradigms such as forward/backward chaining and EEG signal processing.

If you're a computer scientist, or neuroscientist, this project may offer a testbed to:
- model perception-based interactions,
- simulate psychological stress scenarios,
- explore the ethical boundaries of emerging BCI technologies.

## 🚀 Goal

The goal is to simulate an environment where a person *feels* persistently surveilled or manipulated,  
similar to the experiences reported by many self-identified Targeted Individuals — but in a **safe, local, and removable way**.

This does **not** claim that such technology currently exists in this form or is deployed by governments or other actors.  
Rather, it is a conceptual tool to promote dialogue, system awareness, and technical exploration of these ideas.

## Design of a sense and respond system

1. Intelligence collection can be acheived using a cam, mic, EEG, possibly with electrodes for long-term wearing
EEG data interpretation requires a solution similar to Thought2Text https://github.com/abhijitmishra/Thought2Text to analyze what the user sees and thinks. The experiment will be realistic when the EEG device will support bluetooth to avoid wires.

2. Intelligence analysis with automated responses can be achieved using forward chaining, or backward chaining. Or, for a quick PoC an LLM can be used. For the LLM to work, it has to be trained using custom rules based on situation-response. The model will be trained based on real situations and responses reported by self-identified targeted individuals.


3. Automated responding can be limited to playing a voice. This can be produced using text to speech that reads the reaction produced by LLM.

4. The delivery of a response can be played via earbuds, or using a technology such as Audio Splotlight https://www.holosonics.com/ The latter solution allows experiments where only you can hear the responses.


Remark: the only significant challenge to overcome is the decoding of EEG into text. Publicly available solutions are PoCs rather than production use.

