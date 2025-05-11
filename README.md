# Task-Rescheduling-System-Managing-Priorities-Dynamically

let tasks = ["Task 1", "Task 2", "Task 3", "Task 4", "Task 5"];
tasks[0] = undefined;  
tasks = ["High-Priority Task 1", "High-Priority Task 2", ...tasks];  
tasks[tasks.length - 1] = "New Last Task";  
console.log(tasks);

