Model : 
Modelica library model 
FMUName=BooleanNetwork1 
 
FMI Type :  
CoSimulation  
 
Generation Tool : 
CATIA R2016x 
 
Available Platforms : 
win32 
 
Known Errors : 
Not all <ScalarVariables variability="constant"> have their start value printed in modeldescription.xml 
 
FMUChecker : 
FMUChecker Version 2.0.3b2 win32 
 
run command : 
set FMUName=BooleanNetwork1
fmuCheck.win32.exe -e %FMUName%_cc.log -o %FMUName%_cc.csv -h 1e0 -s 25 %FMUName%.fmu 
