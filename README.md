# Coffee_machine
# stage 1
# Write your code here
print('Starting to make a coffee')
print('Grinding coffee beans')
print('Boiling water')
print('Mixing boiled water with crushed coffee beans')
print('Pouring coffee into the cup')
print('Pouring some milk into the cup')
print('Coffee is ready!')

# stage 2
# Write your code here for calculator
print('Write how many cups of coffee you will need:')
n = int(input())
print('For 125 cups of coffee you will need:')

print(str(n * 200) + 'ml of water')

print(str(n * 50) + 'ml of milk')

print(str(n * 15) + 'g of coffee beans')

#stage 3
# Write your code here
print('Write how many ml of water the coffee machine has:')
water = int(input())
print('Write how many ml of milk the coffee machine has:')
milk = int(input())
print('Write how many grams of coffee beans the coffee machine has:')
beans = int(input())
print('Write how many cups of coffee you will need:')
cups = int(input())
water_cups = int((water - cups*200) // 200)
milk_cups = int((milk - cups*50) // 50)
beans_cups = int((beans - cups*15) // 15)
m = min(int(beans_cups), int(milk_cups), int(water_cups))
p = min(water // 200, milk // 50, beans // 15)
if(water // cups > 400 // 1 and (milk // cups > 100 // 1) and (beans // cups > 30 // 1)):
    print('Yes, I can make that amount of coffee and even ' + str(m) + ' more than that')
elif (water // cups > 200 // 1) and (milk // cups > 50 // 1) and (beans // cups > 15 // 1):
    print('Yes, I can make that amount of coffee ')
elif (water // cups < 200 // 1) or (water // cups < 50 // 1) or (beans // cups < 15 // 1):
    print('No, I can make only ' + str(p) + 'cups of coffee')
    
    
