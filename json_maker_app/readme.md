This application forms a JSON string from string arrays. The dApp allows adding an element to an existing JSON, deleting it, and reading a value by key.

> To simplify deployment, you can create a dApp that invokes itself. It will follow the same dApp-to-dApp invocation principles.

The JSON maker app has five [callable](https://docs.waves.tech/en/ride/functions/callable-function) functions:

-   **`makeJSONInternal()`**: forms a JSON string value from two initial data arrays;
-   **`makeJSON()`**: forms a JSON string value from two data (keys and their value) arrays;
-   **`addToJSON()`**: adds new entries to the JSON object;
-   **`readByJSONKey()`**: gets a value from the JSON object by its key;
-   **`deleteByJSONKey()`**: removes an entry from the JSON object by its key.
