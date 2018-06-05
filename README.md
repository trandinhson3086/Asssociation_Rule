# Asssociation_Rule
Association Rules Mining, Apriori Implimentation

Data Mining class                                                                               
Professor: Yonggwan Won                                 
Student: Tran Dinh Son, ID: 177290, mail: trandinhson3086@gmail.com 

('Dataset: ', data/example/out1.csv', ' MinSup: ', 0.03, ' MinConf: ', 0.7)
==================================================================
1 : Blackberry Tart (15), Apple Danish (36) support= 0.139                                                          
2 : Gongolais Cookie (22), Napoleon Cake (9) support= 0.181   														
3 : Lemon Cake (1), Single Espresso (49) support= 0.127 															
4 : Apple Tart (12), Berry Tart (14), Blueberry Tart (16) support= 0.257																			

Skyline Itemsets: 4																			

Rule 1 : Blackberry Tart (15) --> Apple Danish (36) [sup= 0.139 conf= 0.751351351351 ] 																		
Rule 2 : Apple Danish (36) --> Blackberry Tart (15) [sup= 0.139 conf= 0.798850574713 ] 																					
Rule 3 : Gongolais Cookie (22) --> Napoleon Cake (9) [sup= 0.181 conf= 0.841860465116 ] 																				
Rule 4 : Napoleon Cake (9) --> Gongolais Cookie (22) [sup= 0.181 conf= 0.804444444444 ] 																	
Rule 5 : Lemon Cake (1) --> Single Espresso (49) [sup= 0.127 conf= 0.814102564103 ] 																
Rule 6 : Single Espresso (49) --> Lemon Cake (1) [sup= 0.127 conf= 0.783950617284 ] 																	
Rule 7 : Apple Tart (12), Berry Tart (14) --> Blueberry Tart (16) [sup= 0.257 conf= 0.958955223881 ] 																			
Rule 8 : Apple Tart (12), Blueberry Tart (16) --> Berry Tart (14) [sup= 0.257 conf= 0.992277992278 ] 																	
Rule 9 : Berry Tart (14), Blueberry Tart (16) --> Apple Tart (12) [sup= 0.257 conf= 0.996124031008 ]																	
