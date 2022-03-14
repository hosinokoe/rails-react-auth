# rails-react-auth
Rails API + React + devise_token_auth

# backend:
mkdir rails-react-auth && cd rails-react-auth
mkdir backend && cd backend
touch Dockerfile docker-compose.yml entrypoint.sh Gemfile Gemfile.lock

# frontend:
mkdir -p components/{layouts,pages,utils} interfaces lib/api

touch components/layouts/{CommonLayout,Header}.tsx
touch components/pages/{Home,SignIn,SignUp}.tsx
touch components/utils/AlertMessage.tsx
touch interfaces/index.ts
touch lib/api/{client,auth,test}.ts

mv components interfaces lib src
