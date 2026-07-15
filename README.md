# train-ticket-by-OOP
# Train Ticket Booking (OOP Practice)

## Class: `Train`

**Attributes** (set in `__init__`):
- `name` — passenger's name
- `passenger_age` — passenger's age
- `travel_class` — travel class (`"G"`, `"S"`, or `"AC"`)
- `distance_km` — distance to travel, in km

**Methods:**
| Method | Purpose |
|---|---|
| `booktic(train_no)` | Books the ticket, prints a confirmation message, and returns a dictionary with booking details |
| `calculate_fare()` | Calculates ticket price based on travel class rate (`G`=0.35, `S`=0.5, `AC`=1.2 per km), applying a 25% discount for passengers under 18 or 60+ |
| `train_status(booked_onDate)` | Prints a simple status message with the booking date |

## Example Usage
```python
t1 = Train("dale", 20, "AC", 500)
t1.booktic("99999")
t1.calculate_fare()
t1.train_status("12-02-2026")
```

