- 👋 Hi, I’m @karta577384
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

# 圖形介面
## 圖形介面
### 圖形介面
#### 圖形介面
***
```
import tkinter as tk
import time
window = tk.Tk()
window.title('GUI')
window.geometry('800x600')
window.resizable(False, False)
window.iconbitmap('C:/Users/user/Desktop/112 API/icon.ico')

check_button = tk.Button(text="確認")
check_button.place(x=200,y=30)
xls_button = tk.Button(text="產生報表")
xls_button.place(x=30,y=550)

def button_event():
    close_button['text'] = 'hello world'

close_button = tk.Button(text="關閉視窗", command=exit)
close_button.place(x=700,y=550)


window.mainloop()

```


<!---
karta577384/karta577384 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
