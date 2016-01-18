# conky-quotes
Conky minimalistic monitor with custom quotes.

# Usage
Just download the `conkyrc` file and run this command on terminal:
```
cd ~/Downloads
cp conkyrc ~/.conkyrc
```

# Quote
In order to change your favorite quote, just edit the `~/.conkyrc` file with your custom quote:
```
${font Dosis:light:size=12}${alignr}"Your custom quote here"$font
${font Dosis:light:size=16}${alignr}Author
```

# Display
Change `minimum_size` and `maximum_width` with your own display values:
```
minimum_size 1890 1
maximum_width 1890
```

# Ethernet
You also need to change the network device with your own values:
```
${font Dosis:bold:size=10} DOWNLOAD $font ${downspeed enp7s0}/s (${totaldown enp7s0}) \
${font Dosis:bold:size=10} UPLOAD $font ${upspeed enp7s0}/s (${totalup enp7s0}) \
```
