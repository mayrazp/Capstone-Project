# Capstone-Project

# I. Defintion:

1. Problem Overvew: Within the company, there is a team that is responsible for defining product characteristics that will be built. For a blender category, for example, this team is responsible for setting the color, cup volume, cup material or even if you will have a filter to fruit juice. To define the characteristics of the different product categories, the team seeks to understand when the customer is interested in a product. This is where the Data Science team is called. Your main objective is to develop a model that can classify the product between "interesting" and "not interesting" given the attributes of it. In addition, it is desirable that you can also indicate which attributes and their values drive the customer's interest the most.

  - Understanding the business: Understanding customer requirements is an important task as it will enable the product design team to create products that are useful to customers.
    - Goals
      -Understand which variables or attributes influence a product's decision to be categorized as interesting and not interesting to the customer.
    - Expected benefits
      -If we create products that meet customer requirements, product sales will be greater than creating products without considering people's interests.
      -Create useful products.

2. Problem Statement

Develop a model that can classify the product between "interesting" and "not interesting" given the attributes of it. In addition, it is desirable to indicate which attributes and their values most drive customer interest.

# II Analysis
1. Data Exploration: Explore the database for insights that can guide you through the learning model creation phase.
  - 1.2 Dataset Description:The dataset was written entirely in Portuguese. For a better understanding of the dataset, I will explain what each attribute means.
  - 1.3 Dataset Attributes:
  
| Attribute name | Description |
|----------------|-------------|
|ITEM_ID | Item Identifier|
|ALTURA | Height of product |
|CAPACIDADE| Capacity of product|
|COMPOSICAO| Type of product material. Values: aluminum, stainless steel, ceramic, enameled steel, porcelain.|
|COR| color|
|FORMATO| Format type. Values: frying pan, oval, square, round and rectangular|
|LARGURA| Width|
|MARCA| Brand |
|PARA_LAVA_LOUCAS| If the product can be washed in the dishwasher. Values: Yes, No|
|PARA_MICROONDAS| If the product can be used in the microwave. Values Yes, No|
|PESO| Weight |
|PROFUNDIDADE| Depth |
|TEMPO_GARANTIA| Warranty Time|
|TEM_FERRO_FUNDIDO| It has cast iron. Values: Yes, No|
|TEM_GRELHA| Has grid. Values: Yes, No|
|TEM_TAMPA| Has lid. Values: 10, 0|
|TIPO_PRODUTO| Product type. Values: Baking pan, popcorn maker, spaghetti pan, pan, custard, wok, saucepan, plate, kettle, frying pan, mug|
|TIPO_WOK| Is wok. Values: Yes, No|
|SESSION_ID|Session identifier|
|ITEM_PRICE| price of the product|
|INTERESTED| Is interested. Values: 0, 10 |

# III. Methodology
1. Data Preprocessing
  - 1.1 Handling null values
  - 1.2 Create a machine learning model can classify the product between "interesting" and "not interesting" given the attributes of the product.
  - 1.3 Use metrics to analyze modeling results
  - 1.4 Conclutions

# IV. Required libraries
* pandas
* numpy
* scikit-learn

# V Acknowledgements
Thanks to Udacity for providing a challenging project to work on.

