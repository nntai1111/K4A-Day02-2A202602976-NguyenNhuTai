# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Như Tài
- Mã học viên: 2A202602976
- Nhóm:  C4
- Candidate problem nhóm chọn: Điều chỉnh CV theo từng JD cho Sinh viên / Fresher.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự scan 6 problem từ trải nghiệm làm Java BE & học AI, hoàn thiện top 3 Problem Cards (nổi bật là Bug Triage Java BE). | Mang tới nhóm 3 bài toán thực tế có workflow 5 bước và số đo giảm thời gian rõ ràng. |
| Pitch Problem Card | Pitch trực tiếp Card #1 (Phân loại bug Java Backend) trong 2 phút, giải thích rõ quy trình 5 bước và bottleneck đọc log. | Giúp nhóm có thêm 1 candidate chất lượng ở mảng kỹ thuật (đạt 28 điểm trong bảng score). |
| Challenge bài của bạn khác | Challenge bài research paper của Huy (về rủi ro bỏ sót bài quan trọng) và bài CV của Cường (về rủi ro AI bịa kỹ năng). | Giúp nhóm làm rõ ranh giới kiểm soát rủi ro cho bài CV (AI chỉ lọc từ Master Profile, không bịa đặt). |
| Gom trùng / cluster | Cùng nhóm phân loại 12 candidate problems thành 4 cụm (A, B, C, D) dựa trên pattern bài toán. | Nhóm nhìn rõ 4 mảng bài toán và thu hẹp danh sách phân tích. |
| Chọn candidate problem | Thảo luận, chấm điểm 3 shortlist candidates và đồng thuận chọn đề tài CV Tailoring của Cường. | Nhóm chốt được 1 candidate problem duy nhất có tính khả thi và impact cao nhất. |
| Validation / research | Phỏng vấn 3 sinh viên/fresher, tổng hợp khảo sát 12 ứng viên IT; chủ động tìm báo cáo Jobscan 2025 làm evidence bài báo. | Cung cấp bằng chứng thực tế (26% coi CV tailoring là rào cản) chứng minh nỗi đau có thật cho nhóm. |
| Workflow nhóm | Đóng góp ý kiến hoàn thiện Future Workflow 4 bước và bổ sung cơ chế Fallback (nếu AI sai thì giữ bullet gốc Master Profile). | Workflow nhóm chặt chẽ, có ranh giới con người (Human Boundary) rõ ràng. |
| Problem Statement | Bổ sung ý kiến hoàn thiện các field Actor, Metric (Match Rate >80%) và Boundary cho PS v0 và v1. | Problem Statement v1 đạt độ sắc nét cao, bám sát nỗi đau thật. |
| Rule / Workflow / Agent | Phân tích ma trận mơ hồ/phức tạp, tham gia trả lời 5 câu hỏi chốt để hạ từ Agent xuống AI-Assisted Workflow. | Nhóm thống nhất chọn mô hình Workflow giải phóng 70% thời gian nhưng vẫn kiểm soát rủi ro. |
| Decision | Cùng nhóm thông qua quyết định Go (pilot nhỏ trên 10 JD với 5 ứng viên), xác định 3 chỉ số đo lường và Exit criteria. | Nhóm có kế hoạch pilot thực tế và phương án rút lui an toàn. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là việc chủ động tìm kiếm báo cáo nghiên cứu Jobscan 2025 làm bằng chứng thực tế (evidence) chứng minh nỗi đau CV tailoring có thật, đồng thời đóng góp đề xuất cơ chế kiểm soát ranh giới (Human Boundary): bắt buộc AI chỉ được trích xuất dữ liệu từ Master Profile và phải có đường dẫn truy vết nguồn gốc cho từng bullet đề xuất.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Tham khảo thêm góc nhìn phân loại công việc và diễn đạt lại câu từ | Gợi ý cách viết câu từ mượt mà, mạch lạc hơn cho 6 problem cá nhân | AI gợi ý một số ý tưởng quá xa rời thực tế công việc hằng tuần | Bỏ các gợi ý rườm rà, giữ lại đúng 6 problem gắn liền với trải nghiệm Java BE và học AI thật |
| Problem Card | Phản biện Skeptical PM cho Problem Card #1 | Chỉ ra điểm yếu: người báo lỗi tả quá ngắn khiến AI dễ phân loại nhầm | AI khen chung chung và gợi ý giải pháp Agent quá đà | Đưa thêm điều kiện fallback: nếu câu tả mơ hồ thì AI gán nhãn "Chờ duyệt thủ công" cho Tech lead |
| Workflow | Tham khảo cú pháp Mermaid để vẽ sơ đồ workflow before/after | Tạo khung sơ đồ Mermaid nhanh chóng, chuẩn định dạng | AI vẽ workflow tương lai thiếu bước Human Boundary và không có luồng Fallback | Tự thêm node Review duyệt bài và bổ sung nhánh Fallback giữ nguyên bullet gốc từ Master Profile |
| Research | Tìm kiếm các công cụ/sản phẩm đã có trên thị trường xử lý bài toán CV | Tổng hợp nhanh danh sách 6 công cụ (LinkedIn, Jobscan, Teal, Enhancv, Kickresume, TopCV) | AI đưa ra một số nhận định hời hợt về rủi ro của từng tool mà không dẫn nguồn cụ thể | Tự kiểm tra lại tính năng thực tế của từng tool và tự tổng hợp Research Takeaway cho nhóm |
| Problem Statement | Đặt câu hỏi phản biện lỗ hổng trong Problem Statement v0 | Chỉ ra field Success Metric "Match Rate > 80%" còn mơ hồ về cách đo | AI không đưa ra được công cụ đo cụ thể mà chỉ trả lời chung chung | Bổ sung phương pháp đo Match Rate bằng thuật toán so sánh từ khóa ATS và giới hạn AI không được sửa số liệu thành tích |
| Rule / Workflow / Agent | Thảo luận phản biện việc chọn mức AI phù hợp | Gợi ý khung 5 câu hỏi chốt để so sánh giữa Rule, Workflow và Agent | AI có xu hướng hướng nhóm chọn Agent cho "ngầu" mặc dù bài toán không cần tự chủ | Kiên quyết giữ quan điểm chọn AI-Assisted Workflow vì luồng xử lý tuyến tính và rủi ro Agent quá cao |
| Decision | Gợi ý khung tiêu chí đánh giá cho phần Pilot và Exit criteria | Đưa ra cấu trúc các số cần đo cho một buổi pilot sản phẩm | AI đề xuất chỉ số pilot quá rộng và khó đo trong thời gian ngắn | Sửa lại thành 3 chỉ số cụ thể: Thời gian tạo CV (<10'), Tỷ lệ bullet chấp nhận (>70%), Match Rate (>80%) |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi lắng nghe top 3 problems của các thành viên trong nhóm, tôi nhận ra bài toán của từng người đều mang tính thực tế rất cao. Ban đầu tôi nghĩ đề tài phân loại bug của mình khá hay nhưng sau khi thảo luận tôi nhận thấy bài toán tùy chỉnh CV của Cường có tệp đối tượng rộng hơn, và nỗi đau khá nhức nhối đối với sinh viên hay những người đang tìm kiếm việc làm. Đã có lúc nhóm bị cuốn vào tâm lý "solution-first" khi một số thành viên muốn xây dựng một AI Agent tự động tìm kiếm job và tự nộp CV cho nhà tuyển dụng để tạo sự ấn tượng. Tuy nhiên, tôi và cả nhóm đã cùng nhìn nhận lại rủi ro rất lớn của Agent nếu AI tự ý điền thông tin sai lệch, từ đó hạ mức xuống AI-Assisted Workflow để giữ con người ở vị trí phê duyệt cuối cùng. Trong artifact cuối của nhóm, dấu tay rõ nhất của tôi nằm ở khâu tìm kiếm bằng chứng nghiên cứu thực tế từ báo cáo Jobscan 2025 nhằm chứng minh 26% người tìm việc thực sự bị nghẽn ở khâu tailoring CV, đồng thời trực tiếp thiết lập ranh giới dữ liệu không cho AI tự bịa kỹ năng. Với tôi, điều khó khăn nhất khi hoàn thiện Problem Statement chính là việc xác định ranh giới (boundary) và cơ chế Fallback sao cho chặt chẽ. Nếu AI gợi ý câu từ quá hoa mỹ hoặc không đúng thực tế, hệ thống bắt buộc phải truy vết về Master Profile để người dùng đối chiếu và giữ lại câu gốc. Qua buổi làm việc nhóm này, bài học lớn nhất tôi rút ra được là AI chỉ thực sự phát huy giá trị khi chúng ta định hình rõ ràng quy trình công việc và đặt ra ranh giới kiểm soát an toàn cho con người.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI


