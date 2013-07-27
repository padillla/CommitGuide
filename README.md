# Commit Guide

## What is this?
This is a simple guide trying to establish an approach to your commit messages.

## How can be this helpful?
When collaborating, or even commiting on your own project, the commit history _should_ look clean and specific, following this tips you will have cleaner commits and a cleaner commit history.

## Commit types
* [feature](#feature)
* [fix](#fix)
* [style](#style)
* [docs](#docs)
* [test](#test)

### Feature
When adding a new feature to a project, you need to commit in the following way:

> feat(feature name): short description
>
> Long description

Example:

```
feat(user registration): added user registration

Now the user should be able to create a new account, going to http://mysite.com/register
```

### Fix
This commit message should be used when fixing a bug of your project.

> fix(feature name): short description
>
> Long description
>
> Issues closed when commiting this fix

Example:

```
fix(user registration): fixed email field validation

Validation wasn't working on the server side, now it is working fine on both client and server sides.

closes #25, #38
```

### Style
When changing _only_ code styling, for example: a bad indentation.

> style(feature name): short description
>
> Long description

Example:

```
style(user registration): added blank line before comment start.

It's better and more entendible ;).
```

### Docs
When adding documentation to your code.

> docs(feature name): short description
>
> Long description

Example:

```
docs(user registration): added documentation for validateMail() function.

Added how to steps, related links and regexp tester url.
```

### Test
When adding a new test to a given feature.

> test(feature name): short description
>
> long description

Example:

```
test(user registration): added new test assertion for validateMail() function.

Added new assertion who will validate domain names with two letters (.es) and
with two set of domains (.es.tl).
```

## Contributing
Have some feedback, suggestions, or want to add commit types? Want to add a translation?
Make a pull request or open an issue.