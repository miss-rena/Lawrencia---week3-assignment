# Analysis of 5 GitHub Issues on Appointment Rescheduling

### Issue 1: Reschedule confirmation not sent
Problem: Patient does not receive email after reschedule
Solution: Add automatic email notification trigger

### Issue 2: Double booking after reschedule
Problem: Old slot not released, causes double booking
Solution: Release old slot immediately when new slot is selected

### Issue 3: No limit on reschedule count
Problem: Patients can reschedule unlimited times
Solution: Set maximum of 2 reschedules per appointment

### Issue 4: Calendar not updating in real-time
Problem: Rescheduled time shows as still busy on other devices
Solution: Implement real-time sync with websockets

### Issue 5: No reason captured for rescheduling
Problem: No data on why appointments are rescheduled
Solution: Add required dropdown: Sickness, Emergency, Transport, Other
