# 氣泡排序 (Bubble Sort)

## 說明

這是一個使用 Python 實作的氣泡排序演算法。

## 演算法原理

氣泡排序是一種簡單的排序演算法，透過重複比較相鄰元素並交換位置，將最大的元素逐步「氣泡」到陣列末端。

## 時間複雜度

- 平均：O(n²)
- 最差：O(n²)
- 最佳：O(n)（已排序時）

## 使用方式

```python
from bubble_sort import bubble_sort

nums = [64, 34, 25, 12, 22, 11, 90]
sorted_nums = bubble_sort(nums)
print(sorted_nums)  # [11, 12, 22, 25, 34, 64, 90]
```

## 執行

```bash
python3 bubble_sort/bubble_sort.py
```