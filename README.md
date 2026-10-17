# Deck keyboard firmware backup  
Mainly for Deck Francium and Hassium,if you have frigate or others firmware welcome to add.  
This project only restore firmware,please use HY USB Firmware Downloader to flash (Some firmwares needs specific version)  

All firmwares from:
1. www.deckkeyboards.co.kr  
2. www.deckkeyboards.com
3. www.deckkeyboards.cn

## List
### From www.deckkeyboards.co.kr:  
| Firmware-Name | Keyboard-model | TIP
| --- | --- | --- |
| `(87P)L2227V351.bin` | Deck Francium Pro (87P) | F11,F12 Normal firmware |
| `L2086V39.bin` | 108XN/108N/108  | Rhythm Game firmware |
| `L2226V35 (1).bin` | 87XN/87N/87  | Rhythm Game firmware |
| `L2226V351(1).bin` | 87XN/87N/87  | Rhythm Game firmware, F11,F12 Normal |
| `(87XN)L2226V301.bin` | 87XN | F11,F12 Normal firmware |
| `(87-1차)L2226V301.bin` | 87-1차 | F11,F12 Normal firmware |
| `(소닉)L2190V24.bin` | 소닉 | F11,F12 Normal firmware |
| `L2226V301.bin` | 프랑슘 거북선, 라이트, 일반 | F11,F12 Normal firmware |
| `L3414V19.bin` | 108XT | Normal firmware |
| `L3414V194.bin`| 108XT | Rhythm Game firmware |
| `L2086V382.bin` | 108XN / 108N / 108 (108 Deckhassium General) | Rhythm Game firmware |
| `L2226V34.bin` | 87XN / 87N / 87 (87 Deck Francium General) | Rhythm Game firmware |
| `L1983V41.bin` | 108P (108P Decehashium Pro) | Rhythm Game firmware |
| `L2039V38.bin` | 87P (87P Deck Francium Pro) | Rhythm Game firmware |
| `L2504V24.bin` | 108S (108S Deck Mantella RGB) | Rhythm Game firmware |
| `L2039V38(1).bin` | From CBL-87P-240102.zip,Rhythm Game firmware |

### From www.deckkeyboards.com:  
| Firmware-Name | Keyboard-model |
| --- | --- |
| `L2227V35 (1).bin` | Francium Pro CBL87P |
| `L1983V36.bin` | Hassium Pro CBL108P |
| `L2226V28.bin` | Francium Standard CBL87 |
| `L2086V34.bin` | Hassium Standard CBL108 |

### Edit Firmware:  
Due to my own need,@Tkiliay help me edit these firmware for Deck Francium Pro (87P)  

2_nkro-original.bin:
1. Add back NKRO mode switch (use FN + F10),based on `(87P)L2227V351.bin`  

2_nkro2.bin (based on `(87P)L2227V351.bin`):
1. Set NKRO mode by default
2. Allow to switch 6KRO (Use FN + F10)
3. Align F11/F12's light logic with other keys.