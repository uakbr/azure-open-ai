In today’s rapidly evolving world, every company is trying to embrace generative AI technology. While giants are after developing large models and have plan to offer those as services, mid and small sized companies are looking to use these technologies and integrate the available services to their applications offering. And all this is happening at incredible speed. While considering the implementation of AI, companies often have questions about how its pricing structure works. In this article, we will get into the details of ChatGPT(GPT-4) pricing, shedding light on its key components and helping them make informed decisions.

Some of the key concepts around current pricing around GPT-4 and other models,

1.  Pay as you go model - Pricing revolves around the concept of usage-based models.
2.  OpenAI has adopted a transparent pricing strategy, one can scale their usage up or down depending on their requirements, without being tied to fixed plans or upfront commitment.
3.  Usage depends upon Tokens, tokens are also called currency of ChatGPT.
4.  OpenAI provides tools for monitoring token usage. These tools empower businesses to track their consumption in real-time, make informed decisions regarding scaling.
5.  It offers different pricing tiers based on token limits, if a conversation exceeds the token limit of a given plan, overage fees come into play.
6.  While token usage forms the foundation of ChatGPT pricing, other factors can impact the overall costs as well. Factors such as the complexity of conversations, the required response times, and additional features or customizations can affect the final pricing.

**Tokens**

A "token" refers to a unit of text that is processed by the language model. It can be as short as a single character or as long as a word. In natural language processing, text is divided into tokens to enable the model to understand and generate language.

Generally, in the sentence "I love cats," the tokens would be three: \["I", "love", "cats"\]. Each word in this sentence is considered a separate token. It processes text by breaking it down into tokens. Tokens can be words or just chunks of characters. For example, the word “hamburger” gets broken up into the tokens “ham”, “bur” and “ger”, while a short and common word like “pear” is a single token. The total number of tokens processed in a given request depends on the length of the input, output and request parameters. Let’s take a look at two examples of Tokens usage,

**Example 1** \- Setup up content with prompt question, notice that total number of tokens is equal to 286. There are total of 235 words,

After response is received, number of tokens changes to 293, 


**Example 2** \- Total number of words are around 71, but number of tokens are 118.


After Generate button is hit, then number of tokens is increased by 2, from 118 to 120. But number of words added is just one – “Entertainment”.


Bottom line is number of tokens depends on various factors and not directly related to number of words.

**Azure regions and models availability**

Right now these OpenAI services are offered under the family of Azure Cognitive services - and are only available in certain Azure regions,

*   East US
*   South Central US
*   West Europe

Below language/image models are available,


**Restrictions**

General restrictions are imposed on usage of OpenAI under Cognitive Services family, increase on limits can be requested if use case demands more - subjected to approval on case-to-case basis.

Note -  These restrictions and quotas can change anytime.


**Pricing for GPT 4**

If we talk about GPT-4 which is arguable most advanced and costly model, here is the pricing from Azure website.


As per above billing, "Per 1,000 tokens" means the cost or price associated with processing 1,000 tokens of text. So, for the GPT-4 model, if we provide a prompt or input text with 1,000 tokens, it would cost ₹2.454. Similarly, generating completion or output text of 1,000 tokens would cost ₹4.907 for the 8K context and ₹9.813 for the 32K context.

Let’s understand more on 8k and 32K Context,

**8K Context**: With an 8K context size, ChatGPT-4 looks at the previous 8,000 tokens of the conversation to generate its responses. This means it considers the immediate conversation history to understand the context and provide relevant replies.

For example: You start a conversation with ChatGPT-4, and in the preceding conversation history, there are 500 tokens. Now, when you ask a question or provide a prompt, ChatGPT-4 takes into account those 500 tokens as context along with your current input to generate a response.

**32K Context:** With a 32K context size, ChatGPT-4 has a broader understanding of the conversation as it considers the preceding 32,000 tokens. This allows the model to have a more extensive view of the conversation history and generate more contextually rich responses.

Continuing the example: Suppose the preceding conversation history contains 10,000 tokens. In this case, ChatGPT-4 can utilize all 10,000 tokens as context to better understand the ongoing conversation and generate more informed responses.

The size of 8K or 32K determines the amount of preceding text that ChatGPT-4 considers to understand the conversation history and generate responses accordingly. A larger context size enables the model to have a more comprehensive view of the conversation and provide more contextually relevant replies.

**Summary**

Understanding OpenAI Azure service pricing structure is crucial for businesses considering its implementation. With a pay-as-you-go model, companies only pay for the AI capabilities they use. The pricing is determined by tokens, which are units of text processed by the language model. Different pricing tiers exist based on token limits. Factors like conversation complexity, response times, and additional features impact the overall costs. Understanding pricing empowers businesses to make informed decisions, optimize costs, and unlock the benefits of enhanced customer interactions and operational efficiencies.

If this article has been helpful, I would appreciate your feedback and comments. Additionally, if there are any other Azure Cognitive Services related topics that you would like me to cover and share information on, please do let me know.
