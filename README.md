# paradigma
project

>>> class Person: // nama class yang dibuat
	def __init__(self, name, age): 
		self.name = name
		self.age = age

		
>>> p1 = Person("John", 36)
>>> print(p1.name)
John
>>> print(p1.age)
36
>>> 
// syntax diatas merupakan syntax untuk membuat class dengan nama Person. dimana kelas tersebut memiliki
fungsi init () untuk menetapkan nilai ke properti objek, atau operasi lain yang perlu dilakukan ketika objek sedang dibuat. 
pada syntax diatas fungsi tersebut meliputi name dan age.Sementara self pada syntax merupakan pendeklarasian atas nama kelas itu sendiri.
p1 merupakan variabel.
perintah print digunakan untuk menampilkan hasil dari objek yang dipanggil.




>>> class Complex:
	def __init__(self, realpart, imagpart):
		self.r = realpart
		self.i = imagpart

		
>>> x = Complex(3.0, -4.5)
>>> x.r, x.i
(3.0, -4.5)

//syntax diatas merupakan syntax untuk membuat class dengan nama Complex. dimana kelas tersebut memiliki
fungsi init () untuk menetapkan nilai ke properti objek, atau operasi lain yang perlu dilakukan ketika objek sedang dibuat. 
pada syntax diatas fungsi tersebut meliputi realpart dan imagpart.Sementara self pada syntax merupakan pendeklarasian atas nama kelas itu sendiri.
r dan i merupakan variabel.
perintah x digunakan untuk menampilkan hasil dari objek yang dipanggil.








>>> class Dog:
	kind = 'canine'
	def __init__(self, name):
		self.name = name

		
>>> d = Dog('Fido')
>>> e = Dog('Buddy')
>>> d.kind
'canine'
>>> e.kind
'canine'
>>> d.name
'Fido'
>>> e.name
'Buddy'

d = Dog('Fido')
