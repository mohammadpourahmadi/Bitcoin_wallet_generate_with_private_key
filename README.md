# Bitcoin_wallet_generate_with_private_key

این کد یک کیف پول بیت‌کوین ایجاد می‌کند و آن را چاپ می‌کند. 

- در خط اول، کتابخانه `bitcoinaddress` فراخوانی شده و کلاس `Wallet` از آن import می‌شود. 
- در خط دوم، یک شیء از کلاس `Wallet` ساخته می‌شود که شامل اطلاعاتی مثل کلید خصوصی و کلید عمومی (آدرس کیف پول) است. 
- در خط سوم، اطلاعات کیف پول (احتمالاً آدرس یا سایر جزئیات) به صورت رشته‌ای چاپ می‌شود.

**نکته:** برای اجرای این کد، نیاز به نصب کتابخانه `bitcoinaddress` دارید که می‌توانید آن را با دستور `pip install bitcoinaddress` نصب کنید.
