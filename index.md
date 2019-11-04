# Termux dictionary
## How to install dictionary in termux

### For installation of termux dictionary
just copy and paste the following command.

```
git clone https://github.com/kcubeterm/Termux_Dictionary

cd Termux_Dictionary

chmod +x dic

chmod +x install.sh

./install.sh

```

I hope after putting above code you got a dictionary in termux. 
If everything is right then put `dic -h` then you can see the help manual for dictionary. 
Let's go for some example about it. 

```
$dic god

God
God  n. 1 a (in many religions) superhuman 
being or spirit worshipped as having
 power over nature, human fortunes, 
etc. B image, idol, etc., symbolizing
 a god. 2 (god) (in christian and 
other monotheistic religions) creator
 and ruler of the universe. 3 adored
 or greatly admired person. 4 (in pl.) 
Theatr. Gallery.  god forbid may it not happen! God knows
 1 it is beyond all knowledge. 2 i call god to witness that.
 God willing if providence allows. [old english]
```

![example screenshot](https://kcubeterm.github.io/termux.github.io/Screenshot_2019-09-2505-27-197_com.termux.PNG)

Second example with `-p` option


When you search word with `-p` it means
dictionary tell whole pronounciation of matched word

For this make sure you have termux API installed in your termux

