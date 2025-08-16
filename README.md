# CryptAncy (Track your portfolio and monitor live crypto prices instantly.)


## Environment Setup

### Frontend (Client)
Create a `.env` file inside the **Client/** directory and add:
```env
VITE_API_URL="http://localhost:3000"
```

### Backend (Server)
Create a `.env` file inside the **Server/** directory and add:

```env

MONGODB_URI="mongodb://127.0.0.1:27017/cryptotrack"
PORT=3000
CLIENT="http://localhost:5173"
JWT_SECRET="YOUR_JWT_SECRET"
```

