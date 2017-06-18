راهنمای نصب ربات
وارد ترمینال بشین و دستور زیر را بزنید 

git clone https://github.com/Kia-Pashang/To_My_Amigos.git && cd To_My_Amigos && chmod +x launch.sh && chmod +x steady.sh &&./launch.sh install

بعد این که ربات رو نصب کردین وارد فایل
bot.lua
بشین و در خط 4 ایدی عددی خودتونو بزارید

بعدش برای اجرا کردن ربات از دستور زیر استفاده کنید

./launch.sh ID (ID : یک عدد انتخا کنید مواظب باشید که عدد تکراری نباشه شماره بدین و تمام)
بعدش شماره بدین و تمام

#Launch All bots by one Autolaunch cammand :
sudo tmux new-session -s To_My_Amigos "bash launch.sh autolaunch"