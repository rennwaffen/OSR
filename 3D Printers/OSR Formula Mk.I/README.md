# Open Source Racing x ZeroG Formula Mk. I
![OSR](3D Printers/OSR Formula Mk.I/Images/GIF_20250311_172744_409.gif)
![Miata HL](https://images.squarespace-cdn.com/content/57dad08459cc68194391b1a1/a1f54af1-55d5-4328-a503-8a67fa4bf656/CAD+Headlights+1.jpg?content-type=image%2Fjpeg)
![Miata Headlights](https://images.squarespace-cdn.com/content/57dad08459cc68194391b1a1/1663892229466-XNIIXY0KBNB88MKIOO8C/306937596_10161513524232069_2610873126066207921_n.jpg?content-type=image%2Fjpeg)

## **Note: it is your responsibility to assemble the printer correctly and to adjust the firmware to your specifications. The only available instructions are from ZeroG.**

## Purpose of the Printer:
The Formula is based on the Mercury Zero G Hydra, but optimized for automotive and motorsports applications. Thousands of hours of print time and experimentation have been put into dialing in every component. You will find that many of the parts are shared with the Zero G, however the name of the game here is simple: maximum volumetric flow, and maximum reliability. As such, the base nozzle starts at 0.8. The bed was tested to temperatures up to (but not limited) 130*C. The chamber successfully reaches 60*C using the Amazon heater with an enclosure. 

In this branch, you will find slicer profiles, reference printer configurations, and necessary files. However, majority of the critical parts must be metal. As such, below you will find the exact components used in the making of the printers and their respective variations. 

## Polymer Selection:
From janky PLA to Form Futura's PA12, TPU, ASA, and more - all three configurations were tested using a variety of materials and temperatures upwards of 350C being the upper limit of what the printed hotend parts can handle. Currently I'm working on a CNC variant of the E34M1 hotend mounts for the Mosquito and Takoto, which will be available once progress is made. 

# Bill of Materials (Last Updated 4/5/2025 - Pending Further Additions). 

## Hot End:
### Universal Parts:
- [Fabreeko 24V Heater 70W](https://www.fabreeko.com/products/fabreeko-60w-24v-heater?srsltid=AfmBOoozdKjiOQuUNo_FEz9J3TYCv_DDS0QNRm1hCXwS1jo39ul0f44h)
- [Honeybadger 4010 9600RPM Hotend Fan](https://www.fabreeko.com/products/4010-axial-fan-by-honeybadger?srsltid=AfmBOopAr45WrYiTOUk7Ux27Ixu7Y8nIJ-mkLK3lFwDWFYWaQNNWVIc-)
- [Honeybadger 5015 9200RPM Part Cooling Fan](https://www.fabreeko.com/products/5015-blower-fan-by-honeybadger?srsltid=AfmBOop3LEOPqd6dELBHj_sOuRGwcZMEHqnA25zVPrgHoWKKCBToQkHt&variant=44775115587839)
- [Honeybadger PT1000 Thermistor](https://www.fabreeko.com/products/pt100-thermistor-platinum-resistance?srsltid=AfmBOooEzOugnPixDcv0gieoq0moBoRDn73A_5oCnBfLi5szM1LZlHrm)
- [Mellow PT1000 Thermistor](https://www.aliexpress.us/item/3256807686326412.html?spm=a2g0o.order_list.order_list_main.126.53101802otLhdf&gatewayAdapt=glo2usa)
- [Slice Engineering PT1000 Thermistor](https://www.fabreeko.com/products/rtd-pt1000-by-slice-engineering?srsltid=AfmBOoqlcm5HsY3eCfCecZkZ3-pRkTZmQ2zagGNX0oy3GCkh-4PDXSX8)
- [Slice Engineering Boron Nitride Paste 5cc](https://www.fabreeko.com/products/boron-nitride-paste?srsltid=AfmBOorLpfZejFu-idOKmXkon1eHRwQ1TzapqCaQ65op19RcD9C4_WUL)
- [Slice Engineering 1.5Nm Torque Wrench](https://www.fabreeko.com/products/slice-engineering-nozzle-torque-wrench%E2%84%A2-1-5-nm?srsltid=AfmBOop2H-ak_yc-7Wz44c1RwjeYvECoKxWsZdUD0ljwJh2yuQTOFgqQ)
- [Slice Engineering GammaMaster Nozzle (0.8mm Minimum)](https://www.fabreeko.com/products/gammamaster%C2%AE-nozzle?srsltid=AfmBOoof_qNUhG0ySzSbC-NE90RcohYIA1nrRvxDVCP_TOZQZLSe_uTs)
### LMP3: [Using E34M1 Phaetus UHF Mount](https://jon-harper.github.io/E34M1/modules/hotend/#phaetus-dragon-uhf)
- [Phaetus Dragon](https://www.fabreeko.com/products/phaetus-dragon-uhf?srsltid=AfmBOoqcoVTzXgT83YADDV_rGX35MrsLY_lpfQ2zG5z8-LKBUPJjLrLm)
- [Phaetus Spare Parts](https://www.fabreeko.com/products/phaetus-dragon-uhf-heatblock?srsltid=AfmBOoriewH9_J389VvogW6SXsp6SkAoceoQqMaj9gvD3Zg8zPTGbQae)
### LMP2: [Using the E34M1 x OSR Mosquito Mount](https://jon-harper.github.io/E34M1/modules/hotend/#__tabbed_1_1)
- [Mosquito Magnum Hotend](https://www.fabreeko.com/products/slice-engineering-the-mosquito-magnum-%C2%AE-hotend?srsltid=AfmBOootH0hZ-9DY64MbzT732plqXUqJH2KwYwCor0NiGR0TcxN_4Wth)
### F1 Dual Heater: [Using the E34M1 x OSR Takoto Mount (pending)]()
![F1](https://images.squarespace-cdn.com/content/v1/57dad08459cc68194391b1a1/1741662331148-5ZEPSR3QADV3PCNNEWQ3/PSX_20250310_175809.jpg?format=1000w)
- [Mellow Volcano Adapter](https://www.aliexpress.us/item/3256803827110622.html?spm=a2g0o.order_list.order_list_main.5.53101802otLhdf&gatewayAdapt=glo2usa)
- [Takoto Hotend](https://www.fabreeko.com/products/takoto-hotend?srsltid=AfmBOorwgK6AgN00jKfdAtrDPVv920yZT2iXQqc0eGkQ1dKgSzIS18iq)
- [Slice Engineering Vanadium Nozzle - 1.4mm](https://www.fabreeko.com/products/copy-of-slice-engineering-copperhead%E2%84%A2-hot-block-heat-braker-for-creality?srsltid=AfmBOop4SIAiLKf6Gi6SpnFumPCAMKsph1NaIPLmw6QbAOjZpBsASDaA)
## Extruder (Only optioned using Orbiter or Lancer)
- [LDO Orbiter 2.5](https://www.fabreeko.com/products/ldo-orbiter-extruder-1-75mm?srsltid=AfmBOoqZkG-wY0miGUY8LV_yhGlyKLxCj2dEoxu7WuR2EuvVGBUXYdkC)
- [Peopoly Lancer Orbiter Extruder](https://www.fabreeko.com/products/lancer-extruder-runout-sensor-by-peopoly?srsltid=AfmBOop4EgyAJDk9nIqgC_2tO4GEycm11DQudTqELquBOmFpDkqG5ZHf)

## Chassis:
The printer uses an Ender 5+ as its base. From there, you must source the necessary upgrades. 
- [2020 Side Reinforcements](https://www.amazon.com/2020-Bracket-Aluminum-Extrusion-Connector/dp/B0B15L5YM1/)
- [2040 Side Reinforcements](https://www.amazon.com/Seekliny-Connector-Accessories-Extrusion-Hardware/dp/B0CQ26ZXGG/)
- [2020 Corner Brackets](https://www.amazon.com/uxcell-38x38x18mm-Connectors-Aluminum-Extrusion/dp/B0BY2RBZ33/)
- [Blurolls Z Axis Stepper Mounts](https://www.aliexpress.us/item/3256806944087091.html?spm=a2g0o.order_list.order_list_main.10.53101802otLhdf&gatewayAdapt=glo2usa)
## CoreXY Mechanism:
### Universal Parts:
- [FYSTEC X-Axis Gantry](https://www.aliexpress.us/item/3256806396921029.html?spm=a2g0o.order_list.order_list_main.36.53101802otLhdf&gatewayAdapt=glo2usa)
- [Gates GT3 Belt](https://www.fabreeko.com/products/gates-gt3-open-belt-ll-gt3-6-9-reinforced?srsltid=AfmBOoodXzlpcVqnLBSY9S8waQ-TzPHchU6PNUkKZn4NZOI1EJ7SVloN)
- [Zero G Mecury Conversion Kit](https://www.fabreeko.com/products/mercury-one-kit?srsltid=AfmBOooZG0IlUvTenBxHTilzx0JIuC_xdqZpJqy6Sz_SXX4RnYZ_S_-g)
### 2WD Configuration:
- [Funssor Mercury 2WD Parts](https://www.aliexpress.us/item/3256806160572831.html?spm=a2g0o.order_list.order_list_main.41.53101802otLhdf&gatewayAdapt=glo2usa)
### 4WD Configuration: [See the original GitHub w/ BOM for printed parts, however below you will find links to machined parts as well. Thank you to Stanciu Andrei.](https://github.com/Stanciu-Andrei/UserMods/tree/main/Mercury_One/stanciuandrei_/AWD_Mod/AWD_MotorMounts_Front)
- [Funssor Mercury AWD Parts](https://www.aliexpress.us/item/3256807810508620.html)

## Z Axis:
- [Funssor Z Axis Bed Mounts](https://www.aliexpress.us/item/3256808008220520.html?spm=a2g0o.order_list.order_list_main.20.53101802otLhdf&gatewayAdapt=glo2usa)
- [500mm TR8X8 Steppers](https://www.aliexpress.us/item/3256803579101212.html)
- [Honeybadger Textured Bed](https://www.fabreeko.com/products/open-beta-semi-satin-thin-dual-sided-textured-beds-by-honeybadger?srsltid=AfmBOooJGIyWiH-0rj6tI1F9kozR3OkUj5AvzX4JWZf8ifB053P8zuGT)
- [Honeybadger Magnetic Adhesive 377x377](https://www.fabreeko.com/products/magnetic-sheets-for-pei-beds-with-high-temp-glue?srsltid=AfmBOorLmO4TaLaF8pre6jQWfe3YN-D0xP_zysx9LsXGZIHfQBW52nDi&variant=44519051755775)
- [Zero G ATP5 Beds](https://www.fabreeko.com/products/zero-g-atp5-aluminum-beds-for-ender-5-pro-plus-hydra-conversion?srsltid=AfmBOopLrL5Kycw6PZ4qBN4RKWKlgG-r6A84_RgRE4BP1f1m2k0rH0vX)

## Electrical:
- [BTT EBB36 CAN Board](https://www.aliexpress.us/item/3256804057059361.html?spm=a2g0o.order_list.order_list_main.120.53101802otLhdf&gatewayAdapt=glo2usa)
- [BTT TMC5160T Pro](https://www.aliexpress.us/item/3256803165386565.html?spm=a2g0o.order_list.order_list_main.86.53101802otLhdf&gatewayAdapt=glo2usa)
- [BTT Octopus Pro 1.1 H723](https://www.aliexpress.us/item/3256807309277526.html?spm=a2g0o.order_list.order_list_main.91.53101802otLhdf&gatewayAdapt=glo2usa)
- [BTT Octopus Pro F446](https://www.fabreeko.com/products/btt-octopus-pro-8-driver-mainboard-pre-order?srsltid=AfmBOoowYtayFAMKpLYb8junFFnfblN96kNbKRNzdNyV5PSFTB-T_DUf)
- [Honeybadger Thermal Fuses 150*C](https://www.fabreeko.com/products/alphatherm-thermal-fuses-130-150c?srsltid=AfmBOoqHAoTgzHBY05N-rWFvjUuNtUf_yS591dEGy9QeZpydtvZhfTOb&variant=44752137322751)
- [Honeybadger Cable Sleeves](https://www.fabreeko.com/products/honeybadger-cable-sleeve?srsltid=AfmBOooIRwy1HkTjy9k7jBVgRIwXHwL3Qx2fCmm5BSucLCR_GOJzlzN7)
- [IGUS CF9 Stepper Wire (Overkill)](https://www.digikey.com/en/products/detail/igus/CF9-05-04/18724259)
- [IGUS CF35 CAN Wire](https://www.digikey.com/en/products/detail/igus/CF35-UL-05-04/12353134)
- [Meanwell PSUs - 24V or 48V or both](https://www.aliexpress.us/item/3256807024522999.html?spm=a2g0o.order_list.order_list_main.81.53101802otLhdf&gatewayAdapt=glo2usa)
- [Molex Connector Plug for Beacon](https://www.digikey.com/en/products/detail/molex/0355070400/403470)
- [Molex Connector Terminals for Beacon](https://www.digikey.com/en/products/detail/molex/0502128000/280175)
- [Molex Microfit for CAN](https://www.digikey.com/en/products/detail/molex/0430250400/252497)
- [Molex Microfit Terminals for CAN Small](https://www.digikey.com/en/products/detail/molex/0430300003/1132449)
- [Molex Microfit Terminals for CAN Large](https://www.digikey.com/en/products/detail/molex/0430300040/11503719)
- [OMRON SSR](https://www.fabreeko.com/products/omron-g3nb-210b-1-solid-state-relay-ssr?srsltid=AfmBOoo2WFzuWVt6gPgcf_O3ToJj07PYDpA296fDn1X2SNY-j0fNvEMh)
  
## Hardware & Misc:
- [PINECIL Soldering Iron](https://www.amazon.com/gp/product/B096X6SG13/ref=ppx_yo_dt_b_asin_title_o03_s00?ie=UTF8&psc=1)
- [M3x5x4 Heat Sets](https://www.fabreeko.com/products/threaded-heat-inserts-m3x5x4-100pc-per-bag?srsltid=AfmBOoreBBjgRY4t3ZLNcJIbDFNdxjRM5wcOHx-MkBAcq8jRzTUGp4hN)

# Results Speak for Themselves:
![GS Wide](https://images.squarespace-cdn.com/content/57dad08459cc68194391b1a1/aaba11cd-0132-44ee-8e49-ac5b2298ad4d/gscad.jpg?content-type=image%2Fjpeg)
![GS Wide 2](https://images.squarespace-cdn.com/content/57dad08459cc68194391b1a1/ee6c9699-aabd-4dcb-b46f-a627b55a6ae9/PSX_20230101_133216.jpg?content-type=image%2Fjpeg)
![Miata Wing](https://images.squarespace-cdn.com/content/57dad08459cc68194391b1a1/e3db159b-9d73-4369-a612-1100c56505e5/cad+wide+2.jpg?content-type=image%2Fjpeg)
![Miata Wing 2](https://images.squarespace-cdn.com/content/57dad08459cc68194391b1a1/dd7f2ed5-3395-4141-8fb9-dee49ccdd2d9/PSX_20250315_114949.jpg?content-type=image%2Fjpeg)
![TPU](https://images.squarespace-cdn.com/content/57dad08459cc68194391b1a1/66213ea4-bbc1-4566-b381-398ca904660d/PSX_20250329_164311.jpg?content-type=image%2Fjpeg)
![Cover 1](https://images.squarespace-cdn.com/content/57dad08459cc68194391b1a1/24bbd57c-6802-40b9-8539-51778e91234e/cad+scan.jpg?content-type=image%2Fjpeg)
![Cover 2](https://images.squarespace-cdn.com/content/57dad08459cc68194391b1a1/e265ccb3-e1fc-4adb-972f-7182d44f1cb5/PSX_20250315_113302.jpg?content-type=image%2Fjpeg)
![Interior](https://images.squarespace-cdn.com/content/57dad08459cc68194391b1a1/99a70730-d095-453d-8740-9ed1fca80f6e/PSX_20250313_223251.jpg?content-type=image%2Fjpeg)
![Evo 1](https://images.squarespace-cdn.com/content/57dad08459cc68194391b1a1/cf5b4b8d-d1ef-490e-9663-00ae8ee840f8/Screenshot+2025-03-15+111528.jpg?content-type=image%2Fjpeg)
![Evo 2](https://images.squarespace-cdn.com/content/57dad08459cc68194391b1a1/4b4a29b5-2e9b-4c79-86fd-f6f0cc252ebe/PSX_20250315_111903.jpg?content-type=image%2Fjpeg)
![Miata Wide](https://images.squarespace-cdn.com/content/57dad08459cc68194391b1a1/1721711703844-4SLAPKFNQUMZTYTFUMG5/PSX_20240116_180553.jpg?content-type=image%2Fjpeg)
