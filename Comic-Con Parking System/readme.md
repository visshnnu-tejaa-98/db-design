# Comic-Con Parking System

A large convention venue hosts Comic-Con India, where thousands of visitors arrive across multiple days for anime screenings, cosplay competitions, gaming showcases, creator meetups, merchandise zones and panel discussions.

During the event, people arrive using bikes, cars, SUVs, cabs and EV vehicles. The venue has a structured parking facility divided into multiple zones and levels. Some parking areas are reserved for cosplayers with props, exhibitors, creators, VIP guests, staff members and EV charging vehicles.

Whenever a vehicle enters the parking facility, the system generates a parking ticket and assigns a suitable parking spot depending on vehicle type and availability. When the vehicle exits, the system records exit time and calculates the parking fee.

The venue management wants a system that can track:

- vehicles entering the parking facility
- vehicle categories
- parking spot allocation
- reserved parking categories
- entry and exit timestamps
- parking sessions
- payment status
- spot availability across zones and levels
- This is a multi-zone event parking system where vehicle types, access categories, sessions, tickets and payments must be modeled properly.

## What You Have to Do

Your design should be able to answer questions like:

- What vehicles entered the parking facility?
- What type of vehicle entered?
- Which parking spot was assigned?
- Which zone or level does that parking spot belong to?
- Was the parking spot reserved for exhibitors, VIP guests, staff, or EV charging?
- When did the vehicle enter the facility?
- When did the vehicle exit the facility?
- What ticket was issued for the parking session?
- Can one vehicle visit the venue multiple times across different days?
- Can one parking spot be reused across multiple parking sessions?
- How is parking availability tracked?
- How are parking charges calculated?
- How is payment recorded for each parking session?
- Can special access categories (cosplayers with props, exhibitors, VIP guests, staff) be represented?
- Can the system track which vehicles are currently parked inside the venue?

## What to Make

Design the ER diagram for this parking system.

Your ERD should include the important structures needed for:

- vehicles
- vehicle categories
- parking spots
- parking spot categories
- parking zones or parking levels
- parking tickets
- parking sessions (entry and exit tracking)
- payment records

Things to think about:

- one vehicle can enter multiple times during the event
- one parking spot can serve many vehicles over time
- parking sessions should store entry and exit timestamps
- tickets and parking sessions may be separate structures
- different vehicle types require different parking spot types
- some parking spots may be reserved
- parking availability must be trackable
- zones or levels may contain multiple parking spots
- payments should be connected to parking sessions
- avoid putting everything into one single entity
