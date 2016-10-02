# watermater-reading

>> figure,imshow(I1)
>> BW = I1;
>> pre_fsr(I,138,164);
>> )
 )
 ↑
错误: 圆括号或方括号不对称或异常。
 
>> imshow(R)
>> BW = I1;
>> fsrRegiongrow2(138,164,8);
>> imshow(R)
>> I2 = bersen(I);
未定义函数或变量 'bersen'。
 
是不是想输入:
>> I2 = bernsen(I);
>> imshow(I2)
>> I2 = im2bw(I);
>> )
 )
 ↑
错误: 圆括号或方括号不对称或异常。
 
>> imshow(I@)
 imshow(I@)
          ↑
错误: 圆括号或方括号不对称或异常。
 
>> imshow(I2)
>> pre_fsr(I,138,164);
>> BW = I2;
>> fsrRegiongrow2(138,164,8);
>> imshow(R
 imshow(R
         ↑
错误: 表达式或语句不正确--可能 (、{ 或 [ 不对称。
 
是不是想输入:
>> imshow(R)
>> fsrRegiongrow2(168,348,8);
>> )
 )
 ↑
错误: 圆括号或方括号不对称或异常。
 
>> imshow(R)
>> imshow(I2)
>> I3 = close(I2);
错误使用 close
图形句柄无效。
 
>> I3 = CLOSE(I2);
找不到 'CLOSE' 的完全匹配项(区分大小写)。

最接近的匹配项为: close(在 E:\MATLAB\toolbox\matlab\graphics\close.p 中)

 
是不是想输入:
>> I3 = close(I2);
错误使用 close
图形句柄无效。
 
>> I3 = imopen(I2);
输入参数的数目不足。

出错 imopen (line 40)
se = images.internal.strelcheck(se_, mfilename, 'SE', 2);
 
>> se = [1;1;1];
>> se

se =

     1
     1
     1

>> I3 = imopen(I2,se);
>> imshow(I3)
>> BW = I3;
>> fsrRegiongrow2(168,348,8);
>> imshow(R)
>> pre_fsr(I,138,164);
>> BW = I3；
 BW = I3；
        ↑
错误: 输入字符不是 MATLAB 语句或表达式中的有效字符。
 
>> BW = I3;
>> fsrRegiongrow2(168,348,8);
>> imshow(R)
>> se = strel('rectangle',[25,25]);
>> I3 = imopen(I2,se);
>> imshow(I3)
>> se = strel('rectangle',[5,5]);
>> I3 = imopen(I2,se);
>> imshow(I3)
>> I3 = imclose(I2,se);
>> imshow(I3)
>> se = strel('rectangle',[2,2]);
>> I3 = imclose(I2,se);
>> imshow(I3)
>> se = strel('rectangle',[3,3]);
>> I3 = imclose(I2,se);
>> imshow(I3)
>> se = strel('rectangle',[4,4]);
>> I3 = imclose(I2,se);
>> imshow(I3)
>> pre_fsr(I,138,164);
>> BW = I3;
>> fsrRegiongrow2(168,348,8);
>> imshow(R);
>> pre_fsr(I,138,164);
>> imshow(R)
>> BW = I3;
>> fsrRegiongrow2(168,348,8);
>> imshow(R)
>> se = strel('rectangle',[3,3]);
>> I3 = imclose(I2,se);
>> imshow(I3)
>> fsrRegiongrow2(168,348,8);
>> imshow(R)
>> I4 = R;;
>> imshow(I4);
>> I5 = imerode(I4,se);
>> imshow(I5)
>> se = strel('rectangle',[4,4]);
>> I5 = imerode(I4,se);
>> imshow(I5)
>> se = strel('rectangle',[10,10]);
>> I5 = imerode(I4,se);
>> imshow(I5)
>> imshow(I4)
>> I5 = bwareaopen(I4);
错误使用 bwareaopen>parse_inputs (line 80)
输入参数的数目不足。

出错 bwareaopen (line 63)
[bw,p,conn] = parse_inputs(varargin{:});
 
>> I5 = bwareaopen(I4,2);
>> imshow(I5);
>> I5 = bwareaopen(I4,3);
>> imshow(I5);
>> I5 = bwareaopen(I4,10);
>> imshow(I5)
>> I5 = bwareaopen(I4,20);
>> figure,imshow(I5)
>> I5 = bwareaopen(I4,50);
>> figure,imshow(I5)
>> I5 = bwareaopen(I4,100);
>> figure,imshow(I5)
>> I5 = bwareaopen(I4,500);
>> figure,imshow(I5)
>> I5 = bwareaopen(I4,1000);
>> figure,imshow(I5)
>> I5 = bwareaopen(I4,5000);
>> figure,imshow(I5)
>> I4 = ~I4;
>> imshow(I4)
>> imshow(I4)
>> I5 = bwareaopen(I4,50);
>> imshow(I5)
>> I5 = bwareaopen(I4,60);
>> I5 = bwareaopen(I4,100);
>> imshow(I5)
>> I5 = bwareaopen(I4,150);
>> imshow(I5)
