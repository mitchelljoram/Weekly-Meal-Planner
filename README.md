# Weekly Meal Planner
Mitchelll Joram

---

## Table of Contents

- [Weekly Meal Planner](#weekly-meal-planner)
  - [Week Meal Planner](#week-meal-planner)
    - [BMR/Macro Calculator](#bmr/macro-calculator)
    - [Meal Planner](#meal-planner) 
  - [Menu](#menu)

---

**DISCLAIMER**: All content presented is for informational and personal purposes only, and is not intened to approximate or replace professional medical advice, diagnosis, or treatment. This is a tool to help track calories and macros and is not to be taken literally as wanted effects are not guaranteed. Calulations are based on limited research. Always seek the advice of your personal physician or other qualified professionals regarding questions regarding your physical health and medical conditions.

--- 

## Week Meal Planner

### BMR/Macro Calculator

1. Enter your **body weight** in the first orange cell in pounds (lbs). If you do not know your weight in lbs, you may enter your weight in kilograms (kg) in the next cell below. The final calculation uses kg.
2. Enter your **height** in the second orange cell in inches. If you do not know your height in inches, you may enter your height in centimeters (cm) in the next cell below. The final calculation uses cm.
3. Enter your **age** in years in the third orange cell.
4. Enter your **gender (M/F)** in the fourth orange cell. Male and female BMR calulations are different.
5. Enter your average **number of workouts** per week.
6. Enter your **goal**. Your options include:
  - **Maintain Current Weight**
  - **Gain Weight**
  - **Lose Weight**
  
**BMR Calculation**
BMR is calculated using the following equations:
**M**: 88 + (**body weight (kg)** x 13) + (**height (cm)** x 5) - (**age** x 5.5)
**F**: 450 + (**body weight (kg)** x 9) + (**height (cm)** x 3) - (**age** x 4)

**Macro Calculation**
Macros per day are calculated using the following equations (with rounding to nearest 10): 
**Calories**: **BMR** + (1.2 + (0.1 * **number of workouts**)) + **goal**
  - **Maintain Current Weight**: 0
  - **Gain Weight**: 500
  - **Lose Weight**: - 10% calculated calories
**Protein**: 
  - **Maintain Current Weight** and **Gain Weight**: (**Calories** x 0.3) / 4
  - **Lose Weight**: (**Calories** x 0.35) / 4
**Carbohydrates (Carbs)**: (**Calories** x 0.5) / 4
**Fats**: 
  - **Maintain Current Weight** and **Gain Weight**: (**Calories** x 0.2) / 9
  - **Lose Weight**: (**Calories** x 0.15) / 9
  
Macros per week are calculated with the above results x 7.

### Meal Planner

Each day in the meal planner contains 6 "meals" for a 3-4 meals per day plan with 2-3 optional snack portions.

Each meal contains 5 menu items. See [Menu](#menu) to see how to add menu items.
1. Enter each menu item.
2. Enter number of servings for each menu item.
Calories, protein, carbs, and fats are calculated based on the menu item and servings entered.

Day Stats are calulated based on entered menu items and servings enter accross all 6 meals.
Week Stats are calculated based on all day stats.
Legend for Day/Week Stats:
  - **Green**: Good with > 80% calculated macro
  - **Yellow**: Neutral with > 50% calculated macro
  - **Red**: Bad with < 50% calculated macro

---

## Menu

Menu items are entered by the user. Menu items are searched through by the [Meal Planner](#meal-planner) to calculate macros. Enter menu items in the table in the following format:
  - **Menu Item**: Menu item name.
  - **Serving Size**: This is a subjective amount to help the user determine number of servings in the Meal Planner for number of servings. Enter in grams (g) or any appropriate unit.
  - **Calories**: Number of calories in each serving size.
  - **Protein**: Number of grams of protein in each serving size.
  - **Carbs**: Number of grams of carbohydrates in each serving size.
  - **Fat**: Number of grams of fat in each serving size.
  
Menu table allows 50 menu items. This can be expanded if the appropriate functions in the Meal Planner are updated to search the expanded table.
i.e. for 100 menu items: Menu!$B$7:$I$56 --> Menu!$B$7:$I$106
