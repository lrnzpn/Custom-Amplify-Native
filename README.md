# AWS Amplify + React Native / Custom Setup Authentication
Follow the steps here: https://fullstackserverless.github.io/docs/auth1-02

### Why the custom setup?
The standard UI from Amplify doesn't mean customer UX requirements, so authentication data is exposed which means there's a risk of information security. 
This repository adds the ```react-native-keychain``` library to store tokens in a more secure place than localStorage or AsyncStorage in the case of React Native.

**For more on AWS Amplify, see here:** https://fullstackserverless.github.io/docs/amplify-00
