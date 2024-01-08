# Proje Başlığı

:information_source: **Dersin Kodu:** [YAZ20411](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)  
:information_source: **Dersin Adı:** [DERİN ÖĞRENME](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)  
:information_source: **Dersin Öğretim Elemanı:** Öğr. Gör. Dr. Fatih BAL  [Github](https://github.com/balfatih)   |    [Web Sayfası](https://balfatih.github.io/)
   
---

## Grup Bilgileri

| Öğrenci No | Adı Soyadı           | Bölüm          		   | Proje Grup No | Grup Üyelerinin Github Profilleri                 |
|------------|----------------------|--------------------------|---------------|---------------------------------------------------|
| 1200505005 | SERHAT DURDURAN		| Yazılım Mühendisliği     | PROJE_8       | [Github](https://github.com/drnserhat)     	   |
| 1200505009 | METİN YILDIZ   		| Yazılım Mühendisliği     | PROJE_8       | [Github](https://github.com/mtn-yldz0154)    	   |
| 1190505803 | AHMET ARİF YILDIRIM  | Yazılım Mühendisliği     | PROJE_8       | [Github](https://github.com/ahmetarifff)   	   |

---

## Proje Açıklaması

	Bu proje, göğüs X-ray görüntülerini kullanarak önceden eğitilmiş bir derin öğrenme modelini  öğrenme yöntemleri ile uygulayarak, 
	görüntülerdeki patolojik durumları sınıflandıran bir uygulamayı içermektedir. 
	Temel amacı, göğüs röntgen görüntülerindeki sağlık durumlarını tanıyarak sınıflandırmaktır. 
	Proje, bir tıbbi görüntü sınıflandırma problemine pratik bir uygulama sunmak amacıyla tasarlanmıştır.

	Kapsam:
		Önceden eğitilmiş VGG16 modeli, transfer öğrenme için temel alınmıştır. 
		Bu model, geniş bir nesne sınıflandırma görevi üzerinde eğitilmiş ve X-ray görüntülerinde patolojik durumları tanıma yeteneği kazanmıştır.
		TensorFlow ve Keras kütüphaneleri, derin öğrenme modelinin oluşturulması, eğitimi ve değerlendirmesi için kullanılmıştır.
		Proje, eğitim, doğrulama ve test veri setleri üzerinde performans değerlendirmesi yaparak modelin gerçek dünya X-ray 
		görüntülerinde nasıl performans gösterdiğini değerlendirmiştir.

	Kullanılan Teknolojiler:
		TensorFlow ve Keras derin öğrenme kütüphaneleri: Model oluşturma, eğitim ve değerlendirme için.
		VGG16 modeli: Transfer öğrenme için temel alınan önceden eğitilmiş model.
		Python programlama dili: Uygulamanın temel programlama dili.

	Nasıl Çalıştırılır:
		Gerekli kütüphaneleri yükleyin: pip install tensorflow matplotlib
		Proje dosyalarını indirin veya klonlayın.
		Ana çalıştırılabilir dosyayı çalıştırarak uygulamayı başlatın.
		Uygulama, önceden eğitilmiş model kullanarak X-ray görüntülerini sınıflandıracaktır.
		
	Proje Yapısı:
		main.py: Ana çalıştırılabilir dosya.
		model_building.py: Modelin oluşturulması ve derlenmesi ile ilgili işlevleri içerir.
		data_preprocessing.py: Veri setlerinin yüklenmesi ve ön işleme adımlarını içerir.
		utils.py: Yardımcı işlevleri içerir.
		best_transfer_learning_model.h5: En iyi modelin kaydedildiği dosya.


---

## Proje Dosya Yapısı

	- **/Pneumonia**
	  - **/X-Ray**
		- **/Bacterial**
		  - `BACTERIA-7422-0001.jpeg`
			.
			.
			.
		- **/Viral**
		  - `person278_virus_572.jpeg`
			.
			.
			.
	  - `1.Deneme.ipynb`
	  - `2.Deneme.ipynb`
	- `README.md`

---

## Kurulum


	Görüntü Dosyalarını İndirme:
	Projenin görüntü dosyalarını içeren Google Drive bağlantısına giderek dosyaları indirin.
	https://drive.google.com/file/d/1QlnV6PUZ3ic8M1_22cC5bAjJocYZKn1P/view

	Proje Kodları İçin Kaynak Kodu Alma:
	Projeyi içeren GitHub reposuna giderek projenin kodlarını indirdik. Visual Studio veya Jupyter Notebook kullanarak kodları açacabilirsiniz.
	Bunun için projenin GitHub sayfasındaki "Preview" düğmesini kullanabilir veya doğrudan bu bağlantıyı kullanabilirsiniz.
	https://github.com/balfatih/YAZ20411_Derin_Ogrenme/blob/main/Week%20%2311/19122023_Derin_Ogrenme_Online_Dersi.ipynb

	Jupyter Notebook'u Başlatma:
	Proje Jupyter Notebook kullanıyorsa, terminal veya komut istemcisinde projenin ana dizinine gidin ve aşağıdaki komutu kullanarak Jupyter Notebook'u başlatın:
	jupyter lab

	Proje Dosyalarını Açma:
	Tarayıcınızda açılan Jupyter Notebook arayüzünde, projenin bulunduğu dizini seçin. 
	Ardından, projenin Jupyter Notebook dosyalarını içeren dizine giderek ilgili notebook'u seçip çalıştırabilirsiniz.

---

## Kullanım
	
	1. Dataların olduğu dizine gidin.
	2. Üstteki dizin girme kısmında veya mouse sol tuşunda o dizine ait terminale girin.
	3. Terminal ekranında jupyter lab kodu yazıp enter tuşuna basın.
	4. Çıkan local jupyter sayfasında yeni bir notebook oluşturun.
	5. Import edilecek kütüphaneleri ekleyin.(Eğer kütüphaneler mevcut değil ise pip install ile terminali açıp teker teker kurabilirsiniz)
	6. Projemiz için gereken kodları teker teker girip çalıştırın.
	7. Datalar çok yüksek veride olduğu için kod kısmında dataların %10 ununu kullanarak çalıştırın.
	8. Sonuçlar için bekleyin.
---

## Katkılar

	1. https://chat.openai.com/
	2. https://github.com/balfatih/YAZ20411_Derin_Ogrenme/blob/main/Week%20%2311/19122023_Derin_Ogrenme_Online_Dersi.ipynb
	3. https://github.com/anjanatiha/Pneumonia-Detection-from-Chest-X-Ray-Images-with-Deep-Learning
	4. https://www.kaggle.com/code/mellonixie/image-classification-cnn-hyperparameter-tuning
	5. https://machinelearningmastery.com/grid-search-hyperparameters-deep-learning-models-python-keras/
	
---

## İletişim

Proje ile ilgili iletişim bilgileri veya bağlantılarınızı ekleyin. Örneğin, e-posta adresleri, sosyal medya hesapları vb.
