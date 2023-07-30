## MERN DevOps

Full Stack MERN Application configuration with DevOps.

### Main domains

| Domain                  | Tech           |
| ----------------------- | -------------- |
| Website Front-End       | React.js       |
| Back-End Server         | Node.js        |
| Primary Database        | MongoDB        |
| Containerization        | Docker         |
| Container Orchestration | Kubernetes     |
| Continuous Integration  | GitHub Actions |
| Continuous Delivery     | Argo CD        |
| Infrastructure as code  | Terraform      |
| Deployment              | AWS            |
| Proxy                   | Nginix         |
| Version Control         | GitHub         |
| Code Editor             | VS Code        |

<!-- ## Features

1. Job referrals to top companies
2. Manage referrals requests
3. Easy apply to jobs referrals
4. Desktop App
5. Mobile App -->

## Getting Started

To get a local copy up and running, please follow these simple steps.
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Here is what you need to be able to run Cal.com.

- Node.js (Version: >=18.x)
- Git
- Docker and Docker Compose
- Yarn _(recommended)_

## Development

### Setup

1. Clone the repo into a public GitHub repository (or fork <https://github.com/sayande2002/refhired.com/fork>). If you plan to distribute the code, keep the source code public to comply with [AGPLv3](https://github.com/sayande2002/refhired.com/blob/main/LICENSE).

   ```sh
   git clone https://github.com/sayande2002/refhired.com
   ```

2. Go to the project folder

   ```sh
   cd refhired.com
   ```

3. Install packages with yarn

   ```sh
   yarn
   ```

4. Set up your `.env` file

   - Duplicate `.env.example` to `.env`
   - Use `openssl rand -base64 32` to generate a key and add it under `NEXTAUTH_SECRET` in the `.env` file.

5. Quick start with `yarn dx`
   This will run the docker compose file in the root directory from the docker image build from @refhired.com/web on `http://localhost:3000/` and docker image build from @refhired.com/prisma (database) on `http://localhost:5432/` and adminar on `http://localhost:8080/`

> - **Requires Docker and Docker Compose to be installed**

```sh
yarn dx
```

6. Once your server has started, go to this url `http://localhost:3000/` and you will see the website running on a Development Server.

### License

-[MIT license](LICENSE)

### Contact 📬

For any query, email <sayandeten@gmail.com>.

Thanks!
