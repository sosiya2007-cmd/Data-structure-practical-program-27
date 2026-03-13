# Enqueue operation using queue (array)

queue = []
max_size = 5

def enqueue():
    if len(queue) >= max_size:
        print("Queue Overflow")
    else:
        item = int(input("Enter element to insert: "))
        queue.append(item)
        print(item, "inserted into queue")

enqueue()

print("Queue elements:", queue)# Data-structure-practical-program-27
