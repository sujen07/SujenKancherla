
## About Me

I enjoy programming and learning about the latest AI developments, and in my free time I play soccer and basketball

### Projects

- [AI Chess and Tic Tac Toe Player](github.com/sujen07/minimax-ai-player)
- Image Resolution Enhancer

## Interests

- AI Development
- Playing Soccer
- Watching Basketball

## Skills

- Python
- TensorFlow
- PyTorch


## Sample Neural Network
```python
class SimpleNeuralNetwork(nn.Module):
    def __init__(self, input_size, hidden_size, num_classes):
        super(SimpleNeuralNetwork, self).__init__()
        self.layer1 = nn.Linear(input_size, hidden_size) 
        self.layer2 = nn.Linear(hidden_size, num_classes)  

    def forward(self, x):
        x = F.relu(self.layer1(x))
        x = self.layer2(x)
        return x
```

### Me in my Prime

- ![Soccer Picture](sujen_soccer.jpg)

## To-Do List

- [x] Start a new AI project
- [ ] Watch the champions league
- [ ] Play basketball with friends

