The `paginate` function in `string_pagination.py` must be used with 2 parameters, `string` and `amount_of_chars`.

Notes
-----

* `string` parameter is the string that will be paginated. Optimally should be used with a string, but can be used with any object that supports indexing.
* `amount_of_chars` is an integer used for indexing each character. **Must be integer.**

Examples
--------

```py
from string_pagination import paginate

def main(my_string: str):
    print(paginate(my_string, 4))
    # Line above will output ['test', 'test', 'x2']

if __name__ == "__main__":
    main("testtestx2")
```
