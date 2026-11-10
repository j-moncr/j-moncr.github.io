---
permalink: /research/
title: "Research"
excerpt: "Black holes in AGN discs: resonances, multiple EMRIs, mergers near supermassive black holes, and statistical tests of the AGN channel."
author_profile: true
---

<!-- Small page-only styles for figure layout (safe to move into _sass later). -->
<style>
  .research-fig { margin: 1.2em 0 1.6em; text-align: center; }
  .research-fig img { max-width: 100%; height: auto; border-radius: 4px; }
  .research-fig figcaption { flex-basis: 100%; font-size: 0.8em; color: #555; margin: 0.5em auto 0; max-width: 46em; text-align: left; }
</style>

Gravitational wave detectors have now recorded hundreds of binary black hole mergers, and some of them are hard to explain with standard channels such as isolated binary evolution or dynamical capture in a dense cluster. Examples include mergers with very unequal masses, black holes in the pair-instability gap, or detections with signs of residual eccentricity. The gaseous discs of active galactic nuclei (AGN) are a leading alternative to explaining such events. In this proposed scenario black holes captured into the disc migrate like planets, encounter one another, and merge rapidly.

My PhD research has focused on the gravitational dynamics of black hole encounters in AGN discs, including the formation of mean motion resonance chains, extreme mass ratio inspirals, and binary black hole mergers.

## Black hole encounters in AGN discs

<figure class="research-fig">
  <img src="/images/research/capture_probability.png" alt="Capture probability of black-hole encounters versus the resonance parameter B, with a lognormal fit" style="max-width: 440px;">
  <figcaption>The outcome of an encounter is set by 𝓑, the ratio of the resonant libration time to the time to cross the resonance. Capture and merger peak at 𝓑 ≈ 1–3; smaller values block the encounter in resonance, larger ones lead to orbit crossing.</figcaption>
</figure>

I used the regularised few-body code TSUNAMI (post-Newtonian terms to 3.5PN) coupled with self-consistent AGN disc models and migration torques, and simulated black-hole encounters across a wide range of disc and mass parameters. We found that encounters often do *not* end in mergers: convergent migration traps the pair in resonance. Borrowing on results in resonance capture theory from planetary dynamics, I derived an analytic criterion for the capture probability as a function of AGN disc parameters and black hole masses that matched the simulations very well. Applying this model to the highly unequal mass event GW190814, it shows that such mergers are favoured only in a narrow range of the AGN parameter space.

<figure class="research-fig">
  <img src="/images/research/coorbital_example.png" alt="Simulation of two black holes in a co-orbital resonance near a migration trap">
  <figcaption>A simulated pair of black holes (2.6 and 23 M<sub>☉</sub>) caught in a co-orbital resonance near a migration trap: semi-major axes and separation over time (left), and the orbit in the inertial and co-rotating frames (right).</figcaption>
</figure>

*Moncrieff, Grishin, Trani, Panther & Pietrosanti 2026, MNRAS 545, staf2217* · [paper](https://doi.org/10.1093/mnras/staf2217) · [arXiv](https://arxiv.org/abs/2511.09129)

## Lasting mEMRIs: resonant pairs in the LISA band

<figure class="research-fig">
  <img src="/images/research/memri_schematic.jpg" alt="Three stages: convergent migration, resonant migration, and gravitational-wave-dominated migration into the SMBH">
</figure>

Black holes that stay locked in resonance can migrate together all the way to the central supermassive black hole. For SMBH masses below about 10<sup>6</sup> M<sub>☉</sub>, the resonance survives once gravitational wave emission dominates gaseous migration torques for low enough mass ratios, so an AGN can host **multiple Extreme Mass Ratio Inspirals (mEMRIs)**, observable simultaneously by LISA. We show that such mEMRIs have an interesting gravitational wave phenomenology that encodes information about the mean motion resonance, which if not accounted for could bias EMRI parameter estimation.

<figure class="research-fig">
  <img src="/images/research/memri_spectrogram.png" alt="Spectrograms of two isolated EMRIs compared with a resonant mEMRI pair">
  <figcaption>Simulated spectrograms of two isolated EMRIs (left, centre) and the same black holes in a mean motion resonance mEMRI (right). The resonant pair adds synodic sidebands and shifted harmonics, so analysing it as an isolated EMRI would give incorrect estimates of the masses.</figcaption>
</figure>

*Moncrieff, Grishin, Panther & Trani 2026, submitted to MNRAS* · [arXiv:2610.29376](https://arxiv.org/abs/2610.29376)

## Relativistic resonance breaking: eccentric mergers near the supermassive black hole

<figure class="research-fig">
  <img src="/images/research/mmr_breaking_schematic.jpg" alt="Schematic: a 4:3 resonance migrates inward, breaks near 30 gravitational radii, and the black holes undergo Hill capture and an eccentric inspiral">
  <figcaption>(a) A resonant pair migrates inward; (b) relativistic precession breaks the resonance and the orbits cross; (c) repeated encounters inside the Hill sphere, perturbed by the SMBH's tide, end in gravitational-wave capture; (d) a highly eccentric inspiral.</figcaption>
</figure>

Around more massive black holes, compact mean motion resonances become unstable due to mean motion resonance overlap about 10–30 gravitational radii from the SMBH. After mean motion resonance breaking, black holes then undergo repeated close encounters that almost always end in a near head-on collision or a highly eccentric merger, deep inside the SMBH's potential. There, line-of-sight acceleration, Doppler shifts, and strong lensing should leave measurable imprints on the gravitational waves. The detection of such environmental effects would provide smoking gun signatures of the AGN channel. This paper is in preperation, arxiv link coming soon.

<figure class="research-fig">
  <img src="/images/research/mmr_breaking_strain.png" alt="Characteristic strain of the captured inspiral and tidal bursts against LISA, DECIGO, Einstein Telescope and A# sensitivity curves" style="max-width: 460px;">
  <figcaption>Gravitational-wave spectrum of one capture: repeated tidal bursts before capture, then an eccentric inspiral and merger, compared with LISA, DECIGO, Einstein Telescope and LIGO A# sensitivities.</figcaption>
</figure>

*Moncrieff, Grishin, Panther & Trani, in preparation*

## What fraction of BBH mergers come from AGN? A statistical test

<figure class="research-fig">
  <img src="/images/research/xcorr_posterior.png" alt="Mixture model for the AGN and non-AGN fractions, and the recovered posterior for a simulated population" style="max-width: 420px;">
  <figcaption>A mixture model of the angular cross-correlation between gravitational-wave skymaps and AGN and galaxy catalogues recovers the AGN fraction f<sub>A</sub> of a simulated population.</figcaption>
</figure>

Individual mergers are too poorly localised to identify their host galaxies. AGN cluster more strongly than ordinary galaxies, so cross-correlating gravitational wave skymaps with AGN and galaxy catalogues can measure what fraction of mergers happen in AGN. I developed a new statistical technique to determine the fraction of BBH mergers coming from AGN using angular cross correlation. We found that after roughly 5,000–10,000 detected mergers at A# sensitivity, this can accurately determine the fraction of BBH mergers coming from AGN.

*Moncrieff & Panther 2025, MNRAS 543, 1833* · [paper](https://doi.org/10.1093/mnras/staf1582)

## What's next

I am building these results into a general theory of resonances with relativistic precession, gravitational-wave dissipation and turbulent forcing, which applies to planets as well as black holes. I am also developing waveform-level models of environmental effects, and population predictions that can be tested against gravitational-wave catalogues.
