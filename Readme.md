The physics of nuclear magnetic resonance (NMR) spectroscopy is difficult. Once one leaves the simple picture of transitions between discrete energy levels behind, one is confronted with a number of models, each with their own advantages and limitations, that go beyond the basic theory needed for other spectroscopic methods in chemistry. All too often one is confronted with non-explanations like "This effect cannot be explained with the model you are using", without offering a model that actually works. Not that these models don't exist. Often, the student is simply unfamiliar with it, or the teacher does not know the knowledge of the student and chooses the simpler model over a more complex one to limit confusion. 

When teaching the physics of spin, a point can be made that a visual description should be totally avoided, because spin as a 4-dimensional property in relativistic spacetime cannot be adequately represented in three or less dimensions. Still, it cannot be denied that graphical representations like the vector model are immensely helpful. Regardless of the personal position in that regard, most students will first learn about spin as a vector property. Hence, learning NMR involves acquiring new knowledge as much as unlearning previous ways of thinking. 

[INSENSITIVE](https://github.com/klausboldt/insensitive) is a tool that displays different models for a system of up to 4 coupled spins in isotropic solution. Each operation, from defining the spin system to processing a 2-dimensional spectrum can be visualised and manipulated. Four representations of the system, the energy level diagram, vector representation, density matrix, and product operators, are shown alongside each other and show the possibilities and limits of each model. In addition to the statistical quantum mechanics of the system, the double cone of a spin 1/2 under the influence of a magnetic field can be shown to illustrate the transition from a single spin to a spn ensemble. The program comes with an extensive tutorial and should be used together with a textbook or relevant literature.

INSENSITIVE was written in C using the GTK-3 toolkit. It replaces the older code base written in Objective-C and using the Cocoa toolkit for macOS. It has been tested on several, modern Linux distributions, including Ubuntu, Fedora and SUSE, and was successfully compiled and tested on 64-bit Windows 7, 10 and 11. It can be run without installation by extracting the [binary archive](https://klausboldt.github.io/Insensitive-windows-x86_64.zip) to any folder and running `bin\insensitive.exe`. A macOS version is currently being prepared.
