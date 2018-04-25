node  { 
  stage 'Run JMeter Test'    
  bat C:\Users\bhalekarg\Downloads\apache-jmeter-3.2\apache-jmeter-3.2\bin\jmeter.bat -n -t 
  C:\Users\bhalekarg\Downloads\apache-jmeter-3.2\apache-jmeter-3.2\bin\SOAPEXAMPLES.jmx
  -l C:\Users\bhalekarg\Downloads\apache-jmeter-3.2\apache-jmeter-3.2\bin\testgit.jtl 
  } 
