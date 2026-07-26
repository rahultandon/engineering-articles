# C# Collections Explained

## Executive Summary
Choosing the right collection improves performance, scalability and maintainability.

## Collections Covered
- Array
- List<T>
- Dictionary<TKey,TValue>
- HashSet<T>
- Queue<T>
- Stack<T>
- ConcurrentDictionary

## Example

```csharp
var users = new Dictionary<int,string>();
users[1] = "Rahul";
```

## Best Practices
- Prefer Dictionary for key lookups.
- Prefer HashSet for uniqueness.
- Use concurrent collections for multithreaded code.

## Interview Questions
1. Why is Dictionary lookup O(1)?
2. When would you choose HashSet over List?
