# Entity-relationship-model-Checkpoint
In the ER model, entities are represented as rectangles and their attributes as ovals. Relationships between entities are represented as diamonds.

Entities and their attributes:

Member:

Unique identifier (UUID)
Last name
First name
Address
Date of birth
Gender
Gym:

Name
Address
Telephone number
Session:

Type of sport
Schedule
Gym (the gym where the session takes place)
Coach:

Last name
First name
Age
Specialty
Relationships:

Member - Session (registered members):

The number of members registered for a session is less than or equal to 20.
Session - Coach (led by coaches):

The number of coaches leading a session is less than or equal to 2.
Gym - Session (has sessions):

Each session belongs to a gym.
Gym - Coach (employs coaches):

Each coach works at a gym.
In this ER model, each relationship has a specific rule that limits the number of related entities.
