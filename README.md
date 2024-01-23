# Hotel Bookings Cancellation Analysis

This repository contains data and analysis on hotel bookings cancellations. The data includes information about room types, guest types, hotel counts, and cancellation statistics based on various factors.

## Data Overview

### Data Source
The dataset used for this analysis includes information about hotel bookings, including details such as reserved room types, assigned room types, guest demographics, hotel types (City Hotel or Resort Hotel), and cancellation status.

### Data Fields
- `room_status`: Indicates whether the reserved room type matches the assigned room type, categorized as "Desired" or "Un-Desired".
- `guest_type`: Categorizes guests as "Couples," "Single," or "Family" based on the number of adults, children, and babies.
- `is_canceled`: Binary variable indicating whether a booking was canceled (1) or not (0).
- `arrival_date_month`: Month of arrival for bookings.

## Analysis Results

### Guest Type and Cancellation
The analysis includes a breakdown of the total number of guests and canceled bookings based on guest types - Couples, Single, and Family.

| Guest Type | Total Guests | Canceled Bookings |
|------------|--------------|-------------------|
| Couples    | 81,560       | 32,424            |
| Family     | 15,253       | 5,245             |
| Single     | 22,577       | 6,555             |

### Hotel Types and Cancellation
An overview of hotel counts and cancellation statistics for City Hotel and Resort Hotel is provided.

| Hotel Type   | Count of Hotel | Sum of Canceled Bookings |
|--------------|----------------|--------------------------|
| City Hotel   | 79,330         | 33,102                   |
| Resort Hotel | 40,060         | 11,122                   |

### Room Status and Cancellation
The analysis categorizes bookings into "Desired" and "Un-Desired" room statuses and provides cancellation statistics.

| Room Status | Count of Bookings | Canceled Bookings |
|-------------|-------------------|-------------------|
| Desired     | 104,473           | 43,422            |
| Un-Desired  | 14,917            | 802               |

### Monthly Cancellation Trends
Monthly breakdown of cancellations is provided to identify patterns.

| Month      | Count of Bookings | Canceled Bookings |
|------------|-------------------|-------------------|
| January    | 5,929             | 1,807             |
| February   | 8,068             | 2,696             |
| ...        | ...               | ...               |
| December   | 6,780             | 2,371             |

## How to Use This Repository

### Code and Data
- The analysis is performed using Excel formulas. The Excel file is available in the repository: [hotel_booking_cancellation.xlsx](hotel_booking_cancellation.xlsx).
- The dataset used for analysis is included as [hotel_bookings.csv](hotel_bookings.csv).

### Running the Analysis
1. Download the Excel file and the dataset.
2. Open the Excel file to explore the formulas and analysis.
3. Feel free to customize the analysis based on your specific requirements.

## License

This project is licensed under the [MIT License](LICENSE).
