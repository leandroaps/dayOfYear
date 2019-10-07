# dayOfYear
This snippet gets the day of the year from a Date object.

```
const dayOfYear = date => 
      Math.floor((date - new Date(date.getFullYear(), 0, 0)) / 1000 / 60 / 60 / 24);
```

**Usage:**
```
dayOfYear(new Date()); // 272
```
