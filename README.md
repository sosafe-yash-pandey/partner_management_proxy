### Getting Started

1. Clone the repo

2. Run `npm install`

3. Run `npm run start`

4. Dummy endpoint is available at: `http://localhost:7007`

5. Open `db.json` to view API schema and edit it according to your needs.

6. As an example, to get all the clients sorted by names in descending order, make a `GET` call to this endpoint: `http://localhost:7007/clients?_sort=name&_order=desc`

```json
[
    {
        "id": 8,
        "name": "Voiceflex",
        "subscription": "active",
        "package": "starter",
        "total_license_issued": 21,
        "license_used": 21,
        "renewal_date": "2016-06-22 19:10:25-07",
        "phishing_simulation_status": "no_campaign",
        "elearning_status": "no_campaign",
        "registration_rate": 82,
        "created_on": "2016-06-22 19:10:25-07"
    },
    {
        "id": 3,
        "name": "Teleinformatic Services",
        "subscription": "inactive",
        "package": "starter",
        "total_license_issued": 22,
        "license_used": 12,
        "renewal_date": "2023-08-11 19:10:25-07",
        "phishing_simulation_status": "active",
        "elearning_status": "active",
        "registration_rate": 67,
        "created_on": "2023-03-19 19:10:25-07"
    },
    {
        "id": 2,
        "name": "Streamline",
        "subscription": "active",
        "package": "essential",
        "total_license_issued": 14,
        "license_used": 14,
        "renewal_date": "2025-03-25 19:10:25-07",
        "phishing_simulation_status": "scheduled",
        "elearning_status": "scheduled",
        "registration_rate": null,
        "created_on": "2022-06-22 19:10:25-07"
    },
    {
        "id": 6,
        "name": "Securepoint",
        "subscription": "active",
        "package": "starter",
        "total_license_issued": 21,
        "license_used": 21,
        "renewal_date": "2016-06-22 19:10:25-07",
        "phishing_simulation_status": "no_campaign",
        "elearning_status": "no_campaign",
        "registration_rate": 33,
        "created_on": "2016-06-22 19:10:25-07"
    },
    {
        "id": 5,
        "name": "Protektis",
        "subscription": "active",
        "package": "starter",
        "total_license_issued": 10,
        "license_used": 8,
        "renewal_date": "2016-06-22 19:10:25-07",
        "phishing_simulation_status": "no_campaign",
        "elearning_status": "no_campaign",
        "registration_rate": 88,
        "created_on": "2016-06-22 19:10:25-07"
    },
    {
        "id": 9,
        "name": "Perfect Day",
        "subscription": "active",
        "package": "starter",
        "total_license_issued": 21,
        "license_used": 21,
        "renewal_date": "2016-06-22 19:10:25-07",
        "phishing_simulation_status": "no_campaign",
        "elearning_status": "no_campaign",
        "registration_rate": 100,
        "created_on": "2016-06-22 19:10:25-07"
    },
    {
        "id": 4,
        "name": "Ingram Micro",
        "subscription": "active",
        "package": "starter",
        "total_license_issued": 21,
        "license_used": 21,
        "renewal_date": "2027-12-12 19:10:25-07",
        "phishing_simulation_status": "pause",
        "elearning_status": "scheduled",
        "registration_rate": null,
        "created_on": "2023-05-13 19:10:25-07"
    },
    {
        "id": 10,
        "name": "Infradax",
        "subscription": "active",
        "package": "starter",
        "total_license_issued": 21,
        "license_used": 21,
        "renewal_date": "2016-06-22 19:10:25-07",
        "phishing_simulation_status": "no_campaign",
        "elearning_status": "no_campaign",
        "registration_rate": 97,
        "created_on": "2016-06-22 19:10:25-07"
    },
    {
        "id": 7,
        "name": "EnBW",
        "subscription": "active",
        "package": "starter",
        "total_license_issued": 21,
        "license_used": 21,
        "renewal_date": "2016-06-22 19:10:25-07",
        "phishing_simulation_status": "no_campaign",
        "elearning_status": "no_campaign",
        "registration_rate": 22,
        "created_on": "2016-06-22 19:10:25-07"
    },
    {
        "id": 1,
        "name": "Defentry",
        "subscription": "active",
        "package": "starter",
        "total_license_issued": 10,
        "license_used": 8,
        "renewal_date": "2025-06-22 19:10:25-07",
        "phishing_simulation_status": "no_campaign",
        "elearning_status": "no_campaign",
        "registration_rate": null,
        "created_on": "2024-06-22 19:10:25-07"
    }
]
```

7. Read more about `json-server` [on this page](https://github.com/typicode/json-server/tree/v0).
