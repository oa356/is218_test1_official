# IS 218 Test 1 Calculator

Name: Olu Akinde

## Purpose

This project is a small Python calculator package that implements addition and subtraction with automated pytest tests.

## Setup

```powershell
py -3.13 -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
```

## Test Commands

```powershell
.\.venv\Scripts\python.exe -m pytest
.\.venv\Scripts\python.exe -m pytest tests checks -v
```

## Issues

- Issue 1: https://github.com/oa356/is218_test1_official/issues/1
- Issue 2: https://github.com/oa356/is218_test1_official/issues/2
- Issue 3: https://github.com/oa356/is218_test1_official/issues/3
- Issue 4: https://github.com/oa356/is218_test1_official/issues/4

## Assertion Explanation

The test `test_subtract_negative_result` calls `subtract(3, 5)` and checks that the returned result equals `-2`.

## Why `.venv` Is Ignored

The `.venv` folder contains my local Python environment. It is ignored because another developer should create their own environment using `requirements.txt`.