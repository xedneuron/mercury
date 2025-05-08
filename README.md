# mercury
* Hyperefficient database querying system and server, serving either clients or other servers.

**mercury** or **mercuryDB** is an experimental tool for efficiently fetching database requests and serving them. It has a unique way of storing this data that is efficient to read, but also allows new data to be used before it is written. A unique querying language, **quicksilver**, is being developed for communication with this tool. "Hard" data is any data that is already stored in its database and can be extracted in a short amount of time. "Soft" data is data still waiting to be written to hard data, but is still accessible, and server requests will prioritize soft data over hard.
