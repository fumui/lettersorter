# Letter Sorter
go package for sorting string based on vocals and consonants

## Getting Started 
1. run ``go get github.com/IndBrony/lettersorter`` to pull this package
2. then install the package using ``go build github.com/IndBrony/lettersorter``
3. you're good to go

## Documentation
- SortString(text string) string
  - this function will return the string of sorted vocals and consonant in english alphabet from the input
  - ex: SortString("osama") will return "aaoms"
  - note: for sorting more than 20 char its recommended to use SortStringConcurrent()

- SortStringConcurrent(text string) string
  - essentialy same as SortString(), but this func implements concurrency to perform better at input more than 20 char
  - ex: SortStringConcurrent("osama") will return "aaoms"
