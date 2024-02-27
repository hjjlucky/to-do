List to store the to-do items
todos = []

Function to add a to-do item
def add_todo(todo):
    todos.append(todo)
    print("Todo added.")

Function to display the to-do list
def show_todos():
    if todos:
        print("To-Do List:")
        for index, todo in enumerate(todos, start=1):
            print(f"{index}. {todo}")
    else:
        print("No todos.")

Function to delete a to-do item
def delete_todo(index):
    if 1 <= index <= len(todos):
        deleted_todo = todos.pop(index - 1)
        print(f"'{deleted_todo}' item deleted.")
    else:
        print("Invalid index.")

User interface
while True:
    print("\n1. Add Todo")
    print("2. Show Todos")
    print("3. Delete Todo")
    print("4. Exit")
    choice = input("Select an option: ")

    if choice == '1':
        todo = input("Enter the todo item: ")
        add_todo(todo)
    elif choice == '2':
        show_todos()
    elif choice == '3':
        show_todos()
        index = int(input("Enter the number of the todo item to delete: "))
        delete_todo(index)
    elif choice == '4':
        print("Exiting the application.")
        break
    else:
        print("Invalid choice. Please select again.")
