INSERT INTO CUSTOMER TABLE

INSERT INTO CUSTOMER VALUES (102, 'Sara Arjun', '4323456789', 'sara.m@email.com', 'Michigan');

INSERT INTO CUSTOMER VALUES (104, 'Fathima Ameen', '7456789012', 'fathima.a@email.com', 'Chennai');

INSERT INTO CUSTOMER VALUES (105, 'John Smith', '7700123456', 'john.smith@email.com', 'London');

INSERT INTO CUSTOMER VALUES (106, 'Emily Johnson', '6135551234', 'emily.j@email.com', 'Toronto');

INSERT INTO CUSTOMER VALUES (107, 'Mohammed Rizwan', '5012345678', 'rizwan@email.com', 'Dubai');

INSERT INTO CUSTOMER VALUES (108, 'Sophia Williams', '4123456789', 'sophia@email.com', 'Sydney');

INSERT INTO CUSTOMER VALUES (109, 'Haruto Tanaka', '9012345678', 'haruto@email.com', 'Tokyo');

INSERT INTO CUSTOMER VALUES (110, 'Lucas Muller', '5123456789', 'lucas@email.com', 'Berlin');


INSERT INTO DRIVER TABLE

INSERT INTO DRIVER VALUES (201, 'David Brown', '0712345678', 'DL1001', 85000);

INSERT INTO DRIVER VALUES (202, 'Mohammed Ibrahim', '0723456789', 'DL1002', 90000);

INSERT INTO DRIVER VALUES (203, 'Arjun Kumar', '0734567890', 'DL1003', 78000);

INSERT INTO DRIVER VALUES (204, 'John Wilson', '0745678901', 'DL1004', 82000);

INSERT INTO DRIVER VALUES (205, 'Ramesh Perera', '0756789012', 'DL1005', 88000);


INSERT INTO VEICHLE TABLE

INSERT INTO VEHICLE VALUES (301, 'CAB1001', 'Toyota', 'Prius', 2022, 'White');

INSERT INTO VEHICLE VALUES (302, 'CAB1002', 'Honda', 'Civic', 2021, 'Black');

INSERT INTO VEHICLE VALUES (303, 'CAB1003', 'Hyundai', 'Elantra', 2023, 'Silver');

INSERT INTO VEHICLE VALUES (304, 'CAB1004', 'Nissan', 'Sunny', 2020, 'Blue');

INSERT INTO VEHICLE VALUES (305, 'CAB1005', 'Suzuki', 'Ciaz', 2022, 'Red');


INSERT INTO RIDE RECORDS

INSERT INTO RIDE VALUES (401, DATE '2026-07-01', 'Colombo', 'Negombo', 35.5, 3500, 'Completed', 101, 201, 301);

INSERT INTO RIDE VALUES (402, DATE '2026-07-01', 'Kandy', 'Peradeniya', 12.8, 1200, 'Completed', 102, 202, 302);

INSERT INTO RIDE VALUES (403, DATE '2026-07-02', 'Galle', 'Matara', 45.0, 4200, 'Completed', 103, 203, 303);

INSERT INTO RIDE VALUES (404, DATE '2026-07-02', 'Chennai', 'Airport', 18.5, 1800, 'Ongoing', 104, 204, 304);

INSERT INTO RIDE VALUES (405, DATE '2026-07-03', 'London', 'Heathrow', 28.0, 3000, 'Completed', 105, 205, 305);

INSERT INTO RIDE VALUES (406, DATE '2026-07-03', 'Toronto', 'Downtown', 15.5, 1600, 'Completed', 106, 201, 301);

INSERT INTO RIDE VALUES (407, DATE '2026-07-04', 'Dubai', 'Marina', 20.0, 2100, 'Cancelled', 107, 202, 302);

INSERT INTO RIDE VALUES (408, DATE '2026-07-04', 'Sydney', 'Opera House', 10.5, 1100, 'Completed', 108, 203, 303);

INSERT INTO RIDE VALUES (409, DATE '2026-07-05', 'Tokyo', 'Shibuya', 9.0, 950, 'Completed', 109, 204, 304);

INSERT INTO RIDE VALUES (410, DATE '2026-07-05', 'Berlin', 'Central Station', 16.0, 1700, 'Ongoing', 110, 205, 305);


INSERT INTO PAYMENT TABLE

INSERT INTO PAYMENT VALUES (501, DATE '2026-07-01', 'Card', 3500, 'Paid', 401);

INSERT INTO PAYMENT VALUES (502, DATE '2026-07-01', 'Cash', 1200, 'Paid', 402);

INSERT INTO PAYMENT VALUES (503, DATE '2026-07-02', 'Online', 4200, 'Paid', 403);

INSERT INTO PAYMENT VALUES (504, DATE '2026-07-02', 'Card', 1800, 'Pending', 404);

INSERT INTO PAYMENT VALUES (505, DATE '2026-07-03', 'Cash', 3000, 'Paid', 405);

INSERT INTO PAYMENT VALUES (506, DATE '2026-07-03', 'Online', 1600, 'Paid', 406);

INSERT INTO PAYMENT VALUES (507, DATE '2026-07-04', 'Card', 2100, 'Pending', 407);

INSERT INTO PAYMENT VALUES (508, DATE '2026-07-04', 'Cash', 1100, 'Paid', 408);

INSERT INTO PAYMENT VALUES (509, DATE '2026-07-05', 'Online', 950, 'Paid', 409);

INSERT INTO PAYMENT VALUES (510, DATE '2026-07-05', 'Card', 1700, 'Pending', 410);

