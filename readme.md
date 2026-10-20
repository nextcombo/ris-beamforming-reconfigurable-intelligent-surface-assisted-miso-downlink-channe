# [RIS+ Beamforming] Reconfigurable Intelligent Surface-Assisted MISO Downlink Channel Covariance Optimization Beamforming [with code]

Introduction: Multi-Input Single-Output (MISO) downlink beamforming, where the base station (BS) deploys multiple transmit antennas and each user equipment (UE) has a single receive antenna, can enhance signal quality by aligning the transmitted beam towards the direction of the users. The UE's transmission beamforming can be optimized for various targets that adhere to Quality of Service constraints [1], [2]. The performance of optimization depends on the current state of the channel and can be analyzed for certain channel models [3]. To improve transmission efficiency and enhance cell coverage, network operators can install reconfigurable intelligent surfaces (RIS) panels in their service areas. By strategically reflecting or redirecting signals, the RIS further improves the Signal-to-Interference-plus-Noise Ratio (SINR) and increases overall network throughput [4]-[6].
However, accurate channel information at the BS is required to optimize the IRS transmission beamforming and reflection coefficients. Apart from [5], the assumption made so far is that perfect current channel knowledge at the BS is available. [5] Investigated and analyzed channel instance estimation with RIS assistance for MISO channels. However, for fast fading channels, obtaining accurate channel estimates requires significant overhead and may not be practical.
In this work, we assume that BS only knows the channel covariance of UE and its rate of change is much slower than that of channel instances. Unlike [5], we apply unsupervised neural networks to optimize all UEs' BS beamforming and transmission power, including those with RIS assistance and those without. The training of the network is based on the optimal structure of the transmitted beam for a rank-one channel covariance matrix, which occurs when the channel to the UE is very sparse. In this environment, the total rate of all UEs proposed by our BNN is higher than that of zero-forcing beamforming with watermark power allocation. When the number of UEs approaches the number of transmit antennas in the BS or when the system load is heavy, there is a significant difference in throughput. From numerical examples with 10 UE and 10 BS antennas, the rate gain can be as high as 100% for a medium SNR of 10 dB. The computation time of BNN algorithm is much lower than that of the zero-forcing beamforming algorithm, especially when the system scale is large.
Article illustrations
Conclusion: Our proposed BNN only utilizes the channel covariance of UE, which is not frequently changing, thus the transmit beam does not need to be updated frequently. When the UE channels are sparse and have rank-1 covariance, the BNN outperforms the ZF scheme. In a reloading system where the number of UEs is close to the number of antennas at the BS, the sum rate gain on ZF is quite evident. The complexity of the BNN is proven to be significantly lower than that of ZF. Future work includes improving the channel covariance of the BNN with ranks greater than 1 and joint optimization of the transmit beam with RIS elements.
Code List

## Images

![[RIS+ Beamforming] Reconfigurable Intelligent Surface-Assisted MISO Downlink Channel Covariance Optimization Beamforming [with code]](01.jpg)
![[RIS+ Beamforming] Reconfigurable Intelligent Surface-Assisted MISO Downlink Channel Covariance Optimization Beamforming [with code]](02.jpg)
![[RIS+ Beamforming] Reconfigurable Intelligent Surface-Assisted MISO Downlink Channel Covariance Optimization Beamforming [with code]](03.jpg)
![[RIS+ Beamforming] Reconfigurable Intelligent Surface-Assisted MISO Downlink Channel Covariance Optimization Beamforming [with code]](04.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
