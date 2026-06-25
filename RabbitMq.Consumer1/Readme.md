Create a project using Service Worker template

install the required dependencies i.e RabbitMQ.Client Version=7.2.1

Delete the Worker.cs class in every projects as it is not required

Install rabbitmq via cmd
C:\Users\fojek>
>>choco install rabbitmq

It starts running right away, but if not, Press Win + R, type services.msc, and hit Enter.
Rclick on RabbitMQ service and select Start.

Goto http://localhost:15672/ and login with default credentials (guest/guest) to access the RabbitMQ management dashboard.