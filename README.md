# Book-DISO-WebAssembly

This repository is a knowledge base for the book 《深入浅出 WebAssembly》.

**Thanks for everybody who provided your correction about the book!**


### Corrigendum

1. **[第5页]** 倒数第3行，参数 `“-fast-math”` -> `“-ffast-math”`；[@xuanhun](https://github.com/xuanhun)
2. **[第23页]** 本页后半部分，短语 `“lzay parsing”` -> `“lazy parsing”`；[@manateelazycat](https://github.com/manateelazycat)
3. **[第41页]** 图1-16下方，第二句短语 `“Unread Engine3”` -> `“Unreal Engine3”`；[@woclass](https://github.com/inkydragon)
4. **[第80页]** 本页开头，词语 `“负责”` -> `“复杂”`；[@nullptru](https://github.com/nullptru)
5. **[第100页]** 本页开头，语句 `“WebAssembly.Instance”` -> `“new WebAssembly.Instance”`；[@nullptru](https://github.com/nullptru)
6. **[第103页]** 本页开头，语句 `“WebAssembly.instantiateStreaming”` -> `“WebAssembly.compileStreaming”`；[@nullptru](https://github.com/nullptru)
7. **[第111页]** 倒数第4行，`“增加10个内存页”` -> `“增加5个内存页”`；[@stephenfire](https://github.com/stephenfire)
8. **[第127页]** Shunting-yard 算法规则：
> 这里由于作者理解错误，所以在算法规则的介绍上有些问题。首先“+”运算符是具有”全结合性“的，相反”-“运算符并不具有全结合性。但其两者却均具有**左结合性**，即按照顺序从左至右对表达式进行求值即可求得正确的终值。而 Shunting-yard 算法在进行栈顶运算符判断时的第二条规则便是根据运算符的”左结合性“来判断的，而不是书中作者写的”全结合性“。同样书中后面给出的例子中所提到的全结合性其实也是由于运算符的左结合性。感谢读者的给力反馈！ [@nullptru](https://github.com/nullptru)

9. **[第135页]** 本页多处，单词 `“lable”` -> `“label”`；[@zxh](https://github.com/zxh0)
10. **[第136页]** 本页开头，语句 `“do...while”` -> `“while”`；[@nullptru](https://github.com/nullptru)
11. **[第165页]** 第4行、图2-44及图2-45中，三处 `“1001010”` -> `“10001010”`；[@stephenfire](https://github.com/stephenfire)
12. **[第168页]** 倒数第6行，`“0x08”` -> `“0x80”`；[@stephenfire](https://github.com/stephenfire)
