# SwitchLanguageDemo
Android应用内实现语言切换的demo
You can get more details from:https://my.oschina.net/jack1900/blog/290694

You can restart activity and refresh language by using this:
Intent intent = new Intent(ChangeLanguageActivity.this,MainActivity.class).setFlags(Intent.FLAG_ACTIVITY_CLEAR_TASK | Intent.FLAG_ACTIVITY_NEW_TASK);
                startActivity(intent);
