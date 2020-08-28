# stormbreaker
fb login bot
from selenium import webdriver
browser=webdriver.Chrome('C:\\chrome\\chromedriver.exe')
browser.get('https://www.facebook.com/')
e=browser.find_element_by_id("email")
e.send_keys("enter your phone number or email")
d=browser.find_element_by_id("pass")
d.send_keys("enter your password btw this")
log=browser.find_element_by_id("u_0_b")
log.click()
