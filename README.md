<p align="center">
<img src="https://app.iplookupapi.com/img/logo/iplookupapi.png" width="300"/>
</p>

# iplookupapi-go: Golang IP Geolocation API

This package is a Golang wrapper for [iplookupapi.com](https://iplookupapi.com) that aims to make the usage of the API as easy as possible in your project.

## Usage

Initialize the API with your API Key (get one for free at [iplookupapi.com](https://app.iplookupapi.com/register)):

```go
iplookupapi.Init("YOUR-API-KEY")
```

Afterwards you can make calls to the API like this:

### Status Endpoint

```go
iplookupapi.Status()
```

### Info Endpoint

```go
iplookupapi.Info({
    "ip": "1.1.1.1",
    "language": "de"
})
```


Find out more about our endpoints, parameters and response data structure in the [docs](https://iplookupapi.com/docs)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[docs]: https://iplookupapi.com/docs
[iplookupapi.com]: https://iplookupapi.com

