# Solution
Get the weight metric of the strings contained in a generated string file based on certain defined rules .
Client-Server Solution in python with socket.

# Requirements
import random
import string
import socket
import logging
import datetime

# Server File (Server.py)
It's the Server start file.
This file needs configuration 
   ## Server Configuration
server_address = (host, port) 
logging.basicConfig(level=logging.DEBUG, filename= logfile_serverpath)
    ## The function Weight_Metric(my_strings) - Calculate the weigth metric for each string line on the file   

# Client File (Client.py)
  ## Start is the main function of this file.
  ## Strings are Generated with the function
      Strings_Generator(num_str, fname)
      if num_str is cero the program generate 1000000 strings lines
   ## To send and received the message from the server the function is Send_Server(server_address, message)

# Thread File (Thread.py)
   It's a configuration file and starts the Client when the Server is open and listening

