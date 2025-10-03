# 📊 Aholi salomatligi va atrof-muhit statistikasi

## 🔹 Loyihaning bosqichlari (MIT-ECG shabloni asosida)

1. **Muhit va kutubxonalar**
   - Python: `pandas`, `requests`, `wbdata`, `matplotlib/plotly`, `geopandas`, `statsmodels/prophet`, `sklearn`

2. **Ma’lumotlarni yuklash**
   - **WHO GHO OData API**: `https://ghoapi.azureedge.net/api/`
   - **World Bank Indicators API**: `wbdata.get_data()`

3. **Oldindan qayta ishlash**
   - Vaqt bo‘yicha formatlash
   - `country-code` bilan birlashtirish
   - NaN qiymatlarni boshqarish (`dropna` / `imputation`)
   - Indikator birliklarini moslashtirish

4. **Xususiyatlar va agregatsiyalar**
   - Oxirgi 5 yil **o‘rtacha umr kutish**
   - **Yillik o‘zgarish foizi**
   - **Sog‘liq xarajatlari (%GDP)**
   - **U5MR (5 yoshgacha o‘lim)** o‘rtacha

5. **Tahlil & Vizualizatsiya**
   - **Vaqt qatori tahlili**
   - **Heatmap (Country × Year)**
   - **Choropleth xaritalar**

6. **Modellash (ixtiyoriy)**
   - Trend forecasting (**Prophet, ARIMA**)
   - Clustering (**country profiling**)
   - Regressiya (**sog‘liq xarajatlari → umr kutish**)

7. **Baholash & hisobot**
   - KPIlar
   - Grafiklar
   - CSV/Excel eksport

8. **Etika & litsenziya**
   - WHO va World Bank ma’lumotlari **ochiq ma’lumot** bo‘lsa-da, **attribution** va **litsenziya** talab etiladi.

---

## 🔹 Tanlangan indikatorlar

- **Umr davomiyligi (Life expectancy at birth)** → `SP.DYN.LE00.IN`
- **Chaqaloqlar va 5 yoshgacha o‘lim (Infant/U5MR mortality)** → `SP.DYN.IMRT.IN`, `SH.DYN.MORT`
- **Sog‘liq xarajatlari (%GDP)** → `SH.XPD.CHEX.GD.ZS`
- **Onalar o‘limi (Maternal mortality)** → `SH.STA.MMRT`
- **DALYs, GHE seriyalari** (WHO GHO)

---

## 🔹 Vizual natijalar (misollar)

### 1. Umr davomiyligi taqqoslash (2000–2023)
📈 O‘zbekiston, AQSh, Xitoy, Rossiya, Qozog‘iston bo‘yicha grafik chizildi.  
📊 Jadvalda **o‘sish (%) va yil bo‘yicha farq** ko‘rsatildi.

### 2. Kasalliklar tarqalishi
- Eng ko‘p uchraydigan kasalliklar (yurak-qon tomir, saraton, diabet).
- Yosh guruhlari bo‘yicha taqqoslash (0–14, 15–24, 25–44, 45–64, 65+).
- Jins bo‘yicha taqqoslash (erkak–ayol).

### 3. Infratuzilma
- Shifoxonalar va poliklinikalar soni viloyatlar bo‘yicha.
- Shifokorlar, diagnostika markazlari va mobil brigadalar statistikasi.

### 4. Nikoh va ajrimlar
- 2024–2025 yillarda nikoh va ajrimlar dinamikasi.
- Erkaklar va ayollarda nikoh yoshi tendensiyalari.

### 5. Ekologiya va salomatlik
- PM2.5 ifloslanishi va nafas kasalliklari soni o‘rtasida **korrelyatsiya (r = 0.97)** aniqlandi.
- Choralar (toza suv, sport, oziq-ovqat xavfsizligi, tibbiy xizmat) ta’siri vizual ko‘rsatildi.

---

## 🔹 Umumiy Xulosa: Aholi salomatligi va atrof-muhit

1. **Sog‘lom aholi – rivojlangan jamiyatning asosi**  
   - Tibbiy xizmatlar, toza suv, oziq-ovqat xavfsizligi, sog‘lom turmush tarzi eng muhim omillar.

2. **Yosh va jinsga qarab farqlilik**  
   - Erkaklar va ayollar uchun optimal nikoh yoshi va sog‘lom turmush omillari turlicha.

3. **Kasalliklar va pandemiyalar**  
   - COVID va OITS bo‘yicha statistikalar profilaktika va ta’lim zarurligini ko‘rsatadi.

4. **Atrof-muhitning roli**  
   - Havo ifloslanishi aholi salomatligiga kuchli ta’sir qiladi. Daraxt ekish va chiqindilarni kamaytirish muhim.

5. **Profilaktika va sog‘lom turmush tarzi**  
   - Sport, ta’lim va axborot kampaniyalari tibbiy xarajatlarni kamaytiradi va aholi sog‘lig‘ini yaxshilaydi.

---

## 📌 Foydalanilgan manbalar

- 🌍 [World Bank Data API](https://data.worldbank.org/)
- 🏥 [WHO Global Health Observatory (GHO) API](https://ghoapi.azureedge.net/api/)
- 📑 Statistika qo‘mitalari, O‘zbekiston davlat hisobotlari
- 🔬 Python kutubxonalari: `pandas`, `matplotlib`, `wbdata`, `requests`

---
