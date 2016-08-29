# gh-app

### requirement

```
npm install
```

Install mongodb locally or configure database uri

### development

```
npm run dev
```

### API

github OAuth

```
GET   /api/auth/github
```
get repo content in json format

```
GET    /api/repository
```

add/update files to repo

```
POST   /api/repository

// form data {branch: 'master', path: 'filename', content: 'content here', message: 'commit message here'}
```