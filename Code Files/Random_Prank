#include "DigiKeyboard.h"
void setup() {
}


void loop() {
 
 DigiKeyboard.update();
 DigiKeyboard.sendKeyStroke(0); //this is generally not necessary but with some older systems it seems to prevent missing the first character after a delay
 switch (random(160)) {
 case 0: // Minimize all windows
 DigiKeyboard.sendKeyStroke(KEY_M, MOD_GUI_LEFT);
 break;
case 1: // Lock screen
 DigiKeyboard.sendKeyStroke(KEY_L, MOD_GUI_LEFT);
 break;
 
 case 2: // Minimize current window
 DigiKeyboard.sendKeyStroke(KEY_DOWN_ARROW, MOD_GUI_LEFT);
 break;
case 3: // Flip screen
 DigiKeyboard.sendKeyStroke(KEY_DOWN_ARROW, MOD_CONTROL_LEFT + MOD_ALT_LEFT);
 break;
default:
 break;
 }
 
 delay(6000);
}
