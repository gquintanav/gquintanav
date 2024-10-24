void loop(){
VALOR = analogread(A0);// lee entrada A0 y asigna a variable VALOR
serial.println(VALOR);//imprime en monitor serial el valor 
delay(500);      // breve demora de medio segundo

if(VALOR>80){
digitalwrite(MOTOR,LOW);
}

else{
digital write(MOTOR,HIGH),
