### KKBox-s_Music_Recommendation_Challenge
#### 一.資料預處理</br>
 (1)將Object轉成category</br>
    為了後續能將NAN填入資料，因此需要先將object(string)轉成category型態</br>
 (2)處理資料欄位</br>
    -合併資料</br>
     根據song_id和msno，將kaggle提供的其他資料(songs,members,song_extra)合併進train和test中</br>
    -增加新欄位</br>
    因為部分欄位包含多值資料，分別計算個數之後加進新欄位genre_id_count,lyricist_count,composer_count,artist_count
    代表該資料有幾位artist，以此類推。
