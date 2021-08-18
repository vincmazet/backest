# Background Estimation in Chemical Spectra

This program estimates the background (or baseline) of optical spectra by the polynomial minimizing a cost function. If the cost function was quadratic, the solution is the least squares estimation, which is not appropriate in this problem. Instead, we need to use of non-quadratic cost function such as the symmetrical Huber function, the symmetrical truncated quadratic or their respective asymmetrical shape.

The program is written in Matlab and should work with Matlab 6 (or higher).
* `demo` allows you to run the program with a simulated spectrum;
* `backcor` is the main function which can be run with or without a graphical user interface.

Type `help backcor` in Matlab to get the syntax of the function.

## References

* V. Mazet. "Développement de méthodes de traitement de signaux spectroscopiques : estimation de la ligne de base et du spectre de raies". Ph.D. thesis, University Henri Poincaré, Nancy 1. Defended on 01/12/2005.
* V. Mazet, C. Carteret, D. Brie, J. Idier, B. Humbert. "Background removal from spectra by designing and minimising a non-quadratic cost function". _Chemometrics and Intelligent Laboratory Systems_, vol. 76, no. 2, p. 121-133, april 2005.
* V. Mazet, D. Brie, J. Idier. "Baseline Spectrum Estimation using Half-Quadratic Minimization". EUSIPCO 2004, p. 305-308, 6-10 september 2004, Vienna, Austria.
* V. Mazet, J. Idier, D. Brie, B. Humbert, C. Carteret. "Estimation de l'arrière-plan de spectres par différentes méthodes dérivées des moindres carrés". Chimiométrie 2003, 3-4 december 2003, Paris, France.

## License

Copyright (c) 2012, Vincent Mazet. All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution
      
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" 
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE 
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE 
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE 
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR 
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF 
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS 
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN 
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) 
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE 
POSSIBILITY OF SUCH DAMAGE.
