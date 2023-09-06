#include <stdio.h>
#include <string.h>
#include <stdlib.h>

int factorial(int n) {
    if (n <= 1)
        return 1;
    return n * factorial(n - 1);
}

int countAnagrams(char *word) {
    int length = strlen(word);
    
  
}

int main() {
    char word[] = "Mono"; 
    int anagramCount = countAnagrams(word);
    
    printf("Слово: %s\n", word);
    printf("Кількість можливих анаграм: %d\n", anagramCount);
    
    return 0;
}
