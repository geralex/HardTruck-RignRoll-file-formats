# Описание

Описание бинарных форматов игр  **Дальнобойщики 1**, **Дальнобойщики 2** (версия 8) и **Дальнобойщики 3**. Для каждого формата доступен (в процессе) шаблон шестнадцатиричного редактора **010 Editor**, который описывает структуры формата, а также дополнительные скрипты для работы с форматами. 

Текущий прогресс [Issues](https://github.com/AlexKimov/HT2-RnR-tools/issues). Описание форматов [Вики страница](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/wiki).

#### Текущие планы

##### Дальнобойщики 1/2
1. **b3D**.

2. Импорт/экспорт форматов.

3. Документации на форматы.

### Форматы файлов

#### Дальнобойщики 1 (1998)

| № | Формат | Прогресс  | Шаблон (010 Editor) | Описание | О формате |
| :-- | :------- | :-- | :-- | :-- | :-- |
|  **1**  |  .b3D**  |   [b3D](https://github.com/AlexKimov/HT2-RnR-tools/issues/2)  | [b3D.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/B3D.bt) | [Wiki](https://github.com/AlexKimov/HT2-RnR-tools/wiki/b3D-File-Format-Rus) | 3D объекты и объекты игровой логики (модели коллизий, порталы, объекты освещения и т.п.) |
|  **2**  | .MSK | [MSK](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/issues/1) |  [MSK.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/MSK.bt) | [WIKI](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/wiki/MSK-File-Format-Rus)  | 8 битные файлы масок, хранятся в архиве .RMP | 
|  **3**  | .PLM | [PLM](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/issues/7) |  [PLM.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/PLM.bt) |  [WIKI](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/wiki/PLM-File-Format-Rus) | Палитра и что-то еще, хранятся в архиве .RMP | 
|  **4**  | .RMP* | [RMP](https://github.com/AlexKimov/HT2-RnR-tools/issues/3) |  [RES.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/RES.bt) | [WIKI](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/wiki/RES-RMP-File-Format-RUS)  | Архив ресурсов (звуки, текстуры) | 
| **5**  | .TXR | [TXR](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/issues/6) |  [TXR.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/TXR.bt) | [WIKI](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/wiki/TXR-File-Format-RUS)  | Текстура | 

    * Формат аналогичен формату RES из второй части игры (Дальнобойщики 2)
    ** Формат аналогичен формату b3D из второй части игры (Дальнобойщики 2), ну или наоборот

#### Дальнобойщики 2 (версия 8)

| № | Формат | Прогресс  | Шаблон (010 Editor) | Описание | О формате |
| :-- | :------- | :-- | :-- | :-- | :-- |
|  **1**  |  .b3D  |   [b3D](https://github.com/AlexKimov/HT2-RnR-tools/issues/2)  | [b3D.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/B3D.bt) | [Wiki](https://github.com/AlexKimov/HT2-RnR-tools/wiki/b3D-File-Format-Rus) | 3D объекты и объекты игровой логики (модели коллизий, порталы, объекты освещения и т.п.) |
|  **2**  | .MSK | [MSK](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/issues/1) |  [MSK.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/MSK.bt) | [Вики](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/wiki/MSK-File-Format-Rus)  | 8/16 битные файлы масок, хранятся в архиве .RES | 
|  **3**  | .PLM | [PLM](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/issues/7) |  [PLM.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/PLM.bt) |  [WIKI](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/wiki/PLM-File-Format-Rus) | Палитра, хранится в архиве .RES | 
|  **4**  | .RAW | [RAW](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/issues/8) |  | [WIKI](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/wiki/RAW-File-Format-RUS)  |  Карты высот | 
|  **5**  | .RES | [RES](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/issues/3) |  [RES.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/RES.bt) | [WIKI](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/wiki/RES-RMP-File-Format-RUS)  | Архив ресурсов (звуки, текстуры) | 
|  **6**  | .TECH | [TECH](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/issues/9) |  [TECH.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/TECH.bt) |   | Параметры транспортных средств | 
|  **7**  | .TXR | [TXR](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/issues/6)  |  [TXR.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/TXR.bt) |   [WIKI](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/wiki/TXR-File-Format-RUS) | Текстура | 
|  **8**  | .WAY | [WAY](https://github.com/AlexKimov/HT2-RnR-tools/issues/4)  | [WAY.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/WAY.bt) |  | Пути для транспорта под управлением ИИ | 

#### Дальнобойщики 3
| № | Формат | Прогресс  | Шаблон |  Описание   |
| :-- | :------- | :-- | :-- | :-- |
|  **1**  |  .WMD  |     | [WMD.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/WDB.bt) | 3D объекты и объекты игровой логики (модели коллизий, порталы, объекты освещения и т.п.) |

### Скрипты

#### 3dsMax
* [raw_to_level_surface.ms]() - скрипт создания поверхности уровня из игры Дальнобойщики 2 на основе файлов **.raw**;
* [raw_export.ms]() - скрипт экспорта в формат **.raw** игры Дальнобойщики 2;
* [raw_import.ms]() - скрипт для импорта данных карты высот **.raw** игры Дальнобойщики 2;
* [material_to_txr_msk.ms]() - скрипт для создания материала из файлов формата **.txr** и **.msk** игры Дальнобойщики 1/2;

#### 010 Editor
* [UnpackResource.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/UnpackResource.1sc) - скрипт 010 Editor для распаковки файлов из игровых ресурсов (**.RES/.RMP**) 
* [mskConversion.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/mskConversion.1sc) - скрипт 010 Editor для конвертирования файлов масок **.msk** игры **Дальнобойщики 1/2** в формат **.tga** или **.bmp**. 
* [PLMtoTGA.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/PLMtoTGA.1sc) - скрипт 010 Editor для конвертирования **.plm** файлов игры Дальнобойщики 1 в формат **.tga**. 
* [TXRtoBMP.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/TXRtoBMP.1sc) - скрипт 010 Editor для конвертирования **.txr** файлов игры **Дальнобойщики 2** в формат **.bmp**. 
* [RawToBMP.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/RawToBMP.1sc) - скрипт конвертирует **.RAW** (карта высот) файл в 8 битное изображение (оттенки серого) в формате **bmp**.
* [RawToObj.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/RawToObj.1sc) - скрипт конвертирует **.RAW** (карта высот) файл в **.obj**.
* [decodeSCH.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/decodeSCH.1sc) - скрипт  для расшифровки зашифрованных **SCH** и **CNF** файлов.
* [KeyGenerator.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/KeyGenerator.1sc) - скрипт для генерации файла ключа для расшифровки **SCH** файлов.
* [b3dToobj.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/b3dToobj.1sc) - скрипт  для конвертирования **B3D** файлов в набор файлов формата **.obj** (в работе).
* [TechToTCH.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/TechToTCH.1sc) - скрипт конвертирования данных из vehicle.tech в исходную текстовую форму.
* [REStoPRO.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/REStoPRO.1sc) - скрипт конвертирования файлов ресурсов **.res** в **.pro**.

## Спасибо
Юрий Гладышенко

## Другие игры

1. [Игры на движке Storm 1: Корсары (2000), Age of Sail 2, Рыцари морей (2001)](https://github.com/AlexKimov/seadogs-file-formats)

2. [Серия Hitman: Hitman Сodename 47, Hitman 2 Silent Assassin](https://github.com/AlexKimov/hitman-file-formats)

3. [Игры Red Storm Ent: Rainbow Six 1/2, Ghost Recon (2001) и др.](https://github.com/AlexKimov/RSE-file-formats)

* * * 
# About
Hard Truck 1 (1998), Hard Truck 2 King of the Road 1.3 and RignRoll (2010) games file formats. Current progress status [see Issues](https://github.com/AlexKimov/HT2-RnR-tools/issues). 

Formats description will be [there (Wiki)](https://github.com/AlexKimov/HT2-RnR-tools/wiki).

#### Roadmap

###### Hard Truck 1/2
1. **b3D** format, evereything else is ready to use (almost).

2. Formats documentation in english.

3. Conversion to other formats.

#### Hard Truck 1 (1998)

| № | Format/Ext | Progress   | Template (010 Editor) |  Description   |
| :-- | :------- | :-- | :-- | :-- | 
|  **1**  |  .b3D**  |   [b3D](https://github.com/AlexKimov/HT2-RnR-tools/issues/2)  | [b3D.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/B3D.bt) | Game logic and 3D objects |
|  **2**  | .RMP* | [RMP](https://github.com/AlexKimov/HT2-RnR-tools/issues/3) |  [RES.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/RES.bt) | Resource archive: sounds, textures | 
|  **3**  | .PLM | [PLM](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/issues/7) | [PLM.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/PLM.bt) |   Palette | 
|  **4**  | .MSK | [MSK](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/issues/1)  |  [MSK.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/MSK.bt) |    Texture Masks, 8-bit with palette | 
|  **5**  | .TXR | [TXR](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/issues/6) |  [TXR.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/TXR.bt) |    Texture file |

    *  almost the same as RES format from Hard Truck 2
    **  b3D format from Hard Truck 2 has the same structure, but there are some differences

#### Hard Truck 2 King of the Road (2002)
| № | Format/Ext | Progress   | Template (010 Editor) |  Description   |
| :-- | :------- | :-- | :-- | :-- |
|  **1**  | .b3D |   [b3D](https://github.com/AlexKimov/HT2-RnR-tools/issues/2)  | [b3D.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/B3D.bt) | Game logic and 3D objects |
|  **2**  | .MSK | [MSK](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/issues/1) |  [MSK.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/MSK.bt) |    Mask files stored in .RES | 
|  **3**  | .PLM | [PLM](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/issues/7) |  [PLM.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/PLM.bt) |    Palette file in .RES | 
|  **4**  | .RAW | [RAW](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/issues/8) |   [RAW.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/RAW.bt) |  Heightmaps | 
|  **5**  | .RES | [RES](https://github.com/AlexKimov/HT2-RnR-tools/issues/3)   | [RES.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/RES.bt) | Resource archive: sounds, textures | 
|  **6**  | .TECH | [TECH](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/issues/9)  |  [TECH.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/TECH.bt) |   Vehicle params | 
|  **7**  | .TXR | [TXR](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/issues/6) |  [TXR.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/TXR.bt) |   Texture file |
|  **8**  | .WAY | [WAY](https://github.com/AlexKimov/HT2-RnR-tools/issues/4)   | [WAY.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/WAY.bt) | AI waypoints | 

#### RignRoll (2010)
| № | Format/Ext | Progress   | Template (010 Editor) |  Description   |
| :-- | :------- | :-- | :-- | :-- |
|  **1**  |  .WMD  |   WIP  | [WMD.bt](https://github.com/AlexKimov/HT2-modding-tools/blob/master/formats/templates/WDB.bt) | Game logic and 3D objects |

### Scripts

* [UnpackResource.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/UnpackResource.1sc) - unpack files from (**.RES/.RMP**) game archives (010 Editor)
* [mskConversion.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/mskConversion.1sc) - **.msk** to **.tga** conversion script (010 Editor) 
* [PLMtoTGA.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/PLMtoTGA.1sc) - **.plm** to **.tga** conversion script (010 Editor) 
* [TXRtoBMP.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/TXRtoBMP.1sc) - **.txr* to **.bmp* conversion script (010 Editor) 
* [RawToBMP.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/RawToBMP.1sc) - **.raw* (HeightMap) to **.bmp** conversion script (010 Editor) 
* [RawToObj.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/RawToObj.1sc) -  **.raw* (HeightMap) to **.obj* conversion script (010 Editor) 
* [decodeSCH.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/decodeSCH.1sc) - decode encrypted **SCH** and **CNF** files, about key file see below.
* [KeyGenerator.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/KeyGenerator.1sc) - key file generation script.
* [b3dToobj.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/b3dToobj.1sc) - convert **B3D** file to set of **.obj** files (WIP).
* [TechToTCH.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/TechToTCH.1sc) - convert data from vehicle.tech to source text data.
* [REStoPRO.1sc](https://github.com/AlexKimov/HardTruck-RignRoll-file-formats/blob/master/scripts/REStoPRO.1sc) - **.res** files to **.pro** format.

## More formats

1. [Sea dogs (2000), Age of Sail 2 (2001)](https://github.com/AlexKimov/seadogs-file-formats)

2. [Hitman Сodename 47, Hitman 2 Silent Assassin](https://github.com/AlexKimov/hitman-file-formats)

3. [Red Storm Ent games: Rainbow Six 1/2, Ghost Recon (2001) and other](https://github.com/AlexKimov/RSE-file-formats)
