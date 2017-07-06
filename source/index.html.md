--- 

title: Jamf Pro Customer API 

language_tabs: 
   - shell 

toc_footers: 
   - <a href='#'>Sign Up for a Developer Key</a> 
   - <a href='https://github.com/lavkumarv'>Documentation Powered by lav</a> 

includes: 
   - errors 

search: true 

--- 

# Introduction 

Jamf Pro Customer API 

**Version:** 0.2 

# /ACCOUNTS
## ***GET*** 

**Summary:** Finds all accounts

### HTTP Request 
`***GET*** /accounts` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /ACCOUNTS/GROUPID/{ID}
## ***GET*** 

**Summary:** Finds groups by ID

### HTTP Request 
`***GET*** /accounts/groupid/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing group by ID

### HTTP Request 
`***PUT*** /accounts/groupid/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new group by ID

### HTTP Request 
`***POST*** /accounts/groupid/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body | Group name | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a group by ID

### HTTP Request 
`***DELETE*** /accounts/groupid/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /ACCOUNTS/GROUPNAME/{NAME}
## ***GET*** 

**Summary:** Finds groups by name

### HTTP Request 
`***GET*** /accounts/groupname/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing group by name

### HTTP Request 
`***PUT*** /accounts/groupname/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a group by name

### HTTP Request 
`***DELETE*** /accounts/groupname/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /ACCOUNTS/USERID/{ID}
## ***GET*** 

**Summary:** Finds accounts by ID

### HTTP Request 
`***GET*** /accounts/userid/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing account by ID

### HTTP Request 
`***PUT*** /accounts/userid/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new account by ID

### HTTP Request 
`***POST*** /accounts/userid/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body | Account name | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes an account by ID

### HTTP Request 
`***DELETE*** /accounts/userid/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /ACCOUNTS/USERNAME/{NAME}
## ***GET*** 

**Summary:** Finds accounts by name

### HTTP Request 
`***GET*** /accounts/username/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing account by name

### HTTP Request 
`***PUT*** /accounts/username/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes an account by name

### HTTP Request 
`***DELETE*** /accounts/username/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /ADVANCEDCOMPUTERSEARCHES
## ***GET*** 

**Summary:** Finds all advanced computer searches

### HTTP Request 
`***GET*** /advancedcomputersearches` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /ADVANCEDCOMPUTERSEARCHES/ID/{ID}
## ***GET*** 

**Summary:** Finds computer searches by ID

### HTTP Request 
`***GET*** /advancedcomputersearches/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing advanced computer search by ID

### HTTP Request 
`***PUT*** /advancedcomputersearches/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new advanced computer search

### HTTP Request 
`***POST*** /advancedcomputersearches/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID to filter by | Yes | integer |
| body | body | Name of object | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a computer search by ID

### HTTP Request 
`***DELETE*** /advancedcomputersearches/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /ADVANCEDCOMPUTERSEARCHES/NAME/{NAME}
## ***GET*** 

**Summary:** Finds advanced computer searches by name

### HTTP Request 
`***GET*** /advancedcomputersearches/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing advanced computer search by name

### HTTP Request 
`***PUT*** /advancedcomputersearches/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a computer search by Name

### HTTP Request 
`***DELETE*** /advancedcomputersearches/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /ADVANCEDMOBILEDEVICESEARCHES
## ***GET*** 

**Summary:** Finds all advanced mobile device searches

### HTTP Request 
`***GET*** /advancedmobiledevicesearches` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /ADVANCEDMOBILEDEVICESEARCHES/ID/{ID}
## ***GET*** 

**Summary:** Finds mobile device searches by ID

### HTTP Request 
`***GET*** /advancedmobiledevicesearches/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing advanced mobile device search by ID

### HTTP Request 
`***PUT*** /advancedmobiledevicesearches/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new advanced mobile device search

### HTTP Request 
`***POST*** /advancedmobiledevicesearches/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body | Name of advanced mobile device search | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device search by ID

### HTTP Request 
`***DELETE*** /advancedmobiledevicesearches/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /ADVANCEDMOBILEDEVICESEARCHES/NAME/{NAME}
## ***GET*** 

**Summary:** Finds advanced mobile device searches by name

### HTTP Request 
`***GET*** /advancedmobiledevicesearches/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing advanced mobile device search by name

### HTTP Request 
`***PUT*** /advancedmobiledevicesearches/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Nameto filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device search by name

### HTTP Request 
`***DELETE*** /advancedmobiledevicesearches/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /ADVANCEDUSERSEARCHES
## ***GET*** 

**Summary:** Finds all advanced user searches

### HTTP Request 
`***GET*** /advancedusersearches` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /ADVANCEDUSERSEARCHES/ID/{ID}
## ***GET*** 

**Summary:** Finds user searches by ID

### HTTP Request 
`***GET*** /advancedusersearches/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing advanced user search by ID

### HTTP Request 
`***PUT*** /advancedusersearches/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***POST*** 

**Summary:** Creates a new advanced user search by ID

### HTTP Request 
`***POST*** /advancedusersearches/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body | Name of advanced user search | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a user search by ID

### HTTP Request 
`***DELETE*** /advancedusersearches/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /ADVANCEDUSERSEARCHES/NAME/{NAME}
## ***GET*** 

**Summary:** Finds user searches by name

### HTTP Request 
`***GET*** /advancedusersearches/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing advanced user search by name

### HTTP Request 
`***PUT*** /advancedusersearches/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***DELETE*** 

**Summary:** Deletes a user search by Name

### HTTP Request 
`***DELETE*** /advancedusersearches/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /ALLOWEDFILEEXTENSIONS
## ***GET*** 

**Summary:** Finds the allowed file extensions

### HTTP Request 
`***GET*** /allowedfileextensions` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /ALLOWEDFILEEXTENSIONS/ID/{ID}
## ***GET*** 

**Summary:** Finds an allowed file extension value by ID

### HTTP Request 
`***GET*** /allowedfileextensions/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Database ID of the extension | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***POST*** 

**Summary:** Creates a new allowed file extension value by ID

### HTTP Request 
`***POST*** /allowedfileextensions/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Database ID of the extension | Yes | integer |
| body | body | Name of advanced user search | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes an allowed file extension value by ID

### HTTP Request 
`***DELETE*** /allowedfileextensions/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Database ID of the extension | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /ALLOWEDFILEEXTENSIONS/EXTENSION/{EXTENSION}
## ***GET*** 

**Summary:** Finds an allowed file extension value by name

### HTTP Request 
`***GET*** /allowedfileextensions/extension/{extension}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| extension | path | String value of extension | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /BUILDINGS
## ***GET*** 

**Summary:** Finds all buildings

### HTTP Request 
`***GET*** /buildings` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /BUILDINGS/ID/{ID}
## ***GET*** 

**Summary:** Finds buildings by ID

### HTTP Request 
`***GET*** /buildings/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing building by ID

### HTTP Request 
`***PUT*** /buildings/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new building

### HTTP Request 
`***POST*** /buildings/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body | Name of building | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a building by ID

### HTTP Request 
`***DELETE*** /buildings/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /BUILDINGS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds buildings by name

### HTTP Request 
`***GET*** /buildings/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing building by name

### HTTP Request 
`***PUT*** /buildings/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a building by name

### HTTP Request 
`***DELETE*** /buildings/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /BYOPROFILES
## ***GET*** 

**Summary:** Finds all personal device profiles

### HTTP Request 
`***GET*** /byoprofiles` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /BYOPROFILES/ID/{ID}
## ***GET*** 

**Summary:** Finds personal device profile by ID

### HTTP Request 
`***GET*** /byoprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates a personal device profile by ID

### HTTP Request 
`***PUT*** /byoprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a personal device profile by ID

### HTTP Request 
`***POST*** /byoprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a personal device profile by ID

### HTTP Request 
`***DELETE*** /byoprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /BYOPROFILES/NAME/{NAME}
## ***GET*** 

**Summary:** Finds a personal device profile by name

### HTTP Request 
`***GET*** /byoprofiles/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates a personal device profile by name

### HTTP Request 
`***PUT*** /byoprofiles/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a personal device profile by name

### HTTP Request 
`***DELETE*** /byoprofiles/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /CATEGORIES
## ***GET*** 

**Summary:** Finds all categories

### HTTP Request 
`***GET*** /categories` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /CATEGORIES/ID/{ID}
## ***GET*** 

**Summary:** Finds categories by ID

### HTTP Request 
`***GET*** /categories/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing category by ID

### HTTP Request 
`***PUT*** /categories/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***POST*** 

**Summary:** Creates a new category by ID

### HTTP Request 
`***POST*** /categories/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body | Name of category | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a category by ID

### HTTP Request 
`***DELETE*** /categories/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /CATEGORIES/NAME/{NAME}
## ***GET*** 

**Summary:** Finds categories by name

### HTTP Request 
`***GET*** /categories/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing category by name

### HTTP Request 
`***PUT*** /categories/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***DELETE*** 

**Summary:** Deletes a category by name

### HTTP Request 
`***DELETE*** /categories/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /CLASSES
## ***GET*** 

**Summary:** Finds all classes

### HTTP Request 
`***GET*** /classes` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /CLASSES/ID/{ID}
## ***GET*** 

**Summary:** Finds classes by ID

### HTTP Request 
`***GET*** /classes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing class by ID

**Description:** The mobile device list is not used by this operation, the mobile device group is used instead.

### HTTP Request 
`***PUT*** /classes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***POST*** 

**Summary:** Creates a new class by ID

**Description:** The mobile device list is not used by this operation, the mobile device group is used instead.

### HTTP Request 
`***POST*** /classes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body | Class name | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a class by ID

### HTTP Request 
`***DELETE*** /classes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /CLASSES/NAME/{NAME}
## ***GET*** 

**Summary:** Finds classes by name

### HTTP Request 
`***GET*** /classes/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing class by name

**Description:** The mobile device list is not used by this operation, the mobile device group is used instead.

### HTTP Request 
`***PUT*** /classes/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***DELETE*** 

**Summary:** Deletes a class by name

### HTTP Request 
`***DELETE*** /classes/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMMANDFLUSH
## ***DELETE*** 

**Summary:** Flushes commands based on information specified in an XML file

### HTTP Request 
`***DELETE*** /commandflush` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMMANDFLUSH/{IDTYPE}/ID/{ID}/STATUS/{STATUS}
## ***DELETE*** 

**Summary:** Flushes commands for devices

### HTTP Request 
`***DELETE*** /commandflush/{idtype}/id/{id}/status/{status}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| idtype | path | Type of device to be flushed | Yes | string |
| id | path | ID of device to be flushed | Yes | integer |
| status | path | Command status to be flushed | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERAPPLICATIONS/APPLICATION/{APPLICATION}
## ***GET*** 

**Summary:** Finds computer applications by name

### HTTP Request 
`***GET*** /computerapplications/application/{application}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| application | path | Application name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERAPPLICATIONS/APPLICATION/{APPLICATION}/INVENTORY/{INVENTORY}
## ***GET*** 

**Summary:** Finds computer applications by name with additional display fields

**Description:** Valid values for inventory are comma separated Display Fields for computers. Display Fields with spaces must be percent encoded (e.g. /computerapplications/application/Safari.app/inventory/Operating%20System,Last%20Check-in)

### HTTP Request 
`***GET*** /computerapplications/application/{application}/inventory/{inventory}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| application | path | Application name to filter by | Yes | string |
| inventory | path | Inventory options | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERAPPLICATIONS/APPLICATION/{APPLICATION}/VERSION/{VERSION}
## ***GET*** 

**Summary:** Finds computer applications by name and version

### HTTP Request 
`***GET*** /computerapplications/application/{application}/version/{version}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| application | path | Application name to filter by | Yes | string |
| version | path | Version to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERAPPLICATIONS/APPLICATION/{APPLICATION}/VERSION/{VERSION}/INVENTORY/{INVENTORY}
## ***GET*** 

**Summary:** Finds computer applications by name and version

**Description:** Generates additional inventory data for the devices matching the search criteria

### HTTP Request 
`***GET*** /computerapplications/application/{application}/version/{version}/inventory/{inventory}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| application | path | Application name to filter by | Yes | string |
| version | path | Version to filter by | Yes | string |
| inventory | path | Inventory options | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERAPPLICATIONUSAGE/ID/{ID}/{START_DATE}_{END_DATE}
## ***GET*** 

**Summary:** Finds computer application usage by computer ID

### HTTP Request 
`***GET*** /computerapplicationusage/id/{id}/{start_date}_{end_date}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | string |
| start_date | path | Start date (e.g. yyyy-mm-dd) | Yes | date |
| end_date | path | End date (e.g. yyyy-mm-dd) | Yes | date |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERAPPLICATIONUSAGE/NAME/{NAME}/{START_DATE}_{END_DATE}
## ***GET*** 

**Summary:** Finds computer application usage by computer name

### HTTP Request 
`***GET*** /computerapplicationusage/name/{name}/{start_date}_{end_date}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |
| start_date | path | Start date (e.g. yyyy-mm-dd) | Yes | string |
| end_date | path | End date (e.g. yyyy-mm-dd) | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERAPPLICATIONUSAGE/UDID/{UDID}/{START_DATE}_{END_DATE}
## ***GET*** 

**Summary:** Finds computer application usage by computer UDID

### HTTP Request 
`***GET*** /computerapplicationusage/udid/{udid}/{start_date}_{end_date}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| udid | path | UDID to filter by | Yes | string |
| start_date | path | Start date (e.g. yyyy-mm-dd) | Yes | string |
| end_date | path | End date (e.g. yyyy-mm-dd) | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERAPPLICATIONUSAGE/SERIALNUMBER/{SERIALNUMBER}/{START_DATE}_{END_DATE}
## ***GET*** 

**Summary:** Finds computer application usage by computer serial number

### HTTP Request 
`***GET*** /computerapplicationusage/serialnumber/{serialnumber}/{start_date}_{end_date}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| serialnumber | path | Serial number to filter by | Yes | string |
| start_date | path | Start date (e.g. yyyy-mm-dd) | Yes | string |
| end_date | path | End date (e.g. yyyy-mm-dd) | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERAPPLICATIONUSAGE/MACADDRESS/{MACADDRESS}/{START_DATE}_{END_DATE}
## ***GET*** 

**Summary:** Finds computer application usage by computer MAC address

### HTTP Request 
`***GET*** /computerapplicationusage/macaddress/{macaddress}/{start_date}_{end_date}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| macaddress | path | MAC address to filter by | Yes | string |
| start_date | path | Start date (e.g. yyyy-mm-dd) | Yes | string |
| end_date | path | End date (e.g. yyyy-mm-dd) | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERCHECKIN
## ***GET*** 

**Summary:** Finds the JSS computer checkin information

### HTTP Request 
`***GET*** /computercheckin` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates the JSS computer checkin information

### HTTP Request 
`***PUT*** /computercheckin` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

# /COMPUTERCOMMANDS
## ***GET*** 

**Summary:** Finds all computer commands

### HTTP Request 
`***GET*** /computercommands` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERCOMMANDS/COMMAND/{COMMAND}
## ***POST*** 

**Summary:** Creates a new computer command using command name

### HTTP Request 
`***POST*** /computercommands/command/{command}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| command | path |  | Yes | string |
| body | body | Command name | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

# /COMPUTERCOMMANDS/ID/{ID}
## ***GET*** 

**Summary:** Finds a computer command by ID

### HTTP Request 
`***GET*** /computercommands/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERCOMMANDS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds all computer commands by name

### HTTP Request 
`***GET*** /computercommands/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERCOMMANDS/UUID/{UUID}
## ***GET*** 

**Summary:** Finds a computer command by UUID

### HTTP Request 
`***GET*** /computercommands/uuid/{uuid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| uuid | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERCONFIGURATIONS
## ***GET*** 

**Summary:** Finds all computer configurations

### HTTP Request 
`***GET*** /computerconfigurations` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERCONFIGURATIONS/ID/{ID}
## ***GET*** 

**Summary:** Finds computer configurations by ID

### HTTP Request 
`***GET*** /computerconfigurations/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing computer configuration by ID

### HTTP Request 
`***PUT*** /computerconfigurations/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new computer configuration by ID

### HTTP Request 
`***POST*** /computerconfigurations/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body | Name of the configuration | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Created |

## ***DELETE*** 

**Summary:** Deletes a computer configuration by ID

### HTTP Request 
`***DELETE*** /computerconfigurations/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERCONFIGURATIONS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds computer configurations by name

### HTTP Request 
`***GET*** /computerconfigurations/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing computer configuration by name

### HTTP Request 
`***PUT*** /computerconfigurations/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a computer configuration by name

### HTTP Request 
`***DELETE*** /computerconfigurations/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTEREXTENSIONATTRIBUTES
## ***GET*** 

**Description:** Finds all computer extension attributes

### HTTP Request 
`***GET*** /computerextensionattributes` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTEREXTENSIONATTRIBUTES/ID/{ID}
## ***GET*** 

**Summary:** Finds computer extension attributes by ID

### HTTP Request 
`***GET*** /computerextensionattributes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing computer extension attribute by ID

### HTTP Request 
`***PUT*** /computerextensionattributes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new computer extension attribute by ID

### HTTP Request 
`***POST*** /computerextensionattributes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body | Extension attribute name | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a computer extension attribute by ID

### HTTP Request 
`***DELETE*** /computerextensionattributes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTEREXTENSIONATTRIBUTES/NAME/{NAME}
## ***GET*** 

**Summary:** Finds computer extension attributes by name

### HTTP Request 
`***GET*** /computerextensionattributes/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing computer extension attribute by name

### HTTP Request 
`***PUT*** /computerextensionattributes/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a computer extension attribute by name

### HTTP Request 
`***DELETE*** /computerextensionattributes/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERGROUPS
## ***GET*** 

**Summary:** Finds all computer groups

### HTTP Request 
`***GET*** /computergroups` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERGROUPS/ID/{ID}
## ***GET*** 

**Summary:** Finds computer groups by ID

### HTTP Request 
`***GET*** /computergroups/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing computer group by ID

### HTTP Request 
`***PUT*** /computergroups/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new computer group by ID

### HTTP Request 
`***POST*** /computergroups/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body | Name of the group | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a computer group by ID

### HTTP Request 
`***DELETE*** /computergroups/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERGROUPS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds computer groups by name

### HTTP Request 
`***GET*** /computergroups/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing computer group by name

### HTTP Request 
`***PUT*** /computergroups/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a computer group by name

### HTTP Request 
`***DELETE*** /computergroups/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERHARDWARESOFTWAREREPORTS/ID/{ID}/{START_DATE}_{END_DATE}
## ***GET*** 

**Summary:** Finds hardware/software reports by computer ID

### HTTP Request 
`***GET*** /computerhardwaresoftwarereports/id/{id}/{start_date}_{end_date}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | string |
| start_date | path | Start date (e.g. yyyy-mm-dd) | Yes | date |
| end_date | path | End date (e.g. yyyy-mm-dd) | Yes | date |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERHARDWARESOFTWAREREPORTS/NAME/{NAME}/{START_DATE}_{END_DATE}
## ***GET*** 

**Summary:** Finds hardware/software reports by computer name

### HTTP Request 
`***GET*** /computerhardwaresoftwarereports/name/{name}/{start_date}_{end_date}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |
| start_date | path | Start date (e.g. yyyy-mm-dd) | Yes | date |
| end_date | path | End date (e.g. yyyy-mm-dd) | Yes | date |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERHARDWARESOFTWAREREPORTS/UDID/{UDID}/{START_DATE}_{END_DATE}
## ***GET*** 

**Summary:** Finds hardware/software reports by computer UDID

### HTTP Request 
`***GET*** /computerhardwaresoftwarereports/udid/{udid}/{start_date}_{end_date}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| udid | path | UDID to filter by | Yes | string |
| start_date | path | Start date (e.g. yyyy-mm-dd) | Yes | date |
| end_date | path | End date (e.g. yyyy-mm-dd) | Yes | date |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERHARDWARESOFTWAREREPORTS/SERIALNUMBER/{SERIALNUMBER}/{START_DATE}_{END_DATE}
## ***GET*** 

**Summary:** Finds hardware/software reports by computer serial number

### HTTP Request 
`***GET*** /computerhardwaresoftwarereports/serialnumber/{serialnumber}/{start_date}_{end_date}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| serialnumber | path | Serial number to filter by | Yes | string |
| start_date | path | Start date (e.g. yyyy-mm-dd) | Yes | date |
| end_date | path | End date (e.g. yyyy-mm-dd) | Yes | date |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERHARDWARESOFTWAREREPORTS/MACADDRESS/{MACADDRESS}/{START_DATE}_{END_DATE}
## ***GET*** 

**Summary:** Finds hardware/software reports by computer MAC address

### HTTP Request 
`***GET*** /computerhardwaresoftwarereports/macaddress/{macaddress}/{start_date}_{end_date}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| macaddress | path | MAC address to filter by | Yes | string |
| start_date | path | Start date (e.g. yyyy-mm-dd) | Yes | date |
| end_date | path | End date (e.g. yyyy-mm-dd) | Yes | date |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERHARDWARESOFTWAREREPORTS/ID/{ID}/{START_DATE}_{END_DATE}/SUBSET/{SUBSET}
## ***GET*** 

**Summary:** Display subsets of information for computer hardware/software history

### HTTP Request 
`***GET*** /computerhardwaresoftwarereports/id/{id}/{start_date}_{end_date}/subset/{subset}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Computer ID to filter by | Yes | integer |
| start_date | path | Start date (e.g. yyyy-mm-dd) | Yes | date |
| end_date | path | End date (e.g. yyyy-mm-dd) | Yes | date |
| subset | path | Subset to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERHISTORY/ID/{ID}
## ***GET*** 

**Summary:** Finds computer history by ID

### HTTP Request 
`***GET*** /computerhistory/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Computer ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERHISTORY/NAME/{NAME}
## ***GET*** 

**Summary:** Finds computer history by name

### HTTP Request 
`***GET*** /computerhistory/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Computer Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERHISTORY/UDID/{UDID}
## ***GET*** 

**Summary:** Finds computer history by UDID

### HTTP Request 
`***GET*** /computerhistory/udid/{udid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| udid | path | Computer UDID to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERHISTORY/SERIALNUMBER/{SERIALNUMBER}
## ***GET*** 

**Summary:** Finds computer history by serial number

### HTTP Request 
`***GET*** /computerhistory/serialnumber/{serialnumber}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| serialnumber | path | Computer Serial Number to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERHISTORY/MACADDRESS/{MACADDRESS}
## ***GET*** 

**Summary:** Finds computer history by MAC address

### HTTP Request 
`***GET*** /computerhistory/macaddress/{macaddress}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| macaddress | path | Computer Mac Address to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERHISTORY/ID/{ID}/SUBSET/{SUBSET}
## ***GET*** 

**Summary:** Display subsets of information for a computer history

### HTTP Request 
`***GET*** /computerhistory/id/{id}/subset/{subset}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Computer ID to filter by | Yes | integer |
| subset | path | Subset to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERINVENTORYCOLLECTION
## ***GET*** 

**Summary:** Finds the JSS computer inventory collection information

### HTTP Request 
`***GET*** /computerinventorycollection` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates the JSS computer inventory collection information

### HTTP Request 
`***PUT*** /computerinventorycollection` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

# /COMPUTERMANAGEMENT/ID/{ID}
## ***GET*** 

**Summary:** Finds computer management information by ID

### HTTP Request 
`***GET*** /computermanagement/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Computer ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERMANAGEMENT/NAME/{NAME}
## ***GET*** 

**Summary:** Finds computer management information by name

### HTTP Request 
`***GET*** /computermanagement/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Computer Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERMANAGEMENT/UDID/{UDID}
## ***GET*** 

**Summary:** Finds computer management information by UDID

### HTTP Request 
`***GET*** /computermanagement/udid/{udid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| udid | path | Computer UDID to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERMANAGEMENT/SERIALNUMBER/{SERIALNUMBER}
## ***GET*** 

**Summary:** Finds computer management information by serial number

### HTTP Request 
`***GET*** /computermanagement/serialnumber/{serialnumber}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| serialnumber | path | Computer Serial Number to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERMANAGEMENT/MACADDRESS/{MACADDRESS}
## ***GET*** 

**Summary:** Finds computer management information by MAC address

### HTTP Request 
`***GET*** /computermanagement/macaddress/{macaddress}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| macaddress | path | Computer Mac Address to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERMANAGEMENT/ID/{ID}/SUBSET/{SUBSET}
## ***GET*** 

**Summary:** Display subsets of management information for a computer

### HTTP Request 
`***GET*** /computermanagement/id/{id}/subset/{subset}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Computer ID to filter by | Yes | integer |
| subset | path | Subset to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERMANAGEMENT/ID/{ID}/USERNAME/{USERNAME}
## ***GET*** 

**Summary:** Display management information for a computer and username

### HTTP Request 
`***GET*** /computermanagement/id/{id}/username/{username}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Computer ID to filter by | Yes | integer |
| username | path | Username to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERMANAGEMENT/ID/{ID}/USERNAME/{USERNAME}/SUBSET/{SUBSET}
## ***GET*** 

**Summary:** Display subsets of management information for a computer and username

### HTTP Request 
`***GET*** /computermanagement/id/{id}/username/{username}/subset/{subset}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Computer ID to filter by | Yes | integer |
| username | path | Username to filter by | Yes | string |
| subset | path | Subset to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERMANAGEMENT/ID/{ID}/PATCHFILTER/{FILTER}
## ***GET*** 

**Summary:** Display patch management information for a computer and filter

### HTTP Request 
`***GET*** /computermanagement/id/{id}/patchfilter/{filter}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Computer ID to filter by | Yes | integer |
| filter | path | filter to apply | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERS
## ***GET*** 

**Summary:** Finds all computers

### HTTP Request 
`***GET*** /computers` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERS/SUBSET/BASIC
## ***GET*** 

**Summary:** Finds basic information for all computers

### HTTP Request 
`***GET*** /computers/subset/basic` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERS/MATCH/{MATCH}
## ***GET*** 

**Summary:** Searches for computers that match the provided parameter

### HTTP Request 
`***GET*** /computers/match/{match}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| match | path | Name, mac address, etc. to filter by.  Match uses the same format as the general search in the JSS.  For instance, admin* can be used to match computer names that begin with admin | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERS/MATCH/NAME/{MATCHNAME}
## ***GET*** 

**Summary:** Searches for computers that match the provided name parameter

### HTTP Request 
`***GET*** /computers/match/name/{matchname}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| matchname | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERS/ID/{ID}
## ***GET*** 

**Summary:** Finds computers by ID

### HTTP Request 
`***GET*** /computers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing computer by ID

### HTTP Request 
`***PUT*** /computers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a computer

### HTTP Request 
`***POST*** /computers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a computer by ID

### HTTP Request 
`***DELETE*** /computers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds the first computer with the given name

### HTTP Request 
`***GET*** /computers/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing computer by name

### HTTP Request 
`***PUT*** /computers/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a computer by name

### HTTP Request 
`***DELETE*** /computers/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERS/UDID/{UDID}
## ***GET*** 

**Summary:** Finds computers by UDID

### HTTP Request 
`***GET*** /computers/udid/{udid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| udid | path | UDID to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing computer by UDID

### HTTP Request 
`***PUT*** /computers/udid/{udid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| udid | path | UDID value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a computer by UDID

### HTTP Request 
`***DELETE*** /computers/udid/{udid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| udid | path | UDID value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERS/SERIALNUMBER/{SERIALNUMBER}
## ***GET*** 

**Summary:** Finds computers by serial number

### HTTP Request 
`***GET*** /computers/serialnumber/{serialnumber}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| serialnumber | path | Serial number to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing computer by serial number

### HTTP Request 
`***PUT*** /computers/serialnumber/{serialnumber}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| serialnumber | path | Serial number value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a computer by serial number

### HTTP Request 
`***DELETE*** /computers/serialnumber/{serialnumber}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| serialnumber | path | Serial number value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERS/MACADDRESS/{MACADDRESS}
## ***GET*** 

**Summary:** Finds computers by MAC address

### HTTP Request 
`***GET*** /computers/macaddress/{macaddress}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| macaddress | path | Mac address to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing computer by MAC address

### HTTP Request 
`***PUT*** /computers/macaddress/{macaddress}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| macaddress | path | MAC address value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a computer by MAC address

### HTTP Request 
`***DELETE*** /computers/macaddress/{macaddress}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| macaddress | path | MAC address value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /COMPUTERS/ID/{ID}/SUBSET/{SUBSET}
## ***GET*** 

**Summary:** Display subsets of information for a computer

### HTTP Request 
`***GET*** /computers/id/{id}/subset/{subset}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID to filter by | Yes | integer |
| subset | path | Subset to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /DEPARTMENTS
## ***GET*** 

**Summary:** Finds all departments

### HTTP Request 
`***GET*** /departments` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /DEPARTMENTS/ID/{ID}
## ***GET*** 

**Summary:** Finds departments by ID

### HTTP Request 
`***GET*** /departments/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing department by ID

### HTTP Request 
`***PUT*** /departments/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new department by ID

### HTTP Request 
`***POST*** /departments/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body | Department name | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a department by ID

### HTTP Request 
`***DELETE*** /departments/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /DEPARTMENTS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds departments by name

### HTTP Request 
`***GET*** /departments/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing department by name

### HTTP Request 
`***PUT*** /departments/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a department by name

### HTTP Request 
`***DELETE*** /departments/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /DIRECTORYBINDINGS
## ***GET*** 

**Summary:** Finds all directory bindings

### HTTP Request 
`***GET*** /directorybindings` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /DIRECTORYBINDINGS/ID/{ID}
## ***GET*** 

**Summary:** Finds directory bindings by ID

### HTTP Request 
`***GET*** /directorybindings/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing directory binding by ID

### HTTP Request 
`***PUT*** /directorybindings/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new directory binding by ID

### HTTP Request 
`***POST*** /directorybindings/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a directory binding by ID

### HTTP Request 
`***DELETE*** /directorybindings/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /DIRECTORYBINDINGS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds directory bindings by name

### HTTP Request 
`***GET*** /directorybindings/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing directory binding by name

### HTTP Request 
`***PUT*** /directorybindings/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a directory binding by name

### HTTP Request 
`***DELETE*** /directorybindings/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /DISKENCRYPTIONCONFIGURATIONS
## ***GET*** 

**Summary:** Finds all disk encryption configurations

### HTTP Request 
`***GET*** /diskencryptionconfigurations` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /DISKENCRYPTIONCONFIGURATIONS/ID/{ID}
## ***GET*** 

**Summary:** Finds disk encryption configurations by ID

### HTTP Request 
`***GET*** /diskencryptionconfigurations/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing disk encryption configuration by ID

### HTTP Request 
`***PUT*** /diskencryptionconfigurations/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new disk encryption configuration by ID

### HTTP Request 
`***POST*** /diskencryptionconfigurations/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a disk encryption configuration by ID

### HTTP Request 
`***DELETE*** /diskencryptionconfigurations/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /DISKENCRYPTIONCONFIGURATIONS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds disk encryption configurations by name

### HTTP Request 
`***GET*** /diskencryptionconfigurations/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing disk encryption configuration by name

### HTTP Request 
`***PUT*** /diskencryptionconfigurations/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a disk encryption configuration by name

### HTTP Request 
`***DELETE*** /diskencryptionconfigurations/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /DISTRIBUTIONPOINTS
## ***GET*** 

**Summary:** Finds all distribution points

### HTTP Request 
`***GET*** /distributionpoints` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /DISTRIBUTIONPOINTS/ID/{ID}
## ***GET*** 

**Summary:** Finds distribution points by ID

### HTTP Request 
`***GET*** /distributionpoints/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing distribution point by ID

### HTTP Request 
`***PUT*** /distributionpoints/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new distribution point by ID

### HTTP Request 
`***POST*** /distributionpoints/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body | Distribution point name | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a distribution point by ID

### HTTP Request 
`***DELETE*** /distributionpoints/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /DISTRIBUTIONPOINTS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds distribution points by name

### HTTP Request 
`***GET*** /distributionpoints/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing distribution point by name

### HTTP Request 
`***PUT*** /distributionpoints/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a distribution point by name

### HTTP Request 
`***DELETE*** /distributionpoints/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /DOCKITEMS
## ***GET*** 

**Summary:** Finds all dock items

### HTTP Request 
`***GET*** /dockitems` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /DOCKITEMS/ID/{ID}
## ***GET*** 

**Summary:** Finds dock items by ID

### HTTP Request 
`***GET*** /dockitems/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing dock item by ID

### HTTP Request 
`***PUT*** /dockitems/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new dock item by ID

### HTTP Request 
`***POST*** /dockitems/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body | Dock item name | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a dock item by ID

### HTTP Request 
`***DELETE*** /dockitems/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /DOCKITEMS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds dock items by name

### HTTP Request 
`***GET*** /dockitems/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing dock item by name

### HTTP Request 
`***PUT*** /dockitems/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a dock item by name

### HTTP Request 
`***DELETE*** /dockitems/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /EBOOKS
## ***GET*** 

**Summary:** Finds all ebooks

### HTTP Request 
`***GET*** /ebooks` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /EBOOKS/ID/{ID}
## ***GET*** 

**Summary:** Finds ebooks by ID

### HTTP Request 
`***GET*** /ebooks/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing ebook by ID

### HTTP Request 
`***PUT*** /ebooks/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new ebook by ID

### HTTP Request 
`***POST*** /ebooks/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body | Ebook name | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes an ebook by ID

### HTTP Request 
`***DELETE*** /ebooks/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /EBOOKS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds ebooks by name

### HTTP Request 
`***GET*** /ebooks/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing ebook by name

### HTTP Request 
`***PUT*** /ebooks/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes an ebook by name

### HTTP Request 
`***DELETE*** /ebooks/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /EBOOKS/ID/{ID}/SUBSET/{SUBSET}
## ***GET*** 

**Summary:** Display subsets of information for an ebook

### HTTP Request 
`***GET*** /ebooks/id/{id}/subset/{subset}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID to filter by | Yes | string |
| subset | path | Subset to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /FILEUPLOADS/{RESOURCE}/{IDTYPE}/{ID}
## ***POST*** 

**Summary:** Creates file attachments in the JSS

**Description:** Here is a sample command curl -k -u user:password https://my.jss:8443/JSSResource/fileuploads/computers/id/2 -F name=@/Users/admin/Documents/Sample.doc -X POST

### HTTP Request 
`***POST*** /fileuploads/{resource}/{idType}/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| resource | path | Resource to attach the file to | Yes | string |
| idType | path | Name is supported for all but the peripherals resource | Yes | string |
| id | path |  | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

# /GSXCONNECTION
## ***GET*** 

**Summary:** Finds the JSS GSX connection information

### HTTP Request 
`***GET*** /gsxconnection` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates the JSS GSX connection information

### HTTP Request 
`***PUT*** /gsxconnection` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

# /HEALTHCARELISTENER
## ***GET*** 

**Summary:** Find all Healthcare Listeners

### HTTP Request 
`***GET*** /healthcarelistener` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /HEALTHCARELISTENER/ID/{ID}
## ***GET*** 

**Summary:** Finds healthcare listener by ID

### HTTP Request 
`***GET*** /healthcarelistener/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing healthcare listener by ID

### HTTP Request 
`***PUT*** /healthcarelistener/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

# /IBEACONS
## ***GET*** 

**Summary:** Finds all iBeacon regions

### HTTP Request 
`***GET*** /ibeacons` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /IBEACONS/ID/{ID}
## ***GET*** 

**Summary:** Finds iBeacon regions by ID

### HTTP Request 
`***GET*** /ibeacons/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing iBeacon region by ID

### HTTP Request 
`***PUT*** /ibeacons/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new iBeacon region by ID

### HTTP Request 
`***POST*** /ibeacons/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body | Name of the iBeacon | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes an iBeacon region by ID

### HTTP Request 
`***DELETE*** /ibeacons/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /IBEACONS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds iBeacon regions by name

### HTTP Request 
`***GET*** /ibeacons/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing iBeacon region by name

### HTTP Request 
`***PUT*** /ibeacons/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes an iBeacon region by name

### HTTP Request 
`***DELETE*** /ibeacons/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /INFRASTRUCTUREMANAGER
## ***GET*** 

**Summary:** Find all Infrastructure Managers

### HTTP Request 
`***GET*** /infrastructuremanager` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /INFRASTRUCTUREMANAGER/ID/{ID}
## ***GET*** 

**Summary:** Finds infrastructure manager by ID

### HTTP Request 
`***GET*** /infrastructuremanager/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing infrastructure manager by ID

### HTTP Request 
`***PUT*** /infrastructuremanager/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

# /LDAPSERVERS
## ***GET*** 

**Summary:** Finds all LDAP servers

### HTTP Request 
`***GET*** /ldapservers` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /LDAPSERVERS/ID/{ID}
## ***GET*** 

**Summary:** Finds LDAP servers by ID

### HTTP Request 
`***GET*** /ldapservers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing LDAP server by ID

### HTTP Request 
`***PUT*** /ldapservers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new LDAP server by ID

### HTTP Request 
`***POST*** /ldapservers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body | LDAP server name | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes an LDAP server by ID

### HTTP Request 
`***DELETE*** /ldapservers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /LDAPSERVERS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds LDAP servers by name

### HTTP Request 
`***GET*** /ldapservers/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing LDAP server by name

### HTTP Request 
`***PUT*** /ldapservers/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes an LDAP server by name

### HTTP Request 
`***DELETE*** /ldapservers/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /LDAPSERVERS/ID/{ID}/USER/{USER}
## ***GET*** 

**Summary:** Display information for matching users for an LDAP server

### HTTP Request 
`***GET*** /ldapservers/id/{id}/user/{user}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Server ID to filter by | Yes | integer |
| user | path | User to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /LDAPSERVERS/ID/{ID}/GROUP/{GROUP}
## ***GET*** 

**Summary:** Display information for matching groups for an LDAP server

### HTTP Request 
`***GET*** /ldapservers/id/{id}/group/{group}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Server ID to filter by | Yes | integer |
| group | path | Group to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /LDAPSERVERS/ID/{ID}/GROUP/{GROUP}/USER/{USER}
## ***GET*** 

**Summary:** Display information about user membership in a group for an LDAP server

### HTTP Request 
`***GET*** /ldapservers/id/{id}/group/{group}/user/{user}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Server ID to filter by | Yes | integer |
| group | path | Group to filter by | Yes | string |
| user | path | User to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /LICENSEDSOFTWARE
## ***GET*** 

**Summary:** Finds all licensed software

### HTTP Request 
`***GET*** /licensedsoftware` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /LICENSEDSOFTWARE/ID/{ID}
## ***GET*** 

**Summary:** Finds licensed software by ID

### HTTP Request 
`***GET*** /licensedsoftware/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing computer command by ID

### HTTP Request 
`***PUT*** /licensedsoftware/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new computer command by ID

### HTTP Request 
`***POST*** /licensedsoftware/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body | Licensed software name | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a computer command by ID

### HTTP Request 
`***DELETE*** /licensedsoftware/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /LICENSEDSOFTWARE/NAME/{NAME}
## ***GET*** 

**Summary:** Finds licensed software by name

### HTTP Request 
`***GET*** /licensedsoftware/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing computer command by name

### HTTP Request 
`***PUT*** /licensedsoftware/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a computer command by name

### HTTP Request 
`***DELETE*** /licensedsoftware/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /LOGFLUSH
## ***DELETE*** 

**Summary:** Flushes a log specified in an XML file

### HTTP Request 
`***DELETE*** /logflush` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /LOGFLUSH/{LOG}/INTERVAL/{INTERVAL}
## ***DELETE*** 

**Summary:** Flushes all logs for a given interval

### HTTP Request 
`***DELETE*** /logflush/{log}/interval/{interval}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| interval | path | Supported values are a combination of [Zero, One, Two, Three, Six] and [Days, Weeks, Months, Years] | Yes | string |
| log | path | At this time, only 'policy' logs are supported | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /LOGFLUSH/{LOG}/ID/{ID}/INTERVAL/{INTERVAL}
## ***DELETE*** 

**Summary:** Flushes a single log for a given interval

### HTTP Request 
`***DELETE*** /logflush/{log}/id/{id}/interval/{interval}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID of policy whose log will be flushed | Yes | string |
| log | path | At this time, only 'policy' logs are supported | Yes | string |
| interval | path | Supported values are a combination of [Zero, One, Two, Three, Six] and [Days, Weeks, Months, Years] | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MACAPPLICATIONS
## ***GET*** 

**Summary:** Finds all mac applications

### HTTP Request 
`***GET*** /macapplications` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MACAPPLICATIONS/ID/{ID}
## ***GET*** 

**Summary:** Finds mac applications by ID

### HTTP Request 
`***GET*** /macapplications/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mac application by ID

### HTTP Request 
`***PUT*** /macapplications/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new mac application by ID

### HTTP Request 
`***POST*** /macapplications/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mac application by ID

### HTTP Request 
`***DELETE*** /macapplications/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MACAPPLICATIONS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds mac applications by name

### HTTP Request 
`***GET*** /macapplications/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mac application by name

### HTTP Request 
`***PUT*** /macapplications/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mac application by name

### HTTP Request 
`***DELETE*** /macapplications/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MACAPPLICATIONS/ID/{ID}/SUBSET/{SUBSET}
## ***GET*** 

**Summary:** Display subsets of information for a mac application

### HTTP Request 
`***GET*** /macapplications/id/{id}/subset/{subset}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID to filter by | Yes | integer |
| subset | path | Subset to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MANAGEDPREFERENCEPROFILES
## ***GET*** 

**Summary:** Finds all managed preference profiles

### HTTP Request 
`***GET*** /managedpreferenceprofiles` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MANAGEDPREFERENCEPROFILES/ID/{ID}
## ***GET*** 

**Summary:** Finds managed preference profiles by ID

### HTTP Request 
`***GET*** /managedpreferenceprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing managed preference profiles by ID

### HTTP Request 
`***PUT*** /managedpreferenceprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new managed preference profile by ID

### HTTP Request 
`***POST*** /managedpreferenceprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a managed preference profiles by ID

### HTTP Request 
`***DELETE*** /managedpreferenceprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MANAGEDPREFERENCEPROFILES/ID/{ID}/SUBSET/{SUBSET}
## ***GET*** 

**Summary:** Display subsets of information for a managed preference profile

### HTTP Request 
`***GET*** /managedpreferenceprofiles/id/{id}/subset/{subset}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID to filter by | Yes | integer |
| subset | path | Subset to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MANAGEDPREFERENCEPROFILES/NAME/{NAME}
## ***GET*** 

**Summary:** Finds managed preference profiles by name

### HTTP Request 
`***GET*** /managedpreferenceprofiles/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing managed preference profiles by name

### HTTP Request 
`***PUT*** /managedpreferenceprofiles/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a managed preference profiles by name

### HTTP Request 
`***DELETE*** /managedpreferenceprofiles/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEAPPLICATIONS
## ***GET*** 

**Summary:** Finds all mobile device applications

### HTTP Request 
`***GET*** /mobiledeviceapplications` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEAPPLICATIONS/ID/{ID}
## ***GET*** 

**Summary:** Finds mobile device applications by ID

### HTTP Request 
`***GET*** /mobiledeviceapplications/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mobile device application by ID

### HTTP Request 
`***PUT*** /mobiledeviceapplications/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new mobile device application by ID

### HTTP Request 
`***POST*** /mobiledeviceapplications/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device application by ID

### HTTP Request 
`***DELETE*** /mobiledeviceapplications/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEAPPLICATIONS/BUNDLEID/{BUNDLEID}
## ***GET*** 

**Summary:** Finds mobile device applications by bundle ID

### HTTP Request 
`***GET*** /mobiledeviceapplications/bundleid/{bundleid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| bundleid | path | Bundle ID to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mobile device application by bundle ID

### HTTP Request 
`***PUT*** /mobiledeviceapplications/bundleid/{bundleid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| bundleid | path | Bundle ID value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device application by bundle ID

### HTTP Request 
`***DELETE*** /mobiledeviceapplications/bundleid/{bundleid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| bundleid | path | Bundle ID value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEAPPLICATIONS/BUNDLEID/{BUNDLEID}/VERSION/{VERSION}
## ***GET*** 

**Summary:** Finds mobile device applications by bundle ID and version

### HTTP Request 
`***GET*** /mobiledeviceapplications/bundleid/{bundleid}/version/{version}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| bundleid | path | Bundle ID to filter by | Yes | string |
| version | path | Version to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mobile device application by bundle ID and version

### HTTP Request 
`***PUT*** /mobiledeviceapplications/bundleid/{bundleid}/version/{version}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| bundleid | path | Bundle ID value to filter by | Yes | string |
| version | path | Version to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device application by bundle ID and version

### HTTP Request 
`***DELETE*** /mobiledeviceapplications/bundleid/{bundleid}/version/{version}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| bundleid | path | Bundle ID value to filter by | Yes | string |
| version | path | Version to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEAPPLICATIONS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds mobile device applications by name

### HTTP Request 
`***GET*** /mobiledeviceapplications/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mobile device application by name

### HTTP Request 
`***PUT*** /mobiledeviceapplications/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device application by name

### HTTP Request 
`***DELETE*** /mobiledeviceapplications/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEAPPLICATIONS/ID/{ID}/SUBSET/{SUBSET}
## ***GET*** 

**Summary:** Display subsets of information for a mobile device application

### HTTP Request 
`***GET*** /mobiledeviceapplications/id/{id}/subset/{subset}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID to filter by | Yes | integer |
| subset | path | Subset to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICECOMMANDS
## ***GET*** 

**Summary:** Finds all mobile device commands

### HTTP Request 
`***GET*** /mobiledevicecommands` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICECOMMANDS/ID/{ID}
## ***GET*** 

**Summary:** Finds a mobile device command by ID

### HTTP Request 
`***GET*** /mobiledevicecommands/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICECOMMANDS/UUID/{UUID}
## ***GET*** 

**Summary:** Finds a mobile device command by UUDI

### HTTP Request 
`***GET*** /mobiledevicecommands/uuid/{uuid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| uuid | path | UUID value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICECOMMANDS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds all mobile device commands by command name

### HTTP Request 
`***GET*** /mobiledevicecommands/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICECOMMANDS/COMMAND/{COMMAND}
## ***GET*** 

**Summary:** Finds all mobile device commands for specified command

### HTTP Request 
`***GET*** /mobiledevicecommands/command/{command}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| command | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICECOMMANDS/COMMAND
## ***POST*** 

**Summary:** Creates a new mobile device command

### HTTP Request 
`***POST*** /mobiledevicecommands/command` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| body | body | Command name | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

# /MOBILEDEVICECOMMANDS/COMMAND/{COMMAND}/ID/{ID_LIST}
## ***POST*** 

**Summary:** Creates a new mobile device command

### HTTP Request 
`***POST*** /mobiledevicecommands/command/{command}/id/{id_list}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id_list | path | Mobile device ID values, multiple IDs may be separated by commas | Yes | string |
| command | path | Command to send device | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

# /MOBILEDEVICECOMMANDS/COMMAND/DEVICENAME/{DEVICE_NAME}/ID/{ID_LIST}
## ***POST*** 

**Summary:** Creates a new command to set the name of a mobile device.

### HTTP Request 
`***POST*** /mobiledevicecommands/command/DeviceName/{device_name}/id/{id_list}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id_list | path | Mobile device ID values, multiple IDs may be separated by commas | Yes | string |
| device_name | path | Device name to set | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

# /MOBILEDEVICECOMMANDS/COMMAND/DEVICELOCK/{LOCK_MESSAGE}/ID/{ID_LIST}
## ***POST*** 

**Summary:** Sends a new lock command to a list of mobile devices

### HTTP Request 
`***POST*** /mobiledevicecommands/command/DeviceLock/{lock_message}/id/{id_list}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id_list | path | Mobile device ID values, multiple IDs may be separated by commas | Yes | string |
| lock_message | path | Lock message for the DeviceLock command | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

# /MOBILEDEVICECONFIGURATIONPROFILES
## ***GET*** 

**Summary:** Finds all mobile device configuration profiles

### HTTP Request 
`***GET*** /mobiledeviceconfigurationprofiles` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICECONFIGURATIONPROFILES/ID/{ID}
## ***GET*** 

**Summary:** Finds mobile device configuration profiles by ID

### HTTP Request 
`***GET*** /mobiledeviceconfigurationprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mobile device configuration profile by ID

### HTTP Request 
`***PUT*** /mobiledeviceconfigurationprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new mobile device configuration profile by ID

### HTTP Request 
`***POST*** /mobiledeviceconfigurationprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device configuration profile by ID

### HTTP Request 
`***DELETE*** /mobiledeviceconfigurationprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICECONFIGURATIONPROFILES/NAME/{NAME}
## ***GET*** 

**Summary:** Finds mobile device configuration profiles by name

### HTTP Request 
`***GET*** /mobiledeviceconfigurationprofiles/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mobile device configuration profile by name

### HTTP Request 
`***PUT*** /mobiledeviceconfigurationprofiles/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device configuration profile by name

### HTTP Request 
`***DELETE*** /mobiledeviceconfigurationprofiles/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICECONFIGURATIONPROFILES/ID/{ID}/SUBSET/{SUBSET}
## ***GET*** 

**Summary:** Display subsets of information for a mobile device configuration profile

### HTTP Request 
`***GET*** /mobiledeviceconfigurationprofiles/id/{id}/subset/{subset}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID to filter by | Yes | integer |
| subset | path | Subset to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEENROLLMENTPROFILES
## ***GET*** 

**Summary:** Finds all mobile device enrollment profiles

### HTTP Request 
`***GET*** /mobiledeviceenrollmentprofiles` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEENROLLMENTPROFILES/ID/{ID}
## ***GET*** 

**Summary:** Finds mobile device enrollment profiles by ID

### HTTP Request 
`***GET*** /mobiledeviceenrollmentprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mobile device enrollment profile by ID

### HTTP Request 
`***PUT*** /mobiledeviceenrollmentprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new mobile device enrollment profile by ID

### HTTP Request 
`***POST*** /mobiledeviceenrollmentprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device enrollment profile by ID

### HTTP Request 
`***DELETE*** /mobiledeviceenrollmentprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEENROLLMENTPROFILES/INVITATION/{INVITATION}
## ***GET*** 

**Summary:** Finds mobile device enrollment profiles by invitation

### HTTP Request 
`***GET*** /mobiledeviceenrollmentprofiles/invitation/{invitation}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| invitation | path | Invitation value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mobile device enrollment profile by invitation

### HTTP Request 
`***PUT*** /mobiledeviceenrollmentprofiles/invitation/{invitation}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| invitation | path | Invitation value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device enrollment profile by invitation

### HTTP Request 
`***DELETE*** /mobiledeviceenrollmentprofiles/invitation/{invitation}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| invitation | path | Invitation value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEENROLLMENTPROFILES/NAME/{NAME}
## ***GET*** 

**Description:** Finds mobile device enrollment profiles by name

### HTTP Request 
`***GET*** /mobiledeviceenrollmentprofiles/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mobile device enrollment profile by name

### HTTP Request 
`***PUT*** /mobiledeviceenrollmentprofiles/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device enrollment profile by name

### HTTP Request 
`***DELETE*** /mobiledeviceenrollmentprofiles/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEENROLLMENTPROFILES/ID/{ID}/SUBSET/{SUBSET}
## ***GET*** 

**Summary:** Display subsets of information for an enrollment profile

### HTTP Request 
`***GET*** /mobiledeviceenrollmentprofiles/id/{id}/subset/{subset}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID to filter by | Yes | integer |
| subset | path | Subset to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEEXTENSIONATTRIBUTES
## ***GET*** 

**Summary:** Finds all mobile device extension attributes

### HTTP Request 
`***GET*** /mobiledeviceextensionattributes` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEEXTENSIONATTRIBUTES/ID/{ID}
## ***GET*** 

**Summary:** Finds mobile device extension attributes by ID

### HTTP Request 
`***GET*** /mobiledeviceextensionattributes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mobile device extension attribute by ID

### HTTP Request 
`***PUT*** /mobiledeviceextensionattributes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new mobile device extension attribute by ID

### HTTP Request 
`***POST*** /mobiledeviceextensionattributes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device extension attribute by ID

### HTTP Request 
`***DELETE*** /mobiledeviceextensionattributes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEEXTENSIONATTRIBUTES/NAME/{NAME}
## ***GET*** 

**Summary:** Finds mobiledeviceextensionattributes by name

### HTTP Request 
`***GET*** /mobiledeviceextensionattributes/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mobile device extension attribute by name

### HTTP Request 
`***PUT*** /mobiledeviceextensionattributes/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device extension attribute by name

### HTTP Request 
`***DELETE*** /mobiledeviceextensionattributes/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEGROUPS
## ***GET*** 

**Summary:** Finds all mobile device groups

### HTTP Request 
`***GET*** /mobiledevicegroups` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEGROUPS/ID/{ID}
## ***GET*** 

**Summary:** Finds mobile device groups by ID

### HTTP Request 
`***GET*** /mobiledevicegroups/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mobile device group by ID

### HTTP Request 
`***PUT*** /mobiledevicegroups/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new mobile device group by ID

### HTTP Request 
`***POST*** /mobiledevicegroups/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device group by ID

### HTTP Request 
`***DELETE*** /mobiledevicegroups/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEGROUPS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds mobile device groups by name

### HTTP Request 
`***GET*** /mobiledevicegroups/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mobile device group by name

### HTTP Request 
`***PUT*** /mobiledevicegroups/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device group by name

### HTTP Request 
`***DELETE*** /mobiledevicegroups/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEHISTORY/ID/{ID}
## ***GET*** 

**Summary:** Finds mobile device history by ID

### HTTP Request 
`***GET*** /mobiledevicehistory/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEHISTORY/NAME/{NAME}
## ***GET*** 

**Summary:** Finds mobile device history by name

### HTTP Request 
`***GET*** /mobiledevicehistory/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEHISTORY/UDID/{UDID}
## ***GET*** 

**Summary:** Finds mobile device history by UDID

### HTTP Request 
`***GET*** /mobiledevicehistory/udid/{udid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| udid | path | UDID to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEHISTORY/SERIALNUMBER/{SERIALNUMBER}
## ***GET*** 

**Summary:** Finds mobile device history by serial number

### HTTP Request 
`***GET*** /mobiledevicehistory/serialnumber/{serialnumber}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| serialnumber | path | Serial number to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEHISTORY/MACADDRESS/{MACADDRESS}
## ***GET*** 

**Summary:** Finds mobile device history by wifi mac address

### HTTP Request 
`***GET*** /mobiledevicehistory/macaddress/{macaddress}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| macaddress | path | Mac address to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICEHISTORY/ID/{ID}/SUBSET/{SUBSET}
## ***GET*** 

**Summary:** Display subsets of information for a mobile device history

### HTTP Request 
`***GET*** /mobiledevicehistory/id/{id}/subset/{subset}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID to filter by | Yes | integer |
| subset | path | Subset to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICES
## ***GET*** 

**Summary:** Finds all mobile devices

### HTTP Request 
`***GET*** /mobiledevices` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICES/MATCH/{MATCH}
## ***GET*** 

**Summary:** Searches for mobile devices that match the provided parameter

### HTTP Request 
`***GET*** /mobiledevices/match/{match}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| match | path | Name, mac address, etc. to filter by. Match uses the same format as the general search in the JSS. | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICES/ID/{ID}
## ***GET*** 

**Summary:** Finds mobile devices by ID

### HTTP Request 
`***GET*** /mobiledevices/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mobile device by ID

### HTTP Request 
`***PUT*** /mobiledevices/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new mobile device by ID

### HTTP Request 
`***POST*** /mobiledevices/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device by ID

### HTTP Request 
`***DELETE*** /mobiledevices/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICES/NAME/{NAME}
## ***GET*** 

**Summary:** Finds mobile devices by name

### HTTP Request 
`***GET*** /mobiledevices/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mobile device by name

### HTTP Request 
`***PUT*** /mobiledevices/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device by name

### HTTP Request 
`***DELETE*** /mobiledevices/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICES/UDID/{UDID}
## ***GET*** 

**Summary:** Finds mobile devices by UDID

### HTTP Request 
`***GET*** /mobiledevices/udid/{udid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| udid | path | UDID to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mobile device by UDID

### HTTP Request 
`***PUT*** /mobiledevices/udid/{udid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| udid | path | UDID value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device by UDID

### HTTP Request 
`***DELETE*** /mobiledevices/udid/{udid}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| udid | path | UDID value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICES/SERIALNUMBER/{SERIALNUMBER}
## ***GET*** 

**Summary:** Finds mobile devices by serial number

### HTTP Request 
`***GET*** /mobiledevices/serialnumber/{serialnumber}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| serialnumber | path | Serial number to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mobile device by serial number

### HTTP Request 
`***PUT*** /mobiledevices/serialnumber/{serialnumber}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| serialnumber | path | Serial number value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device by serial number

### HTTP Request 
`***DELETE*** /mobiledevices/serialnumber/{serialnumber}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| serialnumber | path | Serial number value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICES/MACADDRESS/{MACADDRESS}
## ***GET*** 

**Summary:** Finds mobile devices by Mac address

### HTTP Request 
`***GET*** /mobiledevices/macaddress/{macaddress}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| macaddress | path | Mac address to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing mobile device by Mac address

### HTTP Request 
`***PUT*** /mobiledevices/macaddress/{macaddress}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| macaddress | path | Mac address value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a mobile device by Mac address

### HTTP Request 
`***DELETE*** /mobiledevices/macaddress/{macaddress}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| macaddress | path | Mac address value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /MOBILEDEVICES/ID/{ID}/SUBSET/{SUBSET}
## ***GET*** 

**Summary:** Display subsets of information for a mobile device

### HTTP Request 
`***GET*** /mobiledevices/id/{id}/subset/{subset}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID to filter by | Yes | integer |
| subset | path | Subset to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /NETBOOTSERVERS
## ***GET*** 

**Summary:** Finds all netboot servers

### HTTP Request 
`***GET*** /netbootservers` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /NETBOOTSERVERS/ID/{ID}
## ***GET*** 

**Summary:** Finds netboot servers by ID

### HTTP Request 
`***GET*** /netbootservers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing netboot server by ID

### HTTP Request 
`***PUT*** /netbootservers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new netboot server by ID

### HTTP Request 
`***POST*** /netbootservers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a netboot server by ID

### HTTP Request 
`***DELETE*** /netbootservers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /NETBOOTSERVERS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds netboot servers by name

### HTTP Request 
`***GET*** /netbootservers/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing netboot server by name

### HTTP Request 
`***PUT*** /netbootservers/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a netboot server by name

### HTTP Request 
`***DELETE*** /netbootservers/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /NETWORKSEGMENTS
## ***GET*** 

**Summary:** Finds all network segments

### HTTP Request 
`***GET*** /networksegments` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /NETWORKSEGMENTS/ID/{ID}
## ***GET*** 

**Summary:** Finds network segments by ID

### HTTP Request 
`***GET*** /networksegments/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing network segment by ID

### HTTP Request 
`***PUT*** /networksegments/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new network segment by ID

### HTTP Request 
`***POST*** /networksegments/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a network segment by ID

### HTTP Request 
`***DELETE*** /networksegments/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /NETWORKSEGMENTS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds network segments by name

### HTTP Request 
`***GET*** /networksegments/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing network segment by name

### HTTP Request 
`***PUT*** /networksegments/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a network segment by name

### HTTP Request 
`***DELETE*** /networksegments/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /OSXCONFIGURATIONPROFILES
## ***GET*** 

**Summary:** Finds all OS X configuration profiles

### HTTP Request 
`***GET*** /osxconfigurationprofiles` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /OSXCONFIGURATIONPROFILES/ID/{ID}
## ***GET*** 

**Summary:** Finds OS X configuration profiles by ID

### HTTP Request 
`***GET*** /osxconfigurationprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing OS X configuration profile by ID

### HTTP Request 
`***PUT*** /osxconfigurationprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new OS X configuration profile by ID

### HTTP Request 
`***POST*** /osxconfigurationprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a OS X configuration profile by ID

### HTTP Request 
`***DELETE*** /osxconfigurationprofiles/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /OSXCONFIGURATIONPROFILES/NAME/{NAME}
## ***GET*** 

**Summary:** Finds OS X configuration profiles by name

### HTTP Request 
`***GET*** /osxconfigurationprofiles/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing OS X configuration profile by name

### HTTP Request 
`***PUT*** /osxconfigurationprofiles/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a OS X configuration profile by name

### HTTP Request 
`***DELETE*** /osxconfigurationprofiles/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /OSXCONFIGURATIONPROFILES/ID/{ID}/SUBSET/{SUBSET}
## ***GET*** 

**Summary:** Display subsets of information for an OS X configuration profile

### HTTP Request 
`***GET*** /osxconfigurationprofiles/id/{id}/subset/{subset}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID to filter by | Yes | integer |
| subset | path | Subset to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /PACKAGES
## ***GET*** 

**Summary:** Finds all packages

### HTTP Request 
`***GET*** /packages` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /PACKAGES/ID/{ID}
## ***GET*** 

**Summary:** Finds packages by ID

### HTTP Request 
`***GET*** /packages/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing package by ID

### HTTP Request 
`***PUT*** /packages/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new package by ID

### HTTP Request 
`***POST*** /packages/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a package by ID

### HTTP Request 
`***DELETE*** /packages/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /PACKAGES/NAME/{NAME}
## ***GET*** 

**Summary:** Finds packages by name

### HTTP Request 
`***GET*** /packages/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing package by name

### HTTP Request 
`***PUT*** /packages/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a package by name

### HTTP Request 
`***DELETE*** /packages/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /PATCHES
## ***GET*** 

**Summary:** Finds all patches

### HTTP Request 
`***GET*** /patches` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /PATCHES/ID/{ID}
## ***GET*** 

**Summary:** Finds patches by ID

### HTTP Request 
`***GET*** /patches/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates a Patch Software Title by ID

### HTTP Request 
`***PUT*** /patches/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to update by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a Patch Software Title by ID

### HTTP Request 
`***DELETE*** /patches/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /PATCHES/NAME/{NAME}
## ***GET*** 

**Summary:** Finds the first patch with the name provided

### HTTP Request 
`***GET*** /patches/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates a Patch Software Title by name

### HTTP Request 
`***PUT*** /patches/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to update by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a Patch Software Title by name

### HTTP Request 
`***DELETE*** /patches/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /PATCHES/ID/{ID}/VERSION/{VERSION}
## ***GET*** 

**Summary:** Display computers on a specific version

### HTTP Request 
`***GET*** /patches/id/{id}/version/{version}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID to filter by | Yes | integer |
| version | path | Version number to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /PERIPHERALS
## ***GET*** 

**Summary:** Finds all peripherals

### HTTP Request 
`***GET*** /peripherals` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /PERIPHERALS/ID/{ID}
## ***GET*** 

**Summary:** Finds peripherals by ID

### HTTP Request 
`***GET*** /peripherals/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing peripheral by ID

### HTTP Request 
`***PUT*** /peripherals/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new peripheral by ID

### HTTP Request 
`***POST*** /peripherals/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a peripheral by ID

### HTTP Request 
`***DELETE*** /peripherals/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /PERIPHERALS/ID/{ID}/SUBSET/{SUBSET}
## ***GET*** 

**Summary:** Display subsets of information for a peripheral

### HTTP Request 
`***GET*** /peripherals/id/{id}/subset/{subset}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID to filter by | Yes | integer |
| subset | path | Subset to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /PERIPHERALTYPES
## ***GET*** 

**Summary:** Finds all peripheral types

### HTTP Request 
`***GET*** /peripheraltypes` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /PERIPHERALTYPES/ID/{ID}
## ***GET*** 

**Summary:** Finds peripheral types by ID

### HTTP Request 
`***GET*** /peripheraltypes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing peripheral by ID

### HTTP Request 
`***PUT*** /peripheraltypes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new peripheral by ID

### HTTP Request 
`***POST*** /peripheraltypes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a peripheral by ID

### HTTP Request 
`***DELETE*** /peripheraltypes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /POLICIES
## ***GET*** 

**Summary:** Finds all policies

### HTTP Request 
`***GET*** /policies` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /POLICIES/ID/{ID}
## ***GET*** 

**Summary:** Finds policies by ID

### HTTP Request 
`***GET*** /policies/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing policy by ID

### HTTP Request 
`***PUT*** /policies/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new policy by ID

### HTTP Request 
`***POST*** /policies/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a policy by ID

### HTTP Request 
`***DELETE*** /policies/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /POLICIES/NAME/{NAME}
## ***GET*** 

**Summary:** Finds policies by name

### HTTP Request 
`***GET*** /policies/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing policy by name

### HTTP Request 
`***PUT*** /policies/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a policy by name

### HTTP Request 
`***DELETE*** /policies/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /POLICIES/ID/{ID}/SUBSET/{SUBSET}
## ***GET*** 

**Summary:** Display subsets of information for a policy

### HTTP Request 
`***GET*** /policies/id/{id}/subset/{subset}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID to filter by | Yes | integer |
| subset | path | Subset to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /POLICIES/CATEGORY/{CATEGORY}
## ***GET*** 

**Summary:** Finds all policies by category

### HTTP Request 
`***GET*** /policies/category/{category}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| category | path | Category to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /POLICIES/CREATEDBY/{CREATEDBY}
## ***GET*** 

**Summary:** Finds all policies by type

### HTTP Request 
`***GET*** /policies/createdBy/{createdBy}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| createdBy | path | Type to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /PRINTERS
## ***GET*** 

**Summary:** Finds all printers

### HTTP Request 
`***GET*** /printers` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /PRINTERS/ID/{ID}
## ***GET*** 

**Summary:** Finds printers by ID

### HTTP Request 
`***GET*** /printers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing printer by ID

### HTTP Request 
`***PUT*** /printers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new printer by ID

### HTTP Request 
`***POST*** /printers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a printer by ID

### HTTP Request 
`***DELETE*** /printers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /PRINTERS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds printers by name

### HTTP Request 
`***GET*** /printers/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing printer by name

### HTTP Request 
`***PUT*** /printers/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a printer by name

### HTTP Request 
`***DELETE*** /printers/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /REMOVABLEMACADDRESSES
## ***GET*** 

**Summary:** Finds all removable Mac addresses

### HTTP Request 
`***GET*** /removablemacaddresses` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /REMOVABLEMACADDRESSES/ID/{ID}
## ***GET*** 

**Summary:** Finds removable Mac addresses by ID

### HTTP Request 
`***GET*** /removablemacaddresses/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing removable Mac address by ID

### HTTP Request 
`***PUT*** /removablemacaddresses/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new removable Mac address by ID

### HTTP Request 
`***POST*** /removablemacaddresses/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a removable Mac address by ID

### HTTP Request 
`***DELETE*** /removablemacaddresses/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /REMOVABLEMACADDRESSES/NAME/{NAME}
## ***GET*** 

**Summary:** Finds removable Mac addresses by name

### HTTP Request 
`***GET*** /removablemacaddresses/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing removable Mac address by name

### HTTP Request 
`***PUT*** /removablemacaddresses/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a removable Mac address by name

### HTTP Request 
`***DELETE*** /removablemacaddresses/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /RESTRICTEDSOFTWARE
## ***GET*** 

**Summary:** Finds all restricted software

### HTTP Request 
`***GET*** /restrictedsoftware` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /RESTRICTEDSOFTWARE/ID/{ID}
## ***GET*** 

**Summary:** Finds restricted software by ID

### HTTP Request 
`***GET*** /restrictedsoftware/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing restricted software by ID

### HTTP Request 
`***PUT*** /restrictedsoftware/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new restricted software by ID

### HTTP Request 
`***POST*** /restrictedsoftware/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a restricted software by ID

### HTTP Request 
`***DELETE*** /restrictedsoftware/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /RESTRICTEDSOFTWARE/NAME/{NAME}
## ***GET*** 

**Summary:** Finds restricted software by name

### HTTP Request 
`***GET*** /restrictedsoftware/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing restricted software by name

### HTTP Request 
`***PUT*** /restrictedsoftware/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a restricted software by name

### HTTP Request 
`***DELETE*** /restrictedsoftware/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /SCRIPTS
## ***GET*** 

**Summary:** Finds all scripts

### HTTP Request 
`***GET*** /scripts` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /SCRIPTS/ID/{ID}
## ***GET*** 

**Summary:** Finds scripts by ID

### HTTP Request 
`***GET*** /scripts/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing script by ID

### HTTP Request 
`***PUT*** /scripts/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new script by ID

### HTTP Request 
`***POST*** /scripts/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a script by ID

### HTTP Request 
`***DELETE*** /scripts/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /SCRIPTS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds scripts by name

### HTTP Request 
`***GET*** /scripts/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing script by name

### HTTP Request 
`***PUT*** /scripts/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a script by name

### HTTP Request 
`***DELETE*** /scripts/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /SITES
## ***GET*** 

**Summary:** Finds all sites

### HTTP Request 
`***GET*** /sites` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /SITES/ID/{ID}
## ***GET*** 

**Summary:** Finds sites by ID

### HTTP Request 
`***GET*** /sites/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing site by ID

### HTTP Request 
`***PUT*** /sites/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new site by ID

### HTTP Request 
`***POST*** /sites/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a site by ID

### HTTP Request 
`***DELETE*** /sites/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /SITES/NAME/{NAME}
## ***GET*** 

**Summary:** Finds sites by name

### HTTP Request 
`***GET*** /sites/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing site by name

### HTTP Request 
`***PUT*** /sites/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a site by name

### HTTP Request 
`***DELETE*** /sites/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /SMTPSERVER
## ***GET*** 

**Summary:** Finds the JSS SMTP server information

### HTTP Request 
`***GET*** /smtpserver` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates the JSS SMTP server information

### HTTP Request 
`***PUT*** /smtpserver` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

# /SOFTWAREUPDATESERVERS
## ***GET*** 

**Summary:** Finds all software update servers

### HTTP Request 
`***GET*** /softwareupdateservers` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /SOFTWAREUPDATESERVERS/ID/{ID}
## ***GET*** 

**Summary:** Finds software update servers by ID

### HTTP Request 
`***GET*** /softwareupdateservers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing software update server by ID

### HTTP Request 
`***PUT*** /softwareupdateservers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new software update server by ID

### HTTP Request 
`***POST*** /softwareupdateservers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a software update server by ID

### HTTP Request 
`***DELETE*** /softwareupdateservers/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /SOFTWAREUPDATESERVERS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds software update servers by name

### HTTP Request 
`***GET*** /softwareupdateservers/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing software update server by name

### HTTP Request 
`***PUT*** /softwareupdateservers/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a software update server by name

### HTTP Request 
`***DELETE*** /softwareupdateservers/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /USEREXTENSIONATTRIBUTES
## ***GET*** 

**Summary:** Finds all user extension attributes

### HTTP Request 
`***GET*** /userextensionattributes` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /USEREXTENSIONATTRIBUTES/ID/{ID}
## ***GET*** 

**Summary:** Finds user extension attributes by ID

### HTTP Request 
`***GET*** /userextensionattributes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing user extension attribute by ID

### HTTP Request 
`***PUT*** /userextensionattributes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new user extension attribute by ID

### HTTP Request 
`***POST*** /userextensionattributes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a user extension attribute by ID

### HTTP Request 
`***DELETE*** /userextensionattributes/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /USEREXTENSIONATTRIBUTES/NAME/{NAME}
## ***GET*** 

**Summary:** Finds user extension attributes by name

### HTTP Request 
`***GET*** /userextensionattributes/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing user extension attribute by name

### HTTP Request 
`***PUT*** /userextensionattributes/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a user extension attribute by name

### HTTP Request 
`***DELETE*** /userextensionattributes/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /USERGROUPS
## ***GET*** 

**Summary:** Finds all user groups

### HTTP Request 
`***GET*** /usergroups` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /USERGROUPS/ID/{ID}
## ***GET*** 

**Summary:** Finds user groups by ID

### HTTP Request 
`***GET*** /usergroups/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates user groups by ID

### HTTP Request 
`***PUT*** /usergroups/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates user groups by ID

### HTTP Request 
`***POST*** /usergroups/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes user groups by ID

### HTTP Request 
`***DELETE*** /usergroups/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /USERGROUPS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds user groups by name

### HTTP Request 
`***GET*** /usergroups/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates user groups by name

### HTTP Request 
`***PUT*** /usergroups/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes user groups by name

### HTTP Request 
`***DELETE*** /usergroups/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /USERS
## ***GET*** 

**Summary:** Finds all users

### HTTP Request 
`***GET*** /users` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /USERS/ID/{ID}
## ***GET*** 

**Summary:** Finds users by ID

### HTTP Request 
`***GET*** /users/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing user by ID

### HTTP Request 
`***PUT*** /users/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new user by ID

### HTTP Request 
`***POST*** /users/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a user by ID

### HTTP Request 
`***DELETE*** /users/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /USERS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds users by name

### HTTP Request 
`***GET*** /users/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing user by name

### HTTP Request 
`***PUT*** /users/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a user by name

### HTTP Request 
`***DELETE*** /users/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /USERS/EMAIL/{EMAIL}
## ***GET*** 

**Summary:** Finds users by email address

### HTTP Request 
`***GET*** /users/email/{email}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| email | path | Email address to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing user by email address

### HTTP Request 
`***PUT*** /users/email/{email}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| email | path | Email address value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a user by email address

### HTTP Request 
`***DELETE*** /users/email/{email}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| email | path | Email address value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /VPPACCOUNTS
## ***GET*** 

**Summary:** Finds all VPP Accounts

### HTTP Request 
`***GET*** /vppaccounts` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /VPPACCOUNTS/ID/{ID}
## ***GET*** 

**Summary:** Finds VPP Account by ID

### HTTP Request 
`***GET*** /vppaccounts/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates a VPP account by ID

### HTTP Request 
`***PUT*** /vppaccounts/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new VPP account by ID

### HTTP Request 
`***POST*** /vppaccounts/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a VPP account by ID

### HTTP Request 
`***DELETE*** /vppaccounts/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /VPPASSIGNMENTS
## ***GET*** 

**Summary:** Finds all VPP Assignments

### HTTP Request 
`***GET*** /vppassignments` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /VPPASSIGNMENTS/ID/{ID}
## ***GET*** 

**Summary:** Finds VPP Assignment by ID

### HTTP Request 
`***GET*** /vppassignments/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates a VPP assignment by ID

### HTTP Request 
`***PUT*** /vppassignments/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new VPP assignment by ID

### HTTP Request 
`***POST*** /vppassignments/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a VPP assignment by ID

### HTTP Request 
`***DELETE*** /vppassignments/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /VPPINVITATIONS
## ***GET*** 

**Summary:** Finds all VPP Invitations

### HTTP Request 
`***GET*** /vppinvitations` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /VPPINVITATIONS/ID/{ID}
## ***GET*** 

**Summary:** Finds a VPP Invitation by ID

### HTTP Request 
`***GET*** /vppinvitations/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates a VPP invitation by ID

### HTTP Request 
`***PUT*** /vppinvitations/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new VPP invitation by ID

### HTTP Request 
`***POST*** /vppinvitations/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a VPP invitation by ID

### HTTP Request 
`***DELETE*** /vppinvitations/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /VPPINVITATIONS/ID/{ID}/SUBSET/{SUBSET}
## ***GET*** 

**Summary:** Display subsets of information for a VPP invitation

### HTTP Request 
`***GET*** /vppinvitations/id/{id}/subset/{subset}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID to filter by | Yes | integer |
| subset | path | Subset to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /WEBHOOKS
## ***GET*** 

**Summary:** Finds all webhooks

### HTTP Request 
`***GET*** /webhooks` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /WEBHOOKS/ID/{ID}
## ***GET*** 

**Summary:** Finds webhooks by ID

### HTTP Request 
`***GET*** /webhooks/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing webhook by ID

### HTTP Request 
`***PUT*** /webhooks/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***POST*** 

**Summary:** Creates a new webhook by ID

### HTTP Request 
`***POST*** /webhooks/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |
| body | body |  | Yes |  |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a webhook by ID

### HTTP Request 
`***DELETE*** /webhooks/id/{id}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | ID value to filter by | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

# /WEBHOOKS/NAME/{NAME}
## ***GET*** 

**Summary:** Finds webhooks by name

### HTTP Request 
`***GET*** /webhooks/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

## ***PUT*** 

**Summary:** Updates an existing webhook by name

### HTTP Request 
`***PUT*** /webhooks/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 201 | Created |

## ***DELETE*** 

**Summary:** Deletes a webhook by name

### HTTP Request 
`***DELETE*** /webhooks/name/{name}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| name | path | Name value to filter by | Yes | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | OK |

<!-- Converted with the swagger-to-slate https://github.com/lavkumarv/swagger-to-slate -->
