# img_via_uart
STM32 Blue Pill program that takes an image as a byte array and outputs it to the ST7920 display.

Usage
---
Simply transmit 1024 bytes over the UART representing the image. I recommend [my Java application](https://github.com/ksmsergei/ImageViaCOMPort), developed specifically for this purpose, which allows you to easily configure and transmit images over the COM port.

A small demonstration
---
<details>
  <summary>Source image:</summary>
  <em><img src="https://github.com/user-attachments/assets/afc84733-872d-49d7-93ad-672a62a8bbbd"></em>
</details>
<img src="https://github.com/user-attachments/assets/04db231b-ffc4-4624-989b-431177fed9f7" alt="1" width="45%">

---
<details>
  <summary>Source image:</summary>
  <em><img src="https://github.com/user-attachments/assets/3da7c4f5-0ba7-4852-b8e9-1a9fe9e34c50"></em>
</details>
<img src="https://github.com/user-attachments/assets/d3efe672-ae59-455e-95e5-efb38f4bad60" alt="2" width="45%">

---
<details>
  <summary>Source image:</summary>
  <em><img src="https://github.com/user-attachments/assets/5bd4acaa-6352-4d2d-89e9-dc984ec84b8d"></em>
</details>
<img src="https://github.com/user-attachments/assets/336f8357-ecef-4af1-abc5-7d5be5dd0197" alt="3" width="45%">

Used libraries
---
- [ST7920_lib](https://youtu.be/RuUFxePFrmo?si=xF2E6PhmXEnKz_lW) - to work with graphics on the ST7920
