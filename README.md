# rcal

# 🏛️ RCAL Roman Calendar

**RCAL** is a lightweight, interactive, and fully client-side web application designed to generate and explore the ancient Roman calendar. Built with pure HTML, CSS, and JavaScript, it allows users to view the calendar in various historical formats, convert Gregorian dates to Roman dates, and print visually appealing, highly-customizable historical calendars.

⚠️ **Status:** *Work in Progress (Under active development)*

## ✨ Features

* **Flexible Views:** View the calendar in 1-Month, 3-Month, or Full-Year (12 months) modes.
* **Gregorian ➔ Roman Converter:** A built-in tool to instantly translate modern Gregorian dates into the Roman dating system (Kalends, Nones, Ides).
* **Print Optimized:** Includes custom CSS for printing. It automatically switches to a clean, black-and-white, ink-saving layout perfectly scaled for A4 paper.
* **URL Sync:** Your active settings, year, and month are automatically saved in the URL, making it easy to bookmark or share specific calendar views with others.
* **Dark/Light Mode:** Seamlessly switch between themes for comfortable viewing.

## 🎛️ Toggles & Options

The calendar is highly customizable. You can toggle the following historical elements on or off:

* **Q/S Months:** Changes the names of July and August back to their original pre-Julian names: *Quintilis* and *Sextilis*.
* **Roman Days:** Converts the modern Arabic numbers (1, 2, 3...) into Roman numerals (I, II, III...).
* **Roman Year:** Displays the current year using Roman numerals.
* **Fasti:** Displays the legal status of the day (*F, C, NP*). 
* **Nundinal:** Displays the 8-day Roman market cycle letters (A through H).
* **Events:** Shows major fixed Roman festivals (*Feriae Stativae*) such as the Saturnalia, Lupercalia, and Lemuria.
* **AUC (Ab Urbe Condita):** Adjusts the year to count from the mythical founding of Rome (753 BC) instead of the AD/BC system.
* **Era:** Displays the historical period or the ruling Emperor for the selected year (e.g., Roman Republic, Augustus, Trajan).

## ⌨️ Keyboard Shortcuts

Navigate and toggle options quickly using the following keyboard shortcuts (disabled while typing in input fields):

* `M` : Cycle through viewing modes (1, 3, or 12 months)
* `C` : Toggle the Converter panel
* `Q` or `S` : Toggle Q/S Months
* `D` : Toggle Roman Days
* `Y` : Toggle Roman Year
* `F` : Toggle Fasti
* `N` : Toggle Nundinal letters
* `E` : Toggle Events / Festivals
* `A` : Toggle AUC year format
* `R` : Toggle historical Era / Emperor
* `T` : Toggle Theme (Light / Dark mode)
* `P` : Open Print dialog

## 🚀 How to Run

Since RCAL is a purely client-side application with no external dependencies or backend, installation is incredibly simple:

1. Clone or download this repository.
2. Open the `index.html` file in any modern web browser.
3. Enjoy!

## 📜 Disclaimer & Historical Accuracy

This software is provided "as is", without warranty of any kind. **The author assumes no responsibility or liability for any errors, omissions, or historical inaccuracies in the generated calendars or conversions.**

**Please note:** * The **Fasti days** and **Nundinal letters** provided by this application are mathematical/historical **approximations**. 
* The ancient Roman calendar, especially prior to the Julian reform in 45 BC, was heavily subject to pontifical intercalation and political manipulation. Therefore, achieving absolute, day-to-day historical accuracy for the deep past is nearly impossible. 
* This tool is intended for entertainment purposes.

## 🤝 Contributing

As this project is a Work in Progress, suggestions, bug reports, and pull requests regarding historical corrections or code optimizations are highly welcome!
