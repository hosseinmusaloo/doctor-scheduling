# doctor-scheduling

A project that explores one practical approach to implementing doctor availability and appointment scheduling.

## Overview

Doctor availability is computed on-demand using:

- Weekly schedules
- Date-specific exceptions
- Existing appointments

## Domain Model

The core domain consists of:

- **Patient**
- **Doctor**
- **DoctorSchedule**  
  Defines regular working hours for a doctor on a specific weekday.
- **DoctorException**  
  Overrides the regular schedule for a specific date.
- **Appointment**  
  Represents a booked time range.

Slots are not part of the domain model (generating on-demand).
