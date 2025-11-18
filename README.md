# calculator (python)
It is a simple menu driven calculator code of python to perform basic operations like addition, substraction, multiplication, division.
Written using user defined function

## Installation

Step 1: Clone the repository
  ```bash
git clone https://github.com/shikha43/unit3-repo.git
cd unit3-repo.git

  ```
## Usage
*python main.py --help*

## Inline code
```python
def add(num1,num2):
    return num1+num2
def sub(num1,num2):
    return num1-num2
def multiply(num1,num2):
    return num1*num2
def divide(num1,num2):
    return num1/num2
print("Select any operation -\n" \
      "1. Add\n"\
      "2. Subtract\n"\
      "3. Multiply\n"\
      "4. Divide\n")
sel= int(input("select operation from 1,2,3,4 : "))

if sel==1:
    num1=int(input("enter first number: "))
    num2=int(input("enter second number: "))
    print(num1, "+", num2, "=", add(num1,num2))
elif sel==2:
    num1=int(input("enter first number: "))
    num2=int(input("enter second number: "))
    print(num1, "-", num2, "=", sub(num1,num2))
elif sel==3:
    num1=int(input("enter first number: "))
    num2=int(input("enter second number: "))
    print(num1, "*", num2, "=", multiply(num1,num2))
elif sel==4:
    num1=int(input("enter first number: "))
    num2=int(input("enter second number: "))
    print(num1, "/", num2, "=", divide(num1,num2))
else:
    print("invalid input")

```
## Output
<img width="500" height="300" alt="calc_output" src="https://github.com/user-attachments/assets/67806f88-5c8d-489c-83e0-454f98afccce" />

### For more info about python:
[click here](https://www.w3schools.com/python/)
