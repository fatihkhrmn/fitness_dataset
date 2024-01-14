Fitness Dataset
Bu model basit bir sinir ağı modeli kullanarak farklı kategorilerdeki verilerle (egzersiz süresi, haftalık antrenman sayısı, su tüketimi, kalori tüketimi vb.) kilo kaybını tahmin etmeye odaklanır.

Kullanılan Kütüphaneler:

-pandas 

-numpy 

-seaborn 

-sklearn


Kilo değişiminin diğer verilerle ilişkisini görselleştirme: 
 
1)Kalori Tüketimi:

<img width="431" alt="image" src="https://github.com/fatihkhrmn/fitness_dataset/assets/116540889/b657d230-7b16-41ac-ab84-ec240f26b5a0">


2)Stres Düzeyi:

<img width="439" alt="image" src="https://github.com/fatihkhrmn/fitness_dataset/assets/116540889/121a09a6-4d97-47b7-9f69-ecd1c0d55743">



3)Su Tüketimi:

<img width="438" alt="image" src="https://github.com/fatihkhrmn/fitness_dataset/assets/116540889/42200188-b4c2-40be-a96e-c34b2618bdc1">



4)Egzersiz Süresi:

<img width="439" alt="image" src="https://github.com/fatihkhrmn/fitness_dataset/assets/116540889/2da6e0e3-9e34-4d41-8c66-0650a512c2d0">



Modelin Oluşturulması
Verilerin ayrı ayrı değerlendirilerek bir model oluşturması amaçlanmıştır ve böylece bu modelin eğitilerek karşılaştırmalı bir şekilde kilo değişiminin analizinin tahmini yapılabilmiştir.

<img width="454" alt="image" src="https://github.com/fatihkhrmn/fitness_dataset/assets/116540889/bb5facd8-c1ec-4827-bda7-90652d83ce02">

Bu örnekte, tüm özelliklerin kullanılarak bir lineer regresyon modeli eğitilir. Ardından, test seti üzerinde performansı değerlendirilir ve kilo değişimi tahmini yapılır.

<img width="454" alt="image" src="https://github.com/fatihkhrmn/fitness_dataset/assets/116540889/f8d1f9b5-0c70-4c58-9383-6b4511e8bd6f">

Bu örnekte, sadece "SuTüketimi" özelliğini kullanarak bir lineer regresyon modeli eğitilir. Ardından, test seti üzerinde performansı değerlendirilir ve belirli bir su tüketimi için kilo değişimi tahmini yapılır.

<img width="454" alt="image" src="https://github.com/fatihkhrmn/fitness_dataset/assets/116540889/f0f58988-b3a4-4e18-b248-7d90346af1be">

Bu örnekte, sadece "StresDüzeyi" özelliğini kullanarak bir lineer regresyon modeli eğitilir. Ardından, test seti üzerinde performansı değerlendirilir ve belirli bir stres düzeyi için kilo değişimi tahmini yapılır.

<img width="454" alt="image" src="https://github.com/fatihkhrmn/fitness_dataset/assets/116540889/c4c9e2f7-5ac0-4ba9-afd0-4a5e5b411886">

Bu örnekte, sadece "KaloriTüketimi" özelliğini kullanarak bir lineer regresyon modeli eğitilir. Ardından, test seti üzerinde performansı değerlendirilir ve belirli bir kalori tüketimi için kilo değişimi tahmini yapılır.

<img width="454" alt="image" src="https://github.com/fatihkhrmn/fitness_dataset/assets/116540889/9238e515-eccc-4b02-a632-bd60ccf43864">

Bu örnekte, sadece "EgzersizSüresi" özelliğini kullanarak bir lineer regresyon modeli eğitilir. Ardından, test seti üzerinde performansı değerlendirilir ve belirli bir egzersiz süresi için kilo değişimi tahmini yapılır. ![image](https://github.com/fatihkhrmn/fitness_dataset/assets/116540889/dd737134-4c23-4d9e-922f-992a842bd333)




