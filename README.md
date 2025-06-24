# Swag Labs Selenium Automation

## Setup

1. Install Python 3.x
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Download [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/) and add to PATH.

## Run Tests

```
pytest tests/
```

## Test Cases
- Login
- Add product to cart
- Complete checkout process

## Deliverables
- Test scripts
- Short video of test execution
- Write-up on challenges and improvements

# Challenges & Improvements

## Challenges
- Locating dynamic elements required careful use of selectors.
- Synchronization issues (waits) can cause flaky tests if not handled.

## Improvements
- Use Page Object Model for maintainability.
- Add explicit waits for better reliability.
- Integrate with CI/CD for automated runs.
