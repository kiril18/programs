import pyowm

owm = pyowm.OWM('819b27ac0e16c4367ceb7f8cfd5343ed')  

observation = owm.weather_at_place('Михнево')
w = observation.get_weather()
temperature = w.get_temperature('celsius')["temp"]

my_file = open("temp.txt", "w")
my_file.write(str(round(temperature)) + "t")  
my_file.close()	
