# ALX Airbnb Project - Requirements

This document outlines the functional and non-functional requirements for the ALX Airbnb Project.

## Functional Requirements

1. **User Management**

   - Users can register, log in, and manage their profiles.
   - Users have roles: guest, host, or admin.

2. **Property Management**

   - Hosts can create, update, and delete property listings.
   - Each property includes details such as name, description, location, and price per night.

3. **Booking Management**

   - Guests can search for available properties and make bookings.
   - Bookings include start and end dates, total price, and status (pending, confirmed, canceled).
   - Hosts and guests can view booking history.

4. **Reviews**

   - Guests can leave ratings and comments for properties they have stayed in.
   - Reviews are linked to both the property and the guest who posted them.

5. **Payments**

   - Guests can make payments using supported methods: credit card, PayPal, or Stripe.
   - Payment records are linked to bookings.

6. **Messaging**
   - Users can send messages to each other regarding properties or bookings.
   - Message history is preserved for communication tracking.

## Non-Functional Requirements

1. **Security**

   - Passwords are securely hashed.
   - User data is protected and accessible only to authorized users.

2. **Performance**

   - The system should handle multiple simultaneous users without performance degradation.

3. **Usability**

   - The interface should be intuitive and user-friendly for both guests and hosts.

4. **Reliability**

   - Data integrity is maintained using relational constraints (foreign keys, UUIDs for primary keys).

5. **Scalability**
   - The system should allow future expansion, including adding new payment methods or additional user roles.
