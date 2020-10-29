class Worker:
      def __init__(self, name, salary, birthday):
          self.__name = name
          self.__salary = salary
          self.__birthday = birthday
      def get_name(self):
          return self.__name
      def set_name(self, n ):
          return self.__name
      def set_salary(self, s):
          self.__salary = s 
      def set_birthday(self, b):
          self.__birthday = b

w1 = Worker("Иван", 20.000, 1995)
n1 = "Иван"
s1 = 20.000
b1 = 1995

print("Работник", n1,  2020 - b1, "лет")
print((b1 + 50 - 2020) * 365, "дней до 50 лет")
