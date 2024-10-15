# Home-Made CNC Milling Machine

## Introduction

This project showcases the design and construction of a home-made CNC milling machine built from scratch. The goal was to create a compact, powerful, and cost-effective CNC machine capable of milling aluminum and handling steel at low speeds.

## Project Videos

-   [Test Video 1](https://www.youtube.com/watch?v=3Vvp7R3YsTk)
-   [Test Video 2](https://youtu.be/EtHsFKGwShk)

## Requirements

-   **Size**: Approximately 50cm x 50cm x 50cm
-   **Power**: Capable of milling aluminum and handling steel at low speeds
-   **Control**: CNC capabilities
-   **Budget**: Around €500

## Components

### Mechanical Components

-   **Base**: Used base from an old Polish WS15 drill
    
    -   Robust and heavy with M14 mount holes and T-slot
    -   Weight: ~30 kg
    -   **Price**: €50
    
-   **Cross Table**
    
    -   Brand new from China
    -   Travel Range: X = 100 mm, Y = 201 mm
    -   Weight: 36 kg
    -   **Price**: €150
    
-   **Column and Z-Axis Assembly**
    
    -   Aluminum column PA6 80x80x450 mm
    -   Plates for Z-axis
    -   Lead screw 16x4 mm
    -   **Price**: €80
    
-   **Pulleys and Belts**
    
    -   2x Pulleys 14 5M 15
    -   2x Pulleys 28 5M 15
    -   Belt HTD 450 5M 15
    -   Belt HTD 375 5M 15
    -   **Price**: €25
    
-   **Miscellaneous Mechanical Parts**
    
    -   Screws, linear rods, bushings
    -   **Price**: Included in miscellaneous expenses

### Electrical Components

-   **Stepper Motors**
    
    -   2x NEMA 23, 3 Nm (new)
        -   **Price**: €60
    -   1x NEMA 23, 1.8 Nm (used)
        -   **Price**: €10
    
-   **CNC Controller Kit**
    
    -   3-axis stepper driver controller TB6600
    -   **Price**: €45
    
-   **Spindle**
    
    -   Used Kress 1050 FME
    -   **Price**: €60
    
-   **Power Supply**
    
    -   24V, 4.2A
    -   **Price**: Included in miscellaneous expenses
    
-   **Control Box**
    
    -   Metal case with 2 DIN rails, 314x396x130 mm
    -   **Price**: €20
    
-   **Computer and Monitor**
    
    -   Used HP terminal
        -   512 MB RAM, 1.2 GHz CPU
        -   USB stick as hard drive
    -   LCD Screen 17"
    -   **Price**: €30
    
-   **Miscellaneous Electrical Parts**
    
    -   Buttons, cables
    -   **Price**: Included in miscellaneous expenses

## Construction Overview

### Base and Frame

The foundation of the milling machine is the heavy-duty base from a WS15 drill, providing stability and rigidity. The aluminum column supports the Z-axis and spindle, ensuring precision during operation.

### Motion System

The X and Y axes utilize the cross table from China, driven by NEMA 23 stepper motors connected via pulleys and belts. The Z-axis is assembled using custom plates, a lead screw, and is powered by another NEMA 23 stepper motor.

### Electronics and Control

The stepper motors are controlled by a TB6600 3-axis driver, housed in a metal case with DIN rails for organization. The system is powered by a 24V power supply.

### Spindle

The Kress 1050 FME spindle offers sufficient power for milling aluminum and steel at low speeds.

### Computer and Software

An HP terminal serves as the controller, running CNC software to interpret G-code and control the machine.


## How to Replicate

1.  **Gather Components**: Refer to the components list to acquire all necessary parts.
2.  **Assemble Mechanical Parts**: Build the base, frame, and motion system.
    
3.  **Set Up Electronics**: Install the stepper motors, driver, and power supply.
    
4.  **Install Software**: Configure the HP terminal with CNC control software (e.g., LinuxCNC).
    
5.  **Calibration**: Calibrate the axes and spindle to ensure precision.
    
6.  **Testing**: Run test programs to verify functionality.
    

## Resources

-   **Videos of the Machine in Action**
    -   [Test Video 1](https://www.youtube.com/watch?v=3Vvp7R3YsTk)
    -   [Test Video 2](https://youtu.be/EtHsFKGwShk)

## Future Improvements

-   Upgrading the spindle for higher torque
-   Implementing limit switches for safety
-   Enhancing the control software interface
-   Adding an enclosure for dust and noise reduction

## License

This project is open-source and available under the MIT License.

## Contact

For questions or contributions, please open an issue or submit a pull request.

[![Watch the video](https://youtu.be/EtHsFKGwShk)](https://youtu.be/EtHsFKGwShk)

### [Little nail - concept](https://little-nail.blogspot.com/2015/08/little-nail-concept.html)

Several times I have suffered because lack of milling machine in my little toolshop. A few month ago the time came to change this. Requirements were quite simple:  
- it has to be relatively small - ~50x50x50cm  
- it has to be quite powerfull - mill alloy and be able to handle steel at low speeds  
- it has to be CNC machine  
- it has to be cheap - round 500 euro  
  
Components:  
  
- used base from old, very good Polish drill WS15 - very robust and heavy with M14 mount holes and t-slot, weight ~30KG: price 50 euro  
  

[![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhzM-Y2v5iljNB-lXq6JpANpPdyPnDjSfHMRZhPvWzM_EYJ_TI-4OMtsCtP_KevsxTiadu1XbxZZOIkiTRf6KQ5dlDcj6X60xH5hmngHErP7lPRM_fOfpkyKgBqKE709n_Aq5z-44giM3lI/s1600/base.jpg)](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhzM-Y2v5iljNB-lXq6JpANpPdyPnDjSfHMRZhPvWzM_EYJ_TI-4OMtsCtP_KevsxTiadu1XbxZZOIkiTRf6KQ5dlDcj6X60xH5hmngHErP7lPRM_fOfpkyKgBqKE709n_Aq5z-44giM3lI/s1600/base.jpg)

  
  
  
  
  
  
  
  
  
  
  
  
  
- brand new cross table from China - Range X = 100, Y=201, weight 36KG, price 150 euro:  
  
  

[![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjsB3_Gzp5sePn2zpbzM8n6_HbS7JnRCiSkHlQY5jH8KeiGQr-MuLt3arm3jjhz88fxM5cQBnva5-Jc_7t4bOL9sltiYVK2zHyvWuoThl0DPrW18_oxo_deQBM6MC5C7FusE5Mrx4mFfQ4o/s320/stk_495x165_zdjwym_1.jpg)](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjsB3_Gzp5sePn2zpbzM8n6_HbS7JnRCiSkHlQY5jH8KeiGQr-MuLt3arm3jjhz88fxM5cQBnva5-Jc_7t4bOL9sltiYVK2zHyvWuoThl0DPrW18_oxo_deQBM6MC5C7FusE5Mrx4mFfQ4o/s1600/stk_495x165_zdjwym_1.jpg)

  

[![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEg5LIZkaw79CDvRwDjrz-E8PE_tM3quAHnNuYe3VESAS7WIoPCJLr3O8hg02YQ17YcuHPrGp0IKHkwfwCTFKrChX9G8vwcvs7F8J9K0PNzlY6OwPsJOX8L1Sefc2BkHr1TzaWdUA0hNZyQ4/s200/stk_495x165_zdjwym_2.jpg)](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEg5LIZkaw79CDvRwDjrz-E8PE_tM3quAHnNuYe3VESAS7WIoPCJLr3O8hg02YQ17YcuHPrGp0IKHkwfwCTFKrChX9G8vwcvs7F8J9K0PNzlY6OwPsJOX8L1Sefc2BkHr1TzaWdUA0hNZyQ4/s1600/stk_495x165_zdjwym_2.jpg)

  

[![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhtpFoysjoCSJKixv9otpLxhkgtG17cRnQREMlZgow6nmztQ1b0cdIo2-SNnLK05fvQSKbN7KhRis-l29fbTjsk2FYNNDEsBggL2pdmiVCBWs8W5g7Wu_9mkklk38pO5nPa36t3_RmTkeKW/s320/stk_495x165_zdjwym_3.jpg)](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhtpFoysjoCSJKixv9otpLxhkgtG17cRnQREMlZgow6nmztQ1b0cdIo2-SNnLK05fvQSKbN7KhRis-l29fbTjsk2FYNNDEsBggL2pdmiVCBWs8W5g7Wu_9mkklk38pO5nPa36t3_RmTkeKW/s1600/stk_495x165_zdjwym_3.jpg)

  

[![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjUKlpApuoNQE1g7f3nsbkNq9vIVg4d3Vm9zikMbJmwnGCgXwauNwQ1JSf9R95GNGoiljSXll-UoW91R_WK_QZi883wUSLF9habdYRG63iONWCUzMsm_zeI72BJ5J7cyAjrwVHWWeWW_C9F/s320/stk_495x165_zdjwym_4.jpg)](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjUKlpApuoNQE1g7f3nsbkNq9vIVg4d3Vm9zikMbJmwnGCgXwauNwQ1JSf9R95GNGoiljSXll-UoW91R_WK_QZi883wUSLF9habdYRG63iONWCUzMsm_zeI72BJ5J7cyAjrwVHWWeWW_C9F/s1600/stk_495x165_zdjwym_4.jpg)

  

[![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiLwbLohofxv8eTYzFQA5OtNKvuEto3LhmnyLw-OW3eHF9trq80g1CKI9665z3rP5esmJpcLyIWYeZuqvI3Tr17JxsloGR3jdWpDUAfLcw6uKYsx1DkyDFJG7YlllEf6BQyaUVaStWp0gp9/s320/stk_495x165_zdjwym_5.jpg)](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiLwbLohofxv8eTYzFQA5OtNKvuEto3LhmnyLw-OW3eHF9trq80g1CKI9665z3rP5esmJpcLyIWYeZuqvI3Tr17JxsloGR3jdWpDUAfLcw6uKYsx1DkyDFJG7YlllEf6BQyaUVaStWp0gp9/s1600/stk_495x165_zdjwym_5.jpg)

  

[![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhNM9bICLXWY0vtRQhWoq4UNNjFYOGGpb5IayyphcS1KVbZLbs_9r4dpoJHdQEtuCImyyVvPa54Qt_Z_jUEX4FUR4c-SQdYPlSjzcE-QD6yl2bxkR34z07JlixFoV1XYUDiXHdllDSa2F5x/s320/stk_495x165_zdjwym_6.jpg)](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhNM9bICLXWY0vtRQhWoq4UNNjFYOGGpb5IayyphcS1KVbZLbs_9r4dpoJHdQEtuCImyyVvPa54Qt_Z_jUEX4FUR4c-SQdYPlSjzcE-QD6yl2bxkR34z07JlixFoV1XYUDiXHdllDSa2F5x/s1600/stk_495x165_zdjwym_6.jpg)

  

  
- new 2 x stepper motors - nema 23, 3NM price 60 euro, used 1 x nema 23 1.8 NM Price 10 Euro:  
  

[![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjagdVPV0fbGEPd1JrfLWdFbWg2Yor6_e_X-Vy4ve42EbKpb2b33AVZQxedjLykOZxVKdykNSQsA5yjDz4aahAEJ14JXpdmzuU0wlUpti1gHT11GCSLRiOhMBaVSqmv98aFWcEn149GZvo9/s320/steppers.jpg)](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjagdVPV0fbGEPd1JrfLWdFbWg2Yor6_e_X-Vy4ve42EbKpb2b33AVZQxedjLykOZxVKdykNSQsA5yjDz4aahAEJ14JXpdmzuU0wlUpti1gHT11GCSLRiOhMBaVSqmv98aFWcEn149GZvo9/s1600/steppers.jpg)

  
  
- right from China CNC Kit 3 Axis Stepper Driver Controller TB6600, price 45 Euro:  
  

[![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEi6oIuHNWMAPv-AGSC_bSRN36MwpI1jxgqOJk3fenv4Rl_sLKneKk0yVnlwnwWBafadfUAIaJN3gSW7_06kQ9VhxqHgayPU3xxysRYnspll3O0oAthqgdwammorS9BRxz4NUbgWKBnVP0yq/s1600/CNC-Kit-3-Axis-Stepper-Driver-Controller-TB6600-5A-Stepping-Motor-Driver-Board-Aluminum-Box-with.jpg_220x220.jpg)](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEi6oIuHNWMAPv-AGSC_bSRN36MwpI1jxgqOJk3fenv4Rl_sLKneKk0yVnlwnwWBafadfUAIaJN3gSW7_06kQ9VhxqHgayPU3xxysRYnspll3O0oAthqgdwammorS9BRxz4NUbgWKBnVP0yq/s1600/CNC-Kit-3-Axis-Stepper-Driver-Controller-TB6600-5A-Stepping-Motor-Driver-Board-Aluminum-Box-with.jpg_220x220.jpg)

  
  
  
- used Kress spindle 1050 FME, Price 60 Euro  

[![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgv-72jybcY_598I-06_rzsFb5reQ1cRxFmLcT3nX_GMMaAWGKFyPNxKZIVNrkp4LEPwuN8oRox8IvjC3KNg51N8BTIlErUQhUyPrPqqJYUG_5YF8w0CZH6FWae2WVbkRjg4iadBhUahfPi/s320/kress.jpg)](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgv-72jybcY_598I-06_rzsFb5reQ1cRxFmLcT3nX_GMMaAWGKFyPNxKZIVNrkp4LEPwuN8oRox8IvjC3KNg51N8BTIlErUQhUyPrPqqJYUG_5YF8w0CZH6FWae2WVbkRjg4iadBhUahfPi/s1600/kress.jpg)

  
  
- metal case with 2 din rails, 314x396x130 mm, Price 20 Euro  
  

[![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhO5No7yggSmiScdZGXo9kTjVdq5G0qMQaTrhU_XXzl4CStXaW1qtn8pobNz3vIf5NMzN-UfzdoM4sqjDBE1Z-If0Au2WImSMtWWpM8Z1oEMwzS78YlKhAMCb3i_k5RO3G8F5hgFM1m8Xtp/s320/case.jpg)](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhO5No7yggSmiScdZGXo9kTjVdq5G0qMQaTrhU_XXzl4CStXaW1qtn8pobNz3vIf5NMzN-UfzdoM4sqjDBE1Z-If0Au2WImSMtWWpM8Z1oEMwzS78YlKhAMCb3i_k5RO3G8F5hgFM1m8Xtp/s1600/case.jpg)

  
  
- used HP terminal 512MB ram, 1,2 GH CPU, usb stick as harddrive and lcd screen 17' price 30 Euto  

[![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhe7t1VnQ3zYHvSPyrp8mORGxYFiidHXOjmA9HK29UBMcP7kS4eSD5tXOGIHrqk3BzvYQMMufCqI4sPH2gs0RCGcw6H1FQxtlUWo5EOMG-4uT7LErVYIwC69Rct0oXGoAlFr9IRVbAJAGs4/s320/terminal.jpg)](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhe7t1VnQ3zYHvSPyrp8mORGxYFiidHXOjmA9HK29UBMcP7kS4eSD5tXOGIHrqk3BzvYQMMufCqI4sPH2gs0RCGcw6H1FQxtlUWo5EOMG-4uT7LErVYIwC69Rct0oXGoAlFr9IRVbAJAGs4/s1600/terminal.jpg)

  
- power supply 24v 4.2A  

[![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgg2d00Nx1IVenksKimQ9jbz68efKn9_SiDEKycQApuG2M661JkPGtaja7BscBM0oHYzyt5goz2q-NVrvq7DrvO94Dm2KwQAb3_JRX7fHzxghfIDD3Sn_cp0MDk5fckuTg78Jra5IvdRdv8/s320/power_supply.jpg)](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgg2d00Nx1IVenksKimQ9jbz68efKn9_SiDEKycQApuG2M661JkPGtaja7BscBM0oHYzyt5goz2q-NVrvq7DrvO94Dm2KwQAb3_JRX7fHzxghfIDD3Sn_cp0MDk5fckuTg78Jra5IvdRdv8/s1600/power_supply.jpg)

  
  
- pulleys and belts htd-5m - 2xPulleys 14 5M 15, 2xPulleys 28 5M 15, Belt HTD 450 5M 15, Belt HTD 375 5M 15 Price 25 Euro  
  

[![](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjbgSw8TABDt1R9n7VZd1T5ZWXw7RI9GyfBizyoBFpndBl0ExyRTOSNxCt-7cpDrptpUXFTRPdJb-ejYlHLoQqzpkzYWzWaEMcO0nrjASLE2t09v6zJrDOq9sihqtsFGvbfV8lHD8z8pL7S/s320/pulley.jpg)](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjbgSw8TABDt1R9n7VZd1T5ZWXw7RI9GyfBizyoBFpndBl0ExyRTOSNxCt-7cpDrptpUXFTRPdJb-ejYlHLoQqzpkzYWzWaEMcO0nrjASLE2t09v6zJrDOq9sihqtsFGvbfV8lHD8z8pL7S/s1600/pulley.jpg)

  
- alloy column PA6 80x80x450, and plates for Z axis, lead screw 16x4,... - 80 Euro  
  
- screws, linear roods and bushings, buttons, cables, ,...
