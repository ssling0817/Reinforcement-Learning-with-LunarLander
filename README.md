# Reinforcement-Learning-with-LunarLander
### Model design description

1. Q network - policy network, used to map state -> action probability, composed with three fc layers.

2. Replay buffer - used to store experience, implemented by deque structure.

3. agent - used to interact with environment and learn, contains local Q network and target Q network.
