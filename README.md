# OrderBot

This project is an automated service designed to collect orders for an online restaurant. It interacts with customers to take their orders, ask for delivery details, and process payments in a conversational manner. The project utilizes OpenAI's language model for generating responses and Chainlit for creating a user-friendly interface.

**Features:**
**Automated Order Collection:** Guides customers through the menu and efficiently collects their desired items, including quantities, sizes, and any special requests.
**Pickup or Home Delivery Options:** Clearly asks customers for their preferred method of receiving the order, and if delivery is chosen, it prompts for the delivery address.
**Order Summarization and Confirmation:** After collecting the full order, OrderBot summarizes it for the customer and provides a final opportunity to add or modify items, ensuring accuracy.
**Payment Collection:** Facilitates the payment process after the order is confirmed.
**Comprehensive Menu Integration:** The bot has access to a detailed menu, allowing it to clarify options, extras, and sizes to uniquely identify each item.
**Conversational and Friendly Style:** Designed to interact in a short, conversational, and friendly manner, enhancing the user experience.
**OpenAI Integration:** Utilizes OpenAI's powerful language models (specifically gpt-3.5-turbo) to understand natural language queries and generate human-like responses.
**Chainlit Interface:** Built with Chainlit for a user-friendly and interactive chat interface, allowing for seamless communication with the bot.

**How It Works:**
Customer Interaction: The bot initiates the conversation by greeting the customer.
Order Collection: The customer places their order by typing their requests. The bot intelligently processes these requests, clarifies any ambiguities (e.g., pizza size, drink type), and adds items to the order.
Delivery/Pickup Confirmation: Once the order is complete, OrderBot asks if the customer prefers pickup or home delivery. If delivery, it requests the address.
Order Summary: The bot presents a summary of the entire order, including prices, and prompts the customer for final confirmation or any additions.
Payment: After final confirmation, the bot proceeds to collect payment.
Chat History: The conversation history is maintained within the Chainlit interface, allowing for a continuous and context-aware interaction.

**Getting Started:**

**Prerequisites:**
- Python 3.x
- OpenAI API Key: You'll need to set up an OpenAI API key.
- Chainlit: The framework for the interactive chat interface.

**Installation:**



**Usage:**
Once the application is running, a new tab will open in your web browser with the OrderBot chat interface.

**Start Chatting:** Begin by typing your order requests in the input field.
**Follow Prompts:** OrderBot will guide you through the ordering process, asking clarifying questions as needed.
**Confirm Order:** Review the order summary and confirm before proceeding to payment.

**Author: **This project is developed and maintained by Priyamvadha Pradeep.
