# Naan-Mudhalvan-
A buzzer is an electronic device that makes a buzzing sound when electricity is supplied. It is commonly used in alarms, indicators, and electronic projects. A buzzer changes electric signals into sound.  It can be active (sounds by itself when powered) or passive (needs a signal to make sound).
int buzzer = 8; // Buzzer connected to pin 8

void setup() {
  pinMode(buzzer, OUTPUT); // Set pin as output
}

void loop() {
  digitalWrite(buzzer, HIGH); // Turn buzzer ON
  delay(1000);                // Wait 1 second
  digitalWrite(buzzer, LOW);  // Turn buzzer OFF
  delay(1000);                // Wait 1 second
}
