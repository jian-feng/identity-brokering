# Stored IdP tokens got from idb-server

Returned from: http://localhost:8180/auth/realms/idbrealm/broker/idp-sso-provider/token

```json
{
"access_token":"eyJhbGciOiJSUzI1NiIsInR5cCIgOiAiSldUIiwia2lkIiA6ICJ1NGV3bnZQVE5EcW9LR0dZYkVvcTgtZzVGZzRsOGI2TVprY1Z2dm1XdjVzIn0.eyJqdGkiOiJmYWEwYTg5ZS1lMzc1LTQzMDYtYThhOC1mMDExZjYxMzQzNDgiLCJleHAiOjE1Njg0NjYwNDEsIm5iZiI6MCwiaWF0IjoxNTY4NDY1NzQxLCJpc3MiOiJodHRwOi8vbG9jYWxob3N0OjgzODAvYXV0aC9yZWFsbXMvaWRwcmVhbG0iLCJhdWQiOiJhY2NvdW50Iiwic3ViIjoiYzQzYzI3YzItNWEzOC00OTAyLTk0ODUtOGQ5YzAwNzU2MDQ5IiwidHlwIjoiQmVhcmVyIiwiYXpwIjoiaWRiLXNzby1icm9rZXIiLCJub25jZSI6ImIxZjEyNmEyLWYwYmUtNDU1ZC04ZGM4LTBlZTcyOTIzZjFkNyIsImF1dGhfdGltZSI6MTU2ODQ2NTc0MSwic2Vzc2lvbl9zdGF0ZSI6IjY2NzEzYTJjLTQxODgtNGEwNy05MjU2LWVmODYyNDY3YmM4YiIsImFjciI6IjEiLCJhbGxvd2VkLW9yaWdpbnMiOlsiaHR0cDovL2xvY2FsaG9zdDo4MTgwIl0sInJlYWxtX2FjY2VzcyI6eyJyb2xlcyI6WyJvZmZsaW5lX2FjY2VzcyIsInVtYV9hdXRob3JpemF0aW9uIiwidXNlciJdfSwicmVzb3VyY2VfYWNjZXNzIjp7ImFjY291bnQiOnsicm9sZXMiOlsibWFuYWdlLWFjY291bnQiLCJtYW5hZ2UtYWNjb3VudC1saW5rcyIsInZpZXctcHJvZmlsZSJdfX0sInNjb3BlIjoib3BlbmlkIHByb2ZpbGUgZW1haWwiLCJlbWFpbF92ZXJpZmllZCI6ZmFsc2UsIm5hbWUiOiJVc2VyIElkUCIsInByZWZlcnJlZF91c2VybmFtZSI6ImlkcHVzZXIiLCJnaXZlbl9uYW1lIjoiVXNlciIsImZhbWlseV9uYW1lIjoiSWRQIiwiZW1haWwiOiJpZHB1c2VyQGV4YW1wbGUuY29tIn0.R3zqyMwEeLpy7zwFbOP7w-piABirr39PwAWVlQ83rRy76__VRbvFt2qc_VuL1Mi9rV_Gt3Rj6QJsW2imrhIdEk1eLLwE5rBNqXnF3N-HpJf_Ag8XoMNSVaY67L6knouiBEiyyOiGe-CqM0Ma51u6PSgsi0qVS7mH5oIOm5ZC5PtqDhAsPZkye14p0pa9SQBoShDJ7PZXfeyilTq9lt6XbQXR9-Z0aeVHvBQeIg2Fl8YgB1D-z-P0OvaCWwXw5q_xARuucCVVwRoHGJwKE_ABrXN524HOK9_3zXJhPu4SNqhlwiTIq8HCaFadU1nnh7QiDL72-LW0VvVWqhkzW1JfYw",
"expires_in":300,
"refresh_expires_in":1800,
"refresh_token":"eyJhbGciOiJIUzI1NiIsInR5cCIgOiAiSldUIiwia2lkIiA6ICJhZTM2YjVkYy1hNDAyLTQ1ZjYtYTc0NC1lZDI1MDU5OWFiN2UifQ.eyJqdGkiOiI4NDBjYmQ1NC0yZTRkLTQwZDQtOWY3Mi03OTIyMDMyMGM0MTYiLCJleHAiOjE1Njg0Njc1NDEsIm5iZiI6MCwiaWF0IjoxNTY4NDY1NzQxLCJpc3MiOiJodHRwOi8vbG9jYWxob3N0OjgzODAvYXV0aC9yZWFsbXMvaWRwcmVhbG0iLCJhdWQiOiJodHRwOi8vbG9jYWxob3N0OjgzODAvYXV0aC9yZWFsbXMvaWRwcmVhbG0iLCJzdWIiOiJjNDNjMjdjMi01YTM4LTQ5MDItOTQ4NS04ZDljMDA3NTYwNDkiLCJ0eXAiOiJSZWZyZXNoIiwiYXpwIjoiaWRiLXNzby1icm9rZXIiLCJub25jZSI6ImIxZjEyNmEyLWYwYmUtNDU1ZC04ZGM4LTBlZTcyOTIzZjFkNyIsImF1dGhfdGltZSI6MCwic2Vzc2lvbl9zdGF0ZSI6IjY2NzEzYTJjLTQxODgtNGEwNy05MjU2LWVmODYyNDY3YmM4YiIsInJlYWxtX2FjY2VzcyI6eyJyb2xlcyI6WyJvZmZsaW5lX2FjY2VzcyIsInVtYV9hdXRob3JpemF0aW9uIiwidXNlciJdfSwicmVzb3VyY2VfYWNjZXNzIjp7ImFjY291bnQiOnsicm9sZXMiOlsibWFuYWdlLWFjY291bnQiLCJtYW5hZ2UtYWNjb3VudC1saW5rcyIsInZpZXctcHJvZmlsZSJdfX0sInNjb3BlIjoib3BlbmlkIHByb2ZpbGUgZW1haWwifQ.K3y_WHfJMdBxLPX3XANPLm5q6yBoMwMntYw6Wy_7qjo",
"token_type":"bearer",
"id_token":"eyJhbGciOiJSUzI1NiIsInR5cCIgOiAiSldUIiwia2lkIiA6ICJ1NGV3bnZQVE5EcW9LR0dZYkVvcTgtZzVGZzRsOGI2TVprY1Z2dm1XdjVzIn0.eyJqdGkiOiIxMTBmMzFjOS1hNzNjLTQxZjgtOWFlNy0wYjRhOGNkYWUyMzEiLCJleHAiOjE1Njg0NjYwNDEsIm5iZiI6MCwiaWF0IjoxNTY4NDY1NzQxLCJpc3MiOiJodHRwOi8vbG9jYWxob3N0OjgzODAvYXV0aC9yZWFsbXMvaWRwcmVhbG0iLCJhdWQiOiJpZGItc3NvLWJyb2tlciIsInN1YiI6ImM0M2MyN2MyLTVhMzgtNDkwMi05NDg1LThkOWMwMDc1NjA0OSIsInR5cCI6IklEIiwiYXpwIjoiaWRiLXNzby1icm9rZXIiLCJub25jZSI6ImIxZjEyNmEyLWYwYmUtNDU1ZC04ZGM4LTBlZTcyOTIzZjFkNyIsImF1dGhfdGltZSI6MTU2ODQ2NTc0MSwic2Vzc2lvbl9zdGF0ZSI6IjY2NzEzYTJjLTQxODgtNGEwNy05MjU2LWVmODYyNDY3YmM4YiIsImFjciI6IjEiLCJlbWFpbF92ZXJpZmllZCI6ZmFsc2UsIm5hbWUiOiJVc2VyIElkUCIsInByZWZlcnJlZF91c2VybmFtZSI6ImlkcHVzZXIiLCJnaXZlbl9uYW1lIjoiVXNlciIsImZhbWlseV9uYW1lIjoiSWRQIiwiZW1haWwiOiJpZHB1c2VyQGV4YW1wbGUuY29tIn0.DSumOs4vZ43xSEHswkV5NSHYV23fVqZmYvqm3V2uhKzdFdwgjPNVrm4aVERC7UDuaDtUoTRKsqTbxlD_HAG7O5X_A4__zH1a0INVewLaH5SbPtRI6t7UwZHBiY5DQ2YJ2q-HYmpJEv2hCF-2_25xU8Zgn-JgEkMT1qC_zUprbaNeW2IsS-D-aOHNWzguwE3xn6mXKoT8j-rAU53UbbZ4n5-SrJr7UrJXWJqv14ovQNWyuBUX1lM309ZPh-T1G4SlUER0oohp2N_9DXcD0FlZiJfSfHsKT0XLO3_Q_-eKMISFcbUmhHE8zpRt_2ENOsmdvNaNclycp4Sm7D5pAMt6sQ",
"not-before-policy":0,
"session_state":"66713a2c-4188-4a07-9256-ef862467bc8b",
"scope":"openid profile email",
"accessTokenExpiration":1568466041
}
```

## Decoded access_token

```json
{
  "alg": "RS256",
  "typ": "JWT",
  "kid": "u4ewnvPTNDqoKGGYbEoq8-g5Fg4l8b6MZkcVvvmWv5s"
}
{
  "jti": "faa0a89e-e375-4306-a8a8-f011f6134348",
  "exp": 1568466041,
  "nbf": 0,
  "iat": 1568465741,
  "iss": "http://localhost:8380/auth/realms/idprealm",
  "aud": "account",
  "sub": "c43c27c2-5a38-4902-9485-8d9c00756049",
  "typ": "Bearer",
  "azp": "idb-sso-broker",
  "nonce": "b1f126a2-f0be-455d-8dc8-0ee72923f1d7",
  "auth_time": 1568465741,
  "session_state": "66713a2c-4188-4a07-9256-ef862467bc8b",
  "acr": "1",
  "allowed-origins": [
    "http://localhost:8180"
  ],
  "realm_access": {
    "roles": [
      "offline_access",
      "uma_authorization",
      "user"
    ]
  },
  "resource_access": {
    "account": {
      "roles": [
        "manage-account",
        "manage-account-links",
        "view-profile"
      ]
    }
  },
  "scope": "openid profile email",
  "email_verified": false,
  "name": "User IdP",
  "preferred_username": "idpuser",
  "given_name": "User",
  "family_name": "IdP",
  "email": "idpuser@example.com"
}
{
  (signature)
}
```

## Decoded refresh_token

```json
{
  "alg": "HS256",
  "typ": "JWT",
  "kid": "ae36b5dc-a402-45f6-a744-ed250599ab7e"
}
{
  "jti": "840cbd54-2e4d-40d4-9f72-79220320c416",
  "exp": 1568467541,
  "nbf": 0,
  "iat": 1568465741,
  "iss": "http://localhost:8380/auth/realms/idprealm",
  "aud": "http://localhost:8380/auth/realms/idprealm",
  "sub": "c43c27c2-5a38-4902-9485-8d9c00756049",
  "typ": "Refresh",
  "azp": "idb-sso-broker",
  "nonce": "b1f126a2-f0be-455d-8dc8-0ee72923f1d7",
  "auth_time": 0,
  "session_state": "66713a2c-4188-4a07-9256-ef862467bc8b",
  "realm_access": {
    "roles": [
      "offline_access",
      "uma_authorization",
      "user"
    ]
  },
  "resource_access": {
    "account": {
      "roles": [
        "manage-account",
        "manage-account-links",
        "view-profile"
      ]
    }
  },
  "scope": "openid profile email"
}
{
  (signature)
}
```

## Decoded id_token

```json
{
  "alg": "RS256",
  "typ": "JWT",
  "kid": "u4ewnvPTNDqoKGGYbEoq8-g5Fg4l8b6MZkcVvvmWv5s"
}
{
  "jti": "110f31c9-a73c-41f8-9ae7-0b4a8cdae231",
  "exp": 1568466041,
  "nbf": 0,
  "iat": 1568465741,
  "iss": "http://localhost:8380/auth/realms/idprealm",
  "aud": "idb-sso-broker",
  "sub": "c43c27c2-5a38-4902-9485-8d9c00756049",
  "typ": "ID",
  "azp": "idb-sso-broker",
  "nonce": "b1f126a2-f0be-455d-8dc8-0ee72923f1d7",
  "auth_time": 1568465741,
  "session_state": "66713a2c-4188-4a07-9256-ef862467bc8b",
  "acr": "1",
  "email_verified": false,
  "name": "User IdP",
  "preferred_username": "idpuser",
  "given_name": "User",
  "family_name": "IdP",
  "email": "idpuser@example.com"
}
{
  (signature)
}
```


# Response of refreshing tokens from idp-server

Returned from: http://localhost:8380/auth/realms/idprealm/protocol/openid-connect/token

```json
{
"access_token":"eyJhbGciOiJSUzI1NiIsInR5cCIgOiAiSldUIiwia2lkIiA6ICJ1NGV3bnZQVE5EcW9LR0dZYkVvcTgtZzVGZzRsOGI2TVprY1Z2dm1XdjVzIn0.eyJqdGkiOiI3MzBkYWVmMS01MmNjLTQ3NzEtOTdjYi05OWYwZTdkNmY1ODciLCJleHAiOjE1Njg0NzkzNTAsIm5iZiI6MCwiaWF0IjoxNTY4NDc5MDUwLCJpc3MiOiJodHRwOi8vbG9jYWxob3N0OjgzODAvYXV0aC9yZWFsbXMvaWRwcmVhbG0iLCJhdWQiOiJhY2NvdW50Iiwic3ViIjoiYzQzYzI3YzItNWEzOC00OTAyLTk0ODUtOGQ5YzAwNzU2MDQ5IiwidHlwIjoiQmVhcmVyIiwiYXpwIjoiaWRiLXNzby1icm9rZXIiLCJub25jZSI6IjU0NWQzNmE1LTA5NjAtNDNjOC05MjUzLTI5NzAxN2I1NjE4MiIsImF1dGhfdGltZSI6MTU2ODQ3MDIyNiwic2Vzc2lvbl9zdGF0ZSI6IjM1YzE1ZjA3LWRiNDktNDJmMS1hZGU3LWQyOWZkYWU2MjIyMSIsImFjciI6IjAiLCJhbGxvd2VkLW9yaWdpbnMiOlsiaHR0cDovL2xvY2FsaG9zdDo4MTgwIl0sInJlYWxtX2FjY2VzcyI6eyJyb2xlcyI6WyJvZmZsaW5lX2FjY2VzcyIsInVtYV9hdXRob3JpemF0aW9uIiwidXNlciJdfSwicmVzb3VyY2VfYWNjZXNzIjp7ImFjY291bnQiOnsicm9sZXMiOlsibWFuYWdlLWFjY291bnQiLCJtYW5hZ2UtYWNjb3VudC1saW5rcyIsInZpZXctcHJvZmlsZSJdfX0sInNjb3BlIjoib3BlbmlkIHByb2ZpbGUgZW1haWwiLCJlbWFpbF92ZXJpZmllZCI6ZmFsc2UsIm5hbWUiOiJVc2VyIElkUCIsInByZWZlcnJlZF91c2VybmFtZSI6ImlkcHVzZXIiLCJnaXZlbl9uYW1lIjoiVXNlciIsImZhbWlseV9uYW1lIjoiSWRQIiwiZW1haWwiOiJpZHB1c2VyQGV4YW1wbGUuY29tIn0.aQ1BPz3-o490GwadRGRCs1NaxmGnbS-3WuOMqCEg6FFDPU_tg_szm8XcWRyPYXTeYVnP94oOqHTLDcFg1v5FE3GYpwtYBf-a8pV1mLu_chtzVzOOAgDGUAms4lKg0LiJHX9BfvuOJW_WFvcs3poWmz6k1Oiv23FWSbX8K4EqCU93FWVcYEF6WWmzvFpaSnR1wADjyqlMNj-5-DACM5aavuB5Se3bWMTR43eGfZXSE4iIfipGphbzpf-LMm-BH4-LzSlTG4lu5TG-AgfTTPd-JTF0rc4WIKEEQFjTx2lqBOUGvykIzB_JOjRhNnmOhASd_3WqRQ1CC4rmv8ei09gs7g",
"expires_in":300,
"refresh_expires_in":1800,
"refresh_token":"eyJhbGciOiJIUzI1NiIsInR5cCIgOiAiSldUIiwia2lkIiA6ICJhZTM2YjVkYy1hNDAyLTQ1ZjYtYTc0NC1lZDI1MDU5OWFiN2UifQ.eyJqdGkiOiI2NjI0Mjg1ZS0wZDQwLTQzNDUtOTBkNS0zYjdhYjE0NDFiYTMiLCJleHAiOjE1Njg0ODA4NTAsIm5iZiI6MCwiaWF0IjoxNTY4NDc5MDUwLCJpc3MiOiJodHRwOi8vbG9jYWxob3N0OjgzODAvYXV0aC9yZWFsbXMvaWRwcmVhbG0iLCJhdWQiOiJodHRwOi8vbG9jYWxob3N0OjgzODAvYXV0aC9yZWFsbXMvaWRwcmVhbG0iLCJzdWIiOiJjNDNjMjdjMi01YTM4LTQ5MDItOTQ4NS04ZDljMDA3NTYwNDkiLCJ0eXAiOiJSZWZyZXNoIiwiYXpwIjoiaWRiLXNzby1icm9rZXIiLCJub25jZSI6IjU0NWQzNmE1LTA5NjAtNDNjOC05MjUzLTI5NzAxN2I1NjE4MiIsImF1dGhfdGltZSI6MCwic2Vzc2lvbl9zdGF0ZSI6IjM1YzE1ZjA3LWRiNDktNDJmMS1hZGU3LWQyOWZkYWU2MjIyMSIsInJlYWxtX2FjY2VzcyI6eyJyb2xlcyI6WyJvZmZsaW5lX2FjY2VzcyIsInVtYV9hdXRob3JpemF0aW9uIiwidXNlciJdfSwicmVzb3VyY2VfYWNjZXNzIjp7ImFjY291bnQiOnsicm9sZXMiOlsibWFuYWdlLWFjY291bnQiLCJtYW5hZ2UtYWNjb3VudC1saW5rcyIsInZpZXctcHJvZmlsZSJdfX0sInNjb3BlIjoib3BlbmlkIHByb2ZpbGUgZW1haWwifQ.8qRikPYpe-eLrDB5gsnNYKRxIHx3UuQmMl-HpHw6_FY",
"token_type":"bearer",
"id_token":"eyJhbGciOiJSUzI1NiIsInR5cCIgOiAiSldUIiwia2lkIiA6ICJ1NGV3bnZQVE5EcW9LR0dZYkVvcTgtZzVGZzRsOGI2TVprY1Z2dm1XdjVzIn0.eyJqdGkiOiJkZjdlMmQ2Ny0yOTZjLTQ4MWMtOGI4ZS00ZTMzYmIwOGZlYWEiLCJleHAiOjE1Njg0NzkzNTAsIm5iZiI6MCwiaWF0IjoxNTY4NDc5MDUwLCJpc3MiOiJodHRwOi8vbG9jYWxob3N0OjgzODAvYXV0aC9yZWFsbXMvaWRwcmVhbG0iLCJhdWQiOiJpZGItc3NvLWJyb2tlciIsInN1YiI6ImM0M2MyN2MyLTVhMzgtNDkwMi05NDg1LThkOWMwMDc1NjA0OSIsInR5cCI6IklEIiwiYXpwIjoiaWRiLXNzby1icm9rZXIiLCJub25jZSI6IjU0NWQzNmE1LTA5NjAtNDNjOC05MjUzLTI5NzAxN2I1NjE4MiIsImF1dGhfdGltZSI6MTU2ODQ3MDIyNiwic2Vzc2lvbl9zdGF0ZSI6IjM1YzE1ZjA3LWRiNDktNDJmMS1hZGU3LWQyOWZkYWU2MjIyMSIsImFjciI6IjAiLCJlbWFpbF92ZXJpZmllZCI6ZmFsc2UsIm5hbWUiOiJVc2VyIElkUCIsInByZWZlcnJlZF91c2VybmFtZSI6ImlkcHVzZXIiLCJnaXZlbl9uYW1lIjoiVXNlciIsImZhbWlseV9uYW1lIjoiSWRQIiwiZW1haWwiOiJpZHB1c2VyQGV4YW1wbGUuY29tIn0.Cg58IU9Z0dU0QgpPGBWPZJXDZ8xSMkJ179u61DOreH1-mLa3wMYALvWW1Fp_KvJwBvdSqlFj_vzA-ObuiOiwDOF_AGzkzUsE5RaHt9zk-_CkzLyUNZIkO-v5pEIxLvHjwPDrbihe4M7siILTcv0AnZxGe3eB5MYR8EH4iaHXGivhpkf_Qtikky4MIG5h_JFFdP8oNYBubZoQeR55IkyhNF8uBLfqOViNlgzG1xCZLXzKJM0M3ovY8hCDixek2NH5g9HCoHKQ7wu3bQsQ32i5nGha30V0fkhAde5O0gelL-_geE0k1l_qqF5bR-8uYNdBFrlHT1zZe8670Mmsmq2dsA",
"not-before-policy":0,
"session_state":"35c15f07-db49-42f1-ade7-d29fdae62221",
"scope":"openid profile email"
}
```

## Decoded access_token

```json
{
  "alg": "RS256",
  "typ": "JWT",
  "kid": "u4ewnvPTNDqoKGGYbEoq8-g5Fg4l8b6MZkcVvvmWv5s"
}
{
  "jti": "730daef1-52cc-4771-97cb-99f0e7d6f587",
  "exp": 1568479350,
  "nbf": 0,
  "iat": 1568479050,
  "iss": "http://localhost:8380/auth/realms/idprealm",
  "aud": "account",
  "sub": "c43c27c2-5a38-4902-9485-8d9c00756049",
  "typ": "Bearer",
  "azp": "idb-sso-broker",
  "nonce": "545d36a5-0960-43c8-9253-297017b56182",
  "auth_time": 1568470226,
  "session_state": "35c15f07-db49-42f1-ade7-d29fdae62221",
  "acr": "0",
  "allowed-origins": [
    "http://localhost:8180"
  ],
  "realm_access": {
    "roles": [
      "offline_access",
      "uma_authorization",
      "user"
    ]
  },
  "resource_access": {
    "account": {
      "roles": [
        "manage-account",
        "manage-account-links",
        "view-profile"
      ]
    }
  },
  "scope": "openid profile email",
  "email_verified": false,
  "name": "User IdP",
  "preferred_username": "idpuser",
  "given_name": "User",
  "family_name": "IdP",
  "email": "idpuser@example.com"
}
{
  (signature)
}
```

## Decoded refresh_token

```json
{
  "alg": "HS256",
  "typ": "JWT",
  "kid": "ae36b5dc-a402-45f6-a744-ed250599ab7e"
}
{
  "jti": "6624285e-0d40-4345-90d5-3b7ab1441ba3",
  "exp": 1568480850,
  "nbf": 0,
  "iat": 1568479050,
  "iss": "http://localhost:8380/auth/realms/idprealm",
  "aud": "http://localhost:8380/auth/realms/idprealm",
  "sub": "c43c27c2-5a38-4902-9485-8d9c00756049",
  "typ": "Refresh",
  "azp": "idb-sso-broker",
  "nonce": "545d36a5-0960-43c8-9253-297017b56182",
  "auth_time": 0,
  "session_state": "35c15f07-db49-42f1-ade7-d29fdae62221",
  "realm_access": {
    "roles": [
      "offline_access",
      "uma_authorization",
      "user"
    ]
  },
  "resource_access": {
    "account": {
      "roles": [
        "manage-account",
        "manage-account-links",
        "view-profile"
      ]
    }
  },
  "scope": "openid profile email"
}
{
  (signature)
}
```

## Decoded id_token

```json
{
  "alg": "RS256",
  "typ": "JWT",
  "kid": "u4ewnvPTNDqoKGGYbEoq8-g5Fg4l8b6MZkcVvvmWv5s"
}
{
  "jti": "df7e2d67-296c-481c-8b8e-4e33bb08feaa",
  "exp": 1568479350,
  "nbf": 0,
  "iat": 1568479050,
  "iss": "http://localhost:8380/auth/realms/idprealm",
  "aud": "idb-sso-broker",
  "sub": "c43c27c2-5a38-4902-9485-8d9c00756049",
  "typ": "ID",
  "azp": "idb-sso-broker",
  "nonce": "545d36a5-0960-43c8-9253-297017b56182",
  "auth_time": 1568470226,
  "session_state": "35c15f07-db49-42f1-ade7-d29fdae62221",
  "acr": "0",
  "email_verified": false,
  "name": "User IdP",
  "preferred_username": "idpuser",
  "given_name": "User",
  "family_name": "IdP",
  "email": "idpuser@example.com"
}
{
  (signature)
}
```
