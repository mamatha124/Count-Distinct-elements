# Count-Distinct-elements in python
n = int(input())
arr = [int(input()) for i in range(n)]
distinct_elements = []
for i in range(n):
    if arr[i] not in distinct_elements:
        distinct_elements.append(arr[i])
print("There are", len(distinct_elements), "distinct element in the array.")
