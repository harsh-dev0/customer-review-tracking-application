# Customer Review Widget Documentation

## Overview
The Customer Review Widget allows you to seamlessly collect and display customer feedback on your website. With easy integration and customization options, you can enhance customer engagement and improve your business's online presence.

## Key Features
- **Real-Time Feedback**: Instantly collect customer reviews and respond accordingly.
- **Easy Integration**: Simply include the widget script on your site.
- **Customizable Appearance**: Tailor the widget's look and feel to match your brand.

## Deployment
The Customer Review Tracking Application is deployed on GitHub Pages. You can view it [here](https://harsh-dev0.github.io/customer-review-tracking-application/).

## Customization Options
To customize the appearance and functionality of the Customer Review Widget, you can provide a configuration object in your JavaScript code before initializing the widget. Below are the available customization options:

1. **Bubble Color**
   - **Property**: bubbleColor
   - **Type**: String (Hex color code)
   - **Default**: #007BFF
   - **Description**: Sets the background color of the review bubble.

2. **Bubble Text Color**
   - **Property**: bubbleTextColor
   - **Type**: String (Hex color code)
   - **Default**: #FFFFFF
   - **Description**: Sets the text color inside the review bubble.

3. **Bubble Size**
   - **Property**: bubbleSize
   - **Type**: String (CSS size)
   - **Default**: 60px
   - **Description**: Specifies the size of the review bubble.

4. **Popup Background Color**
   - **Property**: popupBackgroundColor
   - **Type**: String (Hex color code)
   - **Default**: #FFFFFF
   - **Description**: Sets the background color of the review popup.

5. **Popup Border Color**
   - **Property**: popupBorderColor
   - **Type**: String (Hex color code)
   - **Default**: #ddd
   - **Description**: Defines the border color of the review popup.

6. **Popup Text Color**
   - **Property**: popupTextColor
   - **Type**: String (Hex color code)
   - **Default**: #000000
   - **Description**: Sets the text color inside the review popup.

7. **Review Header Text**
   - **Property**: reviewHeaderText
   - **Type**: String
   - **Default**: Customer Reviews
   - **Description**: Text displayed as the header in the review popup.

8. **No Reviews Text**
   - **Property**: noReviewsText
   - **Type**: String
   - **Default**: No reviews available.
   - **Description**: Message shown when there are no reviews to display.

9. **Submit Button Text**
   - **Property**: submitButtonText
   - **Type**: String
   - **Default**: Submit Review
   - **Description**: Text on the submit button in the review form.

10. **Position**
    - **Property**: position
    - **Type**: Object
    - **Default**: { bottom: '20px', right: '20px' }
    - **Description**: Specifies the position of the review bubble on the screen.
