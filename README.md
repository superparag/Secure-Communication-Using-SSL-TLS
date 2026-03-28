# Steps to run:

# Create keystore file
keytool -genkeypair -keyalg RSA -keysize 2048 -validity 365 -alias mykey -keystore keystore.jks

# Run Server
Java SSLServer

# Run Client
Java SSLClient
