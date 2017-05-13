# Quiz: Practicing Conditionals with Vowels

## Objectives

You will answer a series of multiple choice questions to help you practice the following:

1. Flow control and the use of `if`, `elsif`, and `else` statements.
2. Flow control and the use of `case` statements.
3. Using comparative operators.

The questions in this quiz are predicated on the idea of building methods that can determine if a letter is a vowel or a consonant. For the purposes of this quiz, vowels will be `"a"`, `"e"`, `"i"`, `"o"`, and `"u"` (sorry, but you're not in the club, `"y"`).

???

# Conditional Vowels

?: Checking for vowels with `if`, `elsif`, and `else`

We're building a method, `vowels_with_if_elsif` that will take in a letter and return `true` if that letter is a vowel and `false` if that letter is a consonant.

```ruby
def vowels_with_if_elsif(letter)
  < fill me in!! >
end
```

Which of the following is the correct implementation of `if`, `elsif`, and `else`?

(X)
```ruby
if letter == "a"
  true
elsif letter == "e"
  true
elsif letter == "i"
  true
elsif letter == "o"
  true
elsif letter == "u"
  true
else
  false
end
```
( )
```ruby
if letter = "a"
  true
elsif letter = "e"
  true
elsif letter = "i"
  true
elsif letter = "o"
  true
elsif letter = "u"
  true
else
  false
end
```

?: What would the following statement return?

```ruby
letter = "b"

if letter == "a" || letter == "e" || letter ==  "i" || letter == "o" || letter == "u"
  "vowel"
else
  "not a vowel"
end
```

( )vowel (X)not a vowel

?: Checking for vowels with `case`

The method `vowels_with_case` takes in a letter as an argument and uses a `case` statement to determine if that letter is a vowel.

```ruby
def vowels_with_case(letter)
  case letter
  < fill me in! > "a"
    true
  < fill me in! > "e"
    true
  < fill me in! > "i"
    true
  < fill me in! > "o"
    true
  < fill me in! > "u"
    true
  else
    false
  end
end
```

Which keyword correctly replaces `< fill me in! > `?

( )`if` ( )`elsif` (X)`when` ( )`while`

?: Which of the following methods would correctly return `true` when given the letter `"o"` as an argument?

(X)
```ruby
def vowels_with_if_single_line(letter)
  true if letter == "a" || letter == "e" || letter == "i" || letter == "o" || letter == "u"
end
```
( )
```ruby
def vowels_with_if_single_line(letter)
  true if letter == "a" && letter == "e" && letter == "i" && letter == "o" && letter == "u"
end
```
( )
```ruby
def vowels_with_if_single_line(letter)
  true if letter == "a" || if letter == "e" || if letter == "i" || if letter == "o" || if letter == "u"
end
```

???

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/conditional-quiz-vowels' title='Quiz: Practicing Conditionals with Vowels'>Quiz: Practicing Conditionals with Vowels</a> on Learn.co and start learning to code for free.</p>
