#### 2019-04-19 更新

## 儀表板相關
+ 新增 icon (請更新 icon fonts) (只加在使用量那頁做示意)
+ 加入 dashboard iframe 的樣式

***

#### 2019-04-15 更新

## 新增 通知郵件
+ 新增客戶通知 https://tianyow.github.io/CSP/emails/CSP_email_create_customer.html
+ 新增使用者通知 https://tianyow.github.io/CSP/emails/CSP_email_create_user.html
+ 預約下單通知 https://tianyow.github.io/CSP/emails/CSP_email_schedule_order.html
+ 訂閱啟動通知 https://tianyow.github.io/CSP/emails/CSP_email_activate_sub.html
+ 訂閱暫停通知 https://tianyow.github.io/CSP/emails/CSP_email_suspend_sub.html
+ 訂閱即將到期通知 https://tianyow.github.io/CSP/emails/CSP_email_expiring_sub.html
+ Azure訂閱預算額度通知 https://tianyow.github.io/CSP/emails/CSP_email_azure_budget_alert.html

***

#### 2019-04-11 更新

## 更新 新增授權訂閱
+ CSS 跟 JS 請更新
+ 新增 images/toggle-arrow.svg
+ 修改米其林圖示

***

#### 2019-04-09 更新

## 更新 DataTable 屬性
### DataTable 新增 Default設定 (更新 js檔)
1. \ $('#AppQryTable').DataTable(qryTableOptions); 把 qryTableOptions 拿掉
2. 可自訂筆數
### CSS 微調 請更新

***

#### 2019-04-08 更新

## 更新 訂閱管理
+ 新增客戶資訊 CustomerInfo_Add.html
+ 授權訂閱 LicenseInfo_Qry.html 
+ - 新增授權訂閱 LicenseInfo_Add.html
+ - 編輯授權訂閱 LicenseInfo_Upd.html
+ Azure訂閱 AzureInfo_Qry.html
+ - 新增 Azure資訊 AzureInfo_Add.html
+ - 編輯 Azure資訊 AzureInfo_Edit.html
+ - 優惠折數設定 DiscountInfo_Upd.html

## 更新 UI樣式
### 1. Table 內的圓形按鈕 都改為 class="btn-circle" 再加上相對應的 class
+ .btn-account // 帳戶
+ .btn-edit // 編輯
+ .btn-auth // 授權訂閱
+ .btn-pwd // 重置密碼
+ .btn-azure // Azure訂閱
+ .btn-relate // 訂閱關聯
+ .btn-software // 軟體訂閱
+ .btn-raw // 原始資料
+ .btn-keep // 保留個體
+ .btn-usage // 使用量報表
+ .btn-fee // 費用報表
+ .btn-delete // 刪除

### 2. 搜尋選項的位置
1. \<div class="data-qry-wrap"> // 會在右上
2. \<div class="data-qry-wrap-fixed"> // 會置底

### 3. Radio Button 樣式修改
