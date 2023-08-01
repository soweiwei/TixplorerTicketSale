此專案僅為練習.NET Core MVC 及 Vue.js + Wei API使用

-------------------------------------------------------------------------------------------
*後台使用方法如下：

進入資料夾「backstage」中，運行終端，輸入執行指令 dotnet TixlorerCore.dll 以運行專案。

運行後，終端視窗會給予網址，透過網址可進入專案中。

專案內部分功能需要登入才可以使用，請輸入帳號staff01、密碼1234 
-------------------------------------------------------------------------------------------
*前台使用方法如下：

進入資料夾「frontend」中，內有三個資料夾，分別進入後運行終端並輸入運行指令，資料夾個別對應指令如下：


CoreMVC => dotnet TixplorerCoreFrontend.dll -- --urls=https://localhost:7289/
Vue.js_SPA/dist => http-server -p 5173
WeiAPI => dotnet FrontendWebApi.dll --urls=https://localhost:7139/

註1：前台需要三個專案都運行中才可以正常操作網頁
註2：會員登入可輸入帳號：mkd@gmail.com、密碼：123456
