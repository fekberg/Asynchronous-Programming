# Asynchronous Programming
This is a breakdown/time line for my talk on Asynchronous Programming

## 0 - 5 minutes
- Introduction, Agenda and setting the expectations

## 5 - 10 minutes (5 minutes)
### What?
- What is the problem we are trying to solve? Bad UX, examples
- Where have we see Asynchronous patters before?

## 10 - 25 minutes (15 minutes)
### Going from Synchronous to Asynchronous in a .NET Application
- What is a task?
- How do we start a task?
- How do we know a task is done?
- How do we know if a task failed?
- How have we solved Asynchronous programming before?
- How do we continue work after a task is done?

## 25 - 40 minutes (15 minutes)
### Going from a simple task to Async & Await
- How do we get the result of an asynchronous task?
- Awaiting different types of Task/Task<T>, what is the difference?
- Where is the continuation?
- How does the continuation differ from Task.ContinueWith?
- Conventions: Naming and Usage
- Async everywhere: Show how to do it in Xamarin, ASP.NET and a WPF application

## 40 - 60 minutes (20 minutes)
### Deep-Dive in Async & Await
- What really happens when we mark a method as async?
- What really happens when we use the await keyword?
- What code is generated?
- What is the problem with the code that is generated?
- What does the state machine do?
- Why are our exceptions swallowed?
- Why we shouldn't wrap a synchronous call in an asynchronous method and call it async
- How does ASP.NET handle asynchronous code? What is the SynchronizationContext?
- What is a cancellation token?

## 60 - 70 minutes (10 minutes)
### Tips & Tricks and Summary
- How do we use async/await in a console application?
- What are common reasons for deadlocking? What is a deadlock?
- How do we avoid a deadlock?
- How do we force to block until a result is ready? GetAwaiter()
- Summarize the talk

## 75 - 85 minutes (15 minutes)
### Q&A
- Want me to show something again?
- Have Async/Await failed you before?
- What is your experience with Async/Await?

### No Questions?
- Re-iterate how to use Async and Await
- Talk about how it is easy to add async/await but how fragile it can be
- Show the async/await code again and re-iterate how to deadlock

