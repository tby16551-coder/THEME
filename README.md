# THEME{
  "name": "متجري العصري",
  "version": "1.0.0",
  "author": "اسمك هنا",
  "settings": [
    {
      "id": "colors",
      "name": "تخصيص الألوان",
      "settings": [
        {
          "id": "primary_color",
          "name": "اللون الرئيسي",
          "type": "color",
          "default": "#2563eb"
        },
        {
          "id": "secondary_color",
          "name": "اللون الثانوي",
          "type": "color",
          "default": "#0f172a"
        }
      ]
    },
    {
      "id": "typography",
      "name": "الخطوط",
      "settings": [
        {
          "id": "font_family",
          "name": "نوع الخط",
          "type": "select",
          "options": [
            { "label": "خط كوفي", "value": "kufi" },
            { "label": "خط النسخ", "value": "naskh" }
          ],
          "default": "kufi"
        }
      ]
    },
    {
      "id": "home_sections",
      "name": "إعدادات الصفحة الرئيسية",
      "settings": [
        {
          "id": "show_slider",
          "name": "إظهار شريط الصور المتحرك (Slider)",
          "type": "checkbox",
          "default": true
        },
        {
          "id": "products_count",
          "name": "عدد المنتجات المعروضة",
          "type": "number",
          "default": 8
        }
      ]
    }
  ]
}
