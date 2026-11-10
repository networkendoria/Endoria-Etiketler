# Endoria Network - Rütbe Etiketleri

Sunucudaki rütbe etiketlerinin kaynak paketi ve ayar dosyaları.

| Dosya | Ne işe yarar |
|---|---|
| `Endoria-Etiketler.zip` | Oyuncuya otomatik inen kaynak paketi (etiket görselleri) |
| `pack-source/` | Kaynak paketinin açık hali (düzenlemek için) |
| `orijinal-etiketler/` | Kesilmiş orijinal etiket PNG'leri |
| `tab/groups.yml` | TAB plugin ayarı (kafa üstü + tab listesi) |
| `luckperms-komutlari.txt` | Grupları oluşturma ve rütbe verme komutları |

## Etiket karakterleri

| Grup | Karakter |
|---|---|
| kurucu | `` |
| admin | `` |
| vip | `` |
| rehber | `` |
| moderator | `` |
| icerikureticisi | `` |
| uye | `` |

## server.properties

```
resource-pack=https://raw.githubusercontent.com/networkendoria/Endoria-Etiketler/main/Endoria-Etiketler.zip
resource-pack-sha1=f0f296b45a53c30a2b754ffa533532a5992bd8fb
require-resource-pack=true
resource-pack-prompt={"text":"Rütbe etiketlerini görmek için kaynak paketini kabul et!"}
```

Zip her değiştiğinde SHA-1 de değişir, yukarıdaki değer güncellenmelidir.

## Sunucu kurulumu

- Sunucu: Paper **26.2** (Java 25 gerekir)
- Oyuncu aralığı: **1.18 – 26.1** (26.2 oyuncuları da girer)
- Pluginler (`plugins/` klasörüne): LuckPerms, TAB (26.2 uyumlu jar), ViaVersion, ViaBackwards
- Sıra: pluginleri koy → sunucuyu aç → `luckperms-komutlari.txt` komutlarını yaz → `tab/groups.yml` dosyasını `plugins/TAB/` içine koy → `/tab reload`
