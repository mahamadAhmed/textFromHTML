# Extracting and Processing Text from HTML Page
This Python script extracts text from an HTML page retrieved from a given URL, applies processing steps to the text, and outputs the unique words.

## Data Extraction
The script retrieves HTML content from a specified URL, such as Wikipedia.
It then extracts text from the HTML page, considering specific tags like <p> or headings.
Processing Steps
### Cleaning Data: Removes any symbols or characters that are not relevant to the data.
### Normalization: Converts all text to lower case for uniformity.
### Tokenization: Splits the text into individual words.
### Lemmatization or Stemming: Reduces each word to its root form.
###Stop Words Removal: Eliminates common stop words from the text.
## Output
The script outputs the unique words found in the processed text.
