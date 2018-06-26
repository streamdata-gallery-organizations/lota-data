---
name: Lota Data
x-slug: lota-data
description: ""
image: ""
x-kinRank: "7"
x-alexaRank: "0"
tags: Lota Data
created: "2018-06-26"
modified: "2018-06-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lota-data/master/_listings/lota-data/apis.md
specificationVersion: "0.14"
apis:
- name: Lota Data Get Events
  x-api-slug: lota-data
  description: Find event occurrences in the area. returns results at specific place
    and time, event groups are expanded for every occurrence..
  image: ""
  humanURL: http://lotadata.com
  baseURL: https://api2.lotadata.com//v2//events
  tags: Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lota-data/master/_listings/lota-data/events-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lota-data/master/_listings/lota-data/events-get-openapi.md
- name: Lota Data Get Events
  x-api-slug: lota-data
  description: Get specific event details..
  image: ""
  humanURL: http://lotadata.com
  baseURL: https://api2.lotadata.com//v2//events/{id}
  tags: Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lota-data/master/_listings/lota-data/eventsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lota-data/master/_listings/lota-data/eventsid-get-openapi.md
- name: Lota Data Get Places
  x-api-slug: lota-data
  description: Venues, landmarks, regions, these are all places to search..
  image: ""
  humanURL: http://lotadata.com
  baseURL: https://api2.lotadata.com//v2//places
  tags: Places
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lota-data/master/_listings/lota-data/places-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lota-data/master/_listings/lota-data/places-get-openapi.md
- name: Lota Data Get Places
  x-api-slug: lota-data
  description: Get specific place details.
  image: ""
  humanURL: http://lotadata.com
  baseURL: https://api2.lotadata.com//v2//places/{id}
  tags: Places
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lota-data/master/_listings/lota-data/placesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lota-data/master/_listings/lota-data/placesid-get-openapi.md
- name: Lota Data
  x-api-slug: lota-data
  description: ""
  image: ""
  humanURL: http://lotadata.com
  baseURL: https://api2.lotadata.com//v2
  tags: Lota Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/lota-data/master/_listings/lota-data/openapi.md
x-common:
- type: x-documentation
  url: https://docs.lotadata.com/
- type: x-website
  url: http://lotadata.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---