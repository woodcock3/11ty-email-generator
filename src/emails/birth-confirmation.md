---
subject: Appointment confirmed to register a birth on {Appointment_AppointmentDate} at {Appointment_StartTime}
preheader: Registrars Birth Appointment 
hidePreheader: true
headline: Appointment confirmed
---

Dear {Appointment_LetterRecipient}

Your {Appointment_AppointmentType} is booked for: 

Date: {Appointment_AppointmentDate}

Time: {Appointment_StartTime}

Location: {Appointment_Office_Address1}, {Appointment_Office_Address2}, {Appointment_Office_Town}, {Appointment_Office_PostCode}

{% include "partials/map-button.html" %}

Customer reference: {Appointment_Id}{Appointment_Office_EmailText}

Please arrive 10 minutes before your scheduled appointment; late arrival will mean that you will not be seen and your appointment will be rebooked.

## Attendance
  - If you are married (or in a civil partnership) only one parent needs to attend
  - If you are NOT married (or in a civil partnership) both parents need to attend if you wish for both parents names to be included on the birth certificate

## Do not forget
Please bring the following documents with you:

- Photographic ID for both parents (e.g. passport, driving licence, biometric residence permit, permanent residence card)
- If you do not have photographic ID please bring birth certificates and proof of address for each parent 
- Your bank card or cash if you wish to purchase birth certificates (£11 each)

## Interpreters
If you have requested an interpreter we will arrange one for you. If we are unable to arrange an interpreter for the appointment you have selected, we will contact you to offer a different date and time that the interpreter can attend. 

{% include "partials/appt-change-privacy.md" %}
