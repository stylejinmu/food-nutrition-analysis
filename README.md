# Food Nutrition Analysis Skill

[简体中文](README_CN.md) | English

A Skill for qualitative nutrition analysis of foods and dishes from a food name, dish name, or food image.

## Features

- Identifies visible foods, main ingredients, cooking methods, and possible oil, sugar, salt, or sauces from images.
- Analyzes seven nutrition categories using qualitative levels: protein, fat, carbohydrates, dietary fiber, vitamins, minerals, and water.
- Explains possible nutritional value and general health relevance without making medical treatment claims.
- Asks for the user's dietary goal before recommending up to three recipes.
- Provides practical guidance on intake, allergens, special populations, sugar/salt/oil, and food safety.
- Does not estimate portion size from images or fabricate precise nutrition numbers.

## Input

The Skill accepts either:

1. A food or dish name.
2. An image of a food or dish.

For images, the analysis includes an identification confidence level and clearly marks uncertain inferences. If the image cannot be reliably identified, the user is asked for a clearer image or additional details.

## Output

The default output contains:

1. Identification results when the input is an image.
2. A qualitative seven-nutrient overview using high, medium, low, or insufficient information.
3. Possible nutritional value and general health relevance.
4. A dietary-goal question before recipe recommendations.
5. Up to three goal-matched recipes after the user provides a goal.
6. Daily intake, allergy, special-population, and food-safety considerations.

## Safety and scope

This Skill provides general nutrition information, not medical diagnosis, treatment, or an individualized dietary prescription. It avoids claims that a food can cure, prevent, or guarantee outcomes for a disease. Users with a disease, severe allergy, pregnancy-related concern, or other special condition should consult a qualified clinician or registered dietitian.
