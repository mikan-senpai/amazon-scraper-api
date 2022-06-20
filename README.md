
# Amazon Scraper Api

- A public api which gives you data from Scrapping the amamzon.com website.
- you can check out the api from right here [Rapid-api](https://rapidapi.com/santanud5d80-Ie9iuzqnUwX/api/mikan-amazon-data-scraper/) 

## API Reference

#### base url 

```http
  https://mikan-amazon-scraper.herokuapp.com/
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |


#### Get Amazon Search Results 

```http
  GET /search/{searchQuery}{api_key=}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `searchQuery`      | `string` | **Required**. Name of item to search |
| `api_key` | `string` | **Required**. Your API key |


#### Get Amazon Product Details

```http
  GET /products/{productId}?{api_key=}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `productId`      | `string` | **Required**. Id of item to fetch |
| `api_key` | `string` | **Required**. Your API key |

#### Get Amazon Product Reviews

```http
  GET /products/{productId}/reviews?{api_key=}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `productId`      | `string` | **Required**. Id of item to fetch |
| `api_key` | `string` | **Required**. Your API key |

#### Get Amazon Offers 

```http
  GET /products/{productId}/offers?{api_key=}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `productId`      | `string` | **Required**. Id of item to fetch |
| `api_key` | `string` | **Required**. Your API key |




## Deployment

To deploy this project run

```bash
  npm start
```


