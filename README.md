# About-Ivo
Sobre mí un poco lo que quiero hacer.

```python
class Developer:
    def __init__(self, name, interests, goals):
        self.name = name
        self.interests = interests
        self.goals = goals
        self.challenges_completed = 0
    
    def code(self):
        print(f"{self.name} está programando 🧑‍💻")
    
    def create_bot(self):
        print("Creando un bot innovador... 🤖")
    
    def solve_challenge(self, platform):
        print(f"Resolviendo retos en {platform}... 💡")
        self.challenges_completed += 1
        print(f"¡Desafío superado! Número total de desafíos completados: {self.challenges_completed} 🏆")
    
    def show_interests(self):
        print(f"Intereses: {', '.join(self.interests)}")
    
    def share_goals(self):
        print(f"Metas: {', '.join(self.goals)}")

# Crear una instancia para Ivo
ivo = Developer(
    "Ivo",
    ["programación", "crear bots"],
    ["superar retos en Edabit"]
)

# Ivo inicia su día
ivo.show_interests()
ivo.code()
ivo.create_bot()
ivo.solve_challenge("Edabit")
ivo.share_goals()
```
