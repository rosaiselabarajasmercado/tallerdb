# 🙋🏻‍♀️Realizado por Rosa Barajas

## Practicando SQL SELECT con Chinook


### 1️⃣. Escriba una consulta para seleccionar los clientes `FirstName`, `LastName` y `Email `de `Country` la tabla `Customer`
**👀Solución:    ⤵️**
```sql
SELECT FirstName, LastName, Email, Country FROM 'Customer'
```

### 2️⃣. Escriba una consulta para seleccionar solo el título del álbum, pero llamado 'Nombre del álbum'
**👀Solución:    ⤵️**
```sql
SELECT Title as "Album Name" FROM Album
```

### 3️⃣. Seleccionar todas las columnas de la tabla Pista
**👀Solución:    ⤵️**
```sql
SELECT * FROM 'Track'
```

### 4️⃣. Seleccione Id y nombre de las listas de reproducción, con un toque diferente
📌Seleccione las columnas `PlaylistId` y `Name` de la `Playlist` tabla, pero cambie el nombre de las columnas a `ID` y `Playlist Name`.
**👀Solución:    ⤵️**
```sql
SELECT PlaylistId as ID, Name as 'Playlist Name' FROM Playlist
```

### 5️⃣. Seleccionar todas las columnas de `Address`
**👀Solución:    ⤵️**
```sql
SELECT * FROM 'Address'
```

### 6️⃣. Seleccione las siguientes columnas de `Product`
📌Seleccione las columnas `ProductNumber`, `Name`, `Color`, `ListPrice`, `DiscontinuedDate`de la `Producttabla`.
**👀Solución:    ⤵️**
```sql
SELECT ProductNumber, Name, Color, ListPrice, DiscontinuedDate FROM 'Product'
```

### 7️⃣. Seleccione las siguientes columnas de `Customer`
📌Seleccione las columnas: `CustomerID`, `Title`, `FirstName`, `LastName` y `EmailAddress` de la `Customer` tabla, pero cámbieles el nombre a `ID`, `Title`(no cambia), `First Name`, `Last Name`, `Email`.
**👀Solución:    ⤵️**
```sql
SELECT CustomerID as ID, Title, FirstName as 'First Name', LastName as 'Last Name', EmailAddress as Email FROM Customer
```
---

## Practica SELECT con la base de datos World


### 1️⃣. Seleccionar todos los registros de la tabla `city`.
**👀Solución:    ⤵️**
```sql
SELECT * FROM city;
```

### 2️⃣. Seleccione sólo las columnas `Name` y de la tabla `CountryCode``city`
**👀Solución:    ⤵️**
```sql

```

### 3️⃣. Seleccionar todos los registros de la tabla `country`.
📌But alias the Name column as Country Name, Continent column as Continent Name and rest of the columns as it is.
**👀Solución:    ⤵️**
```sql

```

### 4️⃣. Seleccione sólo las columnas `Code`, `Name` y `Continent` de la tabla `country`.
📌But alias the Code column as Country Code, Name column as Country Name and Continent column as Continent Name.
**👀Solución:    ⤵️**
```sql

```

### 5️⃣. Seleccionar todos los registros de la tabla `countrylanguage`.
**👀Solución:    ⤵️**
```sql

```

### 6️⃣. Seleccionar todos los registros de la tabla  pero asignarle a la `Language` columna `countrylanguage` el alias `Language Name`.
**👀Solución:    ⤵️**
```sql

```

### 7️⃣. Seleccione sólo las columnas `CountryCode`, `Language` y `Percentage` de la  tabla `countrylanguage`.
📌But alias the CountryCode column as Country Code, Language column as Language Name and Percentage column as Language Percentage.
**👀Solución:    ⤵️**
```sql

```

### 8️⃣. Seleccione sólo las columnas `Name` , `SurfaceArea` y `Population` de la tabla `country`.
📌But alias the CountryCode column as Country Code, Language column as Language Name and Percentage column as Language Percentage.
**👀Solución:    ⤵️**
```sql

```

### 9️⃣. Seleccione sólo las columnas `Code`, `Name`, `HeadOfState` y `Capital` de la tabla country
📌Asignar a la columna `Code` el alias `Country Code`, columna `Name` como `Country Name`, columna `HeadOfState` como `Head Of State` y columna `Capital` como `Capital City`.
**👀Solución:    ⤵️**
```sql

```
