---
artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)
---

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** PaperPulse — AI hỗ trợ tổng quan tài liệu nghiên cứu  

> Đây là **file duy nhất** của Lab 2.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải brainstorm thêm thật nhiều tính năng AI.
Mục tiêu là:

1. **xác định người dùng thực sự đang cố hoàn thành job gì**
2. **hiểu họ đang dùng giải pháp nào để hoàn thành job đó hôm nay**
3. **chỉ ra AI nên chen vào đúng bước nào trong workflow**
4. **viết ra product hypothesis và assumption còn phải validate**

Quy tắc xuyên suốt: **không rõ job thì đừng bàn feature.**

---

## Cần mở song song 2 thứ

1. **File này** — để điền trực tiếp
2. **`Strategyn_JTBD_Playbook.pdf`** — giảng viên gửi kèm

### Cách dùng playbook cho đúng

Bạn **không cần đọc hết 48 trang**.  
Trong bài này, playbook chủ yếu dùng để tra 4 thứ:

1. **Cách nhìn thị trường qua JTBD lens**
2. **`Job executor` là ai**
3. **Cách viết `job statement`: `verb + object + contextual clarifier`**
4. **8 bước của `job map`**:
   `define -> locate -> prepare -> confirm -> execute -> monitor -> modify -> conclude`

### 2 chương nên mở nhiều nhất

- **Chapter 2 — Define Your Market**
- **Chapter 3 — Build Your Job Map**

> Dùng playbook để **tra framework và ví dụ**.  
> Dùng file này để **làm bài và chốt output**.

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 6 phần trong chính file này:

1. **`Project slice` + market context**
2. **`Job executor` + `core JTBD`**
3. **3 `job stories`**
4. **`JTBD lite map` + pain points**
5. **`AI leverage point` + `product hypothesis`**
6. **`Assumptions to validate` + verdict cuối sau thảo luận**

Nếu thiếu một trong sáu phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (25 phút)

```text
3'  Chốt 1 lát cắt cụ thể của dự án
7'  Viết market context + job executor + core JTBD
6'  Viết 3 job stories + current alternatives
6'  Điền JTBD lite map + AI leverage point + hypothesis
3'  Share trong bàn và sửa version cuối
```

> Nếu dự án làm theo nhóm, cả nhóm có thể thảo luận chung.  
> Nhưng file này vẫn nên có **version chốt rõ ràng** của người nộp.

---

## Bước 0 — Khoanh đúng 1 lát cắt của dự án

Phần lớn dự án nhóm viết quá rộng ở bước này, rồi sau đó mọi thứ mơ hồ theo.

### Khoanh đúng 1 lát cắt theo 4 điểm

- [x] **1 nhóm người dùng chính**
- [x] **1 hoàn cảnh / tình huống rõ**
- [x] **1 job cốt lõi**
- [x] **1 workflow đủ cụ thể để vẽ ra được**

### Điền nhanh trước khi làm

- **Dự án của nhóm tôi là:** PaperPulse, công cụ AI giúp tổng quan tài liệu nghiên cứu, hỗ trợ upload PDF và tìm kiếm paper liên quan
- **Lát cắt tôi chọn để phân tích hôm nay là:** Nghiên cứu sinh đang cần nắm bắt nhanh landscape một chủ đề mới để bắt đầu viết literature review
- **Vì sao tôi chọn lát cắt này:**  
  > Đây là nhóm có pain rõ nhất và xảy ra thường xuyên nhất, mỗi nghiên cứu sinh đều phải đọc hàng chục đến hàng trăm paper trong giai đoạn đầu, trong khi chưa có nền tảng đủ để biết paper nào quan trọng. Đây cũng là lúc AI có thể tạo giá trị thật sự thay vì chỉ là "đọc dùm".


---

## Bước 1 — Viết `Project Snapshot`

### Tóm tắt dự án trong 3 dòng

1. **Nhóm tôi đang nghĩ mình đang giải quyết vấn đề gì?**  
   > Sinh viên và nghiên cứu sinh mất quá nhiều thời gian đọc và tổng hợp tài liệu nghiên cứu — PaperPulse dùng AI để tóm tắt, trả lời câu hỏi từ PDF, và gợi ý paper liên quan.


2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > Sinh viên đại học / học viên cao học đang làm thesis hoặc NCKH, đặc biệt ở giai đoạn đầu khi cần nắm bắt một chủ đề nghiên cứu mới.


3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > Google Scholar + đọc abstract thủ công + ChatGPT/Claude để hỏi + Zotero để quản lý reference + tự ghi note ra Google Docs. Cobble together từ 4-5 tool khác nhau.


---

## Bước 2 — Viết `Market Context`

Ở đây chưa cần solution. Chỉ cần bối cảnh thị trường đủ để hiểu:
**ai đang gặp chuyện gì, trong hoàn cảnh nào, và vì sao bây giờ đáng giải.**

### Trả lời 4 câu ngắn

1. **Ai đang gặp vấn đề này?**  
   > Sinh viên năm 3-4 đại học và học viên cao học đang bắt đầu hoặc đang trong quá trình làm thesis/NCKH — đặc biệt nhóm chưa có kinh nghiệm đọc paper chuyên sâu.


2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   > Ngay trước khi bắt đầu viết literature review cho thesis/NCKH — khi chủ đề còn mới, chưa biết nên tìm paper theo hướng nào, chưa biết paper nào là foundational, paper nào là mới nhất, và cần nắm nhanh landscape chung trong vài ngày. Khi đó, họ phải đọc 20-50 paper để hiểu landscape, nhưng không biết bắt đầu từ đâu, paper nào quan trọng, và khoảng trống nghiên cứu nằm ở đâu.


3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > Dùng Google Scholar để tìm, đọc abstract, đôi khi dùng ChatGPT/Claude hỏi tóm tắt, quản lý reference bằng Zotero, note ra Google Docs. Việc này tốn rất nhiều thời gian và không có tính kế thừa.


4. **Vì sao đây là thời điểm đáng giải?**  
   > Hiện nay, các mô hình ngôn ngữ lớn (LLM) đã đủ mạnh để tóm tắt văn bản và trả lời câu hỏi từ tài liệu PDF với độ chính xác cao. Điều này làm giảm đáng kể rào cản công nghệ cho việc giải quyết bài toán này bằng AI. Đồng thời, số lượng paper khoa học được xuất bản đang tăng nhanh chóng, khiến việc đọc thủ công ngày càng không khả thi.


### Tóm tắt market context trong 3-4 dòng

> Sinh viên thesis đang phải tự kết hợp 4-5 tool rời rạc để làm một việc duy nhất: hiểu đủ một chủ đề nghiên cứu để bắt đầu viết. Không tool nào hiện tại giúp họ đi từ "chủ đề mới" đến "có đủ bức tranh tổng quan để viết" trong một workflow liền mạch. AI đã đủ capable để thay đổi điều này — câu hỏi là ai sẽ làm đúng workflow đó.


---

## Bước 3 — Xác định `Job Executor`

`Job executor` là người **trực tiếp dùng một giải pháp để hoàn thành job**.

### Đừng nhầm với:

- người mua tiền nhưng không trực tiếp làm job
- người ảnh hưởng quyết định
- cả một công ty hay một phòng ban quá rộng

### Gợi ý viết cho đúng

- Sai hoặc quá rộng: `SME`, `doanh nghiệp`, `thị trường`
- Tốt hơn: `chủ shop online`, `nhân viên CSKH`, `recruiter`, `sales ops manager`

### Điền

- **Job executor của dự án này là:** 
  > Sinh viên / học viên đang tự thực hiện literature review cho thesis hoặc bài nghiên cứu
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > Họ là người trực tiếp dành hàng giờ để đọc paper và loay hoay với các tool hiện tại. Họ có pain rõ nhất và là người ra quyết định cuối cùng trong việc thử một giải pháp mới cho công việc cá nhân. 


---

## Bước 4 — Viết `Core JTBD`

`Core JTBD` là công việc cốt lõi người dùng đang cố hoàn thành.

### Công thức gợi ý

```text
[verb] + [object] + [contextual clarifier]
```

### Ví dụ

- Chưa tốt: `trả lời inbox bằng AI`
- Tốt hơn: `giải quyết câu hỏi trước mua hàng nhanh và chính xác trong giờ cao điểm`

- Chưa tốt: `dùng AI để viết nội dung`
- Tốt hơn: `tạo bản nháp nội dung chiến dịch phù hợp với brand trong thời gian rất ngắn`

### 3 tiêu chí tự kiểm

- [x] Nếu bỏ tool hiện tại đi, job này vẫn còn tồn tại
- [x] Trong câu không có tên sản phẩm, AI, chatbot, app, màn hình
- [x] Câu đang mô tả **điều user muốn hoàn thành**, không phải thứ product đang làm

### Bản nháp 1

**Core JTBD bản nháp:**  
> Dùng AI để tóm tắt paper nhanh hơn

### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: "AI", "tóm tắt"

### Bản chốt

**Core JTBD cuối cùng:**  
> Nắm bắt đủ landscape của một chủ đề nghiên cứu mới để xác định hướng đi và bắt đầu viết trong thời gian giới hạn


---

## Bước 5 — Viết 3 `Job Stories`

Nếu `core JTBD` là job ở mức cốt lõi, thì `job story` giúp bạn thấy
**job này xuất hiện trong hoàn cảnh nào**.

### Format

```text
When [trigger], I want to [motivation], so I can [outcome].
```

### Ví dụ

`When inbox đổ dồn vào buổi tối, tôi muốn có câu trả lời nhất quán ngay lập tức, so I can không mất đơn vì phản hồi chậm.`

### Bảng 3 job stories

| # | Trigger / When | Motivation / I want to | Outcome / so I can | Điều story này cho thấy |
|---|---|---|---|---|
| JS1 | Khi được giao chủ đề thesis và phải nộp đề cương trong 2 tuần | Tôi muốn hiểu nhanh các hướng nghiên cứu chính và tranh luận hiện tại trong chủ đề này| so I can viết phần background và research gap một cách có căn cứ, không bị giảng viên hỏi ngược | Paper landscape mapping là pain point ở giai đoạn đầu — không phải đọc sâu từng paper |
| JS2 | Khi đang đọc một paper và gặp khái niệm không quen, cần hiểu context mà không phải thoát ra Google Scholar | Tôi muốn hiểu khái niệm đó trong ngữ cảnh của field này, kèm paper nào đã define nó | so I can tiếp tục đọc mà không mất mạch và không lãng phí 30 phút đi tìm | In-context understanding là nhu cầu micro — AI có thể serve ngay tại điểm đọc |
| JS3 | Khi đã đọc 15-20 paper và cần viết literature review nhưng không biết tổ chức thế nào | Tôi muốn có dàn ý logic và nắm được các nhánh tranh luận chính, có trích dẫn cụ thể | so I can viết literature review có cấu trúc logic thay vì chỉ liệt kê paper theo thứ tự đọc | Synthesis và structure là pain lớn nhất, đọc xong vẫn không biết nói gì |

### Tự kiểm nhanh

- [x] Mỗi story là một **tình huống thật**, không phải slogan chung chung
- [x] 3 story không trùng hệt nhau
- [x] Sau khi đọc 3 story, tôi hình dung được lúc nào product của mình đáng xuất hiện

---

## Bước 6 — Liệt kê `Current Alternatives`

Qua JTBD lens, đối thủ không chỉ là app cùng ngành.
Đối thủ là **bất kỳ thứ gì user đang "thuê" để làm job**:

- thao tác tay
- file Excel / Google Sheets
- intern / nhân viên
- agency
- ChatGPT / Claude / Gemini
- công cụ chuyên dụng khác
- hoặc thậm chí là **không làm gì cả**

### Bảng alternatives

| Alternative hiện tại | User đang thuê nó để làm gì? | Nó làm tốt gì? | Nó fail ở đâu? | Switching cost hiện tại cao hay thấp? |
|---|---|---|---|---|
| Google Scholar + đọc abstract thủ công | Tìm và lọc paper | Free, toàn diện, trusted| Chậm, không tổng hợp được, không biết paper nào thật sự quan trọng| Thấp — habit, không cần cài gì |
| ChatGPT / Claude | Hỏi về nội dung paper, giải thích khái niệm, tóm tắt đoạn text paste vào| Linh hoạt, trả lời nhanh, giải thích tốt| Không đọc được file PDF dài trực tiếp (bản free), hallucinate citation, không có context về field| Thấp — đã quen dùng |
| Zotero / Mendeley | Quản lý và lưu trữ reference| Tốt cho citation management| Không giúp đọc hay tổng hợp nội dung| Trung bình — đã có library |
| Đọc tay + ghi note Google Docs | Tổng hợp và ghi lại hiểu biết| Flexible, tự kiểm soát| Cực kỳ chậm, khó scale khi số paper tăng| Thấp — workflow quen thuộc |
| Perplexity / Consensus | Tìm kiếm câu trả lời có nguồn từ paper| Nhanh, có citation| Không đọc sâu, không upload file riêng, coverage không toàn diện| Thấp |

### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  
> Combo ChatGPT + Google Scholar + Google Docs vì switching cost thấp và đây là workflow họ đã quen.



---

## Bước 7 — Điền `JTBD Lite Map`

Đây là bản rút gọn của `job map` trong playbook.

### Mục tiêu

Không phải để làm consultant workshop hoàn chỉnh.  
Mục tiêu là nhìn ra:

1. workflow hiện tại của user đi qua những bước nào
2. bước nào đang đau nhất
3. AI có nên chen vào đó không

### 8 bước tham chiếu từ playbook

1. `Define`
2. `Locate`
3. `Prepare`
4. `Confirm`
5. `Execute`
6. `Monitor`
7. `Modify`
8. `Conclude`

> Không nhất thiết bước nào cũng quan trọng như nhau trong dự án của bạn.  
> Nếu ít liên quan, ghi `N/A`, đừng để trống.

### Bảng JTBD Lite Map

| Step | Trong workflow này user đang cố làm gì? | Hôm nay họ đang dùng gì? | Friction / pain hiện tại | Mức đau |
|---|---|---|---|---|
| Define | Xác định scope chủ đề: cần đọc loại paper nào, từ khoá nào, field nào | Hỏi giảng viên + Google + ChatGPT | Không có framework rõ ràng để biết mình đang nhìn đúng góc chưa | High |
| Locate | Tìm paper liên quan đủ để cover landscape | Google Scholar, Semantic Scholar, arXiv | Quá nhiều kết quả, không biết paper nào foundational vs. peripheral, mất 1-2 tiếng chỉ để lọc | High |
| Prepare | Lọc và ưu tiên paper nào đọc trước | Đọc abstract thủ công, hỏi ChatGPT | Tốn thời gian, thiếu context để đánh giá đúng độ quan trọng | Medium |
| Confirm | Xác nhận mình đã có đủ paper để viết literature review chưa | Tự đánh giá hoặc hỏi giảng viên | Không có cách kiểm tra "đủ chưa" — thường chỉ biết khi bị giảng viên hỏi ngược | High |
| Execute | Đọc và hiểu nội dung từng paper | Đọc tay + highlight + ghi note | Chậm, dễ mất mạch khi gặp khái niệm lạ, không có ngữ cảnh so sánh | Medium |
| Monitor | Theo dõi mình đã cover được những cluster nào, còn thiếu gì | Google Docs / Zotero tags | Rất khó hình dung "bức tranh tổng thể" khi đang đọc từng paper riêng lẻ | High |
| Modify | Điều chỉnh hướng đọc khi phát hiện field rộng hơn dự kiến | Hỏi giảng viên, tìm thêm | Mất nhiều thời gian backtrack, đôi khi phải đọc lại từ đầu | Medium |
| Conclude | Tổng hợp thành literature review có cấu trúc | Tự viết từ note | Không biết tổ chức thế nào, hay bị liệt kê thay vì synthesize | High |

### Chốt 2 bước đau nhất

**Bước đau nhất #1:** Locate — tìm đúng paper trong biển kết quả  
**Bước đau nhất #2:** Conclude — tổng hợp thành literature review có cấu trúc  

**Vì sao đây là nơi đáng chú ý nhất:**  
> Với Locate: với số lượng paper khổng lồ, việc tìm đúng paper phù hợp trong biển kết quả là cực kỳ tốn thời gian, nhiều khi phải mò mẫm qua lại giữa Google Scholar và các nguồn khác.  
> Với Conclude: Tự viết từ note dẫn đến việc khó hình dung “bức tranh tổng thể”, dẫn đến văn phong liệt kê thay vì tổng hợp, cần nhiều lần chỉnh sửa để có một luồng narrative mạch lạc.
> AI có lợi thế rõ ở cả hai: xử lý lượng lớn text nhanh (Locate) và tạo structure từ nhiều nguồn (Conclude).

---

## Bước 8 — Chỉ ra `AI Leverage Point`

Sau khi map workflow, mới hỏi:
**AI nên vào đâu, với vai trò gì, và vì sao là ở đó?**

### Nhắc nhanh

- Đừng nhét AI vào chỉ vì "có AI thì nghe hay"
- Nếu pain lớn nhất không nằm ở chỗ AI giải tốt, hãy thành thật ghi ra
- Nếu current alternative đã đủ tốt, project cần xem lại

### Bảng leverage point

| Step | AI nên giúp bằng cách nào? | Vì sao AI hợp ở đây? | Rủi ro chính nếu dùng AI |
|---|---|---|---|
| Locate | Ranking paper theo độ relevance với research question của user; gợi ý các "foundational paper" và cluster chủ đề | AI xử lý được lượng lớn metadata + citation graph + abstract để rank tốt hơn con người đọc thủ công | Hallucinate paper không tồn tại; bias theo training data nếu field mới |
| Conclude | Tạo thematic map từ tập paper user đã đọc; gợi ý cách nhóm paper theo cluster; draft outline literature review | AI có thể cross-reference nhiều paper cùng lúc và identify pattern mà con người khó thấy khi đọc tuần tự | User có thể accept output mà không critical review → literature review sai về mặt học thuật |

### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  
> Bước Locate — giúp sinh viên đi từ "chủ đề mới" đến "có danh sách paper có cấu trúc theo cluster" trong vài phút thay vì vài tiếng.

**Vì sao không phải ở bước khác:**  
> Execute (đọc từng paper) vẫn cần human review đọc để hiểu sâu — AI tóm tắt có thể thiếu nuance quan trọng. Define và Confirm cần input từ giảng viên hướng dẫn, không thể AI quyết thay. Locate là bước thuần thông tin — AI có lợi thế rõ nhất ở đây mà rủi ro học thuật thấp hơn.

---

## Bước 9 — Viết `Product Hypothesis`

Bây giờ mới đến lúc viết hypothesis.

### Công thức gợi ý

```text
Nếu chúng ta giúp [job executor] làm [job / sub-job] tốt hơn ở bước [x],
bằng cách [AI leverage],
thì họ sẽ chuyển từ [current alternative] sang [hướng giải pháp của nhóm],
vì [giá trị rõ nhất].
```

### Bản hypothesis của tôi

> Nếu chúng ta giúp sinh viên thesis làm nắm bắt landscape của chủ đề mới tốt hơn ở bước Locate và Conclude,

bằng cách AI ranking paper theo research question + tạo thematic cluster map từ tập paper đã upload,

thì họ sẽ chuyển từ combo Google Scholar + ChatGPT + Google Docs rời rạc sang PaperPulse,

vì tiết kiệm được 3-5 tiếng đọc thủ công trong giai đoạn đầu thesis và có structure rõ hơn để bắt đầu viết.  

### Tín hiệu sớm nếu hypothesis này đúng

1. User dùng PaperPulse ngay ở đầu thesis (không phải sau khi đã đọc xong) — tức là nó được dùng như starting point, không phải finishing tool
2. User giảm số lần hỏi giảng viên "em nên đọc thêm paper nào?" sau khi dùng PaperPulse

---

## Bước 10 — Liệt kê `Assumptions to Validate`

Job story chưa có research vẫn chỉ là **giả thuyết tốt hơn**, chưa phải sự thật.

### 5 assumption thường đáng kiểm

- Tôi đã chọn đúng `job executor`
- Pain này thật sự đủ đau và xảy ra đủ thường xuyên
- User sẽ đổi khỏi alternative hiện tại nếu có giải pháp tốt hơn
- AI thực sự tạo giá trị ở step tôi chọn
- User đủ tin kết quả AI để đưa vào workflow thật

### Bảng assumptions

| Assumption | Vì sao assumption này rủi ro? | Tôi đang có bằng chứng gì? | Cần validate bằng cách nào tiếp theo? |
|---|---|---|---|
| A1 | Sinh viên đã quen Google Scholar + ChatGPT, switching cost thấp nhưng habit cost cao | Chưa có — chỉ là inference từ experience cá nhân | Phỏng vấn 5-10 sinh viên đang làm thesis: họ mất bao lâu ở bước tìm paper? Có frustrated không? |
| A2 | LLM có thể hallucinate citation hoặc miss paper quan trọng trong field hẹp | Chưa có — chưa test accuracy | Build prototype và test với 1 chủ đề quen thuộc, so sánh kết quả với expert review |
| A3 | Nếu user chỉ dùng sau khi đã đọc xong thì value prop khác hoàn toàn và weaker | Chưa có | Track session timing trong prototype: user upload paper sau bao lâu kể từ khi bắt đầu research? |
| A4 | Có thể user vẫn thích tự organize theo cách riêng — AI-generated structure có thể cảm giác "imposed" | Chưa có | A/B test: nhóm dùng cluster map vs. nhóm tự viết — so sánh quality và thời gian |
| A5 | Đây là rủi ro credibility cao — nếu giảng viên phản đối AI-assisted review thì cả product vô nghĩa | Chưa có — phụ thuộc vào từng trường/giảng viên | Survey thái độ của sinh viên và giảng viên về AI trong academic writing tại các trường target |

### Assumption nguy hiểm nhất nếu tôi đang sai

> A5 — nếu context học thuật (trường, giảng viên, ngành) không chấp nhận AI-assisted literature review, toàn bộ product hypothesis sẽ sập bất kể AI có tốt đến đâu. Đây là assumption cần validate sớm nhất, trước khi build thêm feature.

---

## Bước 11 — Share trong bàn (3')

### Mỗi người / mỗi nhóm chỉ nói 4 thứ

1. **Job executor của bạn là ai**
2. **Core JTBD của bạn là gì**
3. **Step đau nhất đang nằm ở đâu**
4. **AI leverage point + assumption rủi ro nhất là gì**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Câu JTBD này có đang lỡ nhét solution vào không?"**
2. **"Alternative hiện tại của user là gì, và tại sao họ chưa bỏ nó?"**
3. **"Pain mạnh nhất nằm ở bước nào trong workflow, có chắc AI giải tốt được không?"**
4. **"Assumption nào nếu sai thì cả hypothesis sẽ sập?"**

### Ghi nhanh sau khi nghe bàn phản biện

| Ý phản biện tôi nghe được | Nó chạm vào phần nào? | Tôi sẽ giữ / sửa gì? |
|---|---|---|
| | | |
| | | |
| | | |

---

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- [ ] Giữ nguyên `job executor`
- [ ] Sửa `job executor`
- [ ] Giữ nguyên `core JTBD`
- [ ] Sửa `core JTBD`
- [ ] Giữ nguyên `AI leverage point`
- [ ] Sửa `AI leverage point`
- [ ] Giữ nguyên `product hypothesis`
- [ ] Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> _______________________________________________  
> _______________________________________________

### Version cuối cùng tôi nộp

**Job executor:**  
> _______________________________________________

**Core JTBD:**  
> _______________________________________________

**2 bước đau nhất trong workflow:**  
> _______________________________________________

**AI leverage point chính:**  
> _______________________________________________

**Product hypothesis:**  
> _______________________________________________

**Assumption cần validate đầu tiên:**  
> _______________________________________________

---

## Checklist trước khi nộp

- [x] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [x] Tôi đã phân biệt được `job executor` với buyer / influencer.
- [x] `Core JTBD` của tôi không nhét solution vào câu.
- [x] Tôi đã viết đủ 3 `job stories`.
- [x] Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- [x] Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- [x] Tôi đã ghi rõ `assumptions to validate`.
- [ ] Tôi đã sửa version cuối sau khi share trong bàn.

---

## Nếu còn thời gian / làm về nhà

- Phỏng vấn nhanh 1 người dùng thật để kiểm xem `job story` nào là sát nhất.
- So sánh `current alternatives` với project của nhóm theo 3 tiêu chí: nhanh hơn, rẻ hơn, tin hơn.
- Tự hỏi lại một câu khó: **nếu không dùng AI, project này còn tạo giá trị không?**
- Nếu câu trả lời là "không", hãy xem lại liệu nhóm đang giải **job thật** hay chỉ đang tìm chỗ để nhét AI.
