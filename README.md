# Employees. DAO.

## Description 
Implement [`com.epam.rd.autocode.dao.DaoFactory`](src/main/java/com/epam/rd/autocode/dao/DaoFactory.java) methods.

It should return Employee and Department DAO instances.

DAO stands for Data Access Object and performs as first line layer between database and web application.

You should implement DAO for Employee and Department classes.

You may refer to DDL in [`init-ddl.sql`](src/test/resources/init-ddl.sql).

You may not change classes in `com.epam.rd.autocode.domain` package.

# Employees. Row Mapper.

## Description 
Implement [`com.epam.rd.autocode.RowMapperFactory.employeeRowMapper`](src/main/java/com/epam/rd/autocode/RowMapperFactory.java) method.

It should return a RowMapper instance that maps current row of result set to an `Employee` instance.

It should not perform any cursor moving.

You may refer to DDL in [`init-ddl.sql`](src/test/resources/init-ddl.sql).

You may not change classes in `com.epam.rd.autocode.domain` package.

# Employees. Row Mapper.

## Description 
Implement [`com.epam.rd.autocode.SetMapperFactory.employeesSetMapper`](src/main/java/com/epam/rd/autocode/SetMapperFactory.java) method.

It should return a SetMapper instance that maps whole result set to a set of `Employee` instances.

It should perform cursor moving in order to get all Employee instances.
Consider result set to be fully scrollable (back and forward, begin, end, etc.).
If an Employee has a Manager it should contain it as Employee instance as well.

You may refer to DDL in [`init-ddl.sql`](src/test/resources/init-ddl.sql).

You may not change classes in `com.epam.rd.autocode.domain` package.

 
 