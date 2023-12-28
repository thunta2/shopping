#

keytool -exportcert -alias androiddebugkey -keystore "C:\Users\USERNAME\.android\debug.keystore" | "
C:\Users\Admin\Downloads\openssl-0.9.8e_X64\bin\openssl" sha1 -binary | "C:
\Users\Admin\Downloads\openssl-0.9.8e_X64\bin\openssl" base64