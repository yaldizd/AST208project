---
layout: default
title: Inferrence Using Gravitational Waves
---

<br>

<br>

<br>

## First LIGO Results
On September 24, 2015, a century after Einstein's predictions of general relativity, at the Laser Inferometer Gravitational-Wave Observatory, gravitational waves were detected for the first time. The waves were produced by a binary black hole merger, the first one ever observed.

<img src="/assets/css/ligo_merger.png" alt="Gravitational Wave Event Observed by LIGO" width="500"/>

The most plausible explanation for the evolution graph above is two masses, $$m_1$$ and $$m_2$$, spiraling in toward each other and producing gravitational waves.
Such an interaction can be modeled by the chirp mass equation,

$$
\mathcal{M} = \frac{(m_1m_2)^{3/5}}{(m_1 + m_2)^{1/5}} = \frac{c^3}{G}\left[ \frac{5}{96}\pi^{-8/3}f^{-11/3}\dot{f} \right]^{3/5}
$$

Where $$f$$ is the frequency observed and $$\dot{f}$$ is its time derivative. The chirp mass $$\mathcal{M}$$ describes the evolution of a compact binary system. From the figure above, a chirp mass of $$\mathcal{M} = 30 M_\odot$$ was obtained, which implies $$M = m_1 + m_2 > 70 M_\odot$$.

## The Detectors

The two LIGO sites in Hanford, WA and Livingston, LA operate incredibly precise Michealson inferometers. They are able to measure the strain effects of gravitational waves as a difference in length for two orthogonal arms. The arms are seperated by

$$
L_x = L_y = L = 4 \text{ km}
$$

And a passing gravitational wave alters the arm lengths such that the measured difference is 

$$
\Delta L(t) = \delta L_x − \delta L_y = h(t)L
$$

Where $$h$$ is the gravitational-wave strain amplitude. This differential length variation effects the phase difference between two light fields which then passes through a beam splitter and gets detected by a photodetector.

<div style="text-align: center;">
  <img src="/assets/css/ligo_setup.png" alt="The LIGO Detector Setup" width="500" />
  <figcaption style="margin-top: 5px; font-style: italic;">Fig 1: The LIGO Detector Setup</figcaption>
</div>

<br>
