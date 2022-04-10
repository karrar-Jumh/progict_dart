# progict_dart

/*

Explane the code: the variable "hour" can't be "const" because it is hold a changable value
that changes over time.

So the right code is:

void main() {
var hour=DateTime.now().hour;
  print(hour);
}

*/

