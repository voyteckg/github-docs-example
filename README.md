# Writing Good Documentation

GitHub Markdown Editor and Github Flavoured Mardown (GFM)
## Step 1 - Using Codeblocks.

Codeblocks in markdown make it very easy for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- example 1
- example 2

```
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
number = gets.chomp.to_i

if number < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}."
end
```

- When you can you should attempt to apply syntax highliting

```
```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
number = gets.chomp.to_i

if number < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}."
end
```
![test image](https://github.com/voyteckg/github-docs-example/assets/48118593/dec08212-708b-4149-8eaa-41b12d7b302e)

> It is example of error
```bash
NameError: undefined local variable or method `x' for main:Object
```
- links

- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

# Step 4 - Use Emojis (Optional)
https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md

:cloud_with_lightning:

## References

- [this is first link](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)<sup>[1]</sup>
- [this is second link](https://youtrack.jetbrains.com/issue/TW-63905/How-to-configure-agent-startup-timeout-period-in-cloud-profiles)<sup>[2]</sup>

## Tables

| test | test2 | Emoji |
| ---- | --- |---|
| cloud | `:cloud:` |:cloud:|

```md
| test | test2 | Emoji |
| ---- | --- |---|
| cloud | `:cloud:` |:cloud:|
```

