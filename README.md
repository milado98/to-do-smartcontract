# to-do-smartcontract
This Smart Contract creates a to do app where users can create, update, delete and complete tasks.

toggleCompleted function is defined to allow the user toggle if the task has been completed.The function also updates the completeCount and incompleteCount variables to keep track of the number of complete and incomplete tasks.

deleteTask function is defined to allow the user to delete a task. The function also updates the completeCount, incompleteCount and taskCount variables to keep track of the number of complete and incomplete tasks and the total number of tasks.

updateTask function is defined to allow the user to update a task. The function updates the task details and updates the completeCount and incompleteCount variables to keep track of the number of complete and incomplete tasks.

getIncompleteTasks function is defined to allow the user to get a list of incomplete tasks. The function returns an array of Task structs containing the details of each incomplete task.

getCompleteTasks function is defined to allow the user to get a list of complete tasks. The function returns an array of Task structs containing the details of each complete task.
