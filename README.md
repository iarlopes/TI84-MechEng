# TI84-MechEng
A Suite of Mechanical Engineering Programs for TI83/84 Calculators

When I was a Mechanical Engineering student at the Faculty of Engineering of the University of Porto (2008-2013),
I have realised that I could ally my interest in numerical methods to some programming skills in order to speed-up the
solution of practical exercises in some curricular units.  
Consequently, I have implemented some useful programs in my old TI84-Plus calculator.
I have rediscovered some of them recently and decided to make them available to the community.  
These programs are in `.8xp` format. They can be edited in the calculator itself, in the [Texas Instruments connectivity software](https://education.ti.com/en-GB/software/details/en/CA9C74CAD02440A69FDC7189D7E1B6C2/swticonnectcesoftware),
or in online editors like [Cemetech](https://www.cemetech.net/sc/).  
They are suitable for Texas Instruments TI-83 Plus and TI-84 series calculators.  
Even though the programs in this initial suite date back to 2011-2012, I believe that they may still be useful for Mechanical Engineering students
using these calculators.  
Feel free to use, edit and share these programs, and to add more programs to this suite.

## List of programs

The programs available here are summarised and briefly described in what follows.

### Colebrook equation solver

In the context of Fluid Mechanics, the Colebrook equation enables the calculation of the friction coefficient given the hydraulic diameter of a pipe,
the roughness of its surface and the Reynolds number.  
The Newton-Raphson method has been employed to solve this non-linear equation.  
When the program [`COLEBROOK`](https://github.com/iarlopes/TI84-MechEng/blob/main/COLEBROOK.8xp) is executed, the diameter `DIAMETRO - D`,
roughness `RUGOSIDADE - E`, and Reynolds number `N REYNOLDS - R` are prompted.
The friction coefficient `F` is returned.

### Determination of natural frequencies

The program [`FREQNAT`](https://github.com/iarlopes/TI84-MechEng/blob/main/FREQNAT.8xp) determines the natural frequencies of an undamped system with two degrees of freedom,
through the solution of the corresponding characteristic equation.  
The mass matrix must be stored in the variable `A` and the stiffness matrix in the variable `B`.
These must be square matrices with dimension 2.
In the calculator, press `2nd>matrix>edit` to edit specific matrices.  
Run the program and the square of the natural frequencies, \\( \omega_1^2 \\)$ and \\( \omega_2^2 \\), is written and stored in variables `D` and `E`, respectively.

### Determination of normalised modal vectors

In the context of vibrations mechanics, the program [`MMODUNIT`](https://github.com/iarlopes/TI84-MechEng/blob/main/MMODUNIT.8xp) returns the normalised (unit)
modal vectors given the $2\times 2$ mass matrix, stored in variable `A`, and two modal vectors stored in variables stored in variables `C` and `D`
(matrices with dimension $2\times 1$), respectively.  
The results are displayed and stored in variables `G` and `H`.

### Determination of the Raileigh quotient

In the context of vibrations mechanics, the program [`QRAYLEIG`](https://github.com/iarlopes/TI84-MechEng/blob/main/QRAYLEIG.8xp) determines the
Raileigh quotient for a system with two degrees of freedom.
The mass and stiffness matrices ($2\times 2$) must be stored in variables `A` and `B`, respectively, and the trial vector in variable `C` ($2\times 1$ matrix).
When the program is executed, the result is displayed and stored in variable `R`.


## Contacts

Send me an e-mail to ilopes@fe.up.pt if you have any question or comment.