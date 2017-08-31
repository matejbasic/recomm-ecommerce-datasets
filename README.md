# Setovi podataka
Različiti setovi podataka korišteni za potrebe diplomskog rada (Sustavi preporuke temeljeni na analizi potrošačke košarice, mentor: prof.dr.sc. Božidar Kliček)

## Struktura:
### product.csv
product_id(int),parent_product_id(int, 0=none),date_created(timestamp, YYYY-MM-DD HH:MM:SS),price(int|float),
### order-product.csv
order_id(int),product_id(int),quantity(int),total_price(int|float)
### product-cat.csv
product_id(int),cat_id(int),parent_cat_id(int, 0=none)
### product-tag.csv
product_id(int),tag_id(int)
### user.csv
user_id(int),registered(timestamp, YYYY-MM-DD HH:MM:SS)
### user-order.csv
user_id(int),order_id(int),date(timestamp, YYYY-MM-DD HH:MM:SS)

Izvor: Neuralab(c)
