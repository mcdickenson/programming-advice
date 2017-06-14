# programming-advice
Lessons learned from a career in software development.

### Development
- Don't overthink it. If you can think of a simple, brute-force approach and a more complex approach, try the simpler one first. Often it will be good enough. 

### Debugging

- Read the error message. Every time.
- Validate the data before debugging your code.
  - That is, if it could be a data problem or a code problem, suspect the data first. This can save you a **lot** of time.
- Make sure the code you're running is the code you think you're running.
  - E.g. re-compile, re-install, clear caches as needed.
  
### Error Handling

- Don't fail silently if you can avoid it.

### Production Software

- Don't run multiple versions in production. If you do, have a plan for when you come to regret it. 

### Scripting

- If you are uncertain about how long some code will take to run, add some indicator of progress. Often you will wish you had done this after you have started a process and realized it will take a long time. Even better, do some back-of-the-envelope calculation ahead of time to estimate how long it will take. 
- Even if it's a one-off script, make your data migrations [idempotent](https://en.wikipedia.org/wiki/Idempotence). There's a good chance you will have to reuse it. 

### References

- [Recurse Center Manual](https://www.recurse.com/manual): This guide has many great tips, especially on the social front. For example: *no feigning surprise*. 
