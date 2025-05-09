# EcoTTD - Ecological Add-on for OpenTTD

## Overview
EcoTTD is an ecological add-on for OpenTTD that raises awareness about environmental issues in transportation and land use planning. Developed as part of the EdUTeam project and the QSimpACT Challenge 2025, this add-on transforms the original game into an educational tool about environmental sustainability.

## Modules
The add-on currently includes two implemented modules, with a third planned for the future:

1. **Sustainable Transportation**
   - Electric and hybrid trains (electric mode not working at the moment)
   - Innovative solar train
   
2. **Waste Management**
   - New "waste" cargo type
   - Recycling centers
   - Waste collection trucks

3. **Renewable Energy** (planned but not implemented in this version)
   - Solar and wind energy industries (partial code included)
   - Electric pylons for the distribution network
   - Bonus for using green energy

You can still visualize the elements (wind turbine, solar panel, etc.) in decoration mode (to be dynamized)

Note: The simplified carbon cost system was also an initial goal but is not included in this version.

## Requirements
- OpenTTD (version 1.9.0 or higher)
- No additional add-ons required

## Installing OpenTTD
1. Download OpenTTD from the official website: https://www.openttd.org/downloads/openttd-releases/latest
2. Install the game by following the instructions for your operating system
3. Launch OpenTTD once to create the necessary folders

## Installing the EcoTTD Add-on
### Method 1: Manual Installation
1. Locate the "newgrf" folder in your OpenTTD directory:
   - Windows: C:\Users\[Your name]\Documents\OpenTTD\newgrf
   - macOS: ~/Documents/OpenTTD/newgrf
   - Linux: ~/.openttd/newgrf
2. Create a new "EcoTTD" folder in this directory
3. Extract all files from the EcoTTD archive into this new folder
4. Make sure the file structure is correct:
   ```
   newgrf/
      ├── energy_pack.grf
      ├── recycled_waste.grf
      └── dev/
         └── energy/
            ├── testgrf.nml
            └── .nmlcache/
                  ├── ...
            └── gfx/
                  ├── centre-solaire.png
                  ├── eolienne.png
                  ├── panneau-solaire.png
                  ├── pylone.png
                  ├── train-hybrid.png
                  ├── train-solaire.png
                  ├── usine-dechet.png
            └── lang/
                  ├── english.lng
            └── sprites/
                  ├── sprites.png
         └── waste/
               ├──mygrf.nml
               └── gfx/
                     ├── recycling_plant.png
               └── lang/
                     ├── english.lng
                     ├── french.lng
   ```

### Method 2: Via the In-game Content Manager (if available)
1. Launch OpenTTD
2. Go to the "Online Content" menu
3. Search for "EcoTTD"
4. Click on "Download"

## Using the Add-on
1. Launch OpenTTD
2. Create a new game or load an existing one
3. In the "Game Settings" > "NewGRF" menu, activate "Energy_Pack" & "recycled_waste"
4. Start playing!

### Electric and Hybrid Trains
- Available in the "Construction" > "Trains" menu
- Electric trains require electrified rails
- Hybrid trains can operate in diesel or electric mode

### Waste Management
- Cities automatically produce waste
- Build recycling centers to process waste
- Use collection trucks to transport waste from cities to recycling centers

### Renewable Energy (planned feature)
This feature was intended in the initial objectives but is not yet fully implemented in this version. Some graphical elements and parts of the code are included in the files, but the functionality is not yet operational. In future versions, you will be able to:
- Build wind farms and solar power plants
- Connect energy sources to cities and industries with electric pylons
- Benefit from performance bonuses for electric trains powered by renewable energy

## Educational Tips
For teachers and educators using EcoTTD as an educational tool:

- Organize challenges where students must create transportation networks with minimal carbon footprint
- Compare economic and environmental performance of different configurations
- Discuss trade-offs between economic efficiency and environmental impact
- Use the provided scientific documentation to explore concepts in depth

## Sustainable Development Goals (SDGs)
This add-on aligns with several UN SDGs:
- SDG 7: Affordable and Clean Energy
- SDG 9: Industry, Innovation and Infrastructure
- SDG 11: Sustainable Cities and Communities
- SDG 12: Responsible Consumption and Production
- SDG 13: Climate Action

## Troubleshooting
- If graphics do not display correctly, check that all PNG files are in the appropriate folder
- In case of crashes when loading, make sure your OpenTTD version is compatible
- If certain elements are not visible, check that the add-on is activated in the NewGRF settings

## Credits
Developed by the Imbattables_IAE team (Clémence Mazoyer, Prabpreet Singh, Eladje Diatta, Lyna Hmadi, Marika Petit, Kadiarou Balde, Hugo Trinquier, Tom Sentieys and Laure Laffon) as part of the EdUTeam project and the QSimpACT Challenge 2025.

## License
This project is distributed under the GPL v2 license, in accordance with FLOSS (Free/Libre Open Source Software) principles.

## Further Information
A complete scientific documentation is available, detailing the ecological principles implemented in the add-on. See the "Documentation - project FLOSS.docx" file for more information.
