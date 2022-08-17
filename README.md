# Hospital Management

---
## screenshots
### Homepage
[![R4389-S6y2o0.jpg](https://i.postimg.cc/PfB2YCDk/R4389-S6y2o0.jpg)](https://postimg.cc/z3FC1Xpd)
### Admin Dashboard
[![2022-08-17-183848.png](https://i.postimg.cc/5y7336zW/2022-08-17-183848.png)](https://postimg.cc/dZCrQQn5)
### Doctor Dashboard
[![2022-08-17-183848.png](https://i.postimg.cc/5y7336zW/2022-08-17-183848.png)](https://postimg.cc/dZCrQQn5)
### Invoice
[![2022-08-17-184134.png](https://i.postimg.cc/Dw9h2czH/2022-08-17-184134.png)](https://postimg.cc/qNxSwyyx)
---
## Functions
### Admin
- Signup into their account. Then Login (No approval Required).
- Can register/view/approve/reject/delete doctor (approve those doctor who applied for job in their hospital).
- Can admit/view/approve/reject/discharge patient (discharge patient when treatment is done).
- Can Generate/Download Invoice pdf (Generate Invoice according to medicine cost, room charge, doctor charge and other charge).
- Can view/book/approve Appointment (approve those appointments which is requested by patient).

### Doctor
- Apply for job in hospital. Then Login (Approval required by hospital admin, Then only doctor can login).
- Can only view their patient details (symptoms, name, mobile ) assigned to that doctor by admin.
- Can view their discharged(by admin) patient list.
- Can view their Appointments, booked by admin.
- Can delete their Appointment, when doctor attended their appointment.

### Patient
- Create account for admit in hospital. Then Login (Approval required by hospital admin, Then only patient can login).
- Can view assigned doctor's details like ( specialization, mobile, address).
- Can view their booked appointment status (pending/confirmed by admin).
- Can book appointments.(approval required by admin)
- Can view/download Invoice pdf (Only when that patient is discharged by admin).

---

## Drawbacks/LoopHoles
- Any one can be Admin. There is no Approval required for admin account. So you can disable admin signup process and use any logic like creating superuser.
- There should be at least one doctor in hospital before admitting patient. So first add doctor.
- On update page of doctor/patient you must have to update password.

## Disclaimer
This project is developed for demo purpose and it's not supposed to be used in real application.


