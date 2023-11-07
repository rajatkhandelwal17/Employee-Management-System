CREATE SCHEMA `employee_db` ;

CREATE TABLE `employee_db`.`tbl_employee` (
  `id` INT NOT NULL,
  `name` VARCHAR(45) NOT NULL,
  `salary` DOUBLE NOT NULL,
  PRIMARY KEY (`id`));