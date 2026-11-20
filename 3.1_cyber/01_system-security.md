# Exploring Your System's Security

## Task 1 --- List System Users

Run:

    cat /etc/passwd

### Screenshot
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/780548e2-d8f6-4988-a8a2-1e544d4e365b" />



### Questions

1.  How many users exist on the system?
2.  Which accounts appear to be system accounts?
3.  Why do operating systems create system accounts?

### Reflection

Explain why understanding system users is important for cybersecurity.

------------------------------------------------------------------------

## Task 2 --- Inspect Running Processes

Run:

    ps aux

### Screenshot

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/6af2c2f2-a950-40b5-b48d-811b82e20e3b" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/8ff3fa4c-89e2-4b16-820c-8c51dd201799" />



### Questions

1.  Which processes are running as `root`?
2.  Why can processes running as root be dangerous?
3.  What could happen if a malicious program ran with root privileges?

### Reflection

What did you learn about system processes and security?

------------------------------------------------------------------------

## Task 3 --- Identify Open Network Ports

Run:

    ss -tulnbash: !nBicyclePlanet: event not found


### Screenshot

(Add screenshot here)

### Questions

1.  Which ports are open?
2.  Which services appear to be listening?
3.  Why might open ports represent a security risk?

### Reflection

Explain the relationship between open ports and potential attack
surfaces.
