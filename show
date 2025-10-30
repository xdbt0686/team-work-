def show_tasks():   #Display all tasks
    if not tasks:
        print("No tasks found.")
        return
    print("\n Current To-Do List:")
    for task in tasks:
        status = "✅ Completed" if task["completed"] else "❌ Not Completed"
        print(f"{task['id']}. {task['title']} - {status}")
    print()
