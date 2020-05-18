# CRUD with AWS DynamoDB and Python + Boto3
## Installation
- Clone de project  
`git clone ...`

- create a virtual env With pipenv (requieres that you have installed **pipenv**)  
in the root repository run: `pipenv install`

- **Or** Install with virtual **venv**  
`python -m venv c:\path\to\myenv_test_crud`

this will install:  
- aws
- boto3

## Configure your aws account
- Put it your account ID and Secret Key, [you can get it in...](https://console.aws.amazon.com/iam/home?#/users)  
`aws configure`  

## Run
- you can the operations CRUD in `dynamodb.py`  
`python dynamodb.py`

- after you run, you can break down the lines in `dynamodb.py` for test operations.
```python
...
if __name__ == '__main__':
     create_table()
    # put_item_on_table()
    # update_item_on_table()
    # conditionally_update_an_item()
...
```
