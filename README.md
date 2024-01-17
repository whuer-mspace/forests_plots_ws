# forests_plots_quadrotor_autonomous-exploration

Given the scarcity of high-precision and high-fidelity forest simulation data in the realm of UAV autonomous forest exploration, we employ a Terrestrial Laser Scanner (TLS) with millimeter-level accuracy to capture extensive data from both artificial and natural forests. The point cloud data we have made openly available encompasses four different scenarios, including both artificial and natural forest point clouds. This authentic forest point cloud data is used to create a high-fidelity simulation model. "We've publicly released high-quality point cloud simulation models. However, due to GitHub's 25MB data upload limit, the ones available under 'map_generator/resource/' are downsampled, lower-quality point cloud simulation models. For the higher-quality point cloud simulation models, please use the following link to download them from Baidu Cloud:

Link：https://pan.baidu.com/s/1yuqRLsZSF0jOdis30nckaA?pwd=d1tb 

Extraction code：d1tb

# A Leica RTC 360 Terrestrial Laser Scanner (TLS) with millimeter-level accuracy
![RTC360](https://github.com/whuer-mspace/forests_plots_ws/assets/44198932/055b0c2d-a3fe-4fb0-a802-9f6a9901abce)

# A self-developed quadrotor platform with autonomous flight and exploration functions

![haibao](https://github.com/whuer-mspace/forests_haep_ws/assets/44198932/db5422e6-a303-4f73-92a1-fefd06c36cc6)


# Forests Plot

![image](https://github.com/whuer-mspace/forests_plots_ws/assets/44198932/40549205-9b50-451d-bbfc-79fb503cace1)


In the past two decades, forestry survey methods have seen unprecedented advancements, thanks to the flourishing of close-range sensing platforms. These platforms primarily encompass static, mobile, terrestrial, and unmanned aerial systems. However, research on achieving fully autonomous drone flights for forestry surveys in the under-canopy environment is just beginning. The forest environment poses a typical complex scenario, especially beneath the canopy, where high-precision global navigation systems fail to provide reliable positioning services. Achieving efficient fully autonomous exploration by drones in such conditions is a challenging task.

The first hurdle to overcome is the high-precision positioning problem for drones in this scenario. Additionally, an outstanding motion planner is required for real-time obstacle avoidance to ensure the drone's safety. The video introduces the latest work from the Multi-source Perception and Cognition Team at Wuhan University, which has successfully achieved efficient under-canopy drone autonomous exploration for forestry survey data collection.

Our quadrotor autonomous exploration field experiments in forests can be found at https://youtu.be/tRm9xuXOqBc.

The simulation code utilizes [MARSIM](https://github.com/hku-mars/MARSIM.git). Please thoroughly review the [MARSIM](https://github.com/hku-mars/MARSIM.git) code configuration for using this publicly available dataset.

## Acknowledgments

We thank the excellent [MARSIM](https://github.com/hku-mars/MARSIM.git) simulation platform and [FUEL](https://github.com/HKUST-Aerial-Robotics/FUEL.git)!
