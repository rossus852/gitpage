
  Exploratory Data Analysis (EDA): là một phương pháp phân tích dữ liệu chủ yếu sử dụng các kỹ thuật về biểu đồ, hình vẽ.
  
  Các bước để phân tích EDA:

  - Chuẩn bị dữ liệu.
  - Xử lý dữ liệu: kiểm tra dữ liệu có bị rỗng, trùng hay không (dùng hàm inull).
  
      + Nếu dữ liệu bị rỗng là các biến định luợng thì thay thế bằng giá trị trung vị hoặc trung bình, còn biến phân loại thì thay thế bằng giá trị xuất hiện nhiều nhất.
  - Sau đó thống kê mô tả dữ liệu. (dùng hàm describe).
  - Sau đó phân tích dữ liệu: Phân tích trực quan các biến định lượng dùng histogram. Phân tích trực quan các biến phân loại dùng count plot, bar plot... Phân tích trực quan sự tương quan giữa các biến định lượng dùng scatter plot, joint plot. Phân tích trực giữa biến định luợng và phân loại dùng box plot.
  - Từ biểu đồ rút ra kết luận và định ra các dự báo.

  Việc thực hiện EDA sử dụng trực quan dữ liệu, với thư viện seaborn:

  - Phân tích trực quan các biến định lượng dùng histogram.
  - Phân tích trực quan các biến phân loại dùng count plot.
  - Phân tích sự tương quan giữa các biến định lượng dùng scatter plot, joint plot (biểu đồ kết hợp).
  - Phân tích sự tương quan giữa các biến phân loại và định lượng dùng biểu đồ boxplot
