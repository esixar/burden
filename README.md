```
     __                   __                
    / /_  __  ___________/ /__  ____          
   / __ \/ / / / ___/ __  / _ \/ __ \
  / /_/ / /_/ / /  / /_/ /  __/ / / /
 /_.___/\__,_/_/   \__,_/\___/_/ /_/ 
                               
```
                                    
Burden is an automated Application Performance Testing tool for load, stress, spike and endurance testing.

## Example of testing localhost web application deployed on Tomcat

PS C:\burden> .\burden.exe --httpendpoint http://localhost:8080/market --loadusers 100000

      ..-::::::-..
  .:-::::::::::::::-:.
  ._:::    ::    :::_.
   .:( ^   :: ^   ):.             __                   __
   .:::   (..)   :::.            / /_  __  ___________/ /__  ____
   .:::::::UU:::::::.           / __ \/ / / / ___/ __  / _ \/ __ \
   .::::::::::::::::.          / /_/ / /_/ / /  / /_/ /  __/ / / /
   -::::::::::::::::-         /_.___/\__,_/_/   \__,_/\___/_/ /_/
   .::::::::::::::::.
    .::::::::::::::.
      oO:::::::Oo

  Welcome to burden! Author: @esixar

  You can get help by running 'burden --help'.

--httpendpoint set to http://localhost:8080/market
--loadusers set to 100000
--loadtime not set, using default value of 1m
Status for endpoint http://localhost:8080/market: 200 
Status for endpoint http://localhost:8080/market: 200 
Status for endpoint http://localhost:8080/market: 200 
Status for endpoint http://localhost:8080/market: 200 
Status for endpoint http://localhost:8080/market: 200 
Status for endpoint http://localhost:8080/market: 200 
Status for endpoint http://localhost:8080/market: 200 
Status for endpoint http://localhost:8080/market: 200 
Status for endpoint http://localhost:8080/market: 200 
Status for endpoint http://localhost:8080/market: 200 
The HTTP request failed with error Get http://localhost:8080/market: dial tcp [::1]:8080: bind: An operation on a socket could not be performed because the system lacked sufficient buffer space or because a queue was full.
The HTTP request failed with error Get http://localhost:8080/market: dial tcp [::1]:8080: bind: An operation on a socket could not be performed because the system lacked sufficient buffer space or because a queue was full.
The HTTP request failed with error Get http://localhost:8080/market: dial tcp [::1]:8080: bind: An operation on a socket could not be performed because the system lacked sufficient buffer space or because a queue was full.
The HTTP request failed with error Get http://localhost:8080/market: dial tcp [::1]:8080: bind: An operation on a socket could not be performed because the system lacked sufficient buffer space or because a queue was full.
The HTTP request failed with error Get http://localhost:8080/market: dial tcp [::1]:8080: bind: An operation on a socket could not be performed because the system lacked sufficient buffer space or because a queue was full.
