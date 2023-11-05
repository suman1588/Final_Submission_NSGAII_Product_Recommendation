Steps:
1. Collect Friend list With linkgrabber
2. Collect Posts with Ctrl+S
3. generate_csv.py will generate a CSV from frind list links
4. Use gephi to get the connected components as person.csv in this project directory
5. Use checks.py to get mappings.csv
6. Use html_t.py to get corrected_mappings.csv
7. Use prepareforFloyd.py to get the floyd.txt for the "graph" project.
8. Use it to generate floyd (pkl) file and copy to the floyd folder. Also generate a hop based hps file and hp.txt
9. NSGAII.py or NSGAII_cost.py can proceed now.
----------------------------------------------------------
