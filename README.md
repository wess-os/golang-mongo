# Golang MongoDB

## Routes

| Method | Endpoint | Description |
| ------ | -------- | ----------- |
| GET    | /user/:id | Get user by id |
| POST   | /user | Create user |
| DELETE | /user/:id | Delete user by id |

## Environment Variables

Create a `.env` file in the root directory of the project and add the following variables:

```bash
MONGODB_URI=your_database_uri
```

## Usage

To run the project, simply execute the following command:

```bash
go run main.go
```

This will start the server on port 9000.
