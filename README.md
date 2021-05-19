# String Methods

# .length()

### Description of what method does:

returns the number of characters that the string contains.

### When to use:

when you want to find the number of characters that the string contains

### Example 1:

```jsx
const str = 'this string has 29 characters'
console.log(str.length) // 29
```

# .trim()

### Description of what method does:

removes white spaces from the beginning and end of a string

### When to use:

when processing the string of a user input field. It is easy to accidentally add spaces, and this ensures you handle the relevant characters.

### Syntax:

```jsx

```

### Example 1:

```jsx
const str = '     the secret to life is 42         '
console.log(str.trim()) // "the secret to life is 42"
```

### Example 2:

```jsx

```

### Example 3:

```jsx

```

# .includes()

### Description of what method does:

determines if a substring is contained in a larger string and returns true or false

### When to use:

string matching for searching/parsing

### Syntax:

```jsx

```

### Example 1:

```jsx
const author = 'George Orwell'
const userSearchTerm1 = 'George'
const userSearchTerm2 = 'Douglas'

console.log(author.includes(userSearchTerm1)) // true
console.log(author.includes(userSearchTerm2)) // false
```

### Example 2:

```jsx

```

### Example 3:

```jsx

```

# .indexOf()

### Description of what method does:

returns the index of the substring within the string. If the substring is not contained in the original string, it will return -1.

### When to use:

when you want to find the index of a substring

### Syntax:

```jsx

```

### Example 1:

```jsx
const author = 'George Orwell'
const userSearchTerm1 = 'Orwell'
const userSearchTerm2 = 'Douglas'

console.log(author.indexOf(userSearchTerm1)) // 7 

console.log(author.indexOf(userSearchTerm2)) // -1
```

### Example 2:

```jsx

```

### Example 3:

```jsx

```

# .toUpperCase()

### Description of what method does:

returns a string with all upper case letters

### When to use:

when you want to capitalize all the letters in a string

### Syntax:

```jsx

```

### Example 1:

```jsx
const str = 'We are some small letters that want to be big'
console.log(str.toUpperCase()) // 'WE ARE SOME SMALL LETTERS THAT WANT TO BE BIG"
```

### Example 2:

```jsx

```

### Example 3:

```jsx

```

# .toLowerCase()

### Description of what method does:

returns a string with all lower case letters

### When to use:

when you want to return all the letters of a string to lowercase

### Syntax:

```jsx

```

### Example 1:

```jsx
const str = 'This has BIG LETTERS. They want to all be small.'
console.log(str.toLowerCase()) // 'this has big letters. they all want to all be small.'
```

### Example 2:

```jsx

```

### Example 3:

```jsx

```

# .replace()

### Description of what method does:

returns a string with a pattern replaced by a replacement string. It takes either a regex or a string as the pattern. With a regex you can globally replace all matches (using the g option), but with a string it will only replace the first occurrence. In the example below, you will notice that world is replaced only once in the first call since it uses a string pattern.

### When to use:

When you want to replace a string with a new value

### Syntax:

```jsx

```

### Example 1:

![String%20Methods%201be09a3a1e3e4dcbaf6191c6f97647ae/Untitled.png](String%20Methods%201be09a3a1e3e4dcbaf6191c6f97647ae/Untitled.png)

### Example 2:

```jsx

```

### Example 3:

```jsx

```

# .slice()

### Description of what method does:

extracts a section of a string based on the index supplied and return it as a new string.

### When to use:

when you know the structure of a sting and want to retrieve a certain portion

### Syntax:

```jsx

```

### Example 1:

![String%20Methods%201be09a3a1e3e4dcbaf6191c6f97647ae/Untitled%201.png](String%20Methods%201be09a3a1e3e4dcbaf6191c6f97647ae/Untitled%201.png)

### Example 2:

![String%20Methods%201be09a3a1e3e4dcbaf6191c6f97647ae/Untitled%202.png](String%20Methods%201be09a3a1e3e4dcbaf6191c6f97647ae/Untitled%202.png)

### Example 3:

```jsx

```

# .split()

### Description of what method does:

takes a separator which you want to split apart the string on, and it returns an array of strings

### When to use:

when you know your string uses a certain character to separate data, or if you want to operate on specific substrings individually.

### Syntax:

```jsx

```

### Example 1:

### Example 2:

```jsx

```

### Example 3:

```jsx

```

# .repeat()

### Description of what method does:

returns a string consisting of the elements of the object repeated the given number of times.

### When to use:

when you want to repeat a string

### Syntax:

```jsx

```

### Example 1:

![String%20Methods%201be09a3a1e3e4dcbaf6191c6f97647ae/Untitled%203.png](String%20Methods%201be09a3a1e3e4dcbaf6191c6f97647ae/Untitled%203.png)

### Example 2:

```jsx

```

### Example 3:

```jsx

```

# .match()

### Description of what method does:

retrieves the matches when matching a string against a regular expression

### When to use it:

when you want to return an array of matching strings

### Syntax:

```jsx

```

### Example 1:

![String%20Methods%201be09a3a1e3e4dcbaf6191c6f97647ae/Untitled%204.png](String%20Methods%201be09a3a1e3e4dcbaf6191c6f97647ae/Untitled%204.png)

### Example 2:

```jsx

```

### Example 3:

```jsx

```

# .charAt()

### Description of what method does:

returns the string character at a given index.

### When to use:

When you want to find a character at a given index

### Syntax:

```jsx

```

### Example 1:

![String%20Methods%201be09a3a1e3e4dcbaf6191c6f97647ae/Untitled%205.png](String%20Methods%201be09a3a1e3e4dcbaf6191c6f97647ae/Untitled%205.png)

### Example 2:

```jsx

```

### Example 3:

```jsx

```

# .charCodeAt()

### Description of what method does:

returns the unicode of the character at a specified index in a string. This an UTF-16 cone integer between 0 and 65535.

### When to use:

when you need to find the unicode character of a specific index in a string

### Syntax:

```jsx

```

### Example 1:

![String%20Methods%201be09a3a1e3e4dcbaf6191c6f97647ae/Untitled%206.png](String%20Methods%201be09a3a1e3e4dcbaf6191c6f97647ae/Untitled%206.png)

### Example 2:

```jsx

```

### Example 3:

```jsx

```
