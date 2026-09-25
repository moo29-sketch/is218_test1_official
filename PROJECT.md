# IS 218 Test 1

Mo Opeyemi-Ajayi

## Purpose

This project is a Python calculator package that implements addition and subtraction and uses pytest to verify that both operations work correctly.

## Setup

Create the virtual environment:

py -3.13 -m venv .venv

Select the Python interpreter located at:

.venv\Scripts\python.exe

Install the requirements:

.\.venv\Scripts\python.exe -m pip install -r requirements.txt

## Testing

Run the six student tests:

.\.venv\Scripts\python.exe -m pytest

Run the student tests and supplied acceptance checks:

.\.venv\Scripts\python.exe -m pytest tests checks -v

## Test Explanation

One addition test uses the inputs 2 and 3 and expects the result to be 5. The assertion checks that add(2, 3) returns 5.

## Virtual Environment

The requirements file is committed so other developers can install the same project dependencies. The .venv folder is kept local because each developer can recreate the environment from requirements.txt.

## Issues

Issue 1: https://github.com/moo29-sketch/is218_test1_official/issues/1

Issue 2: https://github.com/moo29-sketch/is218_test1_official/issues/2

Issue 3: https://github.com/moo29-sketch/is218_test1_official/issues/3

Issue 4: https://github.com/moo29-sketch/is218_test1_official/issues/4