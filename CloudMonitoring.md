# CloudMonitoring
雲端監控隨筆
## Why monitoring is important ?
1. 主動性監控: 
2. 預防性監控: `依據Metrics的變動去預防issue`
## Steps of Monitoring
1. Collect 收集資料
2. Storage 儲存資料
3. Analysis 分析資料
4. Action 對應動作
## Dimesion of Monitoring
1. Logging 日誌
2. Metrics 指標 `健康狀況`
3. Event 事件 
4. Alerting 警報 `預防性警報(出現pattern)、事故性警報`
## Levels of Monitoring
1. Info
2. Warning
3. Urgent
## Points of Monitoring
1. Visibility `視覺化呈現`
2. Insight `洞察數據`
3. Optimization `持續優化`

### CloudWatch
雲端學習隨筆
### Azure Monitor
1. `C#` `Java` `Javascript` `Node.js` `Angular` `React`
2. Application Insight 機制 => SDK部屬agent => 收集遙測資料
3. 不一定部屬在雲上，本機也是可以監測的
### Cloud Monitoring (Stackdriver)


# Learning Cloud
## 要訣一：`功能性服務`
1. No : 一頭栽進最底層的`雲端架構`，最嚴格的`安全準則`
2. Yes : 感受`重點服務(ex AWS EC2)`的特別功能、操作設定
3. Yes : 比較與`轉統機房主機`、`本地資料庫`架設的差別
## 要訣二：模熟`網路架構`，`串連`重要服務
1. `雲端本質`：雲端服務`獨立性`
2. `雲端網路`：單點式 > > `串連式`
3. `傳統網路架構`：傳統三層式架構(VPC)
4. `雲端網路架構`：Route53-CF-S3 Host-ELB-EC2-RDS
## 要訣三：掌握`權限管理`，照顧`雲端內部`
1. `資安事件`：第二名攻擊來自`內部員工`
2. `權責分明`
3. `IAM架構`
