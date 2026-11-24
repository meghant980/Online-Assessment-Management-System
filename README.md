# Smart OA – CSE Department

Updated Expo app with a role-based entry screen and clearer, larger controls.

## Main page
- Student: separate Student Login and Student Sign up actions.
- Admin: login only.
- Technical Staff: login only.
- Demo-account information is intentionally not displayed on the public login page.

## Role permissions
- Admin: CSE student directory, registration approvals, OA creation, room management, OA room assignment, CSV export. No Wi-Fi complaint menu, dashboard card, or complaint management access.
- Student: own profile/session, upcoming OA and assigned room, Wi-Fi complaint submission, receipt download and complaint tracking.
- Technical Staff: room-wise Wi-Fi complaints, status updates and resolution notes.

## Run locally
```bash
npm install
npx expo start --web
```
For Expo Go:
```bash
npx expo start
```

## Demo credentials (for local demonstration only)
- Admin: admin@college.edu / admin123
- Technical Staff: tech@college.edu / tech123
- Student: 23cse001@college.edu / student123

The app uses local AsyncStorage demo data. It is not a production multi-device backend. Do not use real student passwords or sensitive data in this demo.
