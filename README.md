<p align="center">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQRyXkG7P3OMrWsLMmIwEmgu_T5c3xhdju2Vw&s" alt="MasterHead"/>
</p>

# Association Rule Based Recommender System

## 1. Business Problem

**Armut**, Turkey's leading online service platform, connects service providers with customers, offering various services such as cleaning, renovation, and moving. The objective is to use **Association Rule Learning** to create a product recommendation system using a dataset that contains users who have received services and the categories of those services. This system will help improve user experience by suggesting relevant services based on prior selections.

### Task:
Develop an Association Rule Learning-based product recommendation system using the service and category data to recommend suitable services to users.

## 2. Dataset Story

The dataset provides information about the services obtained by users, the categories of these services, and the date and time each service was performed. The dataset includes anonymized **UserId**, **ServiceId**, and **CategoryId** fields to ensure privacy. Services might be repeated across different categories, meaning the same ServiceId can appear under different CategoryIds but represent distinct services.

### 2.1 Variables:
- **UserId**: Unique identifier for each customer
- **ServiceId**: Anonymized services linked to specific categories (e.g., upholstery cleaning, radiator cleaning, or furniture assembly)
- **CategoryId**: Anonymized service categories (e.g., cleaning, moving, renovation)
- **CreateDate**: The date the service was purchased by the customer

## 3. Objective

The primary goal of this project is to develop a **recommender system** that suggests services to users based on their previous interactions with the platform. By applying **Association Rule Learning**, the system will identify patterns between different services and categories, enabling more personalized recommendations. 

### Key Goals:
1. Leverage **Association Rule Learning** to discover frequently occurring service associations.
2. Provide relevant service recommendations to users based on their historical service purchases.
3. Enhance customer satisfaction by making the platform more intuitive and personalized.

## 4. Conclusion

By implementing the Association Rule Learning-based recommendation system, **Armut** will be able to offer more personalized service suggestions to users, improving the overall customer experience and potentially increasing the use of its services. This system will serve as a valuable tool to help users discover services they may need, based on their prior interactions with the platform.
