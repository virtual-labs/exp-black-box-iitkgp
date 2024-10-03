# Theory


### Ohm's Law

1. The law states that the current through a conductor between two points is directly proportional to the voltage across the two points. Such a conductor is characterized by its ‘Resistance’ – R measured in Ohms.
2. V=I×R
- V is the Voltage in Volts across the conductor.
- I is the current in Amperes through the conductor.
- Voltage(V) is directly proportional to current i.e V=I×R.
- Resistance(R) in inversely proportional to current(I) i.e $$I=\frac{V}{R}$$

- Forward and reverse biased characteristics of a Silicon diode

**In forward biasing**, the positive terminal of battery is connected to the P side and the negative terminal of battery is connected to the N side of the diode. Diode will conduct in forward biasing because the forward biasing will decrease the depletion region width and overcome the barrier potential. In order to conduct, the forward biasing voltage should be greater than the barrier potential. During forward biasing the diode acts like a closed switch with a potential drop of nearly 0.6 V across it for a silicon diode. The forward and reverse bias characteristics of a silicon diode. From the graph, you may notice that the diode starts conducting when the forward bias voltage exceeds around 0.6 volts (for Si diode). This voltage is called cut-in voltage.


**In reverse biasing**, the positive terminal of battery is connected to the N side and the negative terminal of battery is connected to the P side of a diode. In reverse biasing, the diode does not conduct electricity, since reverse biasing leads to an increase in the depletion region width; hence current carrier charges find it more difficult to overcome the barrier potential. The diode will act like an open switch and there is no current flow.

### Diode Equation

In the forward-biased and reversed-biased regions, the current (I<sub>f</sub>), and the voltage (V<sub>f</sub>), of a semiconductor diode are related by the diode equation:

$$I_f= I_s(exp^\frac{v_f}{nV_T}-1)$$

where,
I<sub>s</sub> is reverse saturation current or leakage current,
I<sub>f</sub> is current through the diode(forward current),
V<sub>f</sub> is potential difference across the diode terminals(forward voltage)
V<sub>T</sub> is thermal voltage, given by

$$V_T=\frac{kT}{q}$$

and 

k is Boltzmann’s constant = 1.38x10<sup>−23</sup> J /°Kelvin.
q is the electronic charge = 1.6x10<sup>−19</sup> joules/volt(Coulombs).
T is the absolute temperature in °Kelvin(°K = 273 + temperature in °C).
At room temperature (25 °C), the thermal voltage is about 25.7 mV.
n is an empirical constant between 0.5 and 2.





<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>