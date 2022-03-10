# Unit-Test for CMake

A set of functions to unit test your cmake macros and functions.

## References

```cmake
ASSERT_STREQ("expected" "value")
```

Issue a ` FATAL_ERROR` message if the two strings are different.

```cmake
EXPECT_STREQ("expected" "value")
```

Issue a ` SEND_ERROR` message if the two strings are different.

```cmake
ASSERT_STRNEQ("expected" "value")
```

Issue a `FATAL ERROR` message if the two strings are equal.

```cmake
EXPECT_STRNEQ("expected" "equal")
```

Issue a ` SEND_ERROR` message if the two strings are equal.

```cmake
ASSERT_EMPTY("value")
```

Issue a ` FATAL_ERROR` message if the string is not empty.

```cmake
EXPECT_EMPTY("value")
```

Issue a ` SEND_ERROR` message if the string is not empty.

```cmake
ASSERT_NOT_EMPTY("value")
```

Issue a `FATAL_ERROR` message if the string is empty.

```cmake
EXPECT_NOT_EMPTY("value")
```

Issue a ` SEND_ERROR`  message if the string is empty.