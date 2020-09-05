# Vilcheuskaya Yuliya

## Contact Info

**Phone:** +375336540199

**Email:** shostko.jn@gmail.com

**LinkedIn:** [Yuliya Shostko](https://www.linkedin.com/in/yulia-shostko-241003144/)

**Skype name:** live:798c4c229d5c4bd2

## Summary

Junior software developer with a strong desire to increase professional skills. Currently
focused on web development. Already finished native JavaScript online courses, HTML/CSS and Angular course.
Looking for internship and further employment. Ready for challenges and accomplishments.

## Skills

* JavaScript/ES6/TypeScript
* HTML
* CSS/SCSS
* Angular
* RxJS
* NgRX
* Git

## Latest code example

Task about cash from CS50 course

```c
#include <stdio.h>
#include <cs50.h>
#include <math.h>

int main(void) {
    int twentyFive = 25;
    int ten = 10;
    int five = 5;
    int one = 1;

    float change;

    int coins = 0;

    do {
        change = get_float("Change owed: ");
    }
    while (change < 0);

    int cents = round(change * 100);
    while(cents > 0) {
        if  (cents >= twentyFive) {
            cents = cents - twentyFive;
            coins++;
        } else {
            if (cents >= ten) {
                cents = cents - ten;
                coins++;
            } else {
                if (cents >= five) {
                    cents = cents - five;
                    coins++;
                } else {
                    if (cents >= one) {
                        cents = cents - one;
                        coins++;
                    }
                }
            }  
        }
    }
    printf("%i\n", coins);
}
```

## Experience

1. Recipe book

Final project of Angular course. It was created using Angular
framework, public API with recipes data, NgRx for
state management and Angular Material.

[Link to gitHub](https://github.com/shostiyuliya/recipe-book-project)

## Education

* **Grodno State University**

Bachelor Degree, Information
resources management

* **Academind**

HTML/CSS/Angular courses

* **Udemy**

Moder JS by Brad Traversy

* **Intexsoft**

Angular course

## English

* **EF SET Certificate**

B2 Upper-Intermidiate
