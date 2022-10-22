# Sentinal-1_data_to_RGB

RGB combination to convert Sentinal-1 data to RGB:

red=VV
green=VH
blue=VV/VH


But If you work with log-scaled data (in dB) it is slightly different because the laws of logarithms which turn ratios into subtraction:

red=VV
green=VH
blue=VV - VH

since the data i got is in db i use the second combination.
