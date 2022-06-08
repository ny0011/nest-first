h3. 컨트롤러

- nest g controller [UserController]
- src에 이미 자동으로 생성되어 있음

h3. 리소스

- nest g resource Users
- 설정

```
  ? What transport layer do you use? REST API
  ? Would you like to generate CRUD entry points? Yes
  CREATE src/users/users.controller.spec.ts (566 bytes)
  CREATE src/users/users.controller.ts (894 bytes)
  CREATE src/users/users.module.ts (247 bytes)
  CREATE src/users/users.service.spec.ts (453 bytes)
  CREATE src/users/users.service.ts (609 bytes)
  CREATE src/users/dto/create-user.dto.ts (30 bytes)
  CREATE src/users/dto/update-user.dto.ts (169 bytes)
  CREATE src/users/entities/user.entity.ts (21 bytes)
  UPDATE src/app.module.ts (322 bytes)
```
