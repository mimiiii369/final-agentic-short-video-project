# Final 自主學習作業：OpenClaw/Hermes Agent 多代理人短影片工作流程

## 團隊資訊
* **學校系所**：國立臺南大學 資訊工程學系
* **課程名稱**：多媒體系統 
* **專案名稱**：國立臺南大學資訊工程學系60秒形象宣傳影片
* **組員名單**：S11259049 李泳儀

---

## 零付費 Token 完成性聲明 
本專案嚴格遵循課程公平性原則，**完全採用零付費路徑完成**。
* **Agent 實作方式**：採用本機模型/模擬乾跑 (Mock/Stub Execution Trace) 產生結構化 JSON 交接檔案。
* **影音製作路徑**：影音腳本與分鏡由 Multi-Agent 流程規劃，最終影片採用手機實地拍攝、免費公開授權素材，並透過免費剪輯工具完成，未訂閱任何付費 AI 生成服務。

---

## 專案目錄結構說明
本儲存庫嚴格依照規範組織，各項評分證據路徑如下：
* **專案結案報告**：`report/Final_Report.pdf`
* **Agent 角色設定**：`agents/` (包含 Planner, Script, Visual, Reviewer 等設定)
* **結構化交接資料**：`handoff/` (各階段傳遞的 JSON 檔案)
* **執行紀錄日誌**：`traces/execution_trace.md`
* **最終短影片成果**：`outputs/final_video.mp4` (55-65秒，含旁白與字幕)
* **素材來源與授權**：`outputs/asset_sources.md`
* **Baseline 對比實驗**：`baseline/single_agent_baseline.md`
