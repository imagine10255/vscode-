# Visual Studio Code (VSCode)

![VSCode](./assets/vscode.png)


## 特性介紹

1. 拼寫修正 (友情提示,點擊自動修正)

![友情提示](./assets/feature-01.png)

2. 根據檔名或是引用跳到檔案, 偵錯跳轉

![偵錯跳轉](./assets/feature-02.png)
![偵錯跳轉](./assets/feature-02b.gif)
![偵錯跳轉](./assets/feature-02c.gif)

3. CSS色碼顯示與直接調整

![CSS色碼顯示與直接調整](./assets/feature-03.png)

4. 內建Git版本控制

![內建Git版本控制1](./assets/feature-04.png)

![內建Git版本控制2](./assets/feature-04b.png)

5. Emmet Snippets (可自定義程式碼片段)

![EmmetSnippets](./assets/feature-05.gif)

6. 自動格式化程式碼

![自動格式化程式碼](./assets/feature-06.gif)

7. 自定義常用的程式碼片段

![自定義常用的程式碼片段](./assets/feature-07.gif)

8. 好看的檔案 ICON

![ICON](./assets/feature-08.png)

9. 強大的 Intellisense

![Intellisense1](./assets/feature-09a.png)
![Intellisense2](./assets/feature-09b.png)

10. 多行選取(Multi Cursor)

![多行選取](./assets/feature-10.gif)

11. 斷點除錯 Debug

![斷點除錯](./assets/feature-11.png)


12. 內建嵌入終端機

![內建嵌入終端機](./assets/feature-12.png)


13. 活躍的社群

![活躍的社群](./assets/feature-13.png)

## 常用快速鍵

| 快速鍵功能 | OSX快速鍵 | Windows快速鍵 |
|:----|:---------|:-------------|
| 上一個游標位置 | Alt+Cmd+左 | 暫無 |
| 下一個游標位置 | Alt+Cmd+右 | 暫無 |
| 整列程式碼上下移動 | Shift+Cmd+上或下 | 暫無 |
| 複製整列程式碼 | Cmd+D | 暫無 |
| 重新命名檔案 | Shift+F6 | 暫無 |
| 關閉Tab視窗 | Cmd+W | 暫無 |
| 新增VSCode視窗 | Shift+Cmd+N | 暫無 |
| 輸入關鍵字查找檔名並開啟檔案 | Shift+Cmd+O | 暫無 |
| 跳至指定行位置 | Cmd+L | 暫無 |
| 多行選取(可跳行) | Shift+Alt+滑鼠壓住移動 | 暫無 | 
| 開啟終端機 | Shift+Control+` | 暫無 |


## 設定檔

- [編輯器全域設定-OSX](setting/setting-osx.json)


- 程式碼片段設定

  - [Javascript(.js)](setting/javascript.json)
  


## 推薦套件

- <font color="#2D9A70">快速鍵對應設定</font>

  - [Keisuke Kato/IntelliJ IDEA Keybindings](https://marketplace.visualstudio.com/items?itemName=k--kato.intellij-idea-keybindings) 
  
      PHPStorm,WebStorm 使用者 無痛轉移 VSCode (連結含快速鍵對應)


- <font color="#2D9A70">程式碼品質檢查</font>

  - [Dirk Baeumer/ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) 
  
    JS程式碼檢查提示, 格式化符合ESLint (ex: 需要是 const 的時候, 若輸入 let 會自動改成 const, <div class會自動改成 <div className)


  - [Shinnosuke Watanabe/stylelint](https://marketplace.visualstudio.com/items?itemName=shinnn.stylelint) 
  
    CSS StyleLint程式碼檢查


- <font color="#2D9A70">自動補全 格式化與修正</font>

  - [Willian Whitehead/Bootstrap 3 Snippets](https://marketplace.visualstudio.com/items?itemName=wcwhitehead.bootstrap-3-snippets) 
  
    Bootstrap3 程式碼片段產生


  - [Mobamed Abusaid/HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets) 
  
    輸入div再按下tab會自動產生

        <div></div>
    輸入 ul>li*2 會自動產生

        <ul>
          <li></li>
          <li></li>
        </ul>

  - [Jun Han/Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) 
  
    更改開頭標籤的時候, 會自動更改結尾標籤


  - [Christian Kohler/Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) 
  
    路徑自動補全 (ex: 輸入 ./st , 底下如果有 styles.css 就會顯示出來, 只需要Enter就會帶入)



  - [charalampos karypidis/JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets) 
  
    可用簡短碼來產生程式碼範本 ex: 輸入 con 就會產生 class constructor() {}
    

  - [HookyQR/Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify) 
  
    自動補全修正, javascript, JSON, CSS, Sass, and HTML
    


  - [Joel Day/Document This](https://marketplace.visualstudio.com/items?itemName=joelday.docthis) 
  
    自動產生註解 (ex: 輸入 /** 按下 enter, 自動偵測 className, 參數 產生註解標頭)
    


- <font color="#2D9A70">Git版本控制強化</font>

  - [Don Jayamanne/Git History (git log)](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) 
  
    透過容易閱讀的UI來查閱Git Log



- <font color="#2D9A70">介面與識別度優化</font>
     

  - [zhuangtongfa/One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme) 
  
    仿Atom Dark 皮膚

     
  - [rokoroku/Darcula Theme](https://marketplace.visualstudio.com/items?itemName=rokoroku.vscode-theme-darcula) 
  
    仿PHPStorm,WebStorm 皮膚


     
  - [Roberto Huertas/vscode-icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons) 
  
    目錄檔案左邊的ICON會根據不同檔案類型顯示各家ICON

     
  - [CoenraadS/Brecket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
  
     誇號{} () 顏色另外醒目提示

     
  - [rid9/Date & Time](https://marketplace.visualstudio.com/items?itemName=rid9.datetime) 
  
    在右下角出現時間, 全螢幕使用者方便看到現在時間使用



- <font color="#2D9A70">除錯</font>

  - [Microsoft/Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome) 
   
    快速的開啟Chrome進行除錯功能

