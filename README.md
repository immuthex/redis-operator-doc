# Redis Operator

A clean and beautiful Redis GUI client.

- Support stand-alone, sentinel and cluster mode
- STRING, LIST, SET, ZSET, HASH and STREAM types
- SSH and SSL
- View value as JSON, XML and HTML, support value codec: BASE64, GZIP, Msgpack, Snappy, BZip2, LZ4, ZSTD, CBOR, LZMA and XZ
- Open key in a new tab
- Auto refresh value
- Manage shown databases
- Edit database alias
- App-level settings, connection-level settings and db-level settings
- Export LIST, SET, ZSET and HASH values to Excel(xlsx) or CSV

## Getting Started

### Add Connection Settings

![](img/add-connection-settings1.png)
![](img/add-connection-settings2.png)
![](img/add-connection-settings3.png)

### Add Keys

![](img/add-key.png)

### Open a Key

Double-click the key to open it in the **Default** tab, or you can right-click the key and choose to open it in a new tab.

![](img/open-key.png)

### Edit Value

After opening a key, you can edit the value of the key.

Value support **JSON**, **XML** and **HTML** view; **BASE64**, **GZIP**, **Msgpack**, **Snappy**, **BZip2**, **LZ4**, **ZSTD**, **CBOR**, **LZMA** and **XZ** codec.

![](img/edit-key.png)

### APP Settings

![](img/go-to-app-settings.png)
![](img/app-settings.png)

### DB Settings

![](img/go-to-db-settings.png)
![](img/db-settings.png)

### Auto Refresh Value

![](img/auto-refresh-value.png)

### Manage Shown Databases

![](img/manage-shown-databases.png)

### Export Collection Values

Support export **collection(LIST, SET, ZSET and HASH)** values as **Excel(xlsx)** and **CSV**.

![](img/export-collection.png)

After clicking **OK** button it will export in the background.

![](img/chose-export-path.png)

There will be a notification after the export is complete, you can click the link in the notification to open the exported file directory.

![](img/export-collection-complete.png)