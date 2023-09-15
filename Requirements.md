# Requirements

## User Stories

## Use Cases
### User
- As a user, I would like the ability to save my order
- As a user, I want a variety of options for my icecream
- As a user, I would like to be rewarded for each purchase
- As a user, I would like to see my order history
- As a user, I would like the ability to quickly reorder an order from my history

### "Flyers" 
- As a flyer, I would like to be compensated (flight time or distance)

### Developer/Admin
- As an admin, I would like the ability to check inventory

### Tester (Potentially nice to have, not necessary)

## Prototypes

## MoSCoW Requirements
**Must-Haves:** 
- A location API that tracks each drone and sends email updates on order progress
- A secure payment system
- A separation of classes for drone size (small, medium, and large) capable of carrying different order sizes
- A UI that allows users to pick between a minimum of 4 flavors, but uses the same size cone for every order 
- Different account types for "customers" and "flyers"
- Account holder and Guest checkout modes
- The ability to add/remove drones in a "flyer" account
- A specific list of compatible drone types
- Manager database that tracks inventory of flavors based on previous orders
- Max distance for an order based on drone battery, e.g. someone cannot order a cone in Wyoming from a location in California
**Should-Haves:**
- Customer support form for users to specify an issue that gets stored in the database
- Set base delivery time that changes based on distance from Drone Cone location
- Point system for ordering from an account, rather than a guest checkout
- The ability to assign multiple drones to a large order
**Could-Haves:**
- Marketing emails and deals for Account holders
- Discounts/deals for "Flyers"
- Real-time location tracking via map, instead of sending updates via email
- SMS updates alongside email updates
**Won't Have (this time):**
- The ability to tip a "flyer"
- Automatic detection of the closest branch, seeing that there is only one branch
