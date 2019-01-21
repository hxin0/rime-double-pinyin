# 小鶴雙拼安裝說明

1. 安裝Rime

    `$ brew cask install squirrel`

1. 下載雙拼配置文件
    - `double_pinyin_flypy.schema.yaml`

1. 把下載的配置文件拷貝到文件夾
    - `~/Library/Rime/`
    - 也可選擇`Squirrel->Settings`打開該文件夾

1. 編輯文件 `default.yaml`
    - 在`schema_list`內添加`- schema: double_pinyin_flypy`
    - 如果不需要保留其他預安裝的輸入法，可以註釋掉
    
    ```
    schema_list:
      # - schema: luna_pinyin
      # - schema: luna_pinyin_simp
      # - schema: luna_pinyin_fluency
      # - schema: bopomofo
      # - schema: bopomofo_tw
      # - schema: cangjie5
      # - schema: stroke
      # - schema: terra_pinyin
      - schema: double_pinyin_flypy
    ```

1. 點擊`Squirrel->Deploy`完成設置

1. 簡繁體轉換
    1. [control]+[`]
    1. 空格鍵選擇小鶴雙拼
    1. 移動箭頭選擇`4. 漢字 → 汉字`
    1. 同樣方法轉換回繁體
    
### 註
雙拼方案文件名：
  - 自然碼雙拼 `double_pinyin.schema.yaml`
  - 智能ABC雙拼 `double_pinyin_abc.schema.yaml`
  - 小鶴雙拼 `double_pinyin_flypy.schema.yaml`
  - MSPY雙拼 `double_pinyin_mspy.schema.yaml`
  - 拼音加加雙拼 `double_pinyin_pyjj.schema.yaml`

