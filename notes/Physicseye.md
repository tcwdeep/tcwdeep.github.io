# Chapter 1: Human Vision

## 1.1.1 How we see things

- Light from the object is refracted by the **cornea** and the **lens** to form a **real, inverted** image on the **retina**.
- **Light-sensitive cells** on the retina detect the light and convert it into nerve impulses.
- Impulses travel along the **optic nerve** to the **brain**, which interprets them as an **erect** image.
- **Blind spot**: where the optic nerve leaves the eye, with no light-sensitive cells.

## 1.1.2 Focusing of incoming light

- Cornea + lens act like a **convex lens**. Image on retina: **inverted, diminished, real**.
- Lens formula (**real-is-positive** convention):

$$\frac{1}{u}+\frac{1}{v}=\frac{1}{f}$$

  - $u>0$ for a real object, $v>0$ for a real image (on the retina), $f>0$ for a convex lens.
- $v$ (lens-to-retina distance) is **fixed**, so the eye must change $f$ for different $u$. This is **accommodation**: changing the shape (focal length) of the lens to form a **sharp** image on the **retina**.

| | Near object (small $u$) | Distant object ($u\to\infty$) |
|---|---|---|
| Ciliary muscles | contract | relax |
| Lens | thicker, more convex | thinner, less convex |
| Focal length $f$ | smaller | larger |
| Refraction | more | less |

## 1.1.3 Changing light into electrical signals

- Light-sensitive cells are **transducers**: light energy $\to$ electrical energy of an impulse.
- **Yellow spot**: very sensitive region on the visual axis (most cones here).
- **Blind spot**: no light-sensitive cells.

| Rods | Cones |
|---|---|
| Black-and-white vision (shades of grey) | Colour vision and fine detail |
| Work well in **dim** light (night) | Work well in **bright** light |
| Everywhere except yellow spot and blind spot | Everywhere except blind spot; most at yellow spot |
| Most sensitive at about $500\ \text{nm}$ | Three types: blue, green, red |

- There are many more rods than cones (about $20:1$).
- Each cone type is most sensitive to a specific wavelength (shown by **receptor absorption curves**).
- The brain perceives the **combined stimulation** of the three cone types as the **colour** of the light.

## 1.1.4 Resolving power of the eye

- Angular separation: $\theta=\dfrac{x}{u}$ (radian), where $x$ = separation of the two objects and $u$ = object distance.
- **Rayleigh criterion** (minimum angle that can just be resolved):

$$\theta_R=1.22\frac{\lambda}{d}\ \text{(radian)}$$

  $\lambda$ = wavelength of light, $d$ = pupil diameter.
- Smaller $\theta_R$ means higher resolving power.
- Two objects are resolved if $\theta\geq\theta_R$.

### Exercise 1

Sophia looks with one eye at the tips of two purple pens (reflecting light of $420\ \text{nm}$). The tips are $1\ \text{cm}$ apart and $70\ \text{m}$ from her eye. Her pupil diameter is $3\ \text{mm}$.

(a) Find the angular separation $\theta$ of the two tips.
(b) Explain why the two tips CANNOT be resolved.
(c) How should she change (i) the distance between the tips, (ii) the distance of the tips from her eye, to make them resolvable?

> [!TIP] Answer
> (a) $\theta=\dfrac{0.01}{70}\approx1.43\times10^{-4}\ \text{rad}$
>
> (b) $\theta_R=1.22\times\dfrac{420\times10^{-9}}{3\times10^{-3}}\approx1.71\times10^{-4}\ \text{rad}$. Since $\theta<\theta_R$, the two tips **cannot** be resolved.
>
> (c) (i) **Increase** the distance between the tips. (ii) **Decrease** the distance from her eye.

### Exercise 2 (2026 DSE Paper 2 Q4.2)

A person with normal eyesight stands in front of an eye-test chart illuminated by light of wavelength $550\ \text{nm}$. His pupil diameter is $5.0\ \text{mm}$. How far is he from the wall if he can just resolve the lines (line separation $x=2.5\ \text{mm}$)?
A. $9\ \text{m}$  B. $15\ \text{m}$  C. $19\ \text{m}$  D. $28\ \text{m}$

> [!TIP] Answer: **C**
> $\theta_R=1.22\times\dfrac{550\times10^{-9}}{5.0\times10^{-3}}=1.342\times10^{-4}\ \text{rad}$
>
> Just resolved: $\dfrac{x}{u}=\theta_R\Rightarrow u=\dfrac{2.5\times10^{-3}}{1.342\times10^{-4}}\approx19\ \text{m}$

## 1.2.1 Refractive power of a lens

- Power: $P=\dfrac{1}{f}$, unit **dioptre (D)** $=\text{m}^{-1}$ ($f$ in metres!).
- Convex lens: $P>0$. Concave lens: $P<0$.
- Lenses close together: $P_{\text{total}}\approx P_1+P_2+\cdots$ (e.g. $4+(-1)+2=5\ \text{D}$).

### Exercise

Two convex lenses of focal lengths $15\ \text{cm}$ and $30\ \text{cm}$ are placed in contact. Find the effective power of the combination.

> [!TIP] Answer
> $P=\dfrac{1}{0.15}+\dfrac{1}{0.30}=\mathbf{10\ D}$

## 1.2.2 Near point and far point

- **Near point**: the **closest** point at which an object can be focused (lens thickest). Normal eye: $25\ \text{cm}$.
- **Far point**: the **farthest** point at which an object can be focused (lens thinnest). Normal eye: **infinity**.
- Looking at the near point: $f$ is **minimum**. Looking at the far point: $f$ is **maximum**.
- Effective power of the eye: $P=\dfrac{1}{u}+\dfrac{1}{v}$ (use metres, so $v=2.8\ \text{cm}=0.028\ \text{m}$).

### Exercise 1

The lens-to-retina distance of a normal eye is $2.8\ \text{cm}$. Find the minimum and maximum focal lengths of the eye.

> [!TIP] Answer
> Near point: $\dfrac{1}{f}=\dfrac{1}{25}+\dfrac{1}{2.8}\Rightarrow f_{\min}\approx\mathbf{2.52\ cm}$
>
> Far point: $\dfrac{1}{f}=0+\dfrac{1}{2.8}\Rightarrow f_{\max}=\mathbf{2.8\ cm}$

### Exercise 2

An eye has a range of accommodation from $25\ \text{cm}$ to infinity and a lens-to-retina distance of $2.3\ \text{cm}$. The power of the cornea is $28\ \text{D}$. Find the power of the lens when (a) the lens is at its maximum thickness, (b) the lens is at its minimum thickness.

> [!TIP] Answer
> (a) Looking at the near point ($u=0.25\ \text{m}$): total $P=\dfrac{1}{0.25}+\dfrac{1}{0.023}\approx47.5\ \text{D}$. Lens $=47.5-28=\mathbf{19.5\ D}$.
>
> (b) Looking at the far point ($u\to\infty$): total $P=0+\dfrac{1}{0.023}\approx43.5\ \text{D}$. Lens $=43.5-28=\mathbf{15.5\ D}$.

## 1.2.3 Short sight (myopia)

- Sees **near** objects clearly, cannot focus **distant** objects. Image of a distant object forms **in front of** the retina.
- Far point is **closer** than infinity.
- Causes: eyeball too **long**, or lens too **thick** when ciliary muscles relax (lens too thick for the eye).
- Correction: **concave (diverging) lens** whose focus is at the **uncorrected far point**. A distant object then gives a virtual image at the uncorrected far point.
- With the lens, the far point is corrected to infinity and the near point moves **farther**.
- Effective power $=P_{\text{lens}}+P_{\text{eye}}$.

### Exercise

The far point of John's eye is at $60\ \text{cm}$ and its lens-to-retina distance is $2.5\ \text{cm}$. What is the power of the corrective lens he should wear?
A. $-2.0\ \text{D}$  B. $-1.7\ \text{D}$  C. $1.7\ \text{D}$  D. $2.0\ \text{D}$

Bonus: Find the corrected near point of John.

> [!TIP] Answer: **B**
> $u=\infty$, image at the far point, $v=-0.6\ \text{m}$ (virtual): $P=0+\dfrac{1}{-0.6}\approx-1.7\ \text{D}$
>
> Bonus: image at the uncorrected near point, $v=-0.25\ \text{m}$: $\dfrac{1}{u}-\dfrac{1}{0.25}=-1.667\Rightarrow u\approx\mathbf{0.429\ m}$

## 1.2.4 Long sight (hypermetropia)

- Sees **distant** objects clearly, cannot focus **near** objects. Image of a near object forms **behind** the retina.
- Near point is **farther** than $25\ \text{cm}$. Near point of accommodation **increases** with age.
- Causes: eyeball too **short**, or lens too **thin** when ciliary muscles contract maximally.
- Correction: **convex lens**. Object at the **normal** near point ($25\ \text{cm}$) gives a virtual image at the **uncorrected** near point.

### Exercise

John cannot see things clearly closer than $0.80\ \text{m}$. What kind of lens and what power should he wear so as to correct his near point to $0.25\ \text{m}$?
A. convex, $+2.75\ \text{D}$  B. convex, $+5.25\ \text{D}$  C. concave, $-2.75\ \text{D}$  D. concave, $-5.25\ \text{D}$

Extra: What will John's far point be when wearing the corrective lens?

> [!TIP] Answer: **A**
> $\dfrac{1}{0.25}+\dfrac{1}{-0.80}=4-1.25=+2.75\ \text{D}$, a convex lens.
>
> Extra: the far point is where the image is at infinity, so $u=f=\dfrac{1}{2.75}\approx\mathbf{0.364\ m}$. A convex lens makes the far point **closer** to the eye.

## 1.2.5 Old sight (presbyopia)

- During accommodation the ciliary muscles **contract** and the lens thickens by its own elasticity.
- With age the lens thickens **less** (decreased elasticity), so the power of the eye drops and light from a close object focuses **behind** the retina (similar to long sight).
- Old sight = a kind of long sight related to ageing. Correction: **convex** lenses.
- Old + long sight: convex lenses. Old + short sight: **bifocal** lenses.

### Exercise 1

John is short-sighted and wears spectacles of power $-1.25\ \text{D}$ to correct the defect. Find the distance of his uncorrected far point from his eyes.

> [!TIP] Answer
> $0+\dfrac{1}{v}=-1.25\Rightarrow v=-0.8\ \text{m}$. The uncorrected far point is $\mathbf{0.8\ m}$ from his eyes.

### Exercise 2

The power $P_0$ of a long-sighted eye is $+50.25\ \text{D}$ when looking at an object at its near point. The distance between the retina and the optical centre of the refracting parts of the eye is $2\ \text{cm}$.
(a) After wearing spectacles, the near point is corrected to $25\ \text{cm}$. Find the power $P_1$ of the spectacle lenses. (What is the uncorrected near point?)
(b) Find the effective power $P_{\text{eff}}$ of the corrected eye when looking at an object at its near point.

> [!TIP] Answer
> Uncorrected near point: $\dfrac{1}{u}+\dfrac{1}{0.02}=50.25\Rightarrow u=4\ \text{m}$.
>
> (a) $\dfrac{1}{0.25}+\dfrac{1}{-4}=P_1\Rightarrow P_1=\mathbf{3.75\ D}$
>
> (b) $P_{\text{eff}}=50.25+3.75=\mathbf{54\ D}$
