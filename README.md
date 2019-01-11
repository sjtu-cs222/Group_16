# Group_16
Input Transformation in Defense Against Adversarial Attacks

#### Basic idea

We're designing a special transform based on a secret key stream to the input to defense both white-box and black-box adversarial attacks.

#### How to use

To see the effect of the idea on white-box attacks,

```shell
python mnist_adv_defense.py
```

"eps" in the code is a tunable parameter to adjust the level of the attack. The higher the stronger.

To see the effect of the idea on black-box attacks, pls compare the result of two files,

```shell
python mnist_blackbox.py
python mnist_blackbox_defense.py
```

"eps" in the code is a tunable parameter to adjust the level of the attack. The higher the stronger.