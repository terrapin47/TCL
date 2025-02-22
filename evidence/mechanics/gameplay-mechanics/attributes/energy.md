# Energy

## Elemental Skill Particle Production Database

**Added:** 12/6/2020

[Full Database](https://docs.google.com/spreadsheets/d/1G05DxDSjtBzj4PZtVjGRA4ATq76HPZa6e4kHVWS6mrA/edit#gid=0)

**Contributors**

* Base information came from this [post](https://twitter.com/_aomu/status/1317287212858433537)
* Steph\#3614
* Aerylle\#1254 
* JarJarThinks
* ＃＃\#0123
* JinJinx \(Mathalos Main\)\#5874

## Only On-Field Characters Gain Energy By Auto Attacks

**By:** c2authoritarian\#5277 and Pinupski\#9999

**Added:** 12/7/2020

Updated: 4/3/2021

**Finding:** Energy recharge gained through auto attacking only applies to the character on field

**Evidence:** The original author didn't provide video evidence, but it was approved due to being easily replicated**.** Special thanks go to Pinupski\#9999 for validating this entry with video evidence.

1. Enemy's health was depleted to ~5% and let to reset to full HP, removing the variable of HP particles
2. [Autoattacking](https://youtu.be/yMstsGRLy5s): Used all bursts to reset the burst meter, then auto attacked with Zhongli until burst was charged
3. [Conclusion](https://youtu.be/3W_Gjd5LfDM): Characters other than Zhongli still had 0 energy.

**Significance:** Off-field characters cannot gain energy via auto attacks from the active character .

## Energy Recharge **D**oes NOT Have a Softcap \(at least up to 300 ER\)

**By:** muakasan\#2792  
**Added:** 4/4/2021

**Evidence:**

1. Bennett was given 300.1% ER
2. Funneled non-pyro elemental particles to Bennett while off-field
3. [Took 33 particles](https://youtu.be/8WRgwQf-zh0), which is almost exactly what was expected

```python
0.6 energy per particle * 3.001 ER * 33 particles = 59.420
```

**Significance:** Helpful when figuring out how much energy recharge is needed to build on a character in a specific team.

## Auto Attack Energy Mechanics

**By:** xf3\#3123 and Zeitraffer\#1074  
**Added:** 5/6/2021  
[Discussion](https://tickettool.xyz/direct?url=https://cdn.discordapp.com/attachments/839361536900595732/840061797561139211/transcript-auto-attack-energy-mechanics.html)

**Finding:**  
Normal attacks have a chance on hit to give the on field character about 1 energy. It can be seen when the on field character's vision flashes. It is not effected by ER% and can work with charged attacks. Multi-hit attacks, such as Keqing's N1C, count each hit individually for proc chance. It also gives energy regardless if the user can get particles or not, such as in Xiao's Bane of All Evil.

**Evidence:** [Google sheets link](https://docs.google.com/spreadsheets/d/1A72e6GlV8tuzHlOUygokWtQYSc3hB7qsyKOqPUhyjj8/edit?usp=sharing)  
Spreadsheet includes videos of ER% testing, multi-hit attack testing, on hit testing, and Xiao's Bane of All Evil Testing. It also includes graphs illustrating the data spread of the tests. From the graphs and averages, multi-hit/projectile attacks on average proc the effect more often \(N Spam KQ vs N1C KQ and N Spam Diona vs N Spam Amber C1\)

**Significance:**  
Attacking enemies with normal/charged attacks can give extra energy. Although in small amounts, being able to cast a burst because of the mechanic may make or break an abyss run. Ideally, this would be done when waiting for particles, waiting for cooldowns, and/or when outside of rotations.

