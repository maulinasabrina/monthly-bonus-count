How I Stopped Driving Myself Crazy with a Calculator Every Payday 🛒

Every month when my salary and bonus hit my account, I used to find myself doing the exact same tedious routine.

I’d open my phone's calculator app, type in my monthly bonus, divide it by my base salary to find the ratio, and then try to calculate how much of that bonus I could guilt-free spend on shopping versus how much I absolutely had to save. Doing this manual math back and forth every single month was incredibly annoying.

So, I built this simple, macOS-themed web calculator to automate my payday calculations. No more manual math, no more guessing.

Why I Built This (The Friction)

When calculating my shopping budget, I set up a personal rule to keep my finances in check. The higher my bonus ratio is compared to my base salary, the more I allow myself to spend as a reward:

$$\text{Bonus Ratio} = \left( \frac{\text{Monthly Bonus}}{\text{Base Salary}} \right) \times 100$$

But calculating this on a standard calculator app meant I had to:

Calculate the ratio.

Remember my personal tier limits.

Multiply the bonus by the respective percentage.

Subtract that from the total bonus to find my savings.

Now, I just input my numbers, and this app handles the rest instantly.

My Personal Budgeting Tiers

Here is the exact logic I programmed into the tool to decide my shopping allowance:

Under 70% Ratio: Honestly, if my bonus is less than 70% of my base salary, I don't give myself any extra shopping budget from it. $100\%$ of the bonus goes straight into my savings.

70% to 99% Ratio: I allow myself to spend $10\%$ of the bonus on shopping, and save the remaining $90\%$.

100% to 119% Ratio: A great month! I spend $20\%$ of the bonus and save $80\%$.

120% and above: Jackpots! I splurge $30\%$ of the bonus on shopping and save $70\%$.

Features I Added to Make My Life Easier

Auto-Formatting Dots (IDR): Typing millions of Rupiahs in a standard input box makes it easy to mistype a zero (is it 5,000,000 or 50,000,000?). I added a script that automatically formats the numbers with thousand separators (e.g., 5.000.000) as I type.

Visual Allocation Bar: Instead of just numbers, I added a progress bar that visually splits my budget. It lets me see in a split-second how much is going to my wallet (Blue) versus my savings (Green).

The macOS Aesthetic: Because I love the clean look of macOS desktop applications, I wrapped the calculator in a sleek glassmorphism window with the classic red, yellow, and green window controls. It just feels nicer to look at on my screen.

Now, checking my payday shopping budget takes exactly 5 seconds! 🚀