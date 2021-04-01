# Team-Beta-Assignment-13
Introduction to GitHub Assignment

//bla bal bla

// Matthew Kevicki Comment
// Hannah Grigg Comment
void setup() {
  pinMode(13, OUTPUT);    // sets the digital pin 13 as output
  pinMode(8, INPUT);      //sets the digital pin 8 as input
}

void loop() {
  digitalWrite(13, HIGH); // sets the digital pin 13 on
  while(digitalRead(8)==HIGH)
  {
    delay(70);            // waits for a second
    digitalWrite(13, LOW);  // sets the digital pin 13 off
    delay(70);            // waits for a second
    digitalWrite(13, HIGH); //sets the digital pin 13 on
  }
}
