# step1 :: create a ssl certificate (self-singed certificate)

> keytool -genkey -alias selfsigned_localhost_sslserver -keyalg RSA -keysize 2048 -validity 700 -keypass password -storepass password -keystore ssl-server.jks

# step2 :: copy the ssl-server.jks from keys -> resource directory

# step3 :: add ssl config in application.properties

# step4 :: Create a RestController and test the request Mapping