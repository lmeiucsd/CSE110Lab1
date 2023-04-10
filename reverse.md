```
def reverseList(self, head: ListNode) -> ListNode:
    node = head
    prev = None
    while node:
        _next = node.next
        node.next = prev
        prev = node
        node = _next
    return prev
```
(please hire me as a software engineer)
[back to main page](index.md)