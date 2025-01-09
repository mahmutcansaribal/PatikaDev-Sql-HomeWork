# PatikaDev-Sql-HomeWork
## ODEV 8
### test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```
CREATE TABLE employee(
	id SERIAL PRIMARY KEY,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
)
```
### Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```
insert into employee (name, birthday, email) values ('Oralle', '7/9/2011', 'oemslie0@marketwatch.com');
insert into employee (name, birthday, email) values ('Isadore', '3/15/2021', 'iscriviner1@list-manage.com');
insert into employee (name, birthday, email) values ('Rianon', '6/14/2020', 'rjaspar2@engadget.com');
insert into employee (name, birthday, email) values ('Torrence', '11/4/2003', 'tsearby3@stumbleupon.com');
insert into employee (name, birthday, email) values ('Tara', '12/21/2014', 'tkurtis4@umn.edu');
insert into employee (name, birthday, email) values ('Lauraine', '5/7/2008', 'lsambells5@tumblr.com');
insert into employee (name, birthday, email) values ('Shandy', '3/2/2019', 'srichard6@nyu.edu');
insert into employee (name, birthday, email) values ('Pammi', '7/12/2012', 'psmeal7@craigslist.org');
insert into employee (name, birthday, email) values ('Alexandro', '1/18/2014', 'aandryushin8@apache.org');
insert into employee (name, birthday, email) values ('Merline', '4/12/2014', 'msaltsberg9@cloudflare.com');
insert into employee (name, birthday, email) values ('Jacquie', '7/23/2023', 'jgniewosza@soup.io');
insert into employee (name, birthday, email) values ('Dallas', '7/1/2016', 'dgronauerb@elegantthemes.com');
insert into employee (name, birthday, email) values ('Nissie', '1/12/2022', 'nblandenc@whitehouse.gov');
insert into employee (name, birthday, email) values ('Margot', '1/23/2016', 'mboolsd@uol.com.br');
insert into employee (name, birthday, email) values ('Mahmoud', '5/29/2012', 'mbeldume@netscape.com');
insert into employee (name, birthday, email) values ('Putnam', '8/24/2009', 'pandresenf@ucsd.edu');
insert into employee (name, birthday, email) values ('Shepherd', '7/19/2003', 'sheatlyg@wordpress.org');
insert into employee (name, birthday, email) values ('Kriste', '8/27/2016', 'kfrayh@clickbank.net');
insert into employee (name, birthday, email) values ('Lauraine', '2/16/2022', 'lvickeri@stanford.edu');
insert into employee (name, birthday, email) values ('Ree', '11/24/2015', 'rbuggj@indiegogo.com');
insert into employee (name, birthday, email) values ('Kimmie', '8/7/2003', 'klorencek@posterous.com');
insert into employee (name, birthday, email) values ('Jonah', '1/26/2003', 'jdurbynl@webeden.co.uk');
insert into employee (name, birthday, email) values ('Sayre', '4/30/2008', 'szuannm@wordpress.org');
insert into employee (name, birthday, email) values ('Gardener', '7/24/2005', 'gmcbreartyn@time.com');
insert into employee (name, birthday, email) values ('Garwood', '12/28/2008', 'glansdaleo@rambler.ru');
insert into employee (name, birthday, email) values ('Alfonse', '5/1/2023', 'asauratp@cargocollective.com');
insert into employee (name, birthday, email) values ('Angelo', '11/4/2018', 'apadillaq@wikipedia.org');
insert into employee (name, birthday, email) values ('Sanders', '6/29/2014', 'sjearumr@upenn.edu');
insert into employee (name, birthday, email) values ('Sal', '4/23/2002', 'shasels@dailymail.co.uk');
insert into employee (name, birthday, email) values ('Tonye', '8/5/2000', 'tmaskewt@home.pl');
insert into employee (name, birthday, email) values ('Hector', '3/13/2006', 'hneilsonu@wikia.com');
insert into employee (name, birthday, email) values ('Emilee', '5/2/2001', 'erickeardv@blogs.com');
insert into employee (name, birthday, email) values ('Grayce', '11/21/2013', 'ghaberchamw@instagram.com');
insert into employee (name, birthday, email) values ('Cyril', '1/11/2009', 'chablotx@usnews.com');
insert into employee (name, birthday, email) values ('Georgine', '7/11/2014', 'glafondy@merriam-webster.com');
insert into employee (name, birthday, email) values ('Amie', '6/20/2024', 'asennz@comsenz.com');
insert into employee (name, birthday, email) values ('Davon', '8/19/2003', 'dbrotherwood10@admin.ch');
insert into employee (name, birthday, email) values ('Tiphanie', '4/10/2003', 'twonham11@about.me');
insert into employee (name, birthday, email) values ('Athena', '11/27/2019', 'achateau12@vistaprint.com');
insert into employee (name, birthday, email) values ('Brandais', '1/13/2014', 'belsmor13@eventbrite.com');
insert into employee (name, birthday, email) values ('Vally', '9/11/2000', 'vsnel14@creativecommons.org');
insert into employee (name, birthday, email) values ('Thea', '11/16/2000', 'tkeijser15@newyorker.com');
insert into employee (name, birthday, email) values ('Cacilia', '8/22/2017', 'cfoucher16@economist.com');
insert into employee (name, birthday, email) values ('Ardith', '7/3/2023', 'akingwell17@ox.ac.uk');
insert into employee (name, birthday, email) values ('Jean', '3/29/2022', 'jbreeder18@cnbc.com');
insert into employee (name, birthday, email) values ('Giacobo', '11/5/2004', 'gshulver19@cdbaby.com');
insert into employee (name, birthday, email) values ('Leroi', '3/11/2016', 'lmccrohon1a@list-manage.com');
insert into employee (name, birthday, email) values ('Panchito', '11/12/2000', 'pwillas1b@lycos.com');
insert into employee (name, birthday, email) values ('Dollie', '11/21/2005', 'ddalgety1c@engadget.com');
insert into employee (name, birthday, email) values ('Yovonnda', '9/5/2019', 'ywestmoreland1d@wired.com');
```
### Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```
UPDATE employee
SET name = 'PATIKA DEV'
WHERE id = 19

UPDATE employee
SET name = 'PATIKA DEV VE LC WAIKIKI',
	email = 'xxxxxxx@gmail.com'
WHERE birthday BETWEEN '2020-01-01' AND '2025-01-01'

UPDATE employee
SET email = 'UPDATE@gmail.com'
WHERE id < 10

UPDATE employee
SET name = '2020 SONRASI DOGUMLULAR'
WHERE birthday > '2020-01-01'

UPDATE employee
SET name = '20. YUZYIL INSANLARI',
	email = '20yuzyil@gmail.com'
WHERE birthday <= '1999-12-31'
```
### Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```
DELETE FROM employee
WHERE id = 1

DELETE FROM employee
WHERE name LIKE '%d'

DELETE FROM employee
WHERE email LIKE 'x%'

DELETE FROM employee
WHERE birthday BETWEEN '2020-01-01' AND '2024-01-01'

DELETE FROM employee
WHERE name = 'Dallas'
```

