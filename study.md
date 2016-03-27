# JSON Study

## Instructions

Read this document entirely. Follow any links and study their content. Readings
and activities are **required** unless otherwise indicated.

## JSON

JSON is a way to represent data. It's typically used to communicate data between
a back-end (*api*) and a front-end (*client*). JSON is a string with a very
specific format. JSON is formally defined [here](http://www.json.org/).

[Example JSON strings](http://json.org/example.html) are a great way to become
familiar with the format.

JSON is not a dictionary. JSON is not an object, nor is it an object literal.
JSON is only a string with a specific format.

JSON cannot have comments, since it is just a string. Putting comments in JSON,
or otherwise treating JSON as if it is a JavaScript object literal, is a common
source of hard-to-debug errors.

JSON cannot have methods, since it is a data exchange format. Since it only
represents data, it cannot have behavior. It cannnot have behavior because it is
not an object.

JSON only looks like an object. It is not an object.

## JSON Example

As it makes sense to you please write the following in JSON format:

-  Jason has many things...
- A Cat named Mr.Kitty
- Two roomates named Dave and Miller
- A Love of the Red Sox, Patriots and Bruins
- Has lived in two places recently: 123 Fake street, and 2 Muchinfo Road

```json
{ "jason": {
  "info": {
    { "pets": {
      "name" : "kitty",
      "species": "cat"
        }
      },
    {"interests": {
      "sports" : ["Red Sox", "Patriots", "Bruinds"]
      }
    },
    {"current residency": {
        "name": "user info",
        "address": "12 somewhere over the rainbow ave.",
        "roomates": [
          {"person": {
            "name": "Dave"
          }
        },
          {"person2": {
            "name": "Miller"
            }
          }
        ]
      }
    },
    {"places lived": [
      {"place1": {
        "street": "123 Fake street"
        }
      },
      {"place2": {
        "street": "2 Muchinfo Road"
        }
      }
    ]
  }
}
}}


```

...I forgot, my roomate Dave has two goldfish, one named Bob (he's red) and the
other named Mr.MagicNibbles (yellow) and bites a bit. Please copy the JSON you
already wrote and include the information about Dave's fish.

```json
{ "jason": {
  "info": {
    { "pets": [
      {"pet 1": {
      "name" : "Bob",
      "species": "Goldfish",
      "color": "Red",
      "owner": "Dave",
        }
      },
      {"pet 2": {
      "name": "Mr. MagicNibbles",
      "color": "Yellow",
      "owner": "Dave"
      }
      }
      {"pet 3": {
        "name": "Kitty",
        "species": "Cat",
        "owner": "jason"

      }
      },
      ]
      },
    {"interests": {
      "sports" : ["Red Sox", "Patriots", "Bruinds"]
      }
    },
    {"current residency": {
        "name": "user info",
        "address": "12 somewhere over the rainbow ave.",
        "roomates": [
          {"person": {
            "name": "Dave"
          }
        },
          {"person2": {
            "name": "Miller"
            }
          }
        ]
      }
    },
    {"places lived": [
      {"place1": {
        "street": "123 Fake street"
        }
      },
      {"place2": {
        "street": "2 Muchinfo Road"
        }
      }
    ]
  }
}
}}
```

## JSON Methods

Using the JSON your wrote above, can you write a method on the JSON?

```json
No, json only has data. You cannot add behaviors(methods) or it will cause errors.
```

## JSON Comments

Using the JSON your wrote above, can you write a comment in the JSON?

```json
No, json is not an object -- it is a string. You cannot add comments or it will cause errors/bugs.
```
