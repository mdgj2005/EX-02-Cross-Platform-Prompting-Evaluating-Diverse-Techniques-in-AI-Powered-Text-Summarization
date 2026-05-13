# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "“Introduction to Blockchain Technology”" using multiple AI platforms and prompting strategies.
Article - https://ntiprit.gov.in/pdf/blockchainanddistributed/Blockchain_Introduction_KR.pdf

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience
# AI PLATFORMS USED

1. ChatGPT
2. Gemini
3. Claude
4. Copilot

---

# PROMPTING TECHNIQUES USED

## 1. Zero-Shot Prompting
The AI is directly asked to summarize the text without examples.

### Prompt
> Summarize the following article on Blockchain Technology in simple words for undergraduate students in 100 words.

---

## 2. Few-Shot Prompting
The AI is given sample summaries before generating the final summary.

### Prompt
>Input: Cloud computing provides services over the internet.<br>
Output: Cloud computing delivers online computing services.

>Input: Cybersecurity protects systems from digital attacks.<br>
Output: Cybersecurity keeps systems and data safe.

>Input: Artificial Intelligence enables machines to learn from data.<br>
Output: AI helps machines learn automatically.

>Input: Explain blockchain from the article in a simple and concise way.<br>
Output:

---

## 3. Chain-of-Thought Prompting
The AI is instructed to think step-by-step before generating the summary.

### Prompt
> Reason step by step to explain how blockchain works in simple language.

---

## 4. Role-Based Prompting
The AI is assigned a specific role.

### Prompt
> You are a university professor explaining Blockchain Technology to first-year engineering students. Summarize the article clearly and simply.


## Algorithm

1. Select a 500-word technical article on **“The Basics of Blockchain Technology.”**

2. Apply four prompting techniques:
   - Zero-shot Prompting
   - Few-shot Prompting
   - Chain-of-Thought Prompting
   - Role-Based Prompting

3. Run the same prompts on multiple AI platforms:
   - ChatGPT
   - Gemini
   - Claude
   - Copilot

4. Generate summaries from each combination of:
   - AI platform
   - Prompting technique

5. Compare the generated summaries based on:
   - Accuracy
   - Coherence
   - Simplicity
   - Speed
   - User Experience

6. Record observations and analyze the outputs.

7. Identify the best-performing AI platform and prompting strategy.
### CHATGPT:
####  Zero-Shot Prompting:
Blockchain technology is a secure digital system used to store and share information across many computers without depending on a central authority. It works like a shared online record book where transactions are grouped into “blocks” and linked together in a chain. Once data is added, it is very difficult to change, making the system transparent and trustworthy. Blockchain reduces fraud, improves security, and removes the need for intermediaries like banks or agents. Although it became popular through Bitcoin and cryptocurrencies, blockchain is also useful in banking, healthcare, supply chains, voting systems, and government services because of its reliability and efficiency

####  Few-Shot Prompting:
Blockchain is a secure digital system that stores and shares data across many computers without a central authority.

#### Chain-of-Thought Prompting:
<img width="1015" height="315" alt="image" src="https://github.com/user-attachments/assets/c2cb343d-60c9-4610-968a-e8976bf4f8a0" />

#### Role-Based Prompting:
Blockchain technology is a digital system used to store and share information securely across many computers. Instead of keeping records in one central place, blockchain distributes the data among all users in the network. Information is stored in units called blocks, and these blocks are connected in order to form a chain. Once data is added, it is very difficult to change, which makes the system secure and trustworthy.
Blockchain removes the need for intermediaries like banks because transactions are verified by the network itself. It offers transparency, security, and reliability. Although it became popular through Bitcoin, blockchain is also used in banking, healthcare, supply chains, digital identity, voting systems, and government services. It helps reduce fraud, improve efficiency, and build trust in digital transactions.

### GEMINI:

####  Zero-Shot Prompting:
Blockchain is a revolutionary digital technology that acts as a decentralized, shared ledger for recording transactions. Unlike traditional systems that rely on a central authority like a bank, blockchain uses a peer-to-peer network where every participant holds a copy of the data.Transactions are grouped into "blocks" and secured using advanced cryptography. Once a block is verified through a consensus process (like "Proof of Work"), it is permanently linked to the previous one, forming an unchangeable chain. This makes the system transparent, tamper-proof, and efficient by eliminating middle-men and reducing fraud.

####  Few-Shot Prompting:
Blockchain is a shared digital ledger that records transactions across a network of computers without needing a central authority. It groups data into "blocks" that are secured with unique cryptographic fingerprints and linked together in a permanent "chain." This structure ensures that information is transparent and cannot be changed or deleted, making the system highly secure and efficient for transferring digital assets.

#### Chain-of-Thought Prompting:
<img width="667" height="744" alt="image" src="https://github.com/user-attachments/assets/fa959320-5183-4c6b-a71a-dbc9bdede673" />

#### Role-Based Prompting:
<img width="725" height="604" alt="image" src="https://github.com/user-attachments/assets/d324184a-a663-4a7c-808f-2b0765d8db88" />

### CLAUDE:

####  Zero-Shot Prompting:
Blockchain Technology — Simple Summary
Blockchain is a digital record-keeping system where data is stored across many computers simultaneously, instead of one central place like a bank. Think of it as a shared notebook that everyone can see but no one can secretly alter.
It was born from Bitcoin, a digital currency designed to eliminate middlemen and make transactions faster and safer. Each "block" stores transaction data and is linked to the previous one, forming a tamper-proof "chain."
It has three types — public, private, and consortium — and supports smart contracts (self-executing agreements). Beyond finance, blockchain can transform supply chains, healthcare, IoT, and more.

####  Few-Shot Prompting:
Blockchain is a shared digital record book, copied across thousands of computers, where every entry is permanent, visible to all, and impossible to secretly alter.

#### Chain-of-Thought Prompting:
<img width="736" height="572" alt="image" src="https://github.com/user-attachments/assets/6fb8b458-641a-4090-b962-0600b6935d58" />

#### Role-Based Prompting:
<img width="732" height="609" alt="image" src="https://github.com/user-attachments/assets/4fa075f3-d10f-492f-ae3f-01cd99550881" />

### COPILOT:

####  Zero-Shot Prompting:
Blockchain is a shared digital ledger that records transactions securely across many computers. Each transaction is grouped into blocks, linked together, and verified by consensus, making tampering nearly impossible. Unlike traditional systems that rely on banks or intermediaries, blockchain allows direct, transparent, and efficient exchanges. First used in Bitcoin, it now powers smart contracts, supply chains, healthcare, and more. Public blockchains are open to all, private ones are restricted, and consortium blockchains are shared among selected groups. In simple terms, blockchain builds trust without middlemen, reduces costs, and opens new opportunities for industries and innovation.

####  Few-Shot Prompting:
Output: Blockchain is a secure digital ledger that records transactions across many computers. Each transaction is grouped into blocks, verified by the network, and added to a chain that cannot be altered. This makes data transparent, trustworthy, and safe without needing banks or middlemen.

#### Chain-of-Thought Prompting:
<img width="925" height="533" alt="image" src="https://github.com/user-attachments/assets/43d43e76-20a3-4077-bfa5-b6c4cb32c9c8" />

#### Role-Based Prompting:
<img width="934" height="426" alt="image" src="https://github.com/user-attachments/assets/f7d09571-dda9-4a55-8790-84364c051f3f" />

## Performance Evaluation Table:
<img width="1461" height="553" alt="image" src="https://github.com/user-attachments/assets/b0d8f840-e188-41c1-ab92-b53af6ddbe8d" />

## Conclusion:
Across all platforms, prompting technique significantly influences clarity and structure, but the model choice determines depth and refinement. Claude performs best in accuracy and coherence, while ChatGPT provides the most balanced combination of simplicity, speed, and usability for students. Gemini is strong in structured reasoning, and Copilot excels in simplicity but lacks depth.

## Result
The experiment clearly shows that prompting technique and model choice together significantly affect summary quality, and role-based prompting consistently delivers the most effective results across platforms for educational content generation.

