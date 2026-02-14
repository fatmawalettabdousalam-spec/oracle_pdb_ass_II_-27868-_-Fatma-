### Overview

This project covers creating an Oracle 21c PDB and setting up a local admin user. It also shows how to delete a temporary PDB and check the database status using OEM Express.

Task 1: New Pluggable Database

The primary objective of this task was the creation of a permanent Pluggable Database (PDB) named fa_pdb_27868. The process involved using the FILE_NAME_CONVERT parameter to map the physical datafiles from the standard PDBSEED template to a custom directory on the C: drive.

Once the PDB was created, it was transitioned from Mounted to Open mode. A user, fatma_plsqlauca_27868, was then created with DBA privileges to to manage the database.

<img width="989" height="351" alt="Screenshot 2026-02-14 152935" src="https://github.com/user-attachments/assets/3d2769e9-b194-45ac-b5a1-9b6b078857d9" />


PDB open state:

<img width="579" height="162" alt="Screenshot 2026-02-14 140630" src="https://github.com/user-attachments/assets/d44493a7-dfe7-4d36-9881-4bc30fec46d2" />


User created inside the PDB:

<img width="805" height="141" alt="Screenshot 2026-02-14 141131" src="https://github.com/user-attachments/assets/5363df3b-0049-408e-9f92-55e0f387585d" />


Task 2: Temporary PDB Lifecycle

This task involved creating and deleting a test PDB to demonstrate database management.


PDB creation:

<img width="1105" height="306" alt="Screenshot 2026-02-14 141956" src="https://github.com/user-attachments/assets/b5f4d0a4-72e9-4d5e-87b5-1e422ac932ec" />


PDB deletion:

<img width="670" height="271" alt="Screenshot 2026-02-14 142608" src="https://github.com/user-attachments/assets/3e470fca-efc1-43d1-9b25-91fb82d58a99" />


Task 3: Monitoring via OEM Express

This task involved using the Oracle Enterprise Manager (OEM) Express web interface to verify that the new PDB was running correctly.

<img width="1338" height="675" alt="Screenshot 2026-02-14 145034" src="https://github.com/user-attachments/assets/fc7709ca-7ecb-4418-8941-78ad2a312d9c" />







I confirm that this assignment is my own individual work. I have executed all commands myself and captured my own screenshots. I have not copied from classmates or used external tools to generate these solutions.






