// Consider a staircase of size
   #
  ##
 ###
####
// Hello-World
//Just another repositoy
#include <math.h>
#include <stdio.h>
#include <string.h>
#include <stdlib.h>
#include <assert.h>
#include <limits.h>
#include <stdbool.h>

int main(){
    int n;
    scanf("%d",&n);
    int i, j, k;
    for(i =1; i <= n; i++){
        for(j = 1; j <= (n - i); j++){
            printf(" ");
        }
        for(k = 1; k <= i; k++){
            printf("#");
        }
        printf("\n");
    }

}
