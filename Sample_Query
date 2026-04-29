SELECT c.customer_name,
       r.room_type,
       b.check_in,
       b.check_out

FROM Customers c
JOIN Bookings b
ON c.customer_id = b.customer_id

JOIN Rooms r
ON b.room_id = r.room_id;
