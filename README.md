# Hospitals Microservice

The Hospitals Microservice deals contains the various methods to manage doctors,beds and other inventory of the hospital. The various endpoints contained in the microservice include the following :

- `/doctor [METHOD = GET]` : This endpoint is used to get the list of all doctors corresponding to a given `hospital_id `

- `/doctor [MRTHOD = POST]` : This method is used to add a doctor to the databse

- `/doctor [METHOD = DELETE]` : This method is used to delete a doctor from the databse

- `/hospital_specialisation` : This method is used to return the hospitals corresponding to a given specialisation

- `/doctor_specialisation` : This method is used to return the `doctor_ids` corresponding to a given specialisation and a given `hospital_id`

- `/get_lab_bills` : This method is used to retrieve the lab bills corresponding to a given `lab_id` and `test_id`

- `/get_doctor_bills` : This method is used to retrieve the bills corresponding to a given `hospital_id` and `doctor_id`

- `/change_status` : This method is used to change the occupany of the beds, that is, either book a bed or vacate a bed

- `/get_beds_status` : This endpoint is used to get the current statistics regarding the availability of beds.

