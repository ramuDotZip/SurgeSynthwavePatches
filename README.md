# SurgeSynthwavePatches
A collection of synth patches in Surge XT that I use for writing synthwave music. Below are descriptions of each patch and some tips on how to use them.

## Descriptions and Tips

**The Wave**  
A classic synthwave bass sound. The "Ramp" macro controls an LFO that ramps up in volume over each quarter note, giving the effect of sidechain compression from the kick drum. If the sound is too wide, decrease the Width in the scene output, and if it's not wide enough, increase the Osc 2 Unison Voices to 2 or 3.

**Anything Pluck Lead**  
A simple but versatile synth pluck sound.

**Considerable Cutting Implement**  
I was running out of ways to say "supersaw", and well, this one is rather considerable. Out of all the supersaws I've made, this is certainly one of them. It's quite similar to GarageBand's "Anthemic Lead" in that it's polyphonic and has a sidechain-like ramp, making it good for playing chords. For better usage as a lead instrument, you can set it to monophonic instead. Besides the macros, you can also change the timbre with the Waveshaper Drive or by changing the mix of oscillators 1, 2, and 3. The shape of the ramp can be changed with S-LFO 1 Deform, with lower values increasing more slowly and steadily, and higher values having a sharper transition. And lastly, I wasn't able to route this anywhere nice, but if you want to change the inflection point of the ramp curve (sort of like the duty cycle) then you can open the formula editor and change the value of the "inflection" variable.

**Contrabrass**  
A brass stab that can be used as a bass or a lead. Some other useful parameters not included in the macros:
- Amp EG Release (Lower values ~0.2s work better for a bass, and higher values ~1s work better for a lead)
- Osc 1/2 Level
- Filter 1 Resonance

**Hot Saw Lead**  
A strong saw-square lead with a bit of supersaw behind it, and a bit of vibrato and portamento as well.

**Mellow Saw**  
A calm lead instrument with a timbre somewhere between a saw and a talk box.

**Super Simple Supersaw**  
I couldn't decide on a simple saw or a supersaw so I made one that was both. The "Simple / Super" macro changes the mix between them.

**Theremin**  
It is, in fact, a theremin. Includes vibrato, portamento, and reverb, as well as some extra macros to change its timbre. You can get a nice clean glissando by temporarily decreasing the vibrato and increasing the portamento.

**Full Orchestra**  
A pad with a rich texture resembling an orchestra. This one's typically better suited to be in the background as a sort of secret sauce, barely noticeable, but giving some nice flavor to the quiet parts of a song.

**Through the Clouds**  
Another classic synthwave sound, this one is best used when playing a chord on every 16th note. Like The Wave, it has a volume ramp to simulate sidechain compression. The Deform parameter on S-LFO 1 can be used to change the shape of the ramp, with negative values increasing quickly and tapering off, and positive values increasing more slowly and linearly. It's easy for this sound to interfere with the bass, so it has a high pass filter that can be controlled by the "Low Cut" macro. One technique I like to use with this one is to slowly increase the Cutoff with an automation to build up to a minor climax, and then quickly bring the Unison up to 75-100% as the Cutoff drops back down, making the bright, tense sound almost seem to dissolve away.

**Warm Lights**  
I don't know what this sound is called, but I've heard it all over. It's a kind of brassy ping that's both warm and bright at the same time. The "Filter Balance" macro can be used to change how much of the sound bypasses the first filter, making the tone warmer or brighter.
