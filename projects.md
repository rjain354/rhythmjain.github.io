## My Projects
### Sur Tarang
#### An interactive bio-feedback music system
<p>
<img align="centre" width="500" alt="Screen Shot 2022-01-28 at 19 00 47" src="https://user-images.githubusercontent.com/78115400/151637279-5af2591c-41aa-4b99-bb5c-c85eb44a932c.png">
<img align="centre" width="500" alt="Screen Shot 2022-01-28 at 19 05 52" src="https://user-images.githubusercontent.com/78115400/151637624-ee30e406-d263-4a2b-a15d-da0acaa2de04.png">
</p>

Sur Tarang is an interactive and generative music system enabling musicians to control several parameters of the accompanying instruments without the need to touch or manipulate physical interfaces. Sur Tarang translated body and mind signals (bio signals via EEG) as well as automatic gesture recognition into
the sounds of the accompanying instruments. The sound design was done in Ableton Live and the generative component used dynamic time warping to recognize gestures and mirror the ”Jugalbandi” style of performance prominent in Hindustani classical music. For more details check out the demo(https://www.youtube.com/watch?v=88lU0gK0yoM) and the [github](https://github.com/rjain354/SurTarang) repository.

### Melograph
![Image](https://user-images.githubusercontent.com/78115400/151636271-d8e6794f-9df5-44bd-8b0d-94c9079dc83a.png) <img width="500" alt="Screen Shot 2022-01-28 at 18 43 55" src="https://user-images.githubusercontent.com/78115400/151636285-5e37ea06-171a-4dbd-8b8b-3990a0f6889a.png">

MeloGraph is a visualization tool to aid musicians with their improvisation techniques. By extracting note-level pitch information from a given audio signal of a monophonic performance, this tool shows the relative note and transition prominence in the user’s performance. We used Harmonic Percussive Source Separation (HPSS) for onset detection, Normalized cross corelation function (NCCF) algorithms for F0 detection and NetworkX and Cytoscape libraries for visualization. For more details check out the [github](https://github.com/nol-alb/melograph_submission) repository.

### Software Synthesizer
We designed a python-based synthesizer that can be run using the command line. The codebase for the project can be found at this [github](https://github.com/rjain354/music6202/tree/main/FinalProject) repository. Taking symbolic music notation (Kern files) as input, the system produces synthesized output files in .wav format, downloaded to the user’s local machine. Synthesis of the signals was done using additive and wave table techniques.
