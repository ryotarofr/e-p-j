### build

```bash
gradle build

gradle shadowJar # 今回こっち使う
```

### 実行コマンド

```bash
 java -jar lib/build/libs/lib-1.0-SNAPSHOT-all.jar -m true "/Users/ryotarofujii/Desktop/Java/e-p-j/ExcelCardDT_hnd_shop.xlsm"

 java -cp lib/build/libs/lib-1.0-SNAPSHOT-all.jar org.epj.ExcelTo "/Users/ryotarofujii/Desktop/Java/e-p-j/ExcelCardDT_hnd_shop.xlsm"
```
