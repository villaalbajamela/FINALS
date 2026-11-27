# GASO Connect

A web-based venue and equipment reservation system for GASO, De La Salle College of Saint Benilde Antipolo.

## How to Use

### Requester (no account needed)

1. Open the reservation form.
2. Select the organization, venue, date, start and end time, and number of attendees.
3. Add the equipment and quantity needed, if any.
4. Enter your name and Benilde email address, then submit.
5. Click the verification link sent to your email.
6. Save your reference number.
7. Use the reference number on the tracking page to see the current approval stage.
8. Once approved, print the booking slip.

To check which venues and equipment are free, open the availability page and choose a date.

### Approving Office (no account needed)

1. Open the single-use link sent to your email.
2. Review the reservation details.
3. Click **Approve** or **Disapprove**. Add remarks if needed.

If you approve, the next office is notified. The last approval marks the reservation as approved. A disapproval ends the request.

### GASO Admin (login required)

1. Log in with your staff account.
2. Use the menu to manage venues, equipment, organizations, the school calendar, and accounts.
3. Open Reservations to search, filter by status, edit pending requests, or cancel.

## How the System Works

1. **Validation:** On submission, the system checks the 7:30 AM to 5:00 PM window, past dates, blocked dates, venue conflicts, venue capacity, and equipment availability.
2. **Email verification:** The request moves forward only after the requester verifies their email.
3. **Approval chain:** Each venue has approving offices in a fixed order. Each is emailed a single-use link in turn.
4. **Result:** The request becomes Approved after the last office approves, or Disapproved if any office rejects it.

## Functions

- **Reservations:** Submit, track, edit pending requests, cancel.
- **Venues:** Manage capacity, location, and approving offices.
- **Equipment:** Manage quantities and per-date availability.
- **Organizations:** Manage recognized organizations and departments.
- **Approvals:** Sequential approval through emailed links.
- **School calendar:** Block campus closures and Philippine holidays (Nager.Date API).
- **Availability:** Public view of free venues and equipment by date.
- **Printing:** Reservation forms and booking slips.
- **Admin accounts:** Staff login and role-based access.

