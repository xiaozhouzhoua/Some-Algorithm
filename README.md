# Some-Algorithm
算法学习
curl -v --insecure -H "Accept: application/json" -H "Content-type: application/json" -X POST -d '{    "auth": {        "identity": {            "password": {                "user": {                    "password": "Huawei@123",                    "domain": {                        "name": "op_svc_mts"                    },                    "name": "op_svc_mts"                }            },            "methods": [                "password"            ]        },        "scope": {            "domain": {                "name": "op_svc_mts"            }        }    }}'   'https://192.144.1.37:31943/v3/auth/tokens'