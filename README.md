CREATE TABLE CEO (
    CEO_ID NUMBER PRIMARY KEY,
    CEO_Name VARCHAR2(100),
    Company_Name VARCHAR2(100),
    Experience_Years NUMBER,
    Net_Worth NUMBER(15,2)
);

INSERT INTO CEO (CEO_ID, CEO_Name, Company_Name, Experience_Years, Net_Worth) VALUES 
 (1, 'Elon Musk', 'Tesla', 25, 230000000000.00),
(2, 'Tim Cook', 'Apple', 20, 1900000000.00),
 (3, 'Sundar Pichai', 'Google', 18, 1310000000.00),


 (4, 'Satya Nadella', 'Microsoft', 22, 970000000.00);
