# userChrome
Ultra-minimalist userChrome.css Firefox theme

<details>

<summary>Preparation for Installation (Enabling Firefox Custom CSS)</summary>

1.Open a new tab in Mozilla Firefox.

2.Type ```
about:config
``` in the address bar. Confirm that you will be careful if a warning message appears for you.


3. Enter the following text in the search 
```
box: toolkit.legacyUserProfileCustomizations.stylesheets
```
4.Set the option to True

</details>

<details>

<summary>Locating Chrome folder.</summary>
* Windows 
```C:\Documents and Settings\XXXXXXX\Application Data\Mozilla\Firefox\Profiles\
```




* Linux
```/home/XXXXXXX/.mozilla/firefox/```
(CTR + H to make hidden folders in your home directory appear)

Locate file labelled with the .default-release or .default extension and navigate inside. If there exists no folder named "chrome" then create it yourself and then either paste the userChrome.css directly in there or create a file named that and copy paste the code contained within the userChrome.css of this repository
</details>
