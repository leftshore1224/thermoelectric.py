# Themoelectric.py — a Python tool for design of high ZT nanoengineered thermoelectrics
Thermoelectrics (TE) are a class of materials that convert heat directly into electricity. If made sufficiently efficient and inexpensive, these materials could be used to recapturing low-grade waste heat from industrial process as useful electrical energy. The potential energy savings this are vast. Recent studies have suggested that recuperating only 10% of heat lost into electricity can improve fuel energy efficiency by 20% while other studies has reported that more than 68% of U.S. energy consumption escaped as waste heat. My studies have sought strategies to make energy harvesting more efficient by using nanoengineering to improve the performance of TEs. To achieve this, I have developed a python design package called thermoelectric.py for modeling thermoelectric performance.
The performance of TE materials at a given temperature, 𝑇, is quantified by a dimensionless figure of merit ZT=(σS^2)/κ T, where κ, σ and S are the material’s thermal conductivity, electrical conductivity and Seebeck coefficient, respectively. The power factor (σS^2) in ZT depends on a combination of strongly interdependent electrical transport properties, that have a countervailing dependence of the charge carrier concentration. The tradeoff of these parameters is well understood, and it has become an accepted truth that optimal TE performance can only be obtained in semiconductors that are highly doped to a narrow window of optimized charge carrier concentration.6 My design tool, thermoelectric.py, consists of a series of sub tools that model the thermal and electrical transport properties that contribute to ZT. The design tool was initially developed to model Si based thermoelectric nanocomposites developed in the Mangolini group that have a carefully engineered nanostructure to enhance both the thermal and electrical contributions to ZT. My tool was validated against these experimental measurements and was able to successfully predict the thermoelectric coefficients in Si across a wide range of temperatures. 
Since validating thermoelectric.py I have applied it to the design of thermoelectric materials in two  ways: In my first design process I explored the enhancement to thermoelectric performance that could be obtained by designing the electron scattering to optimally harness the mechanism of electron energy filtering (a mechanism to improve ZT by impeding low energy electrons). Remarkably, I found that using electron energy filtering can completely free engineers from the established paradigm that the optimal carrier concentration is constrained and that only semiconductors can make good thermoelectrics. The model demonstrates that if one applies perfect energy filtering then one can obtain greatly enhanced power factor by doping the material to push the Fermi energy even deep into the conduction band. In fact, it is possible to make TE with optimal performance that are metallic!
My second design study using thermoelectric.py focused on how to design the nanoscale morphology of a thermoelectric to obtain favorable electron scattering. For this I extended my thermoelectric.py tool with a module to compute the quantum mechanically predicted rates of electron scattering from heterogeneities with a variety of different geometries. Most recently I have applied it for the optimal design of porosity.
One currently very active area research in TEs is to engineer materials to contain nanoscale porosity.  These impede heat transport and can dramatically increase ZT by reducing the denominator κ; However, porosity also impedes electrical transport, reducing the thermoelectric power factor, σS^2, in the numerator of ZT. I have used thermoelectric.py to find design strategies to this problem. I have found that the detrimental effect of pores can be largely mitigated in the thermoelectric design by subtly tuning the doping concentration to higher carrier concentration compared to bulk materials. I have surveyed different shape and size of pores and shown that as a design strategy, for the largest enhancement in Seebeck one needs to get in pores of any shape, if you can make them as small as possible. I have shown that in a n-type thermoelectric the highest practical filtering threshold that can be provided by a dispersion of spherical nanopores with characteristic length around 16 nm giving a theoretical maximum power factor as high as 89% of the maximum power factor that can be obtained in bulk Si at room temperature. The results presented in this study form a complementary design principle for optimizing the electrical transport properties in nanoengineered thermoelectrics.
My advancements make a significant and novel contribution to the field of TE, showing that the conventional paradigm is overly restrictive, and there are whole other class of materials can be good TE. As a result of this research, I am the lead author of three manuscripts on this topic. Two of them submitted and the third manuscript is in final level of preparation. I am also co-author of the fourth paper on heat anticorrelation effect in porous TEs in which I have used thermal tools in thermoelectric.py to quantify phonon scattering at the interface of the pores. I have presented my work on the transport properties of TE at five national and international conferences I have recently been collaborating with Dr Romano from MIT to extend my model to nanoporous SiGe alloys (a promising material for TE applications). This design idea can open a new horizon in TE application by introducing extremely high ZT SiGe alloys. The thermoelectric.py tools is made available to for public. All of the theory and molding was accomplished by me, and I thankful for collaboration by the Mangolini group whom performed all of the experimental works. 
