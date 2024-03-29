# honeybee_seasonal_aging_model

This repository contains the Matlab code associated with the publication Lemanski, N.J., S. Bansal, and N.H. Fefferman. 2020. The sensitivity of a honeybee colony to worker mortality depends on season and resource availability. BMC Evolutionary Biology. 20(1):1-9.

List of code files and their dependencies:
1. 'graphresults_matrixbeemodel_foragers_BMC.m' - depends on 'elasticityallseasons_foragers.m'
2. 'graphresults_matrixbeemodel_nurses_BMC.m' - depends on 'elasticityallseasons_nurses.m'
3. 'elasticityallseasons_foragers.m' - depends on 'eigenvalue_v3_NLalt.m'
4. 'elasticityallseasons_nurses.m' - depends on 'eigenvalue_v3_NLalt_nurses.m'
5. 'eigenvalue_v3_NLalt.m' - depends on 'eigenvalueHelper_NLedit.m', 'spring_setValues.m', 'summer_setValues.m', 'fall_setValues.m', 'winter_setValues.m'
6. 'eigenvalue_v3_NLalt_nurses.m' - depends on 'eigenvalueHelper_NLedit_nurse.m', 'spring_setValues.m', 'summer_setValues.m', 'fall_setValues.m', 'winter_setValues.m'
7. 'eigenvalueHelper_NLedit.m' - depends on 'insertValues_v3_NLedit.m'
8. 'eigenvalueHelper_NLedit_nurse.m' - depends on 'insertValues_v3_NLedit.m'
9. 'spring_setValues.m'
10. 'summer_setValues.m'
11. 'fall_setValues.m'
12. 'winter_setValues.m'
13. 'insertValues_v3_NLedit.m'
14. 'broodsurvivalanalysis.m' - depends on 'eigenvalueHelper_NLedit.m', 'winter_setValues.m'
