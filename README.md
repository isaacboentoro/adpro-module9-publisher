> 1. How much data your publisher program will send to the message broker in one run? 
The publisher program sends 5 UserCreatedEventMessage objects to a rabbitmq message broker in one run. each message contains a user_id field and use_name field.

> 2. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?
Means both publisher and subscriber are using the same message broker to communicate.

### Running rabbitMQ
![rabbitmq running](images/rabbitmq.png)
