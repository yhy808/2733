This is a conversion to NEURON of the mitral cell model described in: Bhalla US 
and Bower JM. (1993) Exploring parameter space in detailed single
neuron models: simulations of the mitral and granule cells of the olfactory bulb. 
*J. Neurophysiol*. 69:1948-1965. 

The original model was written in GENESIS and is available from:
http://www.bbb.caltech.edu/BABEL/babeldirs/cells/mitral_granule/

Running the model (by executing mosinit.hoc) runs a simulation comparable
to Figure 5A. The GENESIS trace is also shown for comparison. 

There are some small discrepancies between the results from the NEURON and
GENESIS versions. I believe these are due to numerical differences, but it is 
possible they are due to bugs in my code.

For more information on this conversion contact Andrew.Davison@iaf.cnrs-gif.fr

For more information on the original model contact U.S. Bhalla or J.M. Bower

Changelog
---------
2022-05: Updated MOD files to compile with the latest neuron releases where
         ion variables used as STATE can not be declared as GLOBAL.
2024-10: Converted readme to markdown.
