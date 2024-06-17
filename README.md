# Marketing Analysis Project
![image](https://github.com/siddharthprakash1/automated-ai-marketing-analysis-instagram/assets/92435819/176ed356-3b59-43e6-a4cf-991195f7f4db)

This project utilizes the CrewAI framework, Groq Cloud, Serper, and the Llama3 language model to conduct marketing analysis and generate creative content for Instagram campaigns.

## Overview

The project consists of several agents and tasks designed to perform various marketing-related activities, such as product and competitor analysis, campaign strategy development, ad copy creation, and image generation.

## Agents

The following agents are defined in the `agents.py` file:

1. **Product Competitor Agent**: Analyzes the given product website and identifies unique features, benefits, and the overall narrative.
2. **Strategy Planner Agent**: Synthesizes insights from product analysis to formulate marketing strategies.
3. **Creative Content Creator Agent**: Develops compelling and innovative content for social media campaigns, with a focus on creating high-impact Instagram ad copies.
4. **Senior Photographer Agent**: Generates descriptions for amazing photographs to be used in Instagram ads, capturing emotions and conveying a compelling message.
5. **Chief Creative Director Agent**: Reviews the work done by the team, ensures alignment with the product's goals, and delegates follow-up work if necessary.

## Tasks

The `tasks.py` file defines the following tasks:

1. **Product Analysis**: Analyzes the given product website and identifies key selling points, market appeal, and suggestions for enhancement or positioning.
2. **Competitor Analysis**: Explores competitors of the given product website, analyzes their strategies, market positioning, and customer perception.
3. **Campaign Development**: Creates a targeted marketing campaign strategy and creative content ideas based on the product details.
4. **Instagram Ad Copy**: Crafts engaging Instagram post copies that resonate with the target audience and highlight the product's unique selling points.
5. **Take Photograph Task**: Generates descriptions for amazing photographs to be used in Instagram ads, capturing emotions and conveying a compelling message.
6. **Review Photo**: Reviews the generated photograph descriptions, ensures alignment with the product's goals, and delegates follow-up work if necessary.

## Tools

The `tools.py` file contains the `SearchTools` class, which provides two tools for searching the internet and Instagram using the Serper API.

## Usage

The `main.py` file orchestrates the agents and tasks to generate an Instagram ad copy and a description for a compelling photograph. The results are printed at the end of the execution.

## Generated Content1
![image](https://github.com/siddharthprakash1/automated-ai-marketing-analysis-instagram/assets/92435819/cc2c26b7-06aa-4b39-9c10-bbaf5c115d7c)
Your midjourney description:
 A surreal shot of a car emerging from a misty dawn, with the sun rising in the background, capturing the thrill of the drive. The car is in the center of the frame, with the surroundings blurred, drawing attention to the vehicle.

## Generated Content2
![image](https://github.com/siddharthprakash1/automated-ai-marketing-analysis-instagram/assets/92435819/81fe07e5-c947-40cb-9200-513207214ca1)

Your midjourney description:
A high-angle shot of a car navigating through a dense cityscape, with towering skyscrapers and neon lights reflecting off its shiny surface. The car is the focal point, with the cityscape blurred in the background, capturing the sense of freedom and adventure.
ng darkness emphasizes its sleek design. The image captures the thrill of the ride and the sense of freedom that comes with it.
