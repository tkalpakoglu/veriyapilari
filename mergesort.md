**[16,21,11,8,12,22]** -> Merge Sort

1.<u>Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.</u>

[16,21,11,8,12,22] ==> 11'den bölünür

​                 [16,21,11]                                                      [8,12,22]

​			[16]            	[21,11]									[8,12]					[22]

​			[16]	  [21]		[11]								[8]				[12]				[22]

​			[16]            	[11,21]									[8,12]					[22]

​					[11,16,21]														[8,12,22]

​													[8,11,12,16,21,22]



<u>2.Big-O gösterimini yazınız.</u>

O(nlogn)