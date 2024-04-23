# golang-email-checking

- domain: Là tên miền (domain name) được nhập vào để kiểm tra.
- hasMX: Biến boolean để lưu kết quả kiểm tra xem domain có MX record (hồ sơ định tuyến email).
- hasSPF: Biến boolean để lưu kết quả kiểm tra xem domain có SPF record (hồ sơ kiểm tra nguồn gửi email).
- sprRecord: Chuỗi lưu giá trị của SPF record nếu có, trống nếu không có SPF record.
- hasDMARC: Biến boolean để lưu kết quả kiểm tra xem domain có DMARC record (_dmarc.domain).
- dmarcRecord: Chuỗi lưu giá trị của DMARC record nếu có, trống nếu không có DMARC record.