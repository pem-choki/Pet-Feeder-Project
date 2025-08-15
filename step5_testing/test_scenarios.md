# Test Results

| Scenario            | Input Conditions                                 | Expected Output             |
|---------------------|--------------------------------------------------|-----------------------------|
| Pet eats as expected| Time = 08:00, Food level = Full, Bowl weight decreases | Log: feeding event success |
| Pet does not eat    | Time = 08:00, Food level = Full, Bowl weight unchanged | Alert: food not eaten      |
| Food bin is empty   | Time = 08:00, Food level = Empty                 | Alert: food not available   |

