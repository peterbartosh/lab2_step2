# lab2_step2
Second step of lab2. Representation of DB structure.

# 1) Language: 
SQLite

# 2) Schema([schema_link](https://github.com/peterbartosh/Lab2_step1/blob/main/README.md)):
Orders table:

![image](https://github.com/peterbartosh/lab2_step2/assets/99812822/2e4320ae-14e1-4d61-abe2-14090cf93fa4)

Orders-Products table:

![image](https://github.com/peterbartosh/lab2_step2/assets/99812822/95c54a21-7a85-43b7-9847-4a875948fbf2)

# 3) Inserting data:
```sql
  Insert Into orders Values(status, date, longtitude, lattitude, preferencesComment)
  Values (1, to_date('dd.MM.yyyy', '10.11.2022), '45.4392352', '37.3455321', 'Some optional comment 1');
  Insert Into orders Values(status, date, longtitude, lattitude, preferencesComment)
  Values (3, to_date('dd.MM.yyyy', '24.03.2022), '41.4436532', '37.3959321', 'Some optional comment 2');
  Insert Into orders Values(status, date, longtitude, lattitude, preferencesComment)
  Values (4, to_date('dd.MM.yyyy', '12.06.2022), '13.3592452', '37.3482945', 'Some optional comment 3');
```

```sql
  Insert Into OrderProducts Values(orderId, amount, productName)
  Values (1, 54, 'Cola');
  Insert Into OrderProducts Values(orderId, amount, productName)
  Values (1, 17, 'Fanta');
  Insert Into OrderProducts Values(orderId, amount, productName)
  Values (3, 96, 'Sprite');
```

