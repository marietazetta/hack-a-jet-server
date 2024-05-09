
# 🛩️ HACK A JET 🛩

This is our private jet operators Alliance, Hack a Jet!


## API Reference

```http
  Operator routes / endpoints
```

| HTTP Verb| URL   |  Request Body             | Action
| :-------- | :------- | :------------ | :------------- | 
| POST | /operators| JSON | Creates a new operators
| GET| /operators| (empty)| Returns all the operators |
| GET| /operators/:operatorId| (empty)| Returns the spcecified operator| 
| PUT| /operators/:operatorId| JSON| Edits the spcecified operator| 


```http
  Aircraft routes / endpoints
```

| HTTP Verb| URL   |  Request Body             | Action
| :-------- | :------- | :------------ | :------------- | 
| POST | /aircrafts| JSON| Creates a new aircraft | 
| GET| /aircrafts| (empty)| Returns all the aircrafts| 
| GET| /aircrafts/:aircraftId| (empty)| Returns the spcecified aircraft| 
| PUT| /aircrafts/:aircraftId| JSON| Edits the spcecified aircraft| 
| DELETE| /aircrafts/:aircraftId | (empty)| Deletes the spcecified aircraft |




## Client Routes

| Path| Description  | 
| :-------- | :------- | 
| `/`| Homepage|
| `/members`| List of Operators | 
|`/fleet`| List of Aircrafts| 
|`/membership`| Become a member of our Alliance|
| `/members/horizon-line` | Horizon Line operator |
| `/members/azure-wings` | Azure Wings operator |
| `/members/private-skies` | Private Skies operator |
| `/fleet/pc24` | Pilatus PC24 aircraft details|
| `/fleet/xls` | Citation XLS+ aircraft details|
| `/fleet/latitude` | Citation Latitude aircraft details|







## Authors

- [@marietazetta](https://github.com/marietazetta)

- [@drialis](https://github.com/Drialis)
