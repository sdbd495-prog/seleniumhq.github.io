from selenium import webdriver
import time

driver = webdriver.Chrome()
driver.get("https://app.expertoption.com")

print("سجّل دخولك يدويًا")
time.sleep(30)  # وقت كافي لتسجيل الدخول

