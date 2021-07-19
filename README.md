| URL Scenerio | Action |
| ------------ | ----------- |
/Queue/Index| Work as normal. First shows all queues, Then starts a slideshow of all individual queues every 30secs       |
/Queue/Index? `queue=Counselor`| Displays and refreshes Counselor queue  |
/Queue/Index? `queue=Dosing`| Displays and refreshes Dosing queue  |
/Queue/Index? `queue=Group`| Displays and refreshes Group queue  |
/Queue/Index? `queue=Intake`| Displays and refreshes Intake queue  |
/Queue/Index? `queue=UA`| Displays and refreshes UA Screen queue  |
/Queue/Index? `queue=UA` & `type=full`| For any other queues, We can define `queueName` and `type` from URL. Queue color will be automaticaly determined |
