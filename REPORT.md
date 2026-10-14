# 學生比賽／活動中期清單（Gmail 掃描）

- **掃描日期：** 2026-10-14（Asia/Hong_Kong）— Daily student events Gmail scan
- **上次發佈／as_of：** 2026-10-12 → 本次更新至 2026-10-14
- **Gmail 帳戶：** tmchan@skhbbss.edu.hk
- **本次搜尋：** `after:2026/10/12` + 比賽／競賽／報名／邀請等關鍵字（約 26 封線程）
- **收錄活動數：** 45（+4 new；1 material update）
- **變更：**
  - 新增「香港網安奪旗賽 2026（HKCERT CTF）」（截止 2026-10-20；[官網](https://ctf.hkcert.org/)；分數 5/3/4/5，total_recommend=12）
  - 新增「第十六屆原來我得㗎美國中學交流獎學金」（截止 2026-10-31；[官網](https://www.yesican.org.hk/)；分數 3/5/3/2，total_recommend=11）
  - 新增「香港機關王競賽 2026/27」（報名截止 2026-11-20；[官網](https://ce.hkfyg.org.hk/teachers-zone/competition/hk_greenmech/)；分數 4/3/4/3，total_recommend=11）
  - 新增「第四屆智醒消費學堂」（智惜碳學校報名截止 2026-11-27；[官網](https://www.consumer.org.hk/sca)；分數 5/4/4/2，total_recommend=13）
  - 更新 r4m-2027 比賽日期為 2027-05-22
- **排除（本次視窗）：** 中電教育基金外判推銷、教師 AI 工作坊／證書課程、FLL 老師推廣、AI Go! 校企計劃、教學工具／講座／書展類郵件
- **GitHub Pages：** 待推至 leonchantm/student-events

## 評分摘要

詳見 [RUBRIC.md](RUBRIC.md)。`total` = 規模+獎項+認受性；複雜度獨立。

## 歷史紀錄

以下保留較早掃描說明。


## Enrichment（2026-10-11）

- **官方連結新填／升級：** 25 項
- **截止日新填：** 19 項
- **方法：** 重讀 Gmail `PLAIN_TEXT` 正文 + 既有 `data/raw_bodies/` + WebSearch／WebFetch 核實官網；**不虛構** URL／日期。
- **仍缺連結及／或截止：**
  - `hengqin-ai-robot-2026` — 缺連結／截止（郵件無公開官網 URL；報名回執 inquiry@ycltesthk.com；詳情在附件 PDF。截止日未在正文列明。）
  - `intl-robotics-ai-2027` — 缺截止（商業教育機構推廣；核對賽事認可度後再推薦。 主辦 Walnut Education；詳情 PDF 見 Google Drive（郵件附件連結）。截止日正文未列明。）
  - `ai-travel-china-video` — 缺連結（報名期至 2026-11-13；影片提交截止 2026-12-31。官方 URL 僅見附件圖片／電話 2881 3113，正文無網址。）
  - `mengxi-stem-2026` — 缺截止（計劃官網有挑戰賽頁；2026 屆具體報名截止僅見附件章程（郵件正文未列），未核實則保持 null。聯絡 www.fnty.org.hk / 2652 9123。）
  - `lions-ai-challenge` — 缺截止（截止日郵件未寫清。 現有連結為啟動禮／說明會回條（2026-10-17）；比賽本體報名截止未在郵件列明。）
  - `clp-lowcarbon-invention-4` — 缺截止（物理／能源主題相關。 中心總覽 https://linktr.ee/lowcarbonenergy；截止日僅見附件「比賽詳情」PDF，正文未列，保持 null。）
  - `dfc-ai-2026-27` — 缺截止（啟動禮 2026-10-31；比賽報名／提交截止未在邀請信正文列明。聯絡 dfc@gacity.org。）
  - `chuangxie-cup-2026` — 缺截止（官網有章程／參賽表格；郵件正文未列報名截止日（賽事 12-05／12-06／12-12）。參賽表格 https://ctea.org.hk/index.php/application-form）
  - `r4m-2027` — 缺截止（日常教育官網頁未在公開摘要列明 2027 屆報名截止；郵件為 Mailchimp 追蹤連結。比賽日期約 2027-05（見官網）。）
  - `ys-drone-football` — 缺截止（報名 https://nwfm.jotform.com/262280819246461 ；截止日郵件未列明。）
  - `steam-sci-tech-2026` — 缺連結（報名截止 2026-11-02；作品提交 2026-12-04。郵件僅有電話／二維碼，無文字 URL。）
- **已過期仍保留（標記 upcoming=false）：** `wycto-2026`（截止 2026-09-24）、`polyu-comp-virtual-gear-2026`（活動日 2026-10-10）。

## 總表（按推薦總分）

| # | 名稱 | 範疇 | 截止 | 比賽日期 | 主辦 | 總分 | 規模 | 獎項 | 認受 | 複雜 | 連結 |
|---|------|------|------|----------|------|------|------|------|------|------|------|
| 1 | 香港電腦奧林匹克競賽 (HKOI) 2026/27 | Computer Science / Programming | 2026-10-27 | 初賽 2026-11-07；決賽 2026-12-05 | 教育局 (EDB) × 香港電腦教育學會 (HKACE)；協辦：中大、城大 | **15** | 5 | 5 | 5 | 5 | [link](https://hkoi.org/zh/hkoi/) |
| 2 | 第六屆香港創科展 (Hong Kong Science Fair) 2026-2027 | STEM / Science Innovation | 2026-11-29 | 展覽及頒獎通常於翌年在會展舉行（具體日期見官網） | 香港創新基金 | **15** | 5 | 5 | 5 | 4 | [link](https://www.hksciencefair.org.hk/) |
| 3 | 2026/27 葛量洪傑出學生選舉 (Grantham Scholars of the Year) | Scholarship / Leadership / General | 2026-12-09 | 提名期（見邀請） | 葛量洪獎學基金 (Grantham Scholarships Fund) | **15** | 5 | 5 | 5 | 4 | [link](https://eform.cefs.gov.hk/form/hab009/en/) |
| 4 | 第五屆城大科學專利挑戰賽 (CityUHK Science Patent Challenge) 2026-27 | Physics / STEM / Innovation | 2027-01-15 | IP 工作坊 2026-10-17；決賽 Pitch 約 2027-03-20；提交截止 2027-01-15 | 香港城市大學理學院 × Provost Office；EDB 科學教育組轉發 | **15** | 5 | 5 | 5 | 4 | [link](https://www.cityu.edu.hk/csci/local-school-outreach/cityuhk-science-patent-challenge) |
| 5 | 2027 國際科學比賽香港區選拔賽 | Science / STEM | 2026-10-13 | — | 香港新一代文化協會 | **12** | 4 | 4 | 4 | 4 | [link](https://stic.newgen.org.hk/apply-international/) |
| 6 | 香港女子電腦奧林匹克競賽 (HKGOI) 2026/27 | Computer Science / Programming | 2026-10-27 | 2026-11-15 | 香港電腦教育學會 (HKACE)；協辦：城大 | **12** | 4 | 4 | 4 | 5 | [link](https://hkoi.org/zh/hkgoi/) |
| 7 | 全港首屆中小學「航天築夢」航天 AI 創新大賽 | STEM / AI / Space | 2026-10-31 | — | 教育局「心繫家國」活動相關 | **12** | 5 | 3 | 4 | 3 | [link](https://www.hkstarcatcher.com/apply.html) |
| 8 | 第九屆大灣區數字教育 STEAM 卓越獎 2027（香港） | STEAM / Digital Education | 2027-04-15 | — | 香港網絡教育工作者協會 (HKNETEA) 等 | **12** | 4 | 4 | 4 | 3 | [link](https://www.hknetea.org/competitions-1/desa-2027) |
| 9 | 2026 橫琴粵澳深度合作區人工智能大賽暨第八屆粵港澳青少年機器人大賽 | AI / Robotics | — | 總決賽 2026-11-28 或 2026-11-29（珠海華發國際會展中心） | 廣東省教育廳白名單賽項相關 | **12** | 4 | 4 | 4 | 4 | — |
| 10 | 第十二屆全港中學微電影創作大賽 | Arts / Media | 2026-10-23 | — | YMCA | **11** | 4 | 3 | 4 | 3 | [link](https://www.facebook.com/MiniMovieCompetition/) |
| 11 | 2027 AI × Engineering Pioneer Program（城大） | AI / Engineering | 2026-11-11 | 多階段：2026-11 至 2027-12 | CityU Bright Future Engineering Talent Hub | **11** | 4 | 3 | 4 | 4 | [link](https://www.gycsi.org/cityuhk-pioneer) |
| 12 | 香港中文大學網絡安全奪旗賽 2026 | Computer Science / Cybersecurity | 2026-12-23 | 2026-12-26 09:00 至 2026-12-27 21:00（線上 36 小時） | 香港中文大學（HKACE 支持轉發） | **11** | 4 | 3 | 4 | 4 | [link](https://docs.google.com/forms/d/e/1FAIpQLSeFf7r_9vI1TLU17QPW3E9EvUhMLDOqoRXDKPJnxkOhW6rYNg/viewform) |
| 13 | 香港教育城 PICCKS 學生獎勵計劃 2026/27 | General / Self-learning / Creativity | 2027-01-15 | 學年內多項挑戰 | 香港教育城 | **11** | 4 | 3 | 4 | 2 | [link](https://www.edcity.hk/home/zh-hant/sic/202627/introduction/) |
| 14 | 2027 國際機械人與人工智能比賽（新加坡／廣州） | Robotics / AI | — | 2027（海外賽） | Walnut Education / 相關國際賽機構 | **11** | 4 | 4 | 3 | 4 | [link](https://www.walnutedutech.com) |
| 15 | 港澳中學化妝品配方比賽 2026/27 | Chemistry / STEM | 2026-10-23 | 正式比賽日見主辦更新 | 香港城市大學 × 香港化粧品同業協會 (CPAHK) | **10** | 4 | 3 | 3 | 3 | [link](https://www.cityu.edu.hk/chem/cosmetic/) |
| 16 | 未來創新者大賽 2027 (Future Maker Competition) | Design / STEM / Innovation | 2026-10-30 | 2027 | 教大創業與創新教育中心 (CEIE, EdUHK) | **10** | 4 | 3 | 3 | 3 | [link](https://ceie.eduhk.hk/future-makers-competition-product-design-competition-2027) |
| 17 | 「組裝」夢家園 – BIM Competition 2026 | STEM / Construction / BIM | 2026-10-31 | 2026-11-28 | 職業訓練局 IVE（建造） | **10** | 4 | 3 | 3 | 3 | [link](https://forms.cloud.microsoft/pages/responsepage.aspx?id=qwXbfulCSEO4kyumJaNQxqu-B1tGeMZKrtir0dF3Hh9URVZUVFFYVExPNjhDVTJMV040SUMxODI0Sy4u&origin=lprLink&route=shorturl) |
| 18 | 「三十港章 慧智北都」AIoT 模型設計比賽 | AI / IoT / STEM | 2026-11-13 | 線上簡介會 2026-10-20 | 香港津貼中學議會、香港中文中學聯會、城大；HKACE / AiTLE 支持 | **10** | 4 | 3 | 3 | 4 | [link](https://www.cityu.edu.hk/skltmw/AIot_Comp/) |
| 19 | 第一屆全港校園電視台「AI帶你遊中國」短視頻大比拼 | AI / Media / Citizenship | 2026-11-13 | 簡介會 2026-10-12 | （HKACE 支持轉發） | **10** | 3 | 4 | 3 | 2 | — |
| 20 | 2027 ROBOFEST × MRC 聯乘挑戰賽（香港區選拔） | Robotics | 2026-12-10 | 2027 | ROBOFEST / MRC 相關 | **10** | 4 | 3 | 3 | 4 | [link](https://global-robot.ai/zh/competitions/rf-x-mrc-hk) |
| 21 | 香港綠色建築議會「綠色空間　由我創造」學生比賽 2026-2027 | Environment / Design / STEM | 2026-12-31 | — | 香港綠色建築議會 (HKGBC) | **10** | 4 | 3 | 3 | 3 | [link](https://www.hkgbc.org.hk/studentcompetition) |
| 22 | 「夢溪少年談」國家成就科普計劃 2026 青少年創科實踐挑戰賽 | STEM / National Achievement Science | — | — | 創新科技署贊助相關計劃 | **10** | 4 | 3 | 3 | 3 | [link](https://fnty-mengxi.org.hk/challenge/) |
| 23 | 獅子會全港學界 AI 挑戰賽 | AI / STEM | — | 啟動禮／說明會（見報名） | 獅子會 | **10** | 4 | 3 | 3 | 3 | [link](https://forms.gle/H1Rvsi4KPAakqx6x8) |
| 24 | 第四屆低碳節能發明大賽（中電） | STEM / Environment / Physics | — | — | 中電低碳能源教育中心 | **10** | 4 | 3 | 3 | 2 | [link](https://forms.gle/NbewzJjNHSBuSTFy8) |
| 25 | World Youth Chemistry Talent Olympiad (WYCTO) 2026 | Chemistry | 2026-09-24 | — | （國際化學人才奧林匹克相關；郵件邀請） | **9** | 3 | 3 | 3 | 4 | [link](https://drive.google.com/drive/folders/1glNfcGxY1NmSezuaXIGkjSY-3AQGVp3Z?usp=sharing) |
| 26 | 理大資訊日 × COMP 高中虛擬戰車編程挑戰賽 | Computer Science / Programming | 2026-10-10 | 配合理大本科入學資訊日 2026 | 香港理工大學電子計算學系 | **9** | 4 | 2 | 3 | 2 | [link](https://polyucomp-turbo2026.site) |
| 27 | 「獅展翼彩·智領低空」中學生及大專生無人機大賽 | STEM / Drone / Robotics | 2026-10-16 | — | 獅子會 | **9** | 3 | 3 | 3 | 4 | [link](https://forms.gle/ukDMMQjqadL9xLQK9) |
| 28 | 第六屆全港青年 STEAM 比賽暨展覽（由 AI 到 SI）及人工智能素養推廣比賽 | STEAM / AI | 2026-10-31 | — | CFS AISI 等 | **9** | 3 | 3 | 3 | 3 | [link](https://padlet.com/loyl/steam-ai-si-detjvjp7shy011wk) |
| 29 | 第7屆「愛．創耆樂」挑戰賽 | STEM / Social Innovation / Ageing | 2026-11-01 | — | （郵件現正接受報名） | **9** | 3 | 3 | 3 | 3 | [link](https://actionhub.hk/event_highlight/detail/9TiKEwM8A2gPnkcpP) |
| 30 | 青少年發明家比賽 2027（第21屆） | STEM / Invention | 2026-11-15 | — | Young Inventor Competition（見報名／Facebook） | **9** | 3 | 3 | 3 | 3 | [link](https://forms.gle/RFuSDDWHCdfBPPnS9) |
| 31 | 2026 ESG 商業創意大賽 | Business / ESG / Innovation | 2026-11-30 | — | IVE（商科）VTC | **9** | 3 | 3 | 3 | 3 | [link](https://docs.google.com/forms/d/e/1FAIpQLSf7FLFoSphyi6gHTK-t6sEOZjR9vBAVkcR7nRP2NN44CmpAUQ/viewform?usp=publish-editor) |
| 32 | 2026–27 DFC × AI 創意行動挑戰賽 | AI / Design Thinking / Citizenship | — | 啟動禮 2026-10-31 | Design for Change 相關 | **9** | 3 | 3 | 3 | 3 | [link](https://www.dfcworld.org/hongkong) |
| 33 | 第二十屆「創協盃」創意科技機械人大賽 2026 | Robotics / AI | — | 港區賽 2026-12-05；創意設計 2026-12-12 | 創協盃組委會 | **9** | 3 | 3 | 3 | 4 | [link](https://ctea.org.hk/) |
| 34 | 「說好香港海事故事」生成式 AI 短片創作比賽 | AI / Media / Maritime | 2026-10-16 | — | VTC 海事服務訓練委員會 (MSTB) | **8** | 3 | 3 | 2 | 2 | [link](https://forms.gle/uu6twpKwjGYqxZS2A) |
| 35 | 2026-2027 全港校際 STEAM 知識問答比賽 | STEAM / General | 2026-11-30 | — | （郵件邀請） | **7** | 3 | 2 | 2 | 1 | [link](https://hksteamedu.org) |
| 36 | 「心事・開拍」全港中學生短片比賽 2026 | Arts / Mental Health / Media | 2026-12-31 | — | （附免費網上培訓） | **7** | 3 | 2 | 2 | 2 | [link](https://harvest.org.hk/tc/What-We-Do/detail/youth-short-film-2026/) |
| 37 | 道路安全 STEAM 比賽 2026-27 | STEAM / Civic | 2027-03-31 | — | HKNETEA 等 | **7** | 3 | 2 | 2 | 2 | [link](https://roadsafetysteam.hk) |
| 38 | 2027 香港 R4M 機械人任務賽 | Robotics | — | 2027 | 日常教育等 | **7** | 3 | 2 | 2 | 3 | [link](https://eduperience.org/hk-r4m-2027/) |
| 39 | 青年廣場「YS 無人機足球挑戰賽」 | STEM / Drone | — | 飛越 Teen 際：YS 無人機競飛嘉年華期間 | 青年廣場 (Youth Square) | **7** | 3 | 2 | 2 | 3 | [link](https://www.youthsquare.hk/play/YSDroneFunFest2026) |
| 40 | STEAM 科學技術比賽 2026 | STEAM | 2026-11-02 | — | （郵件邀請） | **6** | 2 | 2 | 2 | 2 | — |

## Top 5（推薦總分 · upcoming）

1. **香港電腦奧林匹克競賽 (HKOI) 2026/27** — total **15**（規模5／獎項5／認受5／複雜5）
   - 截止：2026-10-27；日期：初賽 2026-11-07；決賽 2026-12-05
   - 連結：https://hkoi.org/zh/hkoi/
   - 享負盛名的年度程式設計比賽，亦是國際信息學奧林匹克 (IOI) 香港代表隊初步遴選。配合新高中 ICT 課程，初賽／決賽可用 Python 或 C++。

2. **第六屆香港創科展 (Hong Kong Science Fair) 2026-2027** — total **15**（規模5／獎項5／認受5／複雜4）
   - 截止：2026-11-29；日期：展覽及頒獎通常於翌年在會展舉行（具體日期見官網）
   - 連結：https://www.hksciencefair.org.hk/
   - 大型創科展覽比賽，歷屆金獎隊可獲安排赴瑞士日內瓦國際發明展。2027 年適逢回歸 30 周年，首次邀請海外隊伍。

3. **2026/27 葛量洪傑出學生選舉 (Grantham Scholars of the Year)** — total **15**（規模5／獎項5／認受5／複雜4）
   - 截止：2026-12-09；日期：提名期（見邀請）
   - 連結：https://eform.cefs.gov.hk/form/hab009/en/
   - 具高度認受性的全港傑出學生獎學金／選舉，需學校提名。

4. **第五屆城大科學專利挑戰賽 (CityUHK Science Patent Challenge) 2026-27** — total **15**（規模5／獎項5／認受5／複雜4）
   - 截止：2027-01-15；日期：IP 工作坊 2026-10-17；決賽 Pitch 約 2027-03-20；提交截止 2027-01-15
   - 連結：https://www.cityu.edu.hk/csci/local-school-outreach/cityuhk-science-patent-challenge
   - 鼓勵物理／科學導向學生把科學構想轉成具專利潛力的創新。金／銀獎可獲香港短期專利申請費用全額贊助，入圍者有 GREAT 課程優先面試機會。

5. **2027 國際科學比賽香港區選拔賽** — total **12**（規模4／獎項4／認受4／複雜4）
   - 截止：2026-10-13；日期：—
   - 連結：https://stic.newgen.org.hk/apply-international/
   - 國際科學比賽之香港區選拔，屬 STEAM／科學創意路徑活動。

## 急截止（≤ 2026-10-31 · upcoming）

- **2026-10-13** — 2027 國際科學比賽香港區選拔賽 · [link](https://stic.newgen.org.hk/apply-international/)
- **2026-10-16** — 「獅展翼彩·智領低空」中學生及大專生無人機大賽 · [link](https://forms.gle/ukDMMQjqadL9xLQK9)
- **2026-10-16** — 「說好香港海事故事」生成式 AI 短片創作比賽 · [link](https://forms.gle/uu6twpKwjGYqxZS2A)
- **2026-10-23** — 第十二屆全港中學微電影創作大賽 · [link](https://www.facebook.com/MiniMovieCompetition/)
- **2026-10-23** — 港澳中學化妝品配方比賽 2026/27 · [link](https://www.cityu.edu.hk/chem/cosmetic/)
- **2026-10-27** — 香港電腦奧林匹克競賽 (HKOI) 2026/27 · [link](https://hkoi.org/zh/hkoi/)
- **2026-10-27** — 香港女子電腦奧林匹克競賽 (HKGOI) 2026/27 · [link](https://hkoi.org/zh/hkgoi/)
- **2026-10-30** — 未來創新者大賽 2027 (Future Maker Competition) · [link](https://ceie.eduhk.hk/future-makers-competition-product-design-competition-2027)
- **2026-10-31** — 全港首屆中小學「航天築夢」航天 AI 創新大賽 · [link](https://www.hkstarcatcher.com/apply.html)
- **2026-10-31** — 「組裝」夢家園 – BIM Competition 2026 · [link](https://forms.cloud.microsoft/pages/responsepage.aspx?id=qwXbfulCSEO4kyumJaNQxqu-B1tGeMZKrtir0dF3Hh9URVZUVFFYVExPNjhDVTJMV040SUMxODI0Sy4u&origin=lprLink&route=shorturl)
- **2026-10-31** — 第六屆全港青年 STEAM 比賽暨展覽（由 AI 到 SI）及人工智能素養推廣比賽 · [link](https://padlet.com/loyl/steam-ai-si-detjvjp7shy011wk)

## 掃描說明與限制

- 信箱確認為 **tmchan@skhbbss.edu.hk**；大量郵件由 `Info@skhbbss.edu.hk` 轉發學界宣傳。
- 互補搜尋（比賽／競賽／contest／活動／報名／deadline／物理／STEAM 等）後，再人工篩出學生可參加項目。
- **已排除：** 純教師 CPD、行政／財務、教材推銷、明顯已過截止（如「減碳＠校園」9月24日截止）、測試郵件等。
- **2026-10-11 enrichment：** 多數「按此」連結已從正文／官網補回；仍缺者多為僅附件 PDF／二維碼、或正文未寫截止。
- **物理科優先關注：** 城大科學專利挑戰賽、香港創科展、中電低碳發明、航天築夢、國際科學選拔等。
- 本階段**未**建立／推送 GitHub repo；網頁草稿見 `index.html`。

## 檔案

| 檔案 | 說明 |
|------|------|
| `data/events.json` | 完整結構化資料 + 分數 |
| `RUBRIC.md` | 公開評分準則 |
| `index.html` | 可篩選本機網頁（內嵌 JSON）＋重要日子月曆 |
| `REPORT.md` | 本中期報告 |
