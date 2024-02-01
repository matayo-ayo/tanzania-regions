# tanzania-regions
Tanzania Regions list

## regular 
Contain listed object in below format
```bash
{
    "REGION": "REGION NAME",
    "REG_CODE": REGION POSTCODE,
    "DISTRIC": "DISTRICT NAME",
    "DIS_CODE": DISTRICT POSTCODE,
    "WARD": "WARD NAME",
    "WAR_CODE": WARD POSTCODE,
    "STREET": "STREET NAME",
    "PLACES": "famous, centers or known places of the street"
  }
```

## simplified
A simplified structude based on regular list.
```bash
{
  [{
    "REGION": "REGION NAME",
    "POSTCODE": REGION POSTCODE,
    "DISTRIC": [{
      "NAME": "DISTRICT NAME",
      "POSTCODE": DISTRICT POSTCODE,
      "WARD": [{
        "NAME": "WARD NAME",
        "POSTCODE": WARD POSTCODE,
        "STREETS": [{
          "NAME": "STREET NAME",
          "PLACES": ["streets of places"]
        },]
      },]
    }]
  }]
}
```