#Initialize Parameters
cur_x = 2
rate = 0.01
precision = 0.000001
previous_step_size = 1
max_iters = 1000
iters = 0
df = lambda x : 2 * (x + 3) #Gradient of our function i.e (x + 3)²
#Run a loop to perform gradient Descent
while previous_step_size > precision and iters < max_iters:
    prev_x = cur_x
    cur_x -= rate * df(prev_x)
    previous_step_size = abs(prev_x - cur_x)
    iters += 1
print("Local Minima Occurs at :",cur_x)
