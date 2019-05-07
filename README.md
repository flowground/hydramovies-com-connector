# ![LOGO](logo.png) Hydra Movies **flow**ground Connector

## Description

A generated **flow**ground connector for the Hydra Movies API (version 1.1).

Generated from: https://api.apis.guru/v2/specs/hydramovies.com/1.1/swagger.json<br/>
Generated at: 2019-05-07T17:42:21+03:00

## API Description

Hydra Movies is a streaming service that holds information on thousands of popular movies. 

The Hydra Movies API gives you access to [their entire collection of full movies.](https://hydramovies.com)

Each film returned provides you with the following data:

- Movie Title
- Movie Release Year
- Genre
- Movie Summary
- Movie Poster
- IMDB ID
- IMDB Rating
- Runtime
- Language
- YouTube trailer

## Authorization

This API does not require authorization.

## Actions

### getMovieByIMDBid

> Returns a movie using the films unique IMDB identifier

*Tags:* `Movies`

#### Input Parameters
* `IMDBid` - _required_ - IMDB ID of the movie to return

### getMovieByYear

> Returns a movie based on the year of its release

*Tags:* `Movies`

#### Input Parameters
* `MovieYear` - _required_ - Release year of the movies to return

## License

**flow**ground :- Telekom iPaaS / hydramovies-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
