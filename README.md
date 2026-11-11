# جلد کتاب‌های مینی‌اپ کتابخانهٔ تلگرامی

جلدهای کوچک (WebP، عرض ۲۰۰ پیکسل) برای مینی‌اپ [telegram-library-miniapp](https://github.com/saeedshariati1351/telegram-library-miniapp).

- `covers/<id // 1000>/<id>.webp` — جلد هر کتاب (شناسهٔ کتاب همان شناسهٔ داده‌های مینی‌اپ است)
- `cv.json` — بیت‌مپ کتاب‌های دارای جلد
- `tools/scrape_covers.py` + `.github/workflows/covers.yml` — دانلود خودکار جلدها از پیش‌نمایش عمومی پست‌های تلگرام
