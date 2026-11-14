# UV-IR Vision Control (Android)

تطبيق Android للتحكم في الكاميرا مع أوضاع محاكاة **IR** و **UV**، مع دعم **النسبة الذهبية φ** و **النسبة العكسية 1/φ**.

## التشغيل السريع
1. افتح المجلد في **Android Studio**
2. Sync Gradle
3. Run على هاتف حقيقي (يفضل)

## package
`com.isnafe.uvircam`

## ملاحظات
- IR و UV هنا **محاكاة بصرية (False Color)** وليست رؤية طيفية علمية.
- معظم الهواتف تملك IR-cut filter.
- للحصول على نتائج أفضل لاحقاً: دعم فلاتر خارجية.

## الملفات الأساسية
- `MainActivity.kt` — الواجهة والتحكم
- `filter/SpectralFilter.kt` — فلاتر IR/UV/Dual
- `ui/PhiOverlayView.kt` — شبكة النسبة الذهبية
