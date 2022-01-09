#include <stdio.h>

int main() {
//variables
int people;
float price;
int tip;


printf("Enter number of people in group: \n");
scanf("%d", &people);

  if (people>0) {

printf(" You entered: %d\n", people);
printf("Enter bill amount: \n");
}

else {
  (printf("INVALID ENTRY\n"));
  return 1;
}

scanf("%f", &price);

if (price>0){

printf("You entered %.2f \n", price);
printf("How much would you like to tip: \n");
}

else {
  printf("INVALID ENTRY\n");
  return 1;
}

scanf("%d", &tip);

if (tip <=0){
  printf("INVALID ENTRY\n");
  return 1;
}

if (30 >= tip){

  printf("You entered %d percent \n", tip);

  printf("Bill total comes out to be: %f \n", (price+ (price* (tip/100.0f))));
  printf("Each person will have to contribute : %f \n ", (price +price*(tip/100.0f)/
  people));
  return 1;

}


else {
printf("INVALID ENTRY!!\n");
  return 1;
}

if ( 5<= tip) {

printf("You entered %d percent\n", tip);

printf("Bill total comes out to be: %f \n", (price + price* (tip/100.0f)));
printf("Each person will have to contribute : %f \n ", (price + price*(tip/100.0f))/
people);
return 1;

}

else {
  printf("INVALID ENTRY!!\n");
    return 1;
}



  return 0;
}
