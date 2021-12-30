# 概要
sklearn.datasetsで提供されているload_wine(3種類のワイン)の分類と重要特徴量の表示、RandomForestの可視化    
# 実行結果（訓練データとテストデータに対する精度、特徴量の重要度）
training accuracy= 1.0  
test accuracy= 0.9777777777777777  

Feature Importances:  
	alcohol              : 0.098148  
	malic_acid           : 0.078885  
	ash                  : 0.002183  
	alcalinity_of_ash    : 0.033373  
	magnesium            : 0.067494  
	total_phenols        : 0.082676  
	flavanoids           : 0.105425  
	nonflavanoid_phenols : 0.001948  
	proanthocyanins      : 0.069859  
	color_intensity      : 0.131774  
	hue                  : 0.027180  
	od280/od315_of_diluted_wines : 0.152421  
	proline              : 0.148633  
# 生成された決定木
![image](https://user-images.githubusercontent.com/62968285/147763258-7df43ebf-64ec-4ddf-bc3a-9d1906b8d8c5.png)
