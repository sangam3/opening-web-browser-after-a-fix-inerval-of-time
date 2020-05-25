# opening-web-browser-after-a-fix-inerval-of-time
# this is my first project with web browser and time.
# Sangam Prashar EEE
# sangamprashar3@gmail.com

import time
import webbrowser

# total numbers of breaks are 5
total_breaks = 6

#initiated from zero
break_count =0

#defining function
def a():
    return 'It is your'

# printing the starting time of thr program
print('This program is started on' +time.ctime())

while(break_count < total_breaks):

    if break_count == 0:
        time.sleep(60) #first break
        print(a(),'first break')
        webbrowser.open('https://www.youtube.com/')
        break_count +=1

        if break_count == 1:
            time.sleep(60) #second break
            print(a(),'second break')
            webbrowser.open('https://www.youtube.com/')
            break_count +=1

            if break_count == 2:
                time.sleep(60) #third break
                print(a(),'third break')
                webbrowser.open('https://www.youtube.com/')
                break_count +=1

                if break_count == 3:
                    time.sleep(60) #forth break
                    print(a(),'forth break')
                    webbrowser.open('https://www.youtube.com/')
                    break_count +=1

                    if break_count == 4:
                        time.sleep(10) #forth break
                        print(a(),'forth break')
                        webbrowser.open('https://www.youtube.com/')
                        break_count+=1

                        if break_count == 5:
                            time.sleep(60) #last break
                            print(a(),'last break')
                            webbrowser.open('https://www.youtube.com/')
                            break_count+=1

#end of program
print('End of the program')
