---
title: Objects in R
localeTitle: كائنات في R
---## شاء

تسمح R بحفظ البيانات عن طريق تخزينها داخل كائن R.

## ما هو كائن؟

إنه مجرد اسم يمكنك استخدامه لاستدعاء البيانات المخزنة. على سبيل المثال ، يمكنك حفظ البيانات في كائن مثل a أو b.

 `> a <- 5 
 > a 
 [1] 5 
` 

## كيفية إنشاء كائن في R؟

1.  لإنشاء كائن R ، اختر اسمًا ثم استخدم الرمز الأقل من ، `<` ، متبوعًا بعلامة السالب ، `-` لحفظ البيانات فيه. هذه المجموعة تبدو وكأنها السهم ، `<-` . سوف يجعل R كائنًا ، ويعطيه اسمك ، ويخزن فيه أي شيء يتبع السهم.
    
2.  عندما تسأل R ماذا يوجد في ، فإنها تخبرك في السطر التالي. فمثلا:
    

 `> die <- 1:6 
 > die 
 [1] 1 2 3 4 5 6 
` 

3.  يمكنك تسمية كائن في R تقريبًا أي شيء تريده ، ولكن هناك بعض القواعد. أول، لا يمكن أن يبدأ الاسم برقم. ثانيًا ، لا يمكن لاسم ما استخدام بعض الرموز الخاصة ، مثل `^, !, $, @, +, -, /, or *` :
    
4.  يفهم R أيضًا الكتابة بالأحرف الكبيرة (أو حساس لحالة الأحرف) ، لذلك سيشير الاسم والاسم إلى كائنات مختلفة.
    
5.  يمكنك رؤية أسماء الكائنات التي استخدمتها بالفعل مع الدالة `ls()` .
    

## المراجع

[المستندات الرسمية](https://cran.r-project.org/manuals.html) [الأشياء في R بواسطة المدونين r](https://www.r-bloggers.com/classes-and-objects-in-r/) [كرا](https://cran.r-project.org/doc/manuals/r-release/R-lang.html)