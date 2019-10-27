# LeetCode_DataBase

[Oracle Database SQL Language Reference][1]

[SQL Tutorial][2]

Wildcard
### Wildcard
Used with the **WHERE LIKE** operator. 

| Symbol | Description | Example |
| ------ | ------ | ------ |
| % | Represents **ZERO or MORE** characters| bl% : black, blue, blob | 
| _ | Represents **ONE** character | h_t : hot, hat, hit |

Example
SELECT * FROM Customers WHERE City LIKE '_ondon';

SELECT * FROM Customers WHERE City LIKE 'ber%';



[1]: https://docs.oracle.com/cd/E11882_01/server.112/e41084/toc.htm
[2]: https://www.techonthenet.com/index.php
