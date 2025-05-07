# print('Hello World!')

> This is my GitHub page. There are many like it, but this one is mine.

```bash
#!/bin/bash
if [[ -f I_LOVE_PROGRAMMING.txt ]]; then
  echo 'Never stop learning!'
else
  echo 'Hope it will never come to that'
  touch I_LOVE_PROGRAMMING.txt
fi
```

### Where is a list[] of $things I love to explore()

```js
const passions = {
    'projectEuler': true,
    'picoCTF{tru3_lov3}': true,
    'pythonChallenge': true,
    'adventOfCode': true,
    'sleepAt($desktop)': false,
    'hackathons': true
};

console.log(Object.keys(passions).filter(key => passions[key]));
```

### And more... 
```go
package main

import "fmt"

func main() {
    myOtherInterests := []string{}
    myOtherInterests = append(myOtherInterests, "Computer Science", "Martial Arts", "Gaming", "Anime")
    
    for _, interest := range myOtherInterests {
        fmt.Printf("I love %s!\n", interest)
    }
}
```

### The C side of life
```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    char* quotes[] = {
        "Code is poetry with logic",
        "Debugging is like being a detective in a crime movie where you're also the murderer",
        "The 'best' error message is the one that never shows up"
    };
    
    srand(time(NULL));
    printf("Daily wisdom: %s\n", quotes[rand() % 3]);
    
    return 0;
}
```

### PHP Magic
```php
<?php
class Programmer {
    private $coffeeLevel = 0;
    private $debuggingHours = 0;
    
    public function drinkCoffee($cups) {
        $this->coffeeLevel += $cups;
        return $this->coffeeLevel >= 3 ? "Ready to code!" : "Need more coffee...";
    }
    
    public function debug($problem) {
        $this->debuggingHours++;
        return ($this->debuggingHours > 4) 
            ? "Found it! It was a semicolon all along." 
            : "Still hunting that bug in '$problem'...";
    }
}

$me = new Programmer();
echo $me->drinkCoffee(4) . "\n";
echo $me->debug("production code");
?>
```
