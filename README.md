# React Firebase push notification

React Firebase push notification demo with react-bootstrap

## screenshot
![Logo](https://i.postimg.cc/wTS7nx5n/13-first-notification-displayed-geekystack.png)

## Getting Started
Steps:
```bash
git clone https://github.com/santoshkamble8168/react-firebase-push-notification.git
```

```bash
cd react-firebase-push-notification
```

```bash
npm install
```

```bash
npm start
```


## Configure firebase

2 files need to update:
```bash
public/firebase-messaging-sw.js
```

```bash
src/firebase.js
```

Update with your keys

```bash
const firebaseConfig = {
  apiKey: "Your_API_KEY",
  authDomain: "Your_AUTH_DOMAIN",
  projectId: "Your_PROJECT_ID",
  storageBucket: "Your_STORAGE_BUCKET",
  messagingSenderId: "Your_MESSAGING_SENDER_ID",
  appId: "Your_APP_ID"
};
```

```bash
{vapidKey: 'Your_WEB_PUSH_CERTIFICATE_KEY_PAIR'}
```
Full Article Here: [Push notification in react with firebase](https://geekystack.com/)
