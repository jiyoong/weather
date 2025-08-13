run weather react 
 - npm install
 - npm run build
 - npm run start

.env.local have 3 setting to edit

VITE_SEARCH_HISTORY_LIMIT
## Sets the maximum number of search history entries 
stored in localStorage to prevent excessive resource usage. ##

VITE_API_KEY
## The API key for accessing the service. Since free accounts 
have limited calls, if data cannot be retrieved, please request another key. ##

VITE_CACHE_EXPIRED_TIME 
## Defines the cache expiration time 
to reduce excessive API requests by displaying recent search data from cache. ##
