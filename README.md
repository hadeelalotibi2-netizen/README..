# README..
Arduino Uno LED Blinking Project using digital output and timing control.
Arduino LED Blinking Project | مشروع وميض الليد باستخدام الأردوينو

Project Overview | نبذة عن المشروع

This project uses an Arduino Uno to control an LED. The LED turns ON for one second and OFF for one second continuously.

يهدف هذا المشروع إلى التحكم في تشغيل وإطفاء الليد باستخدام لوحة Arduino Uno، بحيث يضيء لمدة ثانية واحدة وينطفئ لمدة ثانية واحدة بشكل متكرر.

Components Used | المكونات المستخدمة

* Arduino Uno — لوحة الأردوينو
* LED — الليد
* Breadboard — لوحة التجارب
* Jumper Wires — أسلاك التوصيل
* USB Cable — كابل USB

How It Works | آلية عمل المشروع

The Arduino sends digital signals to turn the LED ON and OFF. The delay(1000) function controls the timing.

ترسل لوحة الأردوينو إشارات رقمية للتحكم في تشغيل الليد وإطفائه، وتُستخدم الدالة delay(1000) لتحديد مدة ثانية واحدة.

Code | الكود البرمجي

void setup() {
  pinMode(LED_BUILTIN, OUTPUT);
  pinMode(9, OUTPUT);
}
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);
  digitalWrite(9, HIGH);
  delay(1000);
  digitalWrite(LED_BUILTIN, LOW);
  digitalWrite(9, LOW);
  delay(1000);
}

Project Result | نتيجة المشروع

Both LEDs blink simultaneously, turning ON and OFF every second.

يعمل الليد المدمج في لوحة الأردوينو والليد المتصل بالمنفذ رقم 9 بالتزامن، حيث يضيئان لمدة ثانية وينطفئان لمدة ثانية باستمرار.

Skills Learned | المهارات المكتسبة

* Arduino Programming — برمجة الأردوينو
* Digital Output Control — التحكم في المخرجات الرقمية
* Basic Electronics — أساسيات الإلكترونيات
* Timing Control — التحكم في التوقيت
