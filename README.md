# TeamOfFortune

## TARGET

## DATA STRUCTURES

| name | city | salary_from | salary_to | salary_currency |  salary_is_gross | location_address | experience | schedule | employment_type | skills_required | specializations | professional_roles | employer_name | employer_is_trusted |
| ---  | ---  | ---         | ---       | ---             | ---              | ---              | ---        | ---      | ---             | ---             | ---             | ---                | ---           | ---                 |
| ...  | ...  | ...         | ...       | ...             | ...              | ...              | ...        | ...      | ...             | ...             | ...             | ...                | ...           | ...                 |

- name: vacancy's name
- city: vacancy's geo location, city
- city: vacancy's geo location, address
- salary_{from, to, currency, is_gross}: data on the offered salary payout
- experience: experience range in years
- schedule: type of schedule (eg., full day, remote, flexible...)
- employment type: full or probation
- skills required: hardware skills (coding language, framewoks ...)
- specializations: area of business
- professional_roles: team's role expected
- employer name: as it is
- employer_is_trusted: has an employer passed the reliability check


## DATA SOURCES:
- https://hh.ru/
	- via api.hh.ru
- kaggle: https://www.kaggle.com/datasets/jackogozaly/data-science-and-stem-salaries
	- via kaggle api
