# Q3 Binary Tree 程式說明

這個程式會從 CSV 檔案讀取 preorder 與 inorder 的資料，
重建二元樹，並輸出對應的 postorder 結果。

## 需要的套件與環境

C++ 編譯器
使用標準 C++ 函式庫
不需要安裝其他額外套件。

## 使用方式

1. 準備一個名為 `input3.csv` 的檔案。

2. 輸入檔格式說明：
   - 以 `#*` 開頭，
   - 每兩行為一題
     - 第一行：preorder
     - 第二行：inorder

   範例如下：
   ```
   #1
   1,2,3,4,5,6
   3,2,4,1,5,6
   ```

3. 執行程式後，會自動產生 `output3.csv`。

4. `output3.csv` 中每一行為一題的 postorder 結果。

---

## 編譯方式

本程式使用 C++ 撰寫。

使用以下指令進行編譯：

```
g++ -std=c++17 q3.cpp -o q3
```

編譯完成後執行：

```
./q3
```

---

## 輸出說明

輸出檔案為 `output3.csv`，
每一行對應一題的 postorder traversal 結果。
