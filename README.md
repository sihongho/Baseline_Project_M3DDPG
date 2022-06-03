
# M3DDPG Baseline 

We provide the training data by using M3DDPG in 8 MPE scenarios. Pictures, training records, training data, trained models are all included.

List of scenarios

Coop s1 - "simple_reference", (No Formal Name), SameR Coop

Coop s2 - "simple_speaker_listener", (Cooperative communication), SameR Coop

Coop s3 - "simple_spread", (Cooperative navigation), SameR Coop

Comp s4 - "simple_adversary", (Physical deception), Non-zerosum Comp

Comp s5 - "simple_crypto", (Covert communication), Zerosum Comp

Comp s6 - "simple_push", (Keep-away), Non-zerosum Comp

Comp s7 - "simple_tag", (Predator-prey), Non-zerosum Comp

Coop&Comp s8 - "simple_world_comm" (No Formal Name), Non-zerosum Comp, SameR Coop, DiifR Coop

![S1](/experiments/plots/s1.png)

![S2](/experiments/plots/s2.png)

![S3](/experiments/plots/s3.png)

![S4](/experiments/plots/s4.png)

![S5](/experiments/plots/s5.png)

![S6](/experiments/plots/s6.png)

![S7](/experiments/plots/s7.png)

![S8](/experiments/plots/s8.png)

## Produce testing model


`python train.py --scenario simple_reference --load-name models/s1/m3_s1_mmmddpg_mmmddpg_e20/model-59000 --exp-name m3_s1_e20 --good-policy mmmddpg --bad-policy mmmddpg --benchmark`

`python train.py --scenario simple_speaker_listener --load-name models/s2/m3_s2_mmmddpg_mmmddpg_e20/model-59000 --exp-name m3_s2_e20 --good-policy mmmddpg --bad-policy mmmddpg --benchmark`

`python train.py --scenario simple_spread --load-name models/s3/m3_s3_mmmddpg_mmmddpg_e20/model-59000 --exp-name m3_s3_e20 --good-policy mmmddpg --bad-policy mmmddpg --benchmark`

`python train.py --scenario simple_adversary --load-name models/s4/m3_s4_mmmddpg_mmmddpg_e20/model-59000 --exp-name m3_s4_e20 --good-policy mmmddpg --bad-policy mmmddpg --benchmark`

`python train.py --scenario simple_crypto --load-name models/s5/m3_s5_mmmddpg_mmmddpg_e20/model-59000 --exp-name m3_s5_e20 --good-policy mmmddpg --bad-policy mmmddpg --benchmark`

`python train.py --scenario simple_push --load-name models/s6/m3_s6_mmmddpg_mmmddpg_e20/model-59000 --exp-name m3_s6_e20 --good-policy mmmddpg --bad-policy mmmddpg --benchmark`

`python train.py --scenario simple_tag --load-name models/s7/m3_s7_mmmddpg_mmmddpg_e20/model-59000 --exp-name m3_s7_e20 --good-policy mmmddpg --bad-policy mmmddpg --benchmark`

`python train.py --scenario simple_world_comm --load-name models/s8/m3_s8_mmmddpg_mmmddpg_e20/model-59000 --exp-name m3_s8_e20 --good-policy mmmddpg --bad-policy mmmddpg --benchmark`
