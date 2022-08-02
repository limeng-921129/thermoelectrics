# Heat Transport
# 
## Thermal Conductivity
The formulation of total thermal conductivity $\kappa\_{\rm {tot}}$ is:
$$\kappa\_{\rm {tot}}=\kappa\_{\rm e}+\kappa\_{\rm l}+\kappa\_{\rm {bip}}$$
where $\kappa\_{\rm e}$ is electronic tensor component (or electronic thermal conductivity), $\kappa\_{\rm l}$ is lattice tensor component (or lattice thermal conductivity), and $\kappa\_{\rm {bip}}$ is bipolar thermal conductivity.
# 
### Electronic Thermal Conductivity

#  
### Lattice Thermal Conductivity
The formulation of lattice thermal conductivity $\kappa\_{\rm l}$ is:
$$\kappa\_{\rm l}=\frac {1}{3} \cdot C_{\rm V} \cdot v \cdot l$$
where $v$ is phonon group velocity, and $l$ is phonon mean free path ( MFP ).
# 
#### Specific Heat Capacity
The amount of heat energy required to raise the temperature of a material is known as the heat capacity — $C_{\rm V}$ at constant volume or $C_{\rm P}$ at constant pressure. When this term is expressed as the amount of heat energy per unit mass of material needed to raise its temperature by 1 K, it is referred to as specific heat capacity.
# 
Normal and Umklapp scattering mechanisms are both responsible for heat propagation in solids. Through Normal scattering, momentum is conserved; through Umklapp scattering, momentum is not conserved. At low temperatures, Normal scattering is dominant due to a lower phonon population and Umklapp scattering has just a minor contribution. When the temperature is high enough, Umklapp scattering can be considerable due to increased phonon–phonon scattering.
# 
**Einstein Model** is a low-temperature model to predict the heat capacity of solids. This model treats all atoms as independent oscillators with their own unique **Einstein Temperatures** ${\it \Theta\_{\rm E}}$, and allows all atoms to freely vibrate in all directions at a single characteristic frequency ( $\omega\$ ). Specifically, we have:
$$C_{\rm V}=3R \cdot \frac {u^2e^u}{(e^u-1)^2}$$
$$u={\it \Theta\_{\rm E}}/T=h\omega\/k_{\rm B}T$$
In above equations, $R$ is gas constant, $h$ is Planck's constant, $k_{\rm B}$ is Boltzmann's constant, and $T$ is absolute temperature in Kelvin.
# 
**Debye Model** is an extend model to Einstein Model to account for the coupling of atomic oscillators seen in real systems. Analogous to ${\it \Theta\_{\rm E}}$, there is a **Debye Temperature** ${\it \Theta\_{\rm D}}$. In Debye Model, $\omega\$ is assumed to be a range of vibrational frequencies, and $\omega\_{\rm max}$ is
used in place of $\omega\$. The Debye model predicts a $T^3$ temperature dependence of heat capacity, namely:
$$C_{\rm V}=12\chi\^3\int_0^x\frac {u^3}{(e^u-1){\rm d}u-\frac {3\chi\}{e^\chi\-1}}$$
$$\chi\={\it \Theta\_{\rm D}}/T=h\omega\_{\rm max}/k_{\rm B}T$$
# 
In a metal, the electronic contribution to the heat capacity can be estimated by plotting very low temperature heat capacity data near 0 K. At these temperatures, the Debye model reduces to:
$$C_{\rm V}=\frac {{\rm C}}{{\it \Theta\_{\rm D}}^3}T^3+\gamma\ T\$$
where the first term refers to phonon contribution to heat capacity, and the second term refers to electron contribution to heat capacity. Then a linear fit of $C_{\rm C}/T$ vs. $T^2$ yields the **Sommerfeld coefficient** ( $\gamma\$ ) as the y-axis intercept, whcih can be used to predict the density-of-states at Fermi level ( ${\rm DOS}(E_{\rm F})$ ) via:
$$\gamma\=\frac {\pi\^2k_{\rm B}^2}{3} \cdot {\rm DOS}(E_{\rm F})$$
Moreover, a plot of $C_{\rm V}/T^3$ versus $T$ is useful for determining the presence of Einstein model, given that:
$$C_{\rm tot}=C_{\rm electronic}+C_{\rm Debye}+C_{\rm Einstein1}+C_{\rm Einstein2}+ \cdot \cdot \cdot$$
