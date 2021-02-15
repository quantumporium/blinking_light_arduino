# blinking_light_arduino
This is my first attempt at embeded programming and robotic.

### Here how the arduino should look.
![](https://github.com/quantumporium/blinking_light_arduino/blob/main/blinking_light_circuit.png)
### Here is the code that make the arduino work. and blink the led.
The code is made with a programming language made by arduino that is similar to c++.
```cpp
void setup() {
  // put your setup code here, to run once:
  pinMode(13,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
  while(1){
    digitalWrite(13, HIGH);
    delay(500);
    digitalWrite(13, LOW);
    delay(500);
  }

}

```

<h4 align = 'center'> :no_entry_sign: This project is currently on hold :no_entry_sign: </h4>

