In this experiment, you are supposed to design a Railway Management System.  The system must provide list of 
functionalities according to the Customer’s(The Railway  Association) requirements. The list is given below :
  System will control the trains, services , trains on the rail.
  System includes:
o  Rails
  Normal : The rails don’t have any extern support. 
  Electrified : The rails supported with electricity.
o  Trains : Trains are being  used to transportation  all  over the  world. They track on the rails that 
created for specific trains. 
  High-Speed Train :This type of trains track on electrified rails. 
  Passanger Train : Passanger trains can move either electrified or normal rails.
   Accelerated Passenger Train : This type of trains track on electrified rails.  It is evolved 
from Passenger Train .
  Goods Train : A goods train can move both  of rails but its weight makes it harmful for 
electrified rails. So it is not preffered.
o  Engine Driver
  Captain : The Engine Drivers who reach  “Enough Track Experience” and “Enough Year 
of Employee”. “Enough” terms can be changed in time. It must be flexible.
  Assistant Captain :  The Engine Drivers who can not be captain yet.
  Certified  Engine  Drivers    :  The  Engine  Drivers  who  has  a  certification  to  operate  High 
Speed Train. Either a Captain or an  Assistant Captain is able to be a Certified  Engine 
Drivers. 
o  Railway Stations
  Main Stations : Main stations are the stations which the trains can garage, assign as Start 
Station and Finish Station.
  Transition  :  Transitions  locate  at  the  towns  which  are  between  two  main  stations.The 
trains can not garage there but can  use as a stop. They  can not be starting or ending 
points of the Services.
o  Users
  Admin : An admin, Administrator of the system, is full-authorized user of the system.
Service  Manager  :  Service  Manager  is  the  editor  of  the  Services.  He  can  add  a  new 
service, can edit and cancel it. He can not add a route. 
   Controller : The controller controls the rails. It directs the trains to optimum rail choices. It 
gives the priority of using electirified rails to the trains which are able to move on only 
electrified rails. 
  Functionalities:
o  New Train, Train Service, Engine Drivers Switch can be added.
o  Signal Sending/Receiving is being used to provide the synchronization of the trains on the rails.
o  Switches link the rails each other. 
o  Types of Train and Engine Drivers can be evolved in the course of time.
  Constraints:
o  Only one Controller can be exist in the system.
o  Train, Engine Drivers , Switch can be added by Admin.
o  Service Manager can add new Train Service. New service’s route must selected from the routes 
added before by an Admin. 
o  Train services have two Engine Drivers ; Captain and Assistant Captain.
o  Accelerated Train and High-Speed Train can not move on normal rail.
o  A Location Signal contains coordinates and timestamp sent by Train.
o  If a Train is on the rail, no other train can use that rail. For example ,there are three rails between 
two switches , at most three train can be exist between these two swit ches at the same time. It 
means each rail can contain only one Train at a time. 
o   A  train  starts  to  its  service  from  the  Starting  Station,  and  ends  at  Finish  Station.  Starting  and 
Finish  stations  must  be  Main  Stations,  and  there  could  be  lots  of  stops,  Main  Stations  or 
Transitions, between these stations. 
o  A service has statements like planning, during, ended.
o  A train has statements like  in the garage, active, waiting rail, waiting service time, waiting move 
garage etc.
o  Controller’s mission is managing the rails’ usage. 
o  Rails has speed-limits and Trains must obey the limits