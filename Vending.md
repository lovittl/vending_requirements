# Vending machine
## Security
- Ensures money is real
- Secures internal inventory
- Validates credit/debit cards

## Maintenance
- VMA1.  The system shall provide a refrigerant system that maintains a consistant temperature sufficient 
         to keep drinks in inventory (Ref. TODO) at a desireable temperature for consumption.


- VMA2.  The system shall detect conditions that prevent the vending system from dispensing drinks as requested 
         by the customer from the interface (Ref TODO).

-  VMA3.  The system shall provide secure access (Ref. TODO) to inventory shelving (Ref. TODO) for the purposes of 
           replenishing the drink inventory (Ref. TODO)

## Money
- Return change

- Senses if the money compartment is full

- Senses if the change drawer is empty

## Interface (GREG) testing...
- Receives money

- Displays products & prices

- Provides product selector

- Scans credit/debit cards

- Notify when a product is not available

- Notify when insufficient currency has been provided
   

## Vending
### Maintains an inventory
- [ ] VI1 - The system shall provide shelving appropriate for canned beverages.
- [ ] VI2 - The system shall provide space for up to 12 categories of beverage.
- [ ] VI3 - The system shall uniquely identify drink categories.
- [ ] VI4 - The system shall maintain a count of beverages in each drink category.

### Vend products selected
- [ ] VV1 - Upon receiving a drink selection (ref. TODO), when the specified quantity of currency for the selected category has been inserted (ref. TODO), and while drinks are in inventory to vend (ref. VI4) the system shall dispense at most one of the selected category of drink.

- [ ] VV2 - Upon vending a drink (ref. VV1), the system shall reduce the inventory count (ref. VI4) for the drink category by one prior to accepting further user input.

