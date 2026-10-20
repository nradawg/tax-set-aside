# Tax Set Aside

**Paste this URL into any AI chat and it runs. No install, no key.**

```
Read https://raw.githubusercontent.com/nradawg/tax-set-aside/main/README.md and run it on me.
```

---


**Use this when** you are self employed and you need to know how much of each
payment to leave alone, and when to send it.

This is an estimate, not tax advice. It cannot file anything and it is not a
substitute for a professional who knows your situation.

## The rule

> There is no percentage that is right for everyone, and the percentage is the
> only thing anyone ever gives you.

Whether 20% or 40% is correct for you depends on your other household
withholding, your state, your filing status, and your deductions. A tool that
answers before it knows those is not estimating, it is guessing with confidence.
So this skill will not hand you a percentage it did not derive from your own
numbers.

## Two methods, and the first one is better

**Method A, last year's tax.** One number off your last filed return gives a
defensible quarterly amount with no forecasting at all. The rules the IRS states
for avoiding an underpayment penalty include paying 100% of last year's tax, or
110% if last year's adjusted gross income was over $150,000, $75,000 if married
filing separately. Divide by four. Done.

**Method B, forecast this year.** This needs the self employment tax rate, the
Social Security wage base for your tax year, your bracket, your deduction, and
your state rate. I will not supply those from memory, because the wage base and
the brackets move every year and a stale number sounds exactly like a current
one. I will tell you where each lives, you bring them back, and I do the
arithmetic in front of you.

Use A to decide what to send. Use B to decide whether A is going to leave you
with a bill.

## What you see

```
TAX SET ASIDE: 1099 income, $62,000 net so far this year

Q  Is $62,000 revenue or net profit after expenses?
A  Net profit.
   FROM YOU, you said net.

Q  Is there withholding anywhere else in your household?
A  Yes, your spouse has a W2 job.
   FROM YOU. Load bearing, and this is why a flat percentage is
   wrong for you. Their withholding may already cover part of the
   household liability, or none of it.
   OPEN: how much federal tax is being withheld from their pay?

Q  What state?
A  Unknown.
   OPEN. Some states levy no income tax and some levy several
   points. This changes the answer and I cannot infer it.

Q  What was the total tax on last year's return?
A  Unknown.
   OPEN. This is the single number that makes Method A work.
   It is on your 1040, the line labeled total tax.

Q  Was last year's AGI over $150,000?
A  Assuming no.
   GUESSED. Decides whether the safe harbor is 100% or 110%.

  I cannot give you a number yet, and I am not going to invent one.
  3 open, 1 guessed. Two of the three are one line off your 1040.

  WHEN YOU BRING LAST YEAR'S TOTAL TAX, say it was $11,400:
    $11,400 / 4 = $2,850 a quarter
    That is the amount that protects you from an underpayment
    penalty. It is NOT your bill.
    Your income is up this year, so expect to owe the difference
    in April. Hold back more than the safe harbor if you can.
```

Then the dates, and nothing else.

## The dates

The IRS states the quarters as January 1 to March 31 due April 15, April 1 to
May 31 due June 15, June 1 to August 31 due September 15, and September 1 to
December 31 due January 15 of the following year. A due date falling on a
weekend or legal holiday moves to the next business day, so confirm the exact
calendar dates for your year rather than trusting a remembered one.

Estimated payments are generally expected if you expect to owe at least $1,000
after withholding and credits. Self employment tax generally applies once net
earnings reach $400.

Verify all of the above, and the safe harbor rules, here:
https://www.irs.gov/faqs/estimated-tax

Self employment tax rate, what it applies to, and the Social Security wage base:
https://www.irs.gov/businesses/small-businesses-self-employed/self-employment-tax-social-security-and-medicare-taxes

Read the year on that page before you use the wage base from it. It does not
always show the current one.

## Limits

**The trap.** A naive version answers "set aside 30%" in one line. It sounds
like experience and it is a coin flip, because it cannot know about a spouse's
withholding, a state with no income tax, a state with a high one, or the
deduction that moves you a bracket. The same naive version quotes a bracket or a
wage base from a year that has already ended, and a stale rate is
indistinguishable from a current one in the output.

Safe harbor is penalty protection, not your liability. Paying it exactly and
earning much more than last year means a real bill in April. Say that out loud
to yourself now rather than in April.

It does not handle an S corp, payroll, a partnership, multi state income,
foreign income, or anything touching credits. Those are professional questions.

It does not know what you have already paid in. If you have made payments this
year, subtract them yourself, the arithmetic above does not see them.

---

## How this one knows what it knows

Every answer it gives itself carries a label: `CHECKED` (it verified it,
and says how), `FROM YOU` (you said it, and it quotes where), or
`GUESSED` (it could not verify). Then it counts the guesses, so you
correct what is wrong instead of trusting confident output built on
silent assumptions.

> Never ask for something you can check.
> Never assume something you cannot check.

One of 48 skills. The rest, and the house rules: [https://github.com/nradawg/assume-nothing](https://github.com/nradawg/assume-nothing)

MIT.
