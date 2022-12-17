# Datalastic live ship tracking API #
The Datalastic live ship tracking API is a tool designed for programmers to access real-time vessel movement data. This includes information on a ship's speed, course, heading, and destination. The API allows developers to retrieve this data in order to track the movements of vessels in real-time. Its primary purpose is to provide a convenient way for programmers to access information about the current location and activities of ships.


[Live Ship Tracking API](https://www.worldindata.com/api/Datalastic-live-ship-tracking-api)

Worldindata API marketplace aims to improve the usability of APIs for users. It does this by indexing a variety of third party APIs and organizing them in a user-friendly manner. This makes it easier for developers to find and access the APIs they need, saving time and effort in the process. By streamlining the API discovery process, Worldindata API marketplace helps make APIs more accessible and user-friendly for all.


## Markets, Industry, and Sectors for the API ##

**Industry and Sectors**
- freight
- maritime
- logistics
- import
- export 
- trade

**Client Types**
- freight and logistics companies
- importers
- exporters
- international traders




## API JSON output, Objects and Parameters ##
The GET /api/v0/vessel endpoint allows users to retrieve real-time vessel tracking data through the Datalastic live ship tracking API.


**filter parameters**
- uuid
- mmsi
- imo
- days
- from
- to

```
{
    "data": {
        "uuid": "b8625b67-7142-cfd1-7b85-595cebfe4191",
        "name": "MAERSK CHENNAI",
        "mmsi": "566093000",
        "imo": "9525338",
        "eni": null,
        "country_iso": "SG",
        "type": "Cargo - Hazard A (Major)",
        "type_specific": "Container Ship",
        "lat": 6.303473,
        "lon": 3.201678,
        "current_draught":13.1
        "speed": 0,
        "course": 326,
        "navigational_status": "Under Way using engine" 
        "heading": 226,
        "destination": "NGAPP>TGLFW",
        "dest_port": "LOME"
        "dest_port_unlocode": "TGLFW"
        "dep_port": "JEBEL ALI [AE]"
        "dep_port_unlocode": "AEJEA"
        "last_position_epoch": 1620484020,
        "last_position_UTC": "2021-05-08T14:27:00Z"
        "atd_epoch": 1621469820
        "atd_UTC":"2021-05-20T00:17:00Z"
        "eta_epoch": 1622980800
        "eta_UTC":"2021-06-06T12:00:00Z"
      },
}

```

**Objects**
- data
- uuid
- name
- mmsi
- imo
- eni
- country_iso
- type
- type_specific
- positions
- lat
- lon
- current_draught
- speed
- course
- heading
- navigational_status
- heading
- destination
- dest_port

## Software Development Kits ##
The Datalastic real-time ship tracking API offers SDKs in JAVA, Ruby, Python, JavaScript, and PHP. These SDKs make it easy for developers to integrate the API into their applications, regardless of the programming language they use.


### Disclaimer of ownership ###
Worldindata is a third-party API marketplace that connects developers with data providers. We do not own the data that is provided through our platform, but rather strive to make it more user-friendly and easily accessible. Our team is made up of big fans of the live ship tracking API and Datalastic, and we are committed to helping developers find the data they need. Please note that the use of data from Worldindata is subject to the terms and conditions set forth by the data providers.


[Worldindata](https://www.worldindata.com)
