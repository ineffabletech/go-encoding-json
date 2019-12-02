Forked from Golang standard library (https://golang.org/src/encoding/json) with the following additions:

 * Added UnmarshalValueError for errors that occur in custom UnmarshalJSON routines.
 * Added UnmarshalUnknownKeyError for errors throw when encountering an unknown key.
 * Added Key parameter in UnmarshalTypeError, UnmarshalValueError, and UnmarshalUnknownKeyError that describes the path within the JSON where the error occurred.
 * omitnil tag option for Marshaller.

