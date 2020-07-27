# Vacation
---
## Vacation planning app

1. As a user, I want to be able to enter places  to get a list of prospective places in a country to visit this year

2. As a user, I want to enter a month to see if that month is a good time in the year to book a flight

3. As a user, I want to enter a city to get things to do in those places

4. As a user, I should be able to save my favorite locations
CLI.rb
“Hi, where would you like to go?”
“What month would you like to travel?”
“What city are you visiting?”
“These are your favorite locations”

---

# Vacation Safe
## The Safe Vacation Planning App



---
## Which Day in History?
--- 
## Introduction
* Returns a historical fact for a date provided

## API
* Utilizes the 'Today in History' API
* url: https://history.muffinlabs.com/

## User Stories
1. As a user, I want to enter a date and receive a historical event for that date

2. As a user, I want to get a random historical event for the current day of access of the app.

3. As a user, I want to find the oldest histrocial event for that date

4. As a user, I want to see the newest historical fact for that date

5. As a user, I want to see a list who was born on the current day.

6. As a user, I want to see a random historical firgure who was born on a provided day.

7. As a user, I only want to see recent history after 1980.

8. User wants to 

---
## Relationships


* make a User class
    - has many :facts

<!-- * TimePeriod class
    - a historical time period
    - can have many facts
    - e.g., Roman, greek, China, India, Australia -->

* make a Fact class
    - has many :users

* make a UserFact class (join)
    belongs_to :User
    belongs_to :Fact

* creat a Facts table
    - add_column :events


