Class 1
=====

## Last Semester's Review

1.char* 存的結尾是\0, 所以length也會多1個char

2.判斷基數偶數不只可用(X % 2 == 0), 也可用2進位判斷, 轉成2進位後判斷最後一個字元 (arr[lastChar] == 0), 即可判斷基偶數

C++ string2binary : 
```
std::string toBinary(int n)
{
    std::string r;
    while(n!=0) {r=(n%2==0 ?"0":"1")+r; n/=2;}
    return r;
}
```

C++ 用&1直接判斷基偶數 : 
```
int main()
{
    bool a = 41 & 1;
    cout<< a;  //1 which is TRUE
    
    bool b = 42 & 1;
    cout<< b;  //0 which is FALSE

    return 0;
}
```

3.正規表示法(Ragular Expression) : https://zh.wikipedia.org/wiki/%E6%AD%A3%E5%88%99%E8%A1%A8%E8%BE%BE%E5%BC%8F#%E5%9F%BA%E6%9C%AC%E8%AF%AD%E6%B3%95

## 1-1 OOP Introduction

1.

