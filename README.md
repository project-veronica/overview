# overview

## Problem:

Client often disconnects from their breathing machine and forgets to reconnect, which can be fatal. We have already had a dozen plus close calls where Client almost suffocated to death.

## Solution:

We equip Client with a "smart" wearable which monitors whether they are connected to their breathing machine. Client simply charges and wears a bracelet. The bracelet, however, talks to a server, records Client's heart rate & motion activity, and sends timely reminders via text to Client to remind their to re-equip the bracelet or reconnect to their machine.

## Considerations:
- architectural feasability (initial construction)
    - time to build
        - planning time
        - dev time
        - design time
        - physical hardware setup
    - cost to build: new accellarometer, server costs, 
- upkeep requirements (maintenance)
- target user & their needs (Client's lifestyle & ability to wear, charge, & not destroy her tech)
- insurance & medical permissions: received

## Proposed Hardware:
- Belkin Wemo
- Raspberry Pi
- Hexiwear Wearable
- Standard Flip Phone (that can send & receieve texts)

## Proposed Services:
- Twilio
- Heroku
