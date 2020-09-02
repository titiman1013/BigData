# Pandas

> 판다스는 다량의 데이터를 엑셀의 형태로 보여주는 것이 가능
>
> Numpy를 사용하여 숫자 계산에 대해서는 강력한 퍼포먼스를 보임



- 판다스 라이브러리 호출 후 파일 읽어와 저장

```python
import pandas as pd
data_frame = pd.read_csv('data/friend_list.csv')
```



- 데이터 출력

```python
data_frame
```

![image-20200902214242164](Pandas.assets/image-20200902214242164.png)



- 앞부터 두개만 출력

```python
data_frame.head(2)
```

- 뒤부터 두개만 출력

```python
data_frame.tail(2)
```



