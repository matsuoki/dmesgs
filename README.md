# dmesgs
FreeBSDでdmesgした時のログ集・・・になる予定



## Neusoft NSG-01
- default:2GB mSATA SSD
- ADVANTECH NAMB-1330. FWA-1330 あたりのOEMモデルか。
- CPU: Intel(R) Celeron(R) CPU  N2807  @ 1.58GHz (1583.38-MHz K8-class CPU)
- BIOS password: none

### FWA-1330の情報
- https://www.advantech.co.jp/products/6e5d3cbf-5420-4e95-9a4a-9a51d929623b/fwa-1330/mod_d4d54c24-20a9-4e89-80a2-c9259cdee2a4


### FWA-1330との差異
- VGAコネクタが無い。内部に2mmピッチのピンヘッダと、PCB上にパターンはある。2mmピッチのピンヘッダをVGAに変換する奴があるとなんとかなるかも。
- mSPCIe にグラボを接続する奴を試したけど認識せず。BIOSの問題かも。
- SATAコネクタはあるが、HDDステイが無いのと、放熱を考えると貼り付ける所も無い。ナントカ出来そうなんだけど。


