# Phloretic acid

#Project This project is to identify target reactions that will enhance production of target chemical through FVSEOF


##Example
        
        
# FVSEOF simulation

1. Create and activate virtual environment

        conda env create -f environment.yml
        conda activate metool
        
2. Run FVSEOF

        python ME_targeting.py -i ./iML1515.xml -o ./output/fvseof -t EX_succ_e -b BIOMASS_Ec_iML1515_core_75p37M -m fvseof
        