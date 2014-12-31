nao_getty
=========

タムケンがgigapan downloaderが使えないとか言うので、超簡単に使えるようにカスタマイズしたものです。  
[Gigapan-Downloader-and-stitcher](https://github.com/DeniR/Gigapan-Downloader-and-stitcher)
#### 使い方
1. まず初めに、このリポジトリをクローンします。  
  
  ```
  git clone https://github.com/geojackassShoichi/nao_getty
  ```  
2. 次にクローンしたnao_gettyというディレクトリへ行きます。  
![dir_pth](img/nao_getty.png)

3. ダウンロードしたいGigaPanの写真IDを入力して、kick.shを起動します。
  - 例えば 113792というIDの写真をダウンロードしたい場合は下記のように入力します。  
  ```
  sh kick.sh 113792
  ```

##### 変更点は、2つあります。  
1. デフォルトで最高画質のイメージをダウンロードするようにしてあることです。  
2. 画像をtifでダウンロードすることです。  

ImageMagickが入っていない場合や、通常のPCで起動すると恐らく最後にMemoryAllocationFaildと表示されます。  
ダウンロードだけ出来れば良いと言う場合用のもので、このコメントは無視して下さい。

*****

License
=======

### MIT
##### Copyright (c) 2014 Shoichi Otomo
>
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
