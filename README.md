git clone https://github.com/voicealone/bot.git && cd bot && chmod +x launch.sh && ./launch.sh install && ./launch.sh 
======================
توجه کنید اگر در سرورتان پس از زدن کد های بالا هر گونه خطایی دیدید 
مثل خطای git 
کد های پایین را به ترتیب وارد کنید و هرکجا از شما سوال پرسیده شده 
y بزنید

اگر خطایی مشاهده نشد نیازی به زدن این کدها نیست

sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev ppa-purge python3-pip python3-dev
sudo pip3 install redis
sudo service redis-server restart
sudo add-apt-repository ppa:ubuntu-toolchain-r/test
sudo apt-get update
sudo apt-get upgrade
sudo apt-get dist-upgrade
sudo ppa-purge


======================



پس از وارد کردن شماره یکبار از ترمینال خارج شده و مجدد وارد شود 
ایدی های خود را طبق فیلم در جاهای مشخص وارد کنید 
توجه کنید در آپدیت جدید آیدی در فایل تولز به اول فایل منتقل شده 
پس از تکمیل کار
 کد های زیر را بزنید

cd permag.ir
./permag.sh

ربات خود را تست کنید و اگر پاسخ دادید و مشکلی نبود کد های زیر را وارد کنید 
اما اگر اخر فایل مثل فیلم بود اما پاسخ نمیداد و داخل ترمینال خطای
old msg 
میداد بدانید که ساعت سرور شما تنظیم نیست از سرور دهنده خود بخواهید ساعت سرور را تنظیم کند
کد تنظیم ساعت سرور در اینترنت موجود است سرچ کنید



و در اخر باز از ترمینال خارج شده مجدد وارد شوید 
و کد های زیر را وارد کنید
cd permag.ir
screen ./permag.sh



اگر احیانا بعدا خواستید کدی را تغییر بدهید 
پس از اینکه کار خود را انجام دادید برای مجدد فعال شدن ربات  
کد های زیر را وارد کنید
cd permag.ir 
killall screen
screen .permag.sh

آموزش اپدیت و نصب پلاگین در تلگرام در کانال ما






جهت عدم جلوگیری از خارج شدن ربات از گروه کد های زیر را وارد کنید

#autoleave disable 
#autoleave enable
