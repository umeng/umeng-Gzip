#友盟 Windowsphone analytics sdk Gzip 库

修改自： http://dotnetzip.codeplex.com/ 的开源工程

大家都知道windowsphone 7 是没有提供gzip压缩的库的，上传数据的时候，为了压缩只能采用第三方 gzip 库，但又苦于第三方库太大，不好使用
这个些文件是从上面的开源工程中抽出来的比较核心的文件，可以直接使用。

```
string ss = UmengSDK.Third.Gzip.GZipStream.CompressString(string s);  //压缩字符串

```

