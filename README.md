# Douk Audio U3

A dedicated page for reverse-engineering the Douk Audio U3 headphone amp.

## PCB

<img src="img/pcb/XZ-U3-P_5.webp" width="640"/>

_original top view_

<img src="img/pcb/desoldered-top.jpg" width="640"/>

_desoldered top view_

## Capacitors

### Original Capacitor Values

 ID | Type
 -- | ----
C3 | 47uF 25V electrolytic (Jwco PET)
C13 | 470uF 35V electrolytic (Jwco VENT)
C12 | 47uF 25V electrolytic (Jwco PET)
C15 | 470uF 25V electrolytic (Jwco VENT)
C18 | 470uF 25V electrolytic (Jwco VENT)
C10 | 470uF 35V electrolytic (Jwco VENT)
C17 | 470uF 35V electrolytic (Jwco VENT)
C4 | 470uF 35V electrolytic (Jwco VENT)
C8 | 470uF 35V electrolytic (Jwco VENT)

## Modifications

### OP-AMP

Using LM4562 OP-AMP as a replacement of the original TI-NE5532 ([datasheet](https://www.ti.com/lit/ds/symlink/lm4562.pdf?ts=1767798031264&ref_url=https%253A%252F%252Fwww.ti.com%252Fproduct%252FLM4562)).

### Capacitors

 ID | Type
 -- | ----
C3 | 47uF 63V LOW ESR electrolytic (Panasonic)
C13 | 470uF 35V LOW ESR, low impedance electrolytic (Panasonic)
C12 | 47uF 63V LOW ESR electrolytic (Panasonic)
C15 | 1000uF 25V LOW ESR, low impedance electrolytic (SAMXON)
C18 | 470uF 35V LOW ESR, low impedance electrolytic (Panasonic)
C10 | 470uF 35V LOW ESR, low impedance electrolytic (Panasonic)
C17 | 470uF 35V LOW ESR, low impedance electrolytic (Panasonic)
C4 | 330uF 35V low impedance polymer (Panasonic SEK)
C8 | 330uF 35V low impedance polymer (Panasonic SEK)

<img src="img/upgrades/recapped.jpg" width="640"/>

### Top

The higher capacitors don't fit into the old case, so I decided to cut of the top of the case and repliace it with plexiglass.
You can 3D print the top case extension and use it as a teplate to drill threaded holes to fasten the plexiglass sheet.

<img src="img/upgrades/cutoff_and_holes.jpg" width="640"/>

<img src="img/upgrades/top_extension_1.jpg" width="640"/>

<img src="img/upgrades/top_extension_2.jpg" width="640"/>

## References

### Manual

[Douk U3 Manual](https://github.com/gitaroktato/douk-u3/blob/main/manual/XZ-U3-English%20Manual.pdf)
