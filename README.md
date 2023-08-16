# lung_tumor_yolo_detection
*English:*
Lung Tumor Detection YOLO Model

This project encompasses a YOLO (You Only Look Once) model for detecting lung tumors, utilizing deep learning and object detection techniques. The YOLO model is a popular approach that simultaneously runs a single classifier and a bounding box regressor to efficiently detect objects in real time.

Project Objectives:
- Automatically detect lung tumors in chest X-ray images.
- Showcase the applicability of deep learning techniques in the field of medical imaging.
- Train the YOLO model on a curated dataset and evaluate its performance.

What We're Doing:
- Training the YOLO model using a pre-collected large dataset of chest X-ray images.
- Experimenting with various hyperparameters to achieve optimal results.
- Evaluating the trained model on test data and measuring detection accuracy.
- If results are promising, planning to assess the model's performance on real-world data.

How You Can Contribute:
1. Fork this repository to make your own improvements and add new features.
2. Review the existing code to fix bugs and propose enhancements.
3. Contribute by collecting new and improved datasets or expanding the current dataset.
4. Offer suggestions for improving the model's performance.

Important Contribution Notes:
- Due to the medical imaging context, be mindful of ethical considerations and privacy.
- Kindly initiate discussions by opening an issue for major changes.

The purpose of the project is for educational and research purposes only. The results obtained do not substitute professional medical evaluation. For more information, please refer to the Usage and License sections.

*Türkçe:*
Akciğer Tümörü Tespiti YOLO Modeli

Bu proje, derin öğrenme ve nesne tespiti yöntemlerini kullanarak akciğer tümörlerini tespit etmek için YOLO (You Only Look Once) modelini içerir. YOLO modeli, tek bir sınıflandırıcı ve yer belirleyici ağı aynı anda çalıştırarak nesneleri gerçek zamanlı olarak tespit etmek için popüler bir yöntemdir.

Projenin Amaçları:
- Göğüs röntgen görüntülerindeki akciğer tümörlerini otomatik olarak tespit etmek.
- Tıbbi görüntüleme alanında derin öğrenme tekniklerinin uygulanabilirliğini göstermek.
- Toplanan veri kümesi üzerinde YOLO modelinin eğitilmesi ve sonuçlarının değerlendirilmesi.

Neler Yapıyoruz:
- Önceden toplanmış büyük bir göğüs röntgeni veri kümesini kullanarak YOLO modelini eğitiyoruz.
- Modeli farklı hiperparametrelerle eğiterek en iyi sonuçları elde etmek için çaba sarf ediyoruz.
- Eğitilen modeli test verileri üzerinde değerlendiriyor ve tespit sonuçlarını ölçüyoruz.
- Eğer elde ettiğimiz sonuçlar tatmin edici ise, gerçek dünya verileri üzerinde de modelin performansını test etmeyi planlıyoruz.

Nasıl Katkı Sağlayabilirsiniz:
1. Bu repo'yu fork ederek kendiniz geliştirmeler yapabilir ve yeni özellikler ekleyebilirsiniz.
2. Varolan kodu inceleyerek hataları düzeltebilir ve iyileştirmeler önerebilirsiniz.
3. Yeni ve daha iyi veri kümesi toplama veya mevcut veri kümesini genişletme konusunda katkıda bulunabilirsiniz.
4. Modelin performansını artırmak için yeni önerilerde bulunabilirsiniz.

Lütfen Katkı Yaparken Dikkat Edilmesi Gerekenler:
- Tıbbi görüntüleme ile ilgili olduğumuz için, etik kurallara ve gizliliğe özen göstermemiz gerektiğini unutmayın.
- Büyük değişiklikler yapmadan önce tartışma amaçlı bir "issue" açarak görüş alışverişinde bulunmanızı rica ederiz.

Projenin Amacı sadece eğitim ve araştırma amaçlıdır. Elde edilen sonuçlar profesyonel tıbbi değerlendirmeyi asla yerine koymamaktadır. Daha fazla bilgi için lütfen Kullanım Şartları ve Lisans bölümlerini inceleyiniz.

**English:**
**Creation of Custom Dataset for Lung Tumor Detection**

In this project, a custom dataset for lung tumor detection was curated using data obtained from the medicaldecathlon website. Out of a total of 96 patient data samples, 64 contained annotated regions representing tumor areas. Using the MRIcro application, these annotated regions were extracted, resulting in a total of 1420 tumor images.

The dataset creation process was facilitated through the makesense.ai platform. This platform enabled the annotation and labeling of tumor regions within the images. This approach aims to enhance the deep learning model's comprehension of the data, ensuring accurate detection of tumors.

This specialized dataset was created to improve project performance and provide results closer to real-world data. The generated dataset will be made accessible to the open-source community.

**Türkçe:**
**Akciğer Tümörü Tespiti İçin Özel Veri Seti Oluşturulması**

Bu proje kapsamında, medicaldecathlon.com sitesinden elde edilen veri setini kullanarak akciğer tümörü tespiti için özel bir veri seti oluşturulmuştur. Toplamda 96 hasta verisini içeren bu setten, 64 tanesi işaretli ve tümörlü bölgeleri içermekteydi. MRIcro uygulaması aracılığıyla bu işaretli bölgeler ayrıştırılarak toplamda 1420 tümörlü görüntü elde edilmiştir.

Veri seti oluşturma süreci makesense.ai platformu kullanılarak gerçekleştirilmiştir. Bu platform sayesinde görüntülerdeki tümörlü bölgeler işaretlenmiş ve etiketlenmiştir. Bu sayede derin öğrenme modelinin veriyi anlaması ve tümörleri doğru bir şekilde tespit etmesi amaçlanmıştır.

Bu özel veri seti, projenin daha iyi performans elde etmesi ve gerçek dünya verilerine daha yakın sonuçlar sunması amacıyla oluşturulmuştur. Oluşturulan veri seti, açık kaynak topluluğu tarafından erişilebilir hale getirilecektir.

***English:***
***Data Annotation and Training Preparations for Lung Tumor Detection***

As part of this project, the annotation process for the dataset obtained from the medicaldecathlon website has been completed using the makesense.ai platform. Out of a total of 96 patient data samples, 64 contained regions corresponding to lung tumor areas. Utilizing the MRIcro application, these tumor regions were delineated, resulting in a total of 1420 tumor images.

Following the annotation of the dataset, the decision was made to employ the Google Colab platform for training purposes. Colab notebooks have been created for both YOLOv5x and YOLOv8x model versions, and these notebooks will be shared in the near future.

These preparation steps lay the groundwork for training the deep learning models that will be utilized in the later stages of the project.

***Türkçe:***
***Akciğer Tümörü Tespiti İçin Veri Seti İşaretleme ve Eğitim Hazırlıkları***

Bu projenin bir parçası olarak, medicaldecathlon sitesinden temin edilen veri setinin işaretlenmesi işlemi makesense.ai platformu kullanılarak tamamlanmıştır. Toplamda 96 hasta verisi içeren bu set, içlerinden 64'ü akciğer tümörü bölgelerini içermekteydi. MRIcro uygulaması kullanılarak bu tümörlü bölgeler ayrıştırılmış ve 1420 adet tümörlü görüntü elde edilmiştir.

Veri setinin işaretlenmesinin ardından, eğitim işlemleri için Google Colab platformunu kullanma kararı alınmıştır. YOLOv5x ve YOLOv8x model versiyonları için uygun Colab notebook'ları oluşturulmuş ve yakın gelecekte bu not defterleri paylaşılacaktır.

Bu hazırlık aşamaları, projenin ileri aşamalarında kullanılacak derin öğrenme modellerinin eğitimi için temel oluşturmayı amaçlamaktadır.

