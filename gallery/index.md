---
title: Team
---

# <i class="fas fa-users"></i>ผลงานของเรา

## ตัวอย่างรูปภาพสินค้าพร้อมคำอธิบาย Product gallery with description

{% capture mediumcards %}
{%
  include card.html
  size="medium"
  image="images/Packages_EZmini.jpg"
  heading="EZ Mini"
  row1="แพ็คเกจ EZ Mini เหมาะสำหรับเว็บไซต์ขนาดเล็ก ความยาวไม่เกิน 1 หน้า และมีรูปภาพน้อยกว่า 10 รูป"
%}
{%
  include card.html
  size="medium"
  image="images/Packages_EZpro.jpg"
  heading="EZ Pro"
  row1="แพ็คเกจ EZ Pro เหมาะสำหรับเว็บไซต์ขนาดกลาง ความยาวไม่เกิน 4 หน้า และมีรูปภาพน้อยกว่า 30 รูป"
%}
{%
  include card.html
  size="medium"
  image="images/Packages_EZpromax.jpg"
  heading="EZ Pro Max"
  row1="แพ็คเกจ EZ Pro Max เหมาะสำหรับเว็บไซต์ขนาดใหญ่ ความยาวเกิน 4 หน้า หรือมีรูปภาพมากกว่า 30 รูป"
%}
{% endcapture %}

{% include centerer.html html=mediumcards %}



