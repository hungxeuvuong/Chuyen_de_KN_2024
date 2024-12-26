Chuyên đề KNATM: Phát hiện mã độc dựa trên học máy AT180651 - Nguyễn Quốc Hưng Đề tài này phân tích thông tin PE của các tệp exe để phát hiện phần mềm độc hại.

Sử dụng Data_Set_Generator.ipynb để tự tạo ra dataset riêng. 
Nếu không có thể dùng dataset có sẵn là data-set/MalwareDataSet.csv MalwareDataSet.csv chứa tổng cộng 137.444 dữ liệu. Có 96.526 phần mềm an toàn và 40.918 phần mềm độc hại. 
Nó có tổng cộng 9 cột. Thông tin của các cột này như sau: * AddressOfEntryPoint * MajorLinkerVersion * MajorImageVersion * MajorOperatingSystemVersion * DllCharacteristics * SizeOfStackReserve * NumberOfSections * ResourceSize * legitimate

Ta sẽ sử dụng 3 thuật toán phân loại khác nhau. Gồm: * K Nearest Neighbors (KNN) * Decision Tree * Random Forest
