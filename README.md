# Arduino_UNO-PN532_I2C

for Arduino UNO
use I2C (SDA, SCL)
https://github.com/kitazaki/Arduino_UNO-PN532_I2C/blob/main/UNO_FeliCa_card_read_I2C_01.ino


for Pro Micro (Arduino Leonardo) 5V / 16MHz
use I2C (SDA:PIN 2, SCL:PIN 3)
https://github.com/kitazaki/Arduino_UNO-PN532_I2C/blob/main/Pro_Micro_FeliCa_card_read_I2C_01.ino

USB Micro Bコネクタが取れやすいので、裏面でブレッドボードへ挿入
          VCC(右から4番目)
12345678901234
OOOOOOOOOOOO
            |
            |→ USB Micro B
            |
OOOOOOOOOOOO
12345678901234
      SCL(右から6番目)
        SDA(右から5番目)
          SCL(右から4番目)
          
