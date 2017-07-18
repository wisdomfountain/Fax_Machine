# Fax_Machine
//Determine action created by lines of code
//Starts the fax machine and displays status 
//Loads paper and sends a fax 
fax.setNumber("8761234567");
fax.load(paper);
String status = fax.run();
System.out.println("The fax result status : " + status);
