# Letter Strings — Cultural Code Curtain & Resonant Synthesizer
Author: https://aiengineeringinsider.substack.com/subscribe

An interactive, physics-based canvas code curtain experience blending Verlet physics strings, modern glassmorphism design, and cultural audio textures (Indonesia, China, India, and México) using the Web Audio API.

<img width="1250" height="780" alt="image" src="https://github.com/user-attachments/assets/24345325-319d-43be-87f3-3d2628b041f6" />


## 🎨 Features

- **Dense Verlet Physics Curtain**: Over 30 uniformly tall, interactive string columns that drape to the bottom of the screen. Sweeping across the strings triggers rich, meditative sounds.
- **Iconic Playable Songs**: Swiping left-to-right plays cultural melodies:
  - **Indonesia**: *Gundul Pacul* (Central Javanese Gamelan Bonang/Saron)
  - **China**: *Mo Li Hua* (Jasmine Flower)
  - **India**: *Raghupati Raghav Raja Ram* (Bhajan in Raga Yaman)
  - **México**: *Cielito Lindo* (Mariachi / Guitarrón Chorus)
- **Authentic Synthesizer & Sound Design**:
  - **Indonesia**: FM ratio $\approx \sqrt{2}$ (bonang shimmer) with a detuned paired oscillator creating authentic gamelan beating (*ombak*).
  - **China**: Clean triangle waves with low FM and gentle 5.5 Hz vibrato (*yín*).
  - **India**: High FM ratio (7.0) simulating a sitar's *jawari* bridge buzz and a sawtooth tanpura drone.
  - **México**: Plucked square waves for the warm, hollow *guitarrón* feel.
- **Procedural Art Canvas**: Live-drawn background canvas patterns corresponding to each theme:
  - **Indonesia**: Batik Kawung & Parang motifs.
  - **China**: Calligraphy cloud lattice scroll patterns.
  - **India**: Concentric Rangoli/Mandala geometry with Paisley motifs.
  - **México**: Aztec stepped sun stone rings and Greca borders.
- **Premium Interface**: Warm parchment textures, responsive slider components, and a premium glassmorphic control deck.

---

## 🚀 How to Run

1. Clone or download this project folder.
2. Locate the file: `letter_strings_curtain.html`
3. Simply open it in any modern web browser (Double-click or drag into Chrome/Safari/Firefox).
4. Click **"Activate Audio"** at the top right, adjust the controls, and swipe your mouse or trackpad across the strings.

---

## 📝 Complete Prompt Blueprint

Below is the **full system prompt** containing the complete architectural requirements, visual designs, and sound physics properties to generate this entire project from scratch:

```text
Create a single-file interactive web application (HTML, CSS, JS) called "Letter Strings Curtain".

The core mechanics must combine:
1. An interactive, high-density HTML5 Canvas Verlet physics curtain.
2. An elegant glassmorphism web panel dashboard themed around "Warm Parchment" design (#f7f4eb background, subtle SVG paper grain noise texture, serif Cinzel titles, and sans-serif Inter typography).
3. A theme-switching state engine featuring 4 distinct cultures:
   - INDONESIA: Javanese script texts, Batik Kawung canvas patterns, Pelog tuning scale playing "Gundul Pacul", FM metalophone synthesis with gamelan beating (ombak) detune cents.
   - CHINA: Tang Dynasty poetry texts, calligraphy cloud lattices, pentatonic tuning scale playing "Mo Li Hua", Guzheng synthesis with left-hand vibrato (yín).
   - INDIA: Sanskrit Slokas, Mandala concentric patterns, Raga Yaman tuning scale playing "Raghupati Raghav Raja Ram", sitar sympathetic FM synthesis, sawtooth tanpura drone.
   - MÉXICO: Nahuatl texts, Aztec sun stone patterns, major mariachi tuning scale playing "Cielito Lindo", guitarrón square wave pluck.

SOUND SYNTHESIS ENGINE (Web Audio API):
- Master gain, convolution reverb node with algorithmic impulse response buffer (3s length, 2.5 decay), bandpass steam noise filter with Q=1.5 and cutoff control.
- Interactive string voices: 1 carrier oscillator + 1 modulator oscillator routed to carrier frequency input (FM synthesis). Dynamic FM depth reacts to string velocity.
- Detuned pair offset for Gamelan (6 cents detuned second oscillator).
- Vibrato LFO routed to carrier pitch for Chinese and Indian elements.
- Soft atmospheric drone track playing matching scale harmonics with culture-specific waveforms (sine, triangle, sawtooth).

PHYSICS CURTAIN & INTERACTION:
- Create 30+ string strands spanning the canvas width. Start coordinates high up (Y=15px) and normalize all string lengths to drape to near the canvas bottom.
- Spacing between columns must be dense (12px), characters rendered in small font size (9px-10px) to look like a realistic fabric curtain.
- Verlet physics update loop: gravity, friction, wind, mouse attraction/repulsion. Plucking/sweeping the curtain activates voice nodes with envelope attack and release.
- Ensure scales are mapped as sequential melody pitches of the popular traditional song so that sweeping left-to-right plays the melody note-by-note.

UI CONTROLS:
- Audio controls: Master Volume, Cutoff frequency, FM Modulation Depth, Reverb Dry/Wet.
- Physics controls: Gravity, Drag, Wind, and custom text inputs.
- Tabs: Four custom responsive pill buttons at the header to smoothly switch themes.
```
# letter-string-curtain
