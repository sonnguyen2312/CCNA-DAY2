# CCNA - Ngày 2: Subnetting
- Topology: 2 switch, 4 PC.
- Cấu hình:
  - VLAN 20 (172.16.20.0/23): PC1 (172.16.20.10), PC2 (172.16.20.11).
  - VLAN 30 (172.16.30.0/23): PC3 (172.16.30.10), PC4 (172.16.30.11).
- Kết quả: 
  - Ping thành công trong VLAN 20 (PC1 → PC2).
  - Ping thất bại từ VLAN 20 → VLAN 30 (do chưa có router).
- Bài tập: Chia subnet 172.16.0.0/16 thành 8 subnet /19, mỗi subnet 8,190 host.
  - Dải: 172.16.0.0/19 – 172.16.31.255, 172.16.32.0/19 – 172.16.63.255, ..., 172.16.224.0/19 – 172.16.255.255.
- Ảnh topology:
- ![image](https://github.com/user-attachments/assets/c659df71-326e-4b86-bc4b-5e0a7fa85555)
![image](https://github.com/user-attachments/assets/fcc07366-7a10-4e74-b2b8-40d6c441fd4a)
