# doorcontrolapi
Create an API to expose the information stored on the door control system in GL SBC.

Pending questions : 

HR Melania : Explain the proyect objective to check with GL if there is any problem with looking at this data or modifying the way people submit the food bonus.

Al : 
  - Can we have the API installed in a server with access to the repository?
  - Can he send us a copy of the current repository?


#Possible features :#

1. Automatic submition of the food bonus without API.

Implement a proccess that runs daily to read the repository and get the list of all people that went to the office the day before and check if they have already submitted 2 food bonus in the week, and submit a new one if not.

Create a separate repository to keep track of visits to the office.
  
2. API to expose data

Implement an API to get the days a person visits the office on date range. This can be a separated feature to allow people submit valid days to the existing google forms.

3. Get door badge reader signal to keep independent record.

We can find out how the reader signal is transmited and capture, so we can implement an independent solution.

4. Replace google forms for a custom repository.




