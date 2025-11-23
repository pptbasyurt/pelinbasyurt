

<details>
  <summary><strong>Clock V1</strong></summary>

<br>

* **1. What is the difference between @State and var?**

  *@State creates a special variable that updates the UI when it changes.
  A normal var is just a regular variable — changing it does not update the view.*

* **2. Why do we reset hour to 0 after 24?**

  *Because clocks use a 24-hour cycle. After hour 23 to the next hour should loop back to 0, starting a new day.*

* **3. How does abstraction help in controlling the minute hand?**

  *Abstraction means hiding details and focusing on the essential idea.
  Instead of manually adjusting positions or angles, you use a simplified concept like “minute value” to control the hand.
  This keeps the code cleaner and easier to manage.*

* **4. How is .onTapGesture similar to Scratch’s event blocks?**

  *Both react to user actions.
  .onTapGesture runs code when the user taps — just like Scratch’s “when this sprite clicked” or “when flag clicked” blocks.*

* **5. How is using minuteSeg an example of abstraction in programming?**

  *minuteSeg represents a simple input (0–59) that controls a more complex behavior, like rotating the minute hand.
  You don’t need to worry about angles or math — just use the abstracted value.*
  

</details>
