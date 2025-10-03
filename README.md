# Opinion-Polls-CLT
Exploring Central Limit Theorem through simulated opinion polls.
# Opinion-Polls-CLT  

Exploring the **Central Limit Theorem (CLT)** through simulated opinion polls.  

## 📌 Project Idea  
This project uses **simulations of opinion polls** (Yes/No responses) to show how the distribution of sample means approaches a normal distribution as the sample size increases — an application of the Central Limit Theorem.  

## ⚙️ How it Works  
1. We assume a fixed probability `p` (e.g., probability that a person answers "Yes").  
2. We run repeated simulations of opinion polls with different sample sizes (`n = 10, 50, 100, 1000, 10000`).  
3. For each sample size, we calculate the mean (proportion of "Yes" responses).  
4. Finally, we compare the distributions of sample means for different sample sizes.  

## 📊 Visualization  
The project shows histograms of sample means.  
- Small sample sizes → more variability, not very "normal".  
- Larger sample sizes → distribution becomes smoother and closer to a bell curve.  

## 🚀 How to Run  
1. Clone this repo  
   ```bash
   git clone https://github.com/muskansh757-afk/Opinion-Polls-CLT.git
