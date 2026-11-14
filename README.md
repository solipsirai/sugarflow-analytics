# SugarFlow Analytics

[Download the source package / Kaynak paketini indir](sugarflow-analytics-source.zip)

Extract the ZIP before running the setup commands. / Kurulum komutlarından önce ZIP dosyasını açın.

## English

A commodity dashboard with a global sugar crop calendar, planting and harvest windows, sugar–ethanol parity, and wheat and corn monitors. The application also includes weather, COT and market-data views. Some screens use illustrative values, and external feeds may be delayed or unavailable.

Use Node.js 22.13 or later and npm. Run `npm ci`, then `npm run dev` and open the local address printed in the terminal. On Linux with GNU coreutils, run `npm test` to build and check the rendered application.

The source package contains no live Site configuration, database dump or browser import history. Data imported through the browser remains in that browser’s storage. The application’s data routes request external sources such as weather and market feeds.

## Türkçe

Küresel şeker mahsul takvimini, ekim ve hasat dönemlerini, şeker–etanol paritesini ve buğday ile mısır izleme ekranlarını bir araya getiren emtia paneli. Hava durumu, COT ve piyasa verisi ekranları da bulunur. Bazı ekranlar temsili değerler kullanır. Dış kaynaklar gecikebilir veya yanıt vermeyebilir.

Node.js 22.13 veya üzeri ve npm ile `npm ci`, ardından `npm run dev` çalıştırın. Terminal’de gösterilen yerel adresi açın. GNU coreutils bulunan Linux’ta derleme ve sayfa kontrolleri için `npm test` çalıştırın.

Kaynak paketi canlı Sites yapılandırması, veritabanı dökümü veya tarayıcıya aktarılmış kullanıcı verisi içermez. Tarayıcıdan içe aktarılan veriler ilgili tarayıcıda tutulur. Veri uç noktaları hava durumu ve piyasa verisi gibi dış kaynaklara istek gönderir.

⚠️ Disclaimer

This project is for educational and engineering research purposes only. It does not constitute financial advice. The developer is not responsible for any financial losses incurred from using this bot or its signals. Trade at your own risk.

⚖️ Yasal Uyarı (Disclaimer)

Bu yazılım tamamen açık kaynaklı bir mühendislik ve veri bilimi araştırma projesi (Proof of Concept) olarak tasarlanmıştır. Çıktıların hiçbiri bir ticaret sistemi teklifi veya finansal yatırım tavsiyesi (YTD) niteliği taşımaz. Finansal piyasalar doğası gereği yüksek risk içerir, projenin kullanımı sonucu doğabilecek kâr veya zararlardan kodun geliştiricileri veya katkıda bulunanlar sorumlu tutulamaz. Yazılımı kullanmadan önce daima kendi risk analizinizi ve testlerinizi gerçekleştirmeniz önerilir.
