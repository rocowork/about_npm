# about_npm

*npm list

*UNMET PEER DEPENDENCY jquery@1.9.1 - 3
*UNMET PEER DEPENDENCY popper.js@^1.14.7
*ENOENT: no such file or directory
*npm i --save jquery popper.js

*npm init

>name: 就是該專案的名字，它預設就是該目錄名。
>description: 專案描述。
>entry point: 專案切入點，這有點複雜，之後再說。
>test command: 專案測試指令，之後說。
>git repository: 專案原始碼的版本控管位置。
>keywoard: 專案關鍵字
>author: 專案作者，以 author-name <author@email.com> 寫之。
>license: 專案版權。
>最後它秀一個預覽的樣子，如果沒問題就 Enter 來產生 package.json。到編輯器裡打開它，它就是一個 json 格式的檔案。

*npm uninstall jquery 就可以把 jquery 移除囉。但要注意，這樣並不會把 package.json 更新!!!!
*npm uninstall jquery --save 這樣才能也把 package.json 中的 jquery 資訊移除~

npm -v 或 npm --version → 查看 npm 版本
npm i [package] 或 npm install [package] → 安裝套件在專案下的 node_modules 目錄
npm i [package] --save 或 npm install [package] --save → 安裝套件在專案下的 node_modules 目錄，並更新該套件資訊到 package.json
npm un [package] 或 npm uninstall [package] → 移除某套件
npm un [package] --save或 npm uninstall [package] --save → 移除某套件，並更新該套件資訊到 package.json

-----------------------------------------
# Homebrew
macOS 的用戶要透過 brew 來安裝 yarn，Homebrew 是一款自由及開放原始碼的軟體套件管理系統，用以簡化 Mac OS X系統上的軟體安裝過程。
ps. 安裝 Homebrew 前先確認是否有安裝 Xcode 若有請先去更新它，因為 Homebrew 是用 Ruby 攥寫並且需要在有 Ruby 環境下使用，然而安裝 Xcode 時會自帶 Ruby 所以 Xcode 也要保持最新狀態
-----------------------------------------
# 安裝 Yarn
>1.macOS用戶
>brew install yarn
>2.若你的電腦本身安裝 Node.js 了可執行下面指令(因為安裝node會一起安裝npm)
>brew install yarn --without-node
>3.若安裝後日後有更新 Yarn 會在命令端提醒警示，這時你可以使用 Homebrew 來完成更新
>brew upgrade yarn
-----------------------------------------
>1.Windows用戶(直接利用 npm 就能裝起來囉)
>npm install yarn --g
>2.安裝結束後來測試是否安裝成功！
>yarn --version

參考：https://ithelp.ithome.com.tw/articles/10191745


