# zoho-function-soap-push-deal

## What does this function do?
✅ Fetches a Deal record by ID from Zoho CRM, prepares a SOAP XML payload,  
then sends it to an external booking system via HTTP POST.

## Why?
- To integrate Zoho CRM Deals with the hotel reservation system (Datamate) using a SOAP API.
- Ensures booking data flows from CRM directly to the hotel system.

## Highlights
- Handles missing/null fields gracefully.
- Constructs SOAP payload dynamically with booking details.
- Parses the response to log or troubleshoot.

## Tips
- Make sure `Phone`, `Email`, `Deal_Name`, `Booking_Date`, `Amount`, and `Number_of_Persons` are valid in your CRM schema.
- Adjust SOAP fields or endpoint if the external API changes.
