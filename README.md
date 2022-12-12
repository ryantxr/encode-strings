# StringEncoder
Encodes and decodes strings. This is a very slim library to encode and decodes strings, somewhat similar to hashids.
The encoded string can be decoded to get the original string.

This is not encryption. Do not use it to encode sensitive information.

## Use case
Sometimes I want to pass some data in a URL and I don't want that data to be publicly visible.
This is purely for esthetic purposes to discoourage the user from looking at the data.
I want the user to think of this as a 'code'.
If the user goes through the hassle of understanding how to decode the string, they cannot get access to anything of consequence.

1. The generated string should be as short as we can make it.
2. The generrated string should consist of characters that can be in a URL.
