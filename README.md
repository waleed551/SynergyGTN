# Unlocking the Therapeutic Potential of Drug Combinations through Synergy Prediction using Graph Transformer Networks
Drug combinations are frequently used to treat cancer to reduce side effects and increase efficacy. The experimental discovery of drug combination synergy is time-consuming and expensive for large datasets. Therefore, an efficient and reliable computational approach is required to investigate these drug combinations. Advancements in deep learning can handle large datasets with various biological problems. In this study, we developed a SynergyGTN model based on the Graph Transformer Network to predict the synergistic drug combinations against an untreated cancer cell line expression profile. We represent the drug via a graph, with each node and edge of the graph containing nine types of atomic feature vectors and four bonds features, respectively. The cell lines represent based on their gene expression profiles. The drug graph was passed through the GTN layers to extract a generalized feature map for each drug pairs. The drug pair extracted features and cell-line gene expression profiles were concatenated and subsequently subjected to processing through multiple densely connected layers. SynergyGTN outperformed the state-of-the-art methods, with a receiver operating characteristic area under the curve improvement of 5\% on the random split cross validation. The accuracy of SynergyGTN was further verified through three types of cross-validation tests strategies namely leave-drug-out, leave-combination-out, and leave-tissue-out, resulting in improvement in accuracy of 8\%, 1\%, and 2\%, respectively. The Astrazeneca Dream dataset was utilized as an independent dataset to validate and assess the generalizability of the proposed method, resulting in an improvement in balanced accuracy of 13\%. In conclusion, SynergyGTN is a reliable and efficient computational approach for predicting drug combination synergy in cancer treatment. Finally, we developed a web server tool to facilitate the pharmaceutical industry and researchers, as available at: http://nsclbio.jbnu.ac.kr/tools/SynergyGTN/
