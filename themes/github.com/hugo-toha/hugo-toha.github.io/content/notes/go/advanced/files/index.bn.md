---
menu:
  notes:
    identifier: notes-go-advanced-files
    name: ফাইল ম্যানিপুলেশন
    parent: notes-go-advanced
    weight: 10
title: ফাইল ম্যানিপুলেশন
weight: 40
---

<!-- Condition -->
{{< note title="Condition">}}

```go
if day == "sunday" || day == "saturday" {
  rest()
} else if day == "monday" && isTired() {
  groan()
} else {
  work()
}
```

```go
if _, err := doThing(); err != nil {
  fmt.Println("Uh oh")
```

{{< /note >}}