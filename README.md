Debugging Report
Application Setup

A React application was created using create-react-app with multiple components including Counter and User.

Tools Used
React Developer Tools
Browser DevTools console
Issues Identified

1. Counter State Not Updating
Observation: Clicking button did not increment count
Cause: Direct mutation of state
# Fix: Replaced with setCount(count + 1)

2. Incorrect Prop Usage in User Component
Observation: Username not displayed
Cause: Used props.username instead of props.name
# Fix: Updated to correct prop reference

# Steps Taken
Inspected component tree using React DevTools
Checked props and state values
Identified mismatch and incorrect state handling
Applied fixes and re-tested
Final Verification
Counter increments correctly ✅
User name displays correctly ✅
No console errors ✅


✅ 3. Final Result

After fixes:

App behaves as expected
State updates properly
Props are correctly passed
