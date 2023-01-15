## 376 Day 2 Lecture Notes
---
#### Potential Functions (Leaking Bucket)

Imagine you have some process(ex. running algorithm or a game) and you wanna show that this process will eventually end(It can't be running forever).
You look at a function and you want to point out some int quantity that depends on the process: decreasing in each "time step" and it's bounded below.

Observation: If we can define a potential function for a process then it must eventually terminate. 

```tsql
Ex(x): //for int x > 0
i ← 1 //iteration
while (x > 0):
    if (i is odd): 
        x ← x - 2 //subtract 2 from x
    else:
        x ← x + 1 //add 1 to x
    i ← i + 1
```
An ex of this iteration: 
    Ex(8) → 6 → 7 → 5 ....
    The first call results to 6 becausse i is odd therefore x -2... and so on
    
Claim: Value of x at end of iterations of the while loop when i is odd("time step") defines potential function. (because when i is off x decreases)
(To Prove This):
    Decreasing: let x 
#### Some PowerShell Code

```powershell
Write-Host "This is a powershell Code block";

# There are many other languages you can use, but the style has to be loaded first

ForEach ($thing in $things) {
    Write-Output "It highlights it using the GitHub style"
}
```
