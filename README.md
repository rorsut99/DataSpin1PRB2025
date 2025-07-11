# DataSpin1PRB2025
Data for the manuscript "SU(N) spin-phonon simulations of Floquet dynamics in spin S>1/2 Mott insulators"
by Ruairidh Sutcliffe, Kathleen Hart, Gil Refael and Arun Paramekanti

## File details:
All files are saved in the JLD2 format. Refer to original work for details of simulations and further model parameters.

### Files for Figure 2
fig2.jld2:<br />
  - Data for the uniform $S_z$ magnetization with a two-phonon drive
  - tpoints: time in units of $\hbar/J$<br />
  - Sz_AFM_HighDrive: Uniform magnetization $M_z^0$ in the AFM phase with a drive of $A = 0.2$<br />
  - Sz_AFM_LowDrive: Uniform magnetization $M_z^0$ in the AFM phase with a drive of $A = 0.1$<br />
  - Sz_QPM_HighDrive: Uniform magnetization $M_z^0$ in the QPM phase with a drive of $A = 0.2$<br />
  - Sz_QPM_LowDrive: Uniform magnetization $M_z^0$ in the QPM phase with a drive of $A = 0.1$<br />

### Files for Figure 3
fig3.jld2:<br />
  - Data for the staggered $S_x$ and $S_y$ magnetizations with a one-phonon drive
  - t_AFM: time in units of $\hbar/J$<br />
  - Mx_AFM: Staggered magnetization $M_x^\pi$ in the AFM phase with a one-phonon drive
  - My_AFM: Staggered magnetization $M_y^\pi$ in the AFM phase with a one-phonon drive
  - t_QPM: time in units of $\hbar/J$<br />
  - Mx_QPM: Staggered magnetization $M_x^\pi$ in the QPM phase with a one-phonon drive
  - My_QPM: Staggered magnetization $M_y^\pi$ in the QPM phase with a one-phonon drive

### Files for Figure 4
fig4.jld2:<br />
  - Data for the dynamical spin structure factor $\mathcal{S}(q,\omega)$ with a one-phonon drive
  - qs: wavevectors $q$ in units of $2\pi$
  - ws: energies $\omega$
  - DSSF_driven: Driven dynamical spin structure factor $\mathcal{S}(q,\omega)$ with a one phonon drive
  - blue_curve: Driven dynamical spin structure factor $\mathcal{S}(q,\omega)$ at $q = (\pi,\pi,\pi)$
  - orange_curve: Equilibrium dynamical spin structure factor $\mathcal{S}(q,\omega)$ at $q = (\pi,\pi,\pi)$
  - blue_curve_inset: Driven dynamical spin structure factor $\mathcal{S}(q,\omega)$ at $q = 1.3(\pi,\pi,\pi)$
  - orange_curve_inset: Equilibrium dynamical spin structure factor $\mathcal{S}(q,\omega)$ at $q = 1.3(\pi,\pi,\pi)$

### Files for Figure 5
Fig5.jld2:<br />
  - Data for the heat capcity of a S=1 antiferromagnet of the cubic lattice, coupled to two phonons:<br />
  - T: temperature data<br />
  - heats: heat capacity, $C_v$<br />

### Files for Figure 6
fig6ab.jld2:<br />
  - Data for the energy and spin length conservation of a single spin in a magnetic field with spin-1.
  - t1: times for timestep $dt = 0.01$
  - energyDiff1: change in energy of the system as a function of time for timestep $dt = 0.01$
  - spinDiff: change in spin length of the system as a function of time for timestep $dt = 0.001$
  - t2: times for timestep $dt = 0.005$
  - energyDiff2: change in energy of the system as a function of time for timestep $dt = 0.005$
  - t3: times for timestep $dt = 0.001$
  - energyDiff3: change in energy of the system as a function of time for timestep $dt = 0.001$<br />

fig5cd.jld2:<br />
  - Data for the energy and spin length conservation of a single spin in a magnetic field with spin-3/2.
  - data is saved with the same format as fig6ab.jld2, but for the spin-3/2 example.

### Files for Figure 8
fig8.jld2:
  - Data for the total staggered magnetization with a two-phonon drive.
  - t_AFM: time in units of $\hbar/J$<br />
  - M_AFM: Staggered magnetization $M^\pi$ in the AFM phase with a two-phonon drive
  - t_QPM: time in units of $\hbar/J$<br />
  - M_QPM: Staggered magnetization $M^\pi$ in the QPM phase with a two-phonon drive

### Files for Figure 10
fig10.jld2:
  - Data for the dynamical spin structure factor $\mathcal{S}(q,\omega)$ in the spin only, undriven and driven systems.
  - qs: wavevectors $q$ in units of $2\pi$
  - ws: energies $\omega$
  - DSSF_spinOnly: Driven dynamical spin structure factor $\mathcal{S}(q,\omega)$ without spin-phonon coupling
  - DSSF_undriven: Driven dynamical spin structure factor $\mathcal{S}(q,\omega)$ with spin-phonon coupling and no phonon drive
  - DSSF_driven: Driven dynamical spin structure factor $\mathcal{S}(q,\omega)$ with spin-phonon coupling and a one phonon drive

### Files for Figure 12
fig12.jld2:
  - Data for the dynamical spin structure factor $\mathcal{S}(q,\omega)$ with a one-phonon drive at energies near the phonon frequency.
  - qs: wavevectors $q$ in units of $2\pi$
  - ws: energies $\omega$
  - DSSF_sidebands: Driven dynamical spin structure factor $\mathcal{S}(q,\omega)$ with a one phonon drive at higher energies (near $\omega \sim 40$)
