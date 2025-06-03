# fingerprinting_tutorial_omega

These scripts accompany the article "The influence of the head model on magnetoencephalography-derived functional connectivity fingerprinting", by Matthias Schelfhout, Thomas Hinault, Sara Lago, Giorgio Arcara, Enrico Amico, Matteo Fraschini, and Daniele Marinazzo.
Note that scripts are changed so that only Theta band is included.

files are meant to be used as follow

- First launch the `Step1_tutorial_omega_mod.m ` script. It is almost a copy of the [tutorial_omega script](https://github.com/brainstorm-tools/brainstorm3/blob/master/toolbox/script/tutorial_omega.m) available on Brainstorm software website. The only difference is in the Noise Covariance. To avoid introducing a further source of confusion related to brain data (but not brain connectivity), we set this to identity matrix. Note that the script should be launched as `'tutorial_omega_mod(MyDir)`, where `MyDir`is the directory of OMEGA protocol (please see Brainstorm websites for details).

- then launch one of the three scripts `Step2_tutorial_brain_fingerprint_randomhead.m`, `Step3_tutorial_brain_fingerprint_samehead.m`, `Step4_tutorial_brain_fingerprint_samesource.m` to reproduce the three approaches used in the article.



