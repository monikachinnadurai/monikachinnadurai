print(' Hospital')
class Hospital:
	def __init__(self,name,age,diseases,city):
		self.name=name
		self.age=age
		self.diseases=diseases
		self.city=city
#__str__method		
	def __str__(self):
		patient=f"Name:{self.name}\nAge:{self.age}\nSuffering from:{self.diseases}\nPlace:{self.city}"
		return patient
#__repr__ method		
	def __repr__(self):
		patient= f"Hospital(Name:{self.name}\nAge:{self.age}\nSuffering from:{self.diseases}\nPlace:{self.city})"
		return patient
		
p=Hospital("Krish","60","chicken pox","Trichy")
print(p)

print([p])
