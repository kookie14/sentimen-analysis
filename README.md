Sử dụng Kaggle để chạy chương trình
Các bước chạy chương trình:
B1: Tải file main.ipynb 
B2: Upload  trên lên Kaggle 
Gắn path của file dữ liệu cần test vào mục Import the dataset
Ví dụ:
path = '/kaggle/input/int3405-sentiment-analysis-problem/test.csv'
thì ta dùng như dưới đây:
df = pd.read_csv('/kaggle/input/int3405-sentiment-analysis-problem/test.csv')
Trong đó dataset là tập train, df là tập dữ liệu cần test
dataset = pd.read_csv('/kaggle/input/cleandata/data1.csv')
df = pd.read_csv('/kaggle/input/int3405-sentiment-analysis-problem/test.csv')
Gắn path của model ở mục Testing
B3. Chạy tất cả và kết quả trong file submission.csv
