# TensorflowForXamarin
A Xamarin bindings library for Tensorflow 1.13.1

# Instructions

Download the solution and open the solution in Visual Studio. The recommended version of Visual Studio is Visual Studio 2019 but 2017 should work fine as well although it 
hasn't been tested.

Build the project. The Project will create an assembly file (the file with extension with extension .dll) in the debug folder inside the bin folder of the solution. In the 
project where you want to use tensorflow, add a reference to this file. Note that this binding is for the Android project. 

Add a using statement as Org.Tensorflow and you should now have access to the tensorflow 1.13.1 library in Xamarin Android!
