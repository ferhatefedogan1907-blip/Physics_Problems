# Problem 2: Electric Potential

## Problem

Point charges

$$
+1 C,\ -2 C,\ +3 C,\ -4 C
$$

are placed at the corners of a square with side length

$$
a = 1.0 m
$$

Calculate the electric potential at the center of the square.

---

## Idea

The electric potential created by one point charge is

$$
V = k \frac{q}{r}
$$

Electric potential is a scalar quantity.

This means we do not add directions. We only add the values algebraically, including the signs of the charges.

At the center of the square, all four corners are at the same distance from the center. Therefore, every charge has the same distance from the center.

---

## Distance from the center to a corner

For a square with side length `a`, the diagonal is

$$
d = a \sqrt{2}
$$

The center of the square is halfway along the diagonal, so the distance from the center to one corner is

$$
r = \frac{d}{2}
$$

Therefore,

$$
r = \frac{a \sqrt{2}}{2}
$$

Since

$$
a = 1.0 m
$$

we get

$$
r = \frac{\sqrt{2}}{2} m
$$

---

## Total potential

The total potential at the center is the sum of the potentials from all charges:

$$
V_total = V_1 + V_2 + V_3 + V_4
$$

Using

$$
V = k \frac{q}{r}
$$

we write

$$
V_total = k \frac{q_1}{r} + k \frac{q_2}{r} + k \frac{q_3}{r} + k \frac{q_4}{r}
$$

Since all distances are the same, we can factor out `k / r`:

$$
V_total = \frac{k}{r} (q_1 + q_2 + q_3 + q_4)
$$

Now add the charges with their signs:

$$
q_1 + q_2 + q_3 + q_4 = 1 - 2 + 3 - 4
$$

$$
q_1 + q_2 + q_3 + q_4 = -2 C
$$

So,

$$
V_total = \frac{k(-2)}{r}
$$

---

## Calculation

Use

$$
k = 8.99 \times 10^9
$$

and

$$
r = \frac{\sqrt{2}}{2} m
$$

Then

$$
V_total = \frac{(8.99 \times 10^9)(-2)}{\sqrt{2}/2}
$$

Dividing by `sqrt(2) / 2` is the same as multiplying by `sqrt(2)`:

$$
V_total = -2(8.99 \times 10^9)\sqrt{2}
$$

$$
V_total \approx -2.54 \times 10^{10} V
$$

---

## Final Answer

$$
\boxed{V_total \approx -2.54 \times 10^{10} V}
$$

The potential is negative because the algebraic sum of the charges is negative.

---

## How to explain during class

First, I would say that electric potential is a scalar quantity. This means we do not need to calculate directions like in electric force or electric field.

All four charges are placed at the corners of the same square, so the distance from each charge to the center is the same.

Because the distance is the same, I can factor out `k / r`. Then I only need to add the charges with their signs:

$$
1 - 2 + 3 - 4 = -2
$$

So the total potential is negative, and the final answer is

$$
V_total \approx -2.54 \times 10^{10} V
$$
