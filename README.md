# Country Sorter and Binary Search

This program is designed to sort a list of countries in alphabetical order and perform a binary search to find a specific country based on its country code.

## Features

- Reads a file called "Countries.txt" to populate two arrays: `countryCode` and `countryName`.
- Displays the contents of the arrays in a tabular format, showing the country code and country name.
- Sorts the `countryCode` array using the bubble sort algorithm.
- Prompts the user to enter a country code.
- Performs a binary search on the sorted `countryCode` array to find the index of the target country code.
- If the target country code is found, it displays the country code and country name. Otherwise, it informs the user that the country code is not in the dataset.

## Usage

1. Make sure you have a file named "Countries.txt" in the same directory as the program executable.
2. The "Countries.txt" file should contain a list of countries, with each line containing a country code and country name separated by a pipe (`|`).
   Example:
`USA|United States of America
CAN|Canada
GBR|United Kingdom
AUS|Australia`
3. Compile and run the program.
4. The program will display the unsorted list of countries.
5. The list of countries will be sorted in ascending order based on the country codes.
6. Enter a country code when prompted.
7. The program will perform a binary search on the sorted list and display the corresponding country code and country name if found.
8. If the country code is not found, a message will be displayed indicating that it is not in the dataset.

## Implementation Details

The program uses the following functions:

- `populateArrays`: Reads the "Countries.txt" file and populates the `countryCode` and `countryName` arrays. It returns a boolean value indicating whether the file was successfully located.
- `displayArrays`: Displays the contents of the `countryCode` and `countryName` arrays in a tabular format.
- `swapElements`: Swaps the values of two string elements.
- `bubbleSort`: Sorts the `countryCode` array in ascending order using the bubble sort algorithm.
- `binarySearch`: Performs a binary search on the sorted `countryCode` array to find the index of a target country code. It returns the index if found or -1 if not found.

## File Format

The "Countries.txt" file should follow the format:

`<Country Code>|<Country Name>`

For example:

`cd <project_directory>`

For example:

`USA|United States of America
CAN|Canada
GBR|United Kingdom
AUS|Australia
...`

Ensure that each country's code and name are separated by a pipe (`|`) on each line.

## Note

- The maximum size of the arrays is defined as `MAX_ARR_SIZE`, which is set to 500. You can adjust this value based on your needs.
- The program assumes that the "Countries.txt" file is correctly formatted and contains valid data.

Enjoy using the Country Sorter and Binary Search program!
