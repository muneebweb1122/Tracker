# Location Tracker (Web) - Phone Setup

## 1. Firebase (phone browser se)
1. console.firebase.google.com -> **Add project** (Google Analytics off).
2. **Build -> Authentication -> Get started -> Email/Password -> Enable**.
3. **Build -> Firestore Database -> Create database** (production mode).
4. Firestore -> **Rules** tab -> `firestore.rules` ka text paste karke **Publish**.
5. Project settings (gear) -> **Your apps** -> Web icon `</>` -> app register karein -> `firebaseConfig` copy karein.
6. `index.html` mein `PASTE YOUR FIREBASE CONFIG HERE` wali jagah apni values paste karein.

## 2. Free hosting (HTTPS zaroori hai, warna location nahi chalti)
GitHub Pages (phone se):
1. github.com par account banayein -> **New repository** (public), naam `tracker`.
2. **Add file -> Upload files** -> `index.html` upload karein -> Commit.
3. **Settings -> Pages -> Branch: main / root -> Save**.
4. 1-2 minute baad link milega: `https://USERNAME.github.io/tracker/`

## 3. Firebase authorized domain
Firebase -> Authentication -> Settings -> **Authorized domains** -> `USERNAME.github.io` add karein.

## 4. Use
Dono friends link kholein, account banayein, UID share karein, request/accept karein, aur friend "Share my live location" ON kare.
Note: location tab hi update hoti hai jab page khula ho.
