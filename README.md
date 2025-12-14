# Excel-Order-Processing-Capstone-_2

# Task – Order Processing Logic

## Task Overview

This task focuses on using text functions and logical conditions in Excel to prepare a clean, decision-ready report for warehouse operations.

## Steps Performed

* Created a State column by extracting the first two letters from the RegionCode using the LEFT function
* Created an URGENT SHIP column using logical conditions
  * Orders are marked SHIP NOW if Status is PENDING and ItemCount is less than 5
  * All other orders are marked HOLD
* Created a Warehouse Note column by combining text and logic

  * Displays [State] – RUSH ORDER for urgent shipments
  * Displays [State] – WAIT for non-urgent orders
* Applied basic formatting such as bold headers and borders to make the report presentable

## Excel Skills Used

* Text functions (`LEFT`)
* Logical functions (`AND`, `IF`)
* Text joining (`CONCATENATE` / `&`)
* Conditional logic
* Data formatting

## Notes

This task simulates real-world order handling rules and demonstrates how Excel can be used to automate shipping decisions.

