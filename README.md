# 9.1-additional

class Cellphone:
    def __init__(self):
        self.manufact = "none"
        self.model = "none"
        self.retail_price = 0
    def set_manufact(self, manufact):
        print("Manufacturer: %s" %(self.manufact))
    def set_model(self, model):
        print("Model Number: %s" %(self.model))
    def set_retail_price(self, retail_price):
        print("Retail Price: %s" %(self.retail_price))
    def get_manufact(self, manufact):
        return self.manufact
    def get_model(self, model):
        return self.model
    def get_retail_price(self, retail_price):
        return self.retail_price

if __name__ == "__main__":
    manufacturer = input("Enter the manufacturer: ")
    model_number = input("Enter the model number: ")
    retail_pricee = float(input("Enter the retail price: "))
    print("Here is the data you entered:")
    manufact1 = Cellphone()
    manufact1.manufact = manufacturer
    manufact1.model = model_number
    manufact1.retail_price = retail_pricee
    print("Manufacturer: %s" %(manufacturer))
    print("Model Number: %s" %(model_number))
    print("Retail Price: $%0.2f" %(retail_pricee))
