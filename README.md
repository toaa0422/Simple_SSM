# Simple_SSM
搭建好的简单的SSM框架模板（Simple SSM framework which have been built）
编译器 IntelliJ IDEA 2018.3.4 x64
Tomcat:9.0.221
Mysql：8.0.16


SQL语句：


/*
SQLyog Ultimate v10.00 Beta1
MySQL - 8.0.16 
*********************************************************************
*/
/*!40101 SET NAMES utf8 */;

create table `student` (
	`studentId` int ,
	`studentName` varchar ,
	`studentMajor` varchar ,
	`studentDept` varchar ,
	`studentSex` int 
); 
insert into `student` (`studentId`, `studentName`, `studentMajor`, `studentDept`, `studentSex`) values('1','浩','软件工程','计算机科学学院','1');
insert into `student` (`studentId`, `studentName`, `studentMajor`, `studentDept`, `studentSex`) values('2','天','软件工程','计算机科学学院','1');
insert into `student` (`studentId`, `studentName`, `studentMajor`, `studentDept`, `studentSex`) values('3','Bryce','网络工程','计算机科学学院','1');
insert into `student` (`studentId`, `studentName`, `studentMajor`, `studentDept`, `studentSex`) values('5','Tim','软件工程','计算机科学学院','1');
insert into `student` (`studentId`, `studentName`, `studentMajor`, `studentDept`, `studentSex`) values('6','Tom','软件工程','计算机科学学院','1');
insert into `student` (`studentId`, `studentName`, `studentMajor`, `studentDept`, `studentSex`) values('7','Bob','软件工程','计算机科学学院','1');
insert into `student` (`studentId`, `studentName`, `studentMajor`, `studentDept`, `studentSex`) values('8','Steven','软件工程','计算机科学学院','1');
insert into `student` (`studentId`, `studentName`, `studentMajor`, `studentDept`, `studentSex`) values('9','Howard','软件工程','计算机科学学院','0');
insert into `student` (`studentId`, `studentName`, `studentMajor`, `studentDept`, `studentSex`) values('10','Jason','软件工程','计算机科学学院','1');
insert into `student` (`studentId`, `studentName`, `studentMajor`, `studentDept`, `studentSex`) values('11','Jack','软件工程','计算机科学学院','0');
insert into `student` (`studentId`, `studentName`, `studentMajor`, `studentDept`, `studentSex`) values('12','Jake','软件工程','计算机科学学院','1');
insert into `student` (`studentId`, `studentName`, `studentMajor`, `studentDept`, `studentSex`) values('13','Joe','软件工程','计算机科学学院','0');
insert into `student` (`studentId`, `studentName`, `studentMajor`, `studentDept`, `studentSex`) values('14','Jodi','软件工程','计算机科学学院','1');
insert into `student` (`studentId`, `studentName`, `studentMajor`, `studentDept`, `studentSex`) values('15','Kiki','软件工程','计算机科学学院','0');
