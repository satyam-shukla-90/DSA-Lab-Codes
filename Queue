                        ----Linear Queue----
Q.1 Write a C program to implement a Linear Queue using an array. Perform the following operations.
Insert 10, 20, and 30 into the queue.
Delete two elements from the Front.
Insert 40 into the Rear.
Display the remaining elements

#include <stdio.h>

int main()
{
    int queue[5];
    int front = 0, rear = -1;
    int i;

    queue[++rear] = 10;
    queue[++rear] = 20;
    queue[++rear] = 30;

    front++;
    front++;

    queue[++rear] = 40;

    printf("Queue elements are: ");

    for(i = front; i <= rear; i++)
    {
        printf("%d ", queue[i]);
    }

    return 0;
}
                         ----Circular Queue----

Q.2 Write a C program to implement a Circular Queue using an array of size 5. Perform the following operations.
Delete two elements from the Front.
Insert 50 and 60 into the queue.
Display the elements of the Circular Queue.

#include <stdio.h>

int main()
{
    int queue[5];
    int front = 0, rear = -1;
    int i;

    queue[++rear] = 10;
    queue[++rear] = 20;
    queue[++rear] = 30;
    queue[++rear] = 40;

    front = (front + 1) % 5;
    front = (front + 1) % 5;

    rear = (rear + 1) % 5;
    queue[rear] = 50;

    rear = (rear + 1) % 5;
    queue[rear] = 60;

    printf("Circular Queue elements are: ");

    for(i = front; i != (rear + 1) % 5; i = (i + 1) % 5)
    {
        printf("%d ", queue[i]);
    }

    return 0;
}
                     ----Double Ended Queue (Deque)----
Q.3 Write a C program to implement a Deque using an array. Perform the following operations.
Insert 10 from Front.
Insert 20 from Rear.
Insert 30 from Front.
Delete one element from Front.
Delete one element from Rear.
Display the remaining elements.

#include <stdio.h>

int main()
{
    int deque[5];
    int front = 2, rear = 2;
    int i;

    deque[front] = 10;

    deque[++rear] = 20;

    deque[--front] = 30;

    front++;

    rear--;

    printf("Deque elements are: ");

    for(i = front; i <= rear; i++)
    {
        printf("%d ", deque[i]);
    }

    return 0;
}
                             ----Priority Queue----                    
Q.4 Write a C program to implement a Priority Queue using an array. Perform the following operations.
Insert 10 with priority 2.
Insert 20 with priority 1.
Insert 30 with priority 3.
Delete the element having the highest priority.
Display the remaining elements with their priorities.

#include <stdio.h>

int main()
{
    int value[3] = {10, 20, 30};
    int priority[3] = {2, 1, 3};
    int i, high = 0;

    for(i = 1; i < 3; i++)
    {
        if(priority[i] > priority[high])
        {
            high = i;
        }
    }

    printf("Deleted element: %d\n", value[high]);

    printf("Remaining elements are:\n");

    for(i = 0; i < 3; i++)
    {
        if(i != high)
        {
            printf("%d (Priority %d)\n", value[i], priority[i]);
        }
    }

    return 0;
}
