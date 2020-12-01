# Lunch :smiley:

Lunch is usually the first day of the meal for me, and I usually have either a chesse bap with chicken slices, or spring rolls with pepper sticks.

### Linkedin Profile 

[My Linkedin Profile](https://www.linkedin.com/in/lucy-power-4a35a01b9/)

### Octocat Image

![Image of Kimonotocat](https://octodex.github.com/Kimonotocat/)


## My favourite games :heart_eyes:

1. Luigi's Mansion
2. LEGO Lord of the Rings
3. Monster Hunter World
4. Super Paper Mario
5. Euro Truck Simulator 2

## ProDev Checklist

[X]Think of topic for report
[X]Week 10 README file task
[ ]Complete Assignment 1

## GEC Odds and Evens Task Sample

```C++
#include <iostream>

int number;
bool odd, even;
int numOfOdd, oddTotal, numOfEven, evenTotal;

int oddOrEven(int number)
{
	int oddEven = number % 2;

	if (oddEven == 0)
	{
		numOfEven++;
		evenTotal = evenTotal + number;
	}
	else if (oddEven != 0)
	{
		numOfOdd++;
		oddTotal = oddTotal + number;
	}

	return 0;
}

int outputResults()
{
	std::cout << "There were " << numOfEven << " even numbers which total to " << evenTotal << std::endl;
	std::cout << "There were " << numOfOdd << " odd numbers which total to " << oddTotal << std::endl;

	return 0;
}

int main()
{
	for (int i = 1; i <= 10; i++)
	{
		std::cout << "Enter a number" << std::endl;
		std::cin >> number;
		
		oddOrEven(number);
	}	

	outputResults();

	return 0;
}```
