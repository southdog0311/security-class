# security-class

RSA-AES 混合加密
檔案:
RSA-AES.ipynb : 主程式檔
private.pem : rsa私鑰
public.pem : rsa公鑰
encrypted_data.bin : aes 金鑰和內容
name.txt 輸入

執行:
ipynb 檔案依序執行
利用 pycryptodome 套件
其分為三部分，第一部分為生成 rsa 公私鑰，並將其分別儲存。
第二部分，輸入檔案加密，取出公鑰，建立aes金鑰，利用rsa加密，再利用aes加密檔案，並將結果輸出存檔中。
第三部分，解密，讀取金鑰解鎖，輸出txt內容。

結果:
經過加解密，檔案內容並不會被修改。
