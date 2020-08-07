# Agile Octopus Gauge
 Displays a gauge indicating the current Agile Octopus unit rate in your area. Updates automatically using AJAX.
 
 The intention is that this page can be left running on a spare phone or tablet to aid with planning energy usage.
 
 ![Example display screenshot](https://ianhampton.net/work/currentOctopusRate.png)
 
 I've hosted a copy with customisable region here - https://hampton.org.uk/octopus/
 
 ---
 
## Installation
 - Update the code to use your Octopus product code and tariff code. [The values can be found in the examples given here](https://octopus.energy/dashboard/developer/).
 - Run somewhere locally or remotely. [Guided access mode works well on iOS](https://support.apple.com/en-gb/HT202612).

---

## Limitations
 - Negative (plunge) pricing drops off the bottom of the gauge. I quite like this :)
 - I *think* I've handled the conversion from UTC to GMT correctly, but I haven't tested it thoroughly.
 - The Octopus API docs suggest that an API key should be passed to retrieve unit rates, but the endpoint seems to work just fine without (which is good, because client-side).

---
## Acknowledgements
 The gauge meter was built by [Daniel Lazarovici](https://codepen.io/TheLaz/pen/Fgdwr)
