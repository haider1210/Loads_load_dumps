### `load`:
- **Function**: `json.load(fp)`
- **Description**: Reads JSON data from a file-like object (e.g., a file opened in read mode) and parses it into a Python dictionary.
- **Example**:
  ```python
  import json

  with open('data.json', 'r') as file:
      data = json.load(file)
  print(data)
  ```
- **Use Case**: Use `load` when you have JSON data in a file and you want to convert it into a Python dictionary.

### `loads`:
- **Function**: `json.loads(s)`
- **Description**: Parses a JSON-formatted string and returns a Python dictionary.
- **Example**:
  ```python
  import json

  json_string = '{"name": "Alice", "age": 30}'
  data = json.loads(json_string)
  print(data)
  ```
- **Use Case**: Use `loads` when you have JSON data as a string and you want to convert it into a Python dictionary.

### `dumps`:
- **Function**: `json.dumps(obj, *, indent=None, ... )`
- **Description**: Serializes a Python object (e.g., a dictionary) into a JSON-formatted string.
- **Example**:
  ```python
  import json

  data = {'name': 'Alice', 'age': 30}
  json_string = json.dumps(data)
  print(json_string)
  ```
- **Use Case**: Use `dumps` when you have a Python object that you want to convert into a JSON-formatted string.

### Summary:
- **`load`**: Read JSON data from a file and parse it into a Python dictionary.
- **`loads`**: Parse a JSON-formatted string into a Python dictionary.
- **`dumps`**: Serialize a Python object into a JSON-formatted string.
