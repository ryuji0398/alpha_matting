# alpha_matting



## やってみたいこと

Alpha mattingを用いてセグメンテーションの境界線をどうにかする

##### step

- Trimapの作成

  →cv2の白色膨張、白色収縮みたいなの使えば作成可能？？

  →モルフォロジー変換

  cv2.erodeとcv2.dilateによるTrimap生成

- 実画像の色を[0,255]での出力にする必要がある

- Trimap上の境界線上の位置情報の取得方法を考える

- 
