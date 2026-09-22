Use the raw outputs you actually received from ChatGPT. The example below shows exactly how to structure the file. 

# Foundational Prompt Log 
 
## Task 1: Text Summarization 
 
### Prompt Input 
 
```text 
Summarize the text below in exactly three bullet points. Text: "Remote work has rapidly expanded, introducing both opportunities and obstacles for modern businesses..." 

ChatGPT Output 

Remote work has expanded rapidly and offers greater flexibility.  

Businesses can reduce office costs while giving employees more freedom.  

Challenges include communication, collaboration, cybersecurity, and company culture.  

Task 2: Information Extraction 

Prompt Input 

Extract the customer's name, email address, and order ID from the support request below. Support Request: "Hello FlexTime, my name is John Doe (john.doe@email.com). I haven't received my shipment updates for order FT-99881. Please check." 

ChatGPT Output 

Field 

Information 

Customer Name 

John Doe 

Email Address 

john.doe@email.com 

Order ID 

FT-99881 

Task 3: Formatting Conversion 

Prompt Input 

Convert the list of product prices below into a markdown table with two columns: "Item" and "Price". List: - Wireless Mouse: $25.00 - Ergonomic Keyboard: $70.00 - Insulated Water Bottle: $18.00 

ChatGPT Output 

Item 

Price 

Wireless Mouse 

$25.00 

Ergonomic Keyboard 

$70.00 

Insulated Water Bottle 

$18.00 

Task 4: Tone Editing 

Prompt Input 

Act as an Editor. Rewrite the draft text below to sound like a professional, polite B2B email sent to a client. Draft: "hey, sorry we are late on the report. it had bugs. we will send it tomorrow. thanks." 

ChatGPT Output 

Dear Client, 

I apologize for the delay in delivering the report. We identified and needed to resolve some issues before finalizing it. 

We expect to send the completed report tomorrow. Thank you for your patience and understanding. 

Best regards, 
 [Your Name] 

Task 5: Constraint-Driven Output 

Prompt Input 

Summarize the sentence below in under 20 words. Do not use the word "help" or "assist". Sentence: "Our customer success managers are available 24 hours a day to guide new users and resolve technical account disputes." 

ChatGPT Output 

Customer success managers are available 24/7 to guide new users and resolve technical account disputes. 

 
### 3. Important requirement 
 
Notice the **blank line before each Markdown table**: 
 
```markdown 
### ChatGPT Output 
 
| Field | Information | 
|---|---| 

and: 

### ChatGPT Output 
 
| Item | Price | 
|---|---:| 
