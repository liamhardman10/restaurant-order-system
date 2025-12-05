# Restaurant Ordering System

## Project Overview
A Windows desktop application for managing restaurant orders with pricing, discounting, and receipt generation capabilities.

## Features
- Create and manage restaurant orders
- Apply various discounts
- Generate detailed receipts
- Real-time pricing calculations
- Unit tested core functionality

## File Structure
- `src/RestaurantOrderSystem/` - Main application
  - `Models/` - Domain models
  - `Services/` - Business logic
  - `Factories/` - Creational patterns
  - `View/` - GUI components
- `tests/` - Unit tests

## Installation Instructions
1. Clone repository: `git clone <repo-url>`
2. Open `RestaurantOrderSystem.sln` in Visual Studio
3. Restore NuGet packages
4. Build solution (Ctrl+Shift+B)
5. Run application (F5)

## API Usage Details
- `IOrderService`: Manage orders
- `IPricingService`: Calculate prices
- `IDiscountService`: Apply discounts
- `ReceiptFactory`: Create receipts

## How Data is Stored
- In-memory storage during runtime
- JSON serialization for receipt export
- No persistent database (for simplicity)

## Known Issues/Limitations
- No database persistence
- Limited to 10 menu items (demo)
- Discounts cannot be combined

## Debugging Summary
- Use unit tests for core logic
- Check discount application order
- Validate input ranges

## Credits and Acknowledgements
- SOLID principles implementation
- Factory design pattern
- MVVM-like architecture

## Experimental Branch
- Feature: `experimental/dynamic-pricing`
- Implements time-based pricing
- Adds surge pricing logic
