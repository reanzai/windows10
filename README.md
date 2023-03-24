# windows10
windows 10 ile gelen uygulamaları otomatik kaldırmaya yarıyor teker teker power sheel e yazmaktansa böyle birşey yaptım

NOT: Yönetici OLARAK ÇALIŞTIRIN


Kolaylık : Hazırladığımız Listeyi Kullanarak Belirli Uygulamaları Kaldırmak
Aşağıda hazırladığımız komutları kullanarak ismi belirtilen uygulamayı kolaylıkla kaldırmanız mümkün.

3D Builder                 : get-appxpackage *3dbuilder* | remove-appxpackage

3D Görüntüleyicisi      : get-appxpackage *3d* | remove-appxpackage

Alarmlar ve Saat        :   get-appxpackage *alarms* | remove-appxpackage

Başlarken ya da İpuçları : get-appxpackage *getstarted* | remove-appxpackage

Finans                       : get-appxpackage *bingfinance* | remove-appxpackage

Finans, Spor, Hava Durumu, Spor : get-appxpackage *bing* | remove-appxpackage

Fotoğraflar               : get-appxpackage *photos* | remove-appxpackage

Geri Bildirim              : get-appxpackage *feedback* | remove-appxpackage

Haritalar                    : get-appxpackage *maps* | remove-appxpackage

Hesap Makinesi          : get-appxpackage *calculator* | remove-appxpackage

Kamera                     : get-appxpackage *camera* | remove-appxpackage

Kişiler                       : get-appxpackage *people* | remove-appxpackage

Mesajlaşma ve Skype Video : get-appxpackage *messaging* | remove-appxpackage

Microsoft Solitaire      : get-appxpackage *solitaire* | remove-appxpackage

Microsoft Wallet         : get-appxpackage *wallet* | remove-appxpackage

Microsoft Wi-Fi        : get-appxpackage *connectivitystore* | remove-appxpackage

Müzik ve Filmler & TV : get-appxpackage *zune* | remove-appxpackage

Office’i Edinin            : get-appxpackage *officehub* | remove-appxpackage

OneNote                   : get-appxpackage *onenote* | remove-appxpackage

Paint 3D                   : get-appxpackage *mspaint* | remove-appxpackage

Ses Kaydedici           : get-appxpackage *soundrecorder* | remove-appxpackage

Skype’ı Edinin           : get-appxpackage *skypeapp* | remove-appxpackage

Sway                       : get-appxpackage *sway* | remove-appxpackage

Takvim ve Posta     : get-appxpackage *communicationsapps* | remove-appxpackage

Telefon                     : get-appxpackage *commsphone* | remove-appxpackage

Telefon Eşitleyicisi     : get-appxpackage *windowsphone* | remove-appxpackage

Uygulama Bağlayıcısı  : get-appxpackage *appconnector* | remove-appxpackage

Uygulama Yükleyicisi  : get-appxpackage *appinstaller* | remove-appxpackage

Ücretli Wi-Fi & Hücresel : get-appxpackage *oneconnect* | remove-appxpackage

Windows Holografik  : get-appxpackage *holographic* | remove-appxpackage

Xbox                       :get-appxpackage *xbox* | remove-appxpackage

Yapışkan Notlar        : get-appxpackage *sticky* | remove-appxpackage
