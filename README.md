# Yearwise-sequence-separation
This snippet for colab allows you to separate your sequences on the basis of date of concern. 
The key function splits the accession number and date based on the "/" character and the date further into year, month, and day based on the "-" character. 
It also includes a check to ensure that the "/" and "-" characters are present in the header line and that there are at least two items after splitting the string by "/" before accessing the second item. 
If any of these conditions is not true, the key function returns an empty string, effectively ignoring the sequence when sorting.
