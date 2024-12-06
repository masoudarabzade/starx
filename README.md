DigiShop - E-commerce Web Application Overview

DigiShop is a foundational e-commerce website designed for showcasing and managing products. The project currently focuses on essential front-end elements with HTML and CSS files. Additionally, it includes a login system for user authentication via phone numbers. While functional, this project has room for expansion by integrating dynamic features using JavaScript.

Files in the Current Project:

1. HTML Files:



index.html: This file serves as the homepage of DigiShop. It contains the layout for displaying product categories, promotional sections, and a navigation menu. The structure is semantic and well-organized, making it easy to extend with dynamic content such as product lists or user-specific recommendations.

login.html: This page enables users to log in using their phone numbers. It includes input fields for entering phone numbers and a button to proceed. Currently, the authentication logic is not implemented and can be enhanced by integrating backend services or JavaScript for validation and API calls.

2. CSS Files:



styles.css: The stylesheet defines the visual layout and responsiveness of the website. It uses modern CSS techniques such as Flexbox and Grid for a clean, mobile-friendly design. It styles elements across both index.html and login.html, maintaining a consistent visual theme throughout the site.

Possible Additions for Expansion (JavaScript Files):

The current project can be extended by incorporating JavaScript functionality to create a more dynamic and interactive experience. Below are suggestions for new features and corresponding JavaScript files:

1. Login Verification (auth.js): To support user authentication, you can implement JavaScript to validate phone number inputs and integrate with an API or backend service for verification. This file could handle:



Phone number validation using regular expressions.

Sending OTP (One-Time Password) requests to the server.

Handling success or error responses during the login process.

2. Dynamic Product Loading (products.js): Introduce JavaScript to dynamically fetch and display product information from an external API or JSON file. This would allow you to manage a large product database without hardcoding it into the HTML.


3. Shopping Cart Functionality (cart.js): Add a shopping cart feature to let users:



Add or remove products.

Update item quantities.

View total price calculations dynamically.

4. User Dashboard (dashboard.js): Once users log in, a JavaScript-powered dashboard could provide personalized features such as:



Viewing their order history.

Saving favorite products.

Managing account details.

5. Search and Filtering (search.js): Add search functionality to enable users to find products by name or category. Include advanced filters for price ranges, ratings, or availability.


6. Checkout and Payment Integration (checkout.js): Develop a checkout system that:



Collects shipping details.

Summarizes the cart for user review.

Integrates with payment gateways (e.g., Stripe or PayPal).

Conclusion:

DigiShop provides a solid foundation for an e-commerce platform with its existing HTML and CSS structure and a basic login system using login.html. The addition of JavaScript functionality will enable dynamic content management, user authentication, shopping cart integration, and payment processing. These enhancements will elevate DigiShop into a full-featured e-commerce solution.

You can view the project online at: https://masoudarabzade.github.io/digishop/.


---



DigiShop  مرور وب‌سایت  فروشگاهی

DigiShop یک پروژه پایه‌ای وب‌سایت فروشگاهی  است که برای نمایش و مدیریت محصولات طراحی شده است. این پروژه در حال حاضر شامل فایل‌های HTML و CSS بوده و یک سیستم ورود کاربران دارد که از طریق شماره تلفن امکان‌پذیر است. این پروژه در حالت فعلی قابل استفاده است اما قابلیت‌های فراوانی برای گسترش و افزودن امکانات داینامیک با جاوا اسکریپت دارد.

فایل‌های موجود در پروژه:

1. فایل‌های HTML:
2. index.html: این فایل به عنوان صفحه اصلی وب‌سایت DigiShop عمل می‌کند. شامل طرح‌بندی دسته‌بندی محصولات، بخش‌های تبلیغاتی و منوی ناوبری است. ساختار این فایل تمیز و معنایی است، که گسترش آن برای افزودن محتواهای داینامیک مانند فهرست محصولات یا پیشنهادهای شخصی‌سازی‌شده را ساده می‌کند.

login.html: این صفحه برای ورود کاربران از طریق شماره تلفن طراحی شده است. شامل فیلدهای ورودی برای شماره تلفن و دکمه‌ای برای ادامه فرآیند است. در حال حاضر، منطق احراز هویت پیاده‌سازی نشده است و می‌توان آن را با استفاده از سرویس‌های سمت سرور یا جاوا اسکریپت برای اعتبارسنجی و درخواست‌های API بهبود بخشید.

2. فایل‌های CSS:



styles.css: این فایل، طرح‌بندی بصری و واکنش‌گرا بودن وب‌سایت را تعریف می‌کند. از تکنیک‌های مدرن CSS مانند Flexbox و Grid برای طراحی موبایل‌پسند و تمیز استفاده شده است. استایل‌های این فایل در هر دو فایل index.html و login.html استفاده می‌شود و تم گرافیکی یکنواختی را ارائه می‌دهد.

امکانات قابل اضافه برای گسترش پروژه (فایل‌های JavaScript):

پروژه می‌تواند با افزودن ویژگی‌های داینامیک جاوا اسکریپت گسترش یابد. در اینجا برخی از امکانات پیشنهادی و فایل‌های مرتبط آورده شده است:

1. اعتبارسنجی ورود (auth.js): برای پشتیبانی از احراز هویت کاربران، می‌توانید جاوا اسکریپت را برای اعتبارسنجی ورودی شماره تلفن و ادغام با یک API یا سرویس سمت سرور برای تأیید اضافه کنید. این فایل می‌تواند شامل موارد زیر باشد:



اعتبارسنجی شماره تلفن با استفاده از عبارات منظم.

ارسال درخواست OTP (کلمه عبور یکبار مصرف) به سرور.

مدیریت پاسخ‌های موفق یا خطا در فرآیند ورود.

2. بارگذاری داینامیک محصولات (products.js): جاوا اسکریپت را برای دریافت و نمایش اطلاعات محصولات به صورت داینامیک از یک API خارجی یا فایل JSON اضافه کنید. این ویژگی مدیریت پایگاه داده محصولات را آسان می‌کند.


3. سبد خرید (cart.js): افزودن ویژگی سبد خرید برای کاربران تا بتوانند:



محصولات را اضافه یا حذف کنند.

تعداد آیتم‌ها را بروزرسانی کنند.

قیمت کل را به صورت داینامیک مشاهده کنند.

4. داشبورد کاربر (dashboard.js): بعد از ورود کاربران، داشبوردی مبتنی بر جاوا اسکریپت می‌تواند امکانات زیر را فراهم کند:



مشاهده تاریخچه سفارشات.

ذخیره محصولات مورد علاقه.

مدیریت جزئیات حساب کاربری.

5. جستجو و فیلتر کردن (search.js): امکان جستجوی محصولات بر اساس نام یا دسته‌بندی را اضافه کنید. همچنین فیلترهای پیشرفته برای محدوده قیمت، امتیازدهی یا موجودی محصولات ارائه دهید.


6. تسویه‌حساب و ادغام درگاه پرداخت (checkout.js): سیستم تسویه‌حسابی طراحی کنید که:



اطلاعات حمل و نقل کاربران را جمع‌آوری کند.

فهرست خرید را برای بررسی نهایی نمایش دهد.

با درگاه‌های پرداخت (مانند زرین پال یا PayPal) ادغام شود.

نتیجه‌گیری:

پروژه DigiShop در حالت فعلی، یک پایه مناسب برای وب‌سایت فروشگاهی با ساختار HTML و CSS و سیستم ورود کاربران ارائه می‌دهد. با اضافه کردن ویژگی‌های جاوا اسکریپت، می‌توانید این وب‌سایت را به یک پلتفرم کامل فروشگاهی با قابلیت مدیریت محتوای داینامیک، احراز هویت کاربران، ادغام درگاه پرداخت و سبد خرید گسترش دهید. این ویژگی‌ها تجربه کاربری را بهبود بخشیده و تعامل بیشتری به سایت اضافه می‌کنند.

شما می‌توانید پروژه را به صورت آنلاین از آدرس زیر مشاهده کنید: https://masoudarabzade.github.io/digishop/.
