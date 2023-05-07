#include<stdio.h>

int Bubble_sort(int Array[],int size)
{
	int i;
	int j;
	int k;
	int temp;
	int comp = 0;
	int count = 0;
	for(i = 0; i<size; i++)
	{
		for(j = 0; j<size-i-1; j++)
		{
			if(Array[j] > Array[j+1])
			{
				temp = Array[j];
				Array[j] = Array[j+1];
				Array[j+1] = temp;
				for(k = 0; k<size; k++)
				{
					printf("%d->",Array[k]);
				}
				printf("\n");
				count++;
			}
			if(Array[j] < Array[j+1]  || Array[j]>Array[j+1])
			{
				comp++;
			}
		}
	}
	printf("The total no. of comparission is:%d\n",comp);
	printf("The total no. of swapping is :%d\n",count);
	return count;
}


int main()
{
	int Sample_array[] = {23,20,9,45,10};
	int size = sizeof(Sample_array) / sizeof(Sample_array[0]);
	Bubble_sort(Sample_array,size);
	for(int i = 0; i<size; i++)
	{
		printf("%d\n",Sample_array[i]);
	}
	return 0;
}
