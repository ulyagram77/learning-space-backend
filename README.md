## API Reference

`BASE URL`: https://learning-space-backend.vercel.app

#### Get all courses

```bash
  GET /courses
```

#### Get all reviws for a given course

```bash
  GET /reviews?courseId=${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `number` | **Required**. Id of course needed to get reviows for this course |

#### Get single course

```bash
  GET /courses/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `number` | **Required**. Id of item to fetch |




