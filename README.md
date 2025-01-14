# practice school
## Finding the current inside a material

 
- Given the voltage Vr, Current Ir, dimensions of the material l x w x h and n = $free charge/per unit volume$.
- To find the current Ir = $Change in charge(dQ) / Change in time (dt)$
- Let us take a thin sheet and find the sheet charge (Qs) and Q be the total charge of the material.

  <img src="docs/find current.jpeg" alt="Diagram" width="600" height="400">
  
 - The current can be written as the total charge in the incremental volume in time &#9651;t:                                                                
   - $I_R$ = $&#9651;q \over &#9651;t$ = $Q_s&#9651;x \over &#9651;t$ = $Q_sV_d$ ,  [ $Q_s$ = nwh is the sheet charge or the charge per unit length,  $V_d$ is the average velocity of the electrons]
   - $V_d$ = $&#9651;x \over &#9651;t$ = &#956;E , [ E = $&#9651;v \over &#9651;x$ , and &#956; is the mobility of the material.]
   - $I_R$ = &#956; $Q_s$ $&#9651;v \over &#9651;x$
  - The incremental resistance can be expressed as:
    - &#9651;R = $&#9651;v \over I_R$ = $\rho$ $&#9651;x \over Wh$
## Finding the capacitance between two parallel plate

<p align="center">
   <img src="docs/find capacitance.jpeg" alt="Description" width="600" height="400"/>
</p>

Lets consider 2 parallel plates connected with a battery of "V" volts.After sometimes of battery connection let the plate connected with the cathode of battery has total charge +Q on its surface and 
the plate connected with the anode of battery has total charge -Q on its surface .\
Gradually as the charge increases on the plate potential also increases.Let the potential on the plates are V1 and V2 respectively .\
Relation between total charge on either plate and potential difference between two parallel plates (V= V1-V2) can be mathematically expressed as:

$$ Q \propto V $$
 
Here the proportionality constant is the capacitance of the parallel plates : 

$$ Q = CV
 
We will apply Gauss's theorem to calculate the capacitance of the parallel plates .\
Gauss Theorem can mathemticallly expressed as

$$\Phi_E = \oint\limits_S\overrightarrow{E} . \overrightarrow{dS} = \frac{Q _{in}}{\epsilon_o}
Q can be expressed as :

$$ Q=\overrightarrow{E}.A.\epsilon_o

Assuming a large area and small separation "d" between plates , Electric feild between plates can be expressed mathematically 

$$ \overrightarrow{E} = \frac{V}{d}

From the equation 1 Capacitance C can be expressed as  : 

$$C= \frac{Q}{V} $$

Therefore putting the values of Q and V from equation 3 and 4 the capacitance of the parallel plates can be expressed as:

 $$ C=\frac{\epsilon_0 \cdot AE}{Ed} = \frac{\epsilon_0 \cdot A}{d}


## Capacitors

| Types  | Cap. Range | Max. Voltage Range | Accuracy | Temp. Stability | Leakage | Comments |
| - | - | - | - | - | - | - |
| Ceramic | 1pf - 1uf | 50-30kv | Poor | Poor | Moderate | Small,Cheap,Most Popular |
| Mica | 1pf - 1uf | 50v-1kv | Poor | Poor | Small | Small,Cheap,Most Popular |
| Mylar  | 1pf - 1uf | 100v-60kv | Poor | Poor | Small | Small,Cheap,Most Popular |
| Teflon  | 1pf - 1uf | 50-30kv | Poor | Poor | Moderate | Small,Cheap,Most Popular |
| Glass  | 1pf - 1uf | 50-500v | Poor | Poor | Small | Small,Cheap,Most Popular |
| Porcelin  | 1pf - 1uf | 2-100kv | Poor | Poor | Moderate | Small,Cheap,Most Popular |
| Tantalum  | 1pf - 1uf | 101-500v | Poor | Poor | Moderate | Small,Cheap,Most Popular |
| Electrolytic  | 1pf - 1uf | 4-630v | Poor | Poor | High | Small,Cheap,Most Popular |
| Vaccum  | 1pf - 1uf | 4.5v-60kv | Poor | Poor | Small | Small,Cheap,Most Popular |


- **Derivation and Solved Examples**: [PS-day2-practice-problem](https://www.dropbox.com/scl/fi/6uyll0l15llozb4sgpkxv/ps-day2.pdf?rlkey=k1su1o4w2au8t0aoc74dl2kbn&st=l0ibl6e0&dl=0)


