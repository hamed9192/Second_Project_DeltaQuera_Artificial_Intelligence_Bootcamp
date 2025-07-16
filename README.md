# Second_Project_DeltaQuera_Artificial_Intelligence_Bootcamp
Second Project, DeltaQuera Artificial Intelligence Bootcamp

-----------------------------------------------------
# مسئله‌ی ۱: دسته‌بندی غذا 

# حامد، علی و محمدحسین 
این پروژه به بررسی تصاویر غدا‌های مختلف در 22 دسته میپردازد آن هم با استفاده از یک مدل pre-trained که 2 بار از قبل آموزش دیده است، یکبار بر روی داده‌های Imagenet و بار دوم بر روی داده‌های food101
## Resnt50
### files for Resnet50 : [Resnet50_food_model,Resnet50_predict]
مدل Resnet50 به دلیل داشتن تعداد مناسبی لایه که به مدل این امکان را میدهد بافت و رنگ غذاها رو به خوبی تشخیص دهد و همچین ساختار بلوکی آن باعث راحتر شدن freeze کردن لایه‌ها متناسب با نیاز شده است

### models for Resnet50 : https://drive.google.com/drive/folders/1YReaMuU8kdZ_W5HdUYomQ6ho5pQlndBR?usp=sharing
 از طریق این لینک میتوانید به مدل آموزش دیده‌ی ما و مدلی که در این پروژه استفاده شده دسترسی داشته باشید

#  مسئله‌ی ۲: تحلیل احساس نظرات 

# مهدی (بخش سوم)، خسرو(بخش اول)، حمید(بخش دوم)
## part 2 : Warranty-Related Review Detection Project

این بخش از پروژه با هدف بررسی و تحلیل نظرات مشتریان درباره‌ی خدمات گارانتی طراحی شده است. هدف، شناسایی نظراتی است که مستقیماً یا به‌طور ضمنی به گارانتی اشاره دارند و تحلیل میزان رضایت کاربران از این خدمات با استفاده از NLP.
### فایل‌های اصلی

#### 221_gensim.ipynb
- آموزش مدل Word2Vec با استفاده از `gensim`
- بررسی کلمات مشابه با "گارانتی" و "وارانتی"

#### 222_vector.ipynb
- استخراج بردارهای جملات با Sentence Transformers
- محاسبه شباهت بین نظرات و جملات مرجع با Cosine Similarity
- فیلتر نظرات مرتبط با گارانتی و تحلیل میانگین رضایت


### ورودی‌ها

- فایل CSV شامل ستون‌های:
- (خلاصه نظر) `summary`
- (امتیاز کاربر) `overal`

### خروجی‌ها
- دیتافریم جدید با ستون `similarity_score`
- داده‌های فیلتر شده مرتبط با گارانتی
- میانگین رضایت کاربران از گارانتی
-------


Part 3 : Sentiment Analysis Model

RoBERTa Sentiment Analysis : https://drive.google.com/drive/folders/1yQFVy7C26saZoM4S0sFHuxngQuRWOgi6?usp=sharing


