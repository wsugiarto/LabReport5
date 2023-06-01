
# Lab Report 5
## Debugging Scenario
### Part 1 Edstem Question:
What environment are you using (computer, operating system, web browser, terminal/editor, and so on)?
PC, Windows 10, google chrome, Visual Studio Code, Bash terminal. 


Detail the symptom you're seeing. Be specific; include both what you're seeing and what you expected to see instead. Screenshots are great, copy-pasted terminal output is also great. Avoid saying “it doesn't work”.
In my grading script, I am encountering this issue where can't get my if statements to echo the messages correctly. I believe that this is due to the fact that the elif statement is not triggering properly. In the code below, I wanted it to echo "Everything is fine" when the $line is an empty string, where the $line represents the first word found in a variable called failures which contains the line from a Junit Test where it says Tests run: some number, Failures: some number. I expected this variable failure to be empty, which is why I wrote the elif to be in that manner, but as you can see in the output below nothing gets echoed by the if statements.
![](1.png)
![](2.png)


Detail the failure-inducing input and context. That might mean any or all of the command you're running, a test case, command-line arguments, working directory, even the last few commands you ran. Do your best to provide as much context as you can.
As shown in those screenshots above, the failure inducing input is when I try to pass in a submission that is supposed to pass all JUnit tests. I belive the issue to be with how the elif is written but I cant seem to figure out how to correctly write this.

