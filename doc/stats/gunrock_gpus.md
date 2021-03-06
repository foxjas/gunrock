
# Comparison on Different GPUs

We ran Gunrock on several GPUs on 5 primitives times 9 datasets. As the compute and memory bandwidth capabilities of the GPUs increase, so does Gunrock's performance.

\htmlonly

  <!-- Container for the visualization gunrock_gpus -->
  <div id="vis_gunrock_gpus"></div>
  <script>
  var vlSpec = {
    "mark": "point", 
    "data": {
        "values": [
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 39.220882415771484, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_hollywood-2009_Thu Dec  1 095837 2016.json\">JSON output</a>", 
                "time": "2016-12-01 09:58:37", 
                "dataset": "hollywood-2009", 
                "m_teps": 5742.517578125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 73.38748168945312, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_hollywood-2009_Thu Dec  1 103118 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:31:18", 
                "dataset": "hollywood-2009", 
                "m_teps": 3069.005859375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 21.172500610351562, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_hollywood-2009_Tue Nov 29 095047 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:50:47", 
                "dataset": "hollywood-2009", 
                "m_teps": 10637.6953125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 42.764427185058594, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_hollywood-2009_Tue Nov 29 200525 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:05:25", 
                "dataset": "hollywood-2009", 
                "m_teps": 5266.68115234375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 88.67948150634766, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_hollywood-2009_Wed Nov 30 141331 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:13:31", 
                "dataset": "hollywood-2009", 
                "m_teps": 2539.78271484375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 74.97293853759766, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_indochina-2004_Thu Dec  1 095841 2016.json\">JSON output</a>", 
                "time": "2016-12-01 09:58:41", 
                "dataset": "indochina-2004", 
                "m_teps": 7952.46142578125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 117.48773956298828, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_indochina-2004_Thu Dec  1 103123 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:31:23", 
                "dataset": "indochina-2004", 
                "m_teps": 5074.7373046875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 46.10724639892578, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_indochina-2004_Tue Nov 29 095055 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:50:55", 
                "dataset": "indochina-2004", 
                "m_teps": 12931.1435546875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 76.62384796142578, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_indochina-2004_Tue Nov 29 200528 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:05:28", 
                "dataset": "indochina-2004", 
                "m_teps": 7781.12060546875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 158.88455200195312, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_indochina-2004_Wed Nov 30 141335 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:13:35", 
                "dataset": "indochina-2004", 
                "m_teps": 3752.5322265625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 735.0242309570312, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rgg_n24_0.000548_Thu Dec  1 100226 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:02:26", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 722.2317504882812, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 1040.33349609375, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rgg_n24_0.000548_Thu Dec  1 103529 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:35:29", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 510.25341796875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 519.3756103515625, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rgg_n24_0.000548_Tue Nov 29 095431 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:54:31", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 1021.9720458984375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 760.2845458984375, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rgg_n24_0.000548_Tue Nov 29 200924 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:09:24", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 698.2745361328125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 1397.9105224609375, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rgg_n24_0.000548_Wed Nov 30 141759 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:17:59", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 379.7506408691406, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 415.5188293457031, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rmat_n22_e64_Thu Dec  1 095902 2016.json\">JSON output</a>", 
                "time": "2016-12-01 09:59:02", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 2329.981201171875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 742.1563110351562, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rmat_n22_e64_Thu Dec  1 103144 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:31:44", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 1304.5194091796875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 181.57334899902344, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rmat_n22_e64_Tue Nov 29 095114 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:51:14", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 5331.87744140625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 502.873291015625, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rmat_n22_e64_Tue Nov 29 200553 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:05:53", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 1925.25830078125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 848.7328491210938, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rmat_n22_e64_Wed Nov 30 141402 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:14:02", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 1140.6607666015625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 580.2526245117188, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rmat_n23_e32_Thu Dec  1 095932 2016.json\">JSON output</a>", 
                "time": "2016-12-01 09:59:32", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 1746.9415283203125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 959.374267578125, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rmat_n23_e32_Thu Dec  1 103219 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:32:19", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 1056.6055908203125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 253.453857421875, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rmat_n23_e32_Tue Nov 29 095141 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:51:41", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 3999.49169921875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 716.7683715820312, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rmat_n23_e32_Tue Nov 29 200626 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:06:26", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 1414.226318359375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 1093.6820068359375, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rmat_n23_e32_Wed Nov 30 141441 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:14:41", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 926.8665161132812, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 726.8362426757812, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rmat_n24_e16_Thu Dec  1 100007 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:00:07", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 1432.943115234375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 1151.7354736328125, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rmat_n24_e16_Thu Dec  1 103257 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:32:57", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 904.2923583984375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 319.7468566894531, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rmat_n24_e16_Tue Nov 29 095212 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:52:12", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 3257.218505859375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 943.738525390625, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rmat_n24_e16_Tue Nov 29 200704 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:07:04", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 1103.63330078125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 1311.9307861328125, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_rmat_n24_e16_Wed Nov 30 141526 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:15:26", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 793.8890380859375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 886.2420043945312, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_road_usa_Thu Dec  1 100029 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:00:29", 
                "dataset": "road_usa", 
                "m_teps": 130.23220825195312, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 1159.2099609375, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_road_usa_Thu Dec  1 103323 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:33:23", 
                "dataset": "road_usa", 
                "m_teps": 99.56543731689453, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 792.4929809570312, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_road_usa_Tue Nov 29 095232 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:52:32", 
                "dataset": "road_usa", 
                "m_teps": 145.63819885253906, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 1045.978271484375, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_road_usa_Tue Nov 29 200728 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:07:28", 
                "dataset": "road_usa", 
                "m_teps": 110.34382629394531, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 1585.858642578125, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_road_usa_Wed Nov 30 141555 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:15:55", 
                "dataset": "road_usa", 
                "m_teps": 72.7790298461914, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 102.33304595947266, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_soc-LiveJournal1_Thu Dec  1 095824 2016.json\">JSON output</a>", 
                "time": "2016-12-01 09:58:24", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 1674.7545166015625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 152.92333984375, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_soc-LiveJournal1_Thu Dec  1 103103 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:31:03", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 1120.7100830078125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 46.662925720214844, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_soc-LiveJournal1_Tue Nov 29 095035 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:50:35", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 3672.78173828125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 127.44052124023438, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_soc-LiveJournal1_Tue Nov 29 200513 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:05:13", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 1344.8056640625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 177.39427185058594, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_soc-LiveJournal1_Wed Nov 30 141315 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:13:15", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 966.1119995117188, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 260.7648620605469, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_soc-orkut_Thu Dec  1 095830 2016.json\">JSON output</a>", 
                "time": "2016-12-01 09:58:30", 
                "dataset": "soc-orkut", 
                "m_teps": 1631.3426513671875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 397.8400573730469, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_soc-orkut_Thu Dec  1 103109 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:31:09", 
                "dataset": "soc-orkut", 
                "m_teps": 1069.2659912109375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 110.84973907470703, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_soc-orkut_Tue Nov 29 095041 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:50:41", 
                "dataset": "soc-orkut", 
                "m_teps": 3837.598876953125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 329.3855895996094, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_soc-orkut_Tue Nov 29 200518 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:05:18", 
                "dataset": "soc-orkut", 
                "m_teps": 1291.48583984375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BC", 
                "elapsed": 457.9451599121094, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BC_soc-orkut_Wed Nov 30 141321 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:13:21", 
                "dataset": "soc-orkut", 
                "m_teps": 928.92529296875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 3.0386924743652344, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_hollywood-2009_Thu Dec  1 095222 2016.json\">JSON output</a>", 
                "time": "2016-12-01 09:52:22", 
                "dataset": "hollywood-2009", 
                "m_teps": 37059.7890625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 5.887913703918457, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_hollywood-2009_Thu Dec  1 101844 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:18:44", 
                "dataset": "hollywood-2009", 
                "m_teps": 19126.181640625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 2.24759578704834, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_hollywood-2009_Tue Nov 29 094505 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:45:05", 
                "dataset": "hollywood-2009", 
                "m_teps": 50103.89453125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 3.5833120346069336, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_hollywood-2009_Tue Nov 29 195802 2016.json\">JSON output</a>", 
                "time": "2016-11-29 19:58:02", 
                "dataset": "hollywood-2009", 
                "m_teps": 31427.15625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 8.58604907989502, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_hollywood-2009_Wed Nov 30 135855 2016.json\">JSON output</a>", 
                "time": "2016-11-30 13:58:55", 
                "dataset": "hollywood-2009", 
                "m_teps": 13115.8466796875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 37.2706413269043, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_indochina-2004_Thu Dec  1 095229 2016.json\">JSON output</a>", 
                "time": "2016-12-01 09:52:29", 
                "dataset": "indochina-2004", 
                "m_teps": 7998.51318359375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 77.2583236694336, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_indochina-2004_Thu Dec  1 101858 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:18:58", 
                "dataset": "indochina-2004", 
                "m_teps": 3858.609619140625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 25.770832061767578, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_indochina-2004_Tue Nov 29 094511 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:45:11", 
                "dataset": "indochina-2004", 
                "m_teps": 11567.7177734375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 39.647865295410156, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_indochina-2004_Tue Nov 29 195817 2016.json\">JSON output</a>", 
                "time": "2016-11-29 19:58:17", 
                "dataset": "indochina-2004", 
                "m_teps": 7518.9345703125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 112.1948471069336, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_indochina-2004_Wed Nov 30 135915 2016.json\">JSON output</a>", 
                "time": "2016-11-30 13:59:15", 
                "dataset": "indochina-2004", 
                "m_teps": 2657.0712890625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 363.4363708496094, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rgg_n24_0.000548_Thu Dec  1 095403 2016.json\">JSON output</a>", 
                "time": "2016-12-01 09:54:03", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 730.2994384765625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 587.0337524414062, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rgg_n24_0.000548_Thu Dec  1 102038 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:20:38", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 452.16717529296875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 301.0084533691406, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rgg_n24_0.000548_Tue Nov 29 094640 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:46:40", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 881.8350830078125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 434.8191833496094, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rgg_n24_0.000548_Tue Nov 29 200005 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:00:05", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 610.444091796875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 730.5275268554688, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rgg_n24_0.000548_Wed Nov 30 140116 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:01:16", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 363.31719970703125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 2.427220344543457, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rmat_n22_e64_Thu Dec  1 095250 2016.json\">JSON output</a>", 
                "time": "2016-12-01 09:52:50", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 199440.46875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 4.062819480895996, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rmat_n22_e64_Thu Dec  1 101921 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:19:21", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 119147.390625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 1.6590595245361328, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rmat_n22_e64_Tue Nov 29 094530 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:45:30", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 291780.625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 2.6423215866088867, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rmat_n22_e64_Tue Nov 29 195843 2016.json\">JSON output</a>", 
                "time": "2016-11-29 19:58:43", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 183201.25, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 5.586099624633789, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rmat_n22_e64_Wed Nov 30 135942 2016.json\">JSON output</a>", 
                "time": "2016-11-30 13:59:42", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 86655.8359375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 4.575681686401367, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rmat_n23_e32_Thu Dec  1 095314 2016.json\">JSON output</a>", 
                "time": "2016-12-01 09:53:14", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 110766.078125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 8.148884773254395, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rmat_n23_e32_Thu Dec  1 101944 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:19:44", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 62196.6015625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 3.057122230529785, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rmat_n23_e32_Tue Nov 29 094553 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:45:53", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 165786.34375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 4.990744590759277, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rmat_n23_e32_Tue Nov 29 195909 2016.json\">JSON output</a>", 
                "time": "2016-11-29 19:59:09", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 101556.015625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 11.403608322143555, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rmat_n23_e32_Wed Nov 30 140011 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:00:11", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 44445.1015625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 9.198880195617676, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rmat_n24_e16_Thu Dec  1 095338 2016.json\">JSON output</a>", 
                "time": "2016-12-01 09:53:38", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 56611.48046875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 17.004657745361328, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rmat_n24_e16_Thu Dec  1 102009 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:20:09", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 30624.197265625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 5.869102478027344, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rmat_n24_e16_Tue Nov 29 094616 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:46:16", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 88728.765625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 10.096597671508789, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rmat_n24_e16_Tue Nov 29 195935 2016.json\">JSON output</a>", 
                "time": "2016-11-29 19:59:35", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 51577.875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 24.052833557128906, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_rmat_n24_e16_Wed Nov 30 140041 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:00:41", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 21650.60546875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 496.05572509765625, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_road_usa_Thu Dec  1 095346 2016.json\">JSON output</a>", 
                "time": "2016-12-01 09:53:46", 
                "dataset": "road_usa", 
                "m_teps": 116.3349609375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 644.6754760742188, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_road_usa_Thu Dec  1 102019 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:20:19", 
                "dataset": "road_usa", 
                "m_teps": 89.5157699584961, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 446.67315673828125, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_road_usa_Tue Nov 29 094623 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:46:23", 
                "dataset": "road_usa", 
                "m_teps": 129.196533203125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 566.5108642578125, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_road_usa_Tue Nov 29 195946 2016.json\">JSON output</a>", 
                "time": "2016-11-29 19:59:46", 
                "dataset": "road_usa", 
                "m_teps": 101.86675262451172, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 905.5538940429688, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_road_usa_Wed Nov 30 140053 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:00:53", 
                "dataset": "road_usa", 
                "m_teps": 63.72743225097656, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 8.141756057739258, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_soc-LiveJournal1_Thu Dec  1 095211 2016.json\">JSON output</a>", 
                "time": "2016-12-01 09:52:11", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 10524.9248046875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 14.206147193908691, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_soc-LiveJournal1_Thu Dec  1 101826 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:18:26", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 6031.9921875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 4.659938812255859, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_soc-LiveJournal1_Tue Nov 29 094456 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:44:56", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 18388.947265625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 8.42447280883789, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_soc-LiveJournal1_Tue Nov 29 195743 2016.json\">JSON output</a>", 
                "time": "2016-11-29 19:57:43", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 10171.71875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 20.2268123626709, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_soc-LiveJournal1_Wed Nov 30 135823 2016.json\">JSON output</a>", 
                "time": "2016-11-30 13:58:23", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 4236.5234375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 3.070402145385742, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_soc-orkut_Thu Dec  1 095217 2016.json\">JSON output</a>", 
                "time": "2016-12-01 09:52:17", 
                "dataset": "soc-orkut", 
                "m_teps": 69273.796875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 5.668067932128906, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_soc-orkut_Thu Dec  1 101837 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:18:37", 
                "dataset": "soc-orkut", 
                "m_teps": 37525.734375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 2.2773027420043945, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_soc-orkut_Tue Nov 29 094501 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:45:01", 
                "dataset": "soc-orkut", 
                "m_teps": 93399.2734375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 3.651261329650879, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_soc-orkut_Tue Nov 29 195754 2016.json\">JSON output</a>", 
                "time": "2016-11-29 19:57:54", 
                "dataset": "soc-orkut", 
                "m_teps": 58253.41015625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "BFS", 
                "elapsed": 7.932782173156738, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/BFS_soc-orkut_Wed Nov 30 135841 2016.json\">JSON output</a>", 
                "time": "2016-11-30 13:58:41", 
                "dataset": "soc-orkut", 
                "m_teps": 26812.587890625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 75.26981830596924, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_hollywood-2009_Thu Dec  1 101004 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:10:04", 
                "dataset": "hollywood-2009", 
                "m_teps": 1497.9632568359375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 94.29543018341064, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_hollywood-2009_Thu Dec  1 104552 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:45:52", 
                "dataset": "hollywood-2009", 
                "m_teps": 1195.7252197265625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 36.89370155334473, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_hollywood-2009_Tue Nov 29 095726 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:57:26", 
                "dataset": "hollywood-2009", 
                "m_teps": 3056.11572265625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 71.04203701019287, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_hollywood-2009_Tue Nov 29 201205 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:12:05", 
                "dataset": "hollywood-2009", 
                "m_teps": 1587.1085205078125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 139.5040988922119, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_hollywood-2009_Wed Nov 30 142105 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:21:05", 
                "dataset": "hollywood-2009", 
                "m_teps": 808.2301635742188, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 451.9904136657715, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_indochina-2004_Thu Dec  1 101034 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:10:34", 
                "dataset": "indochina-2004", 
                "m_teps": 668.0885620117188, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 891.6281223297119, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_indochina-2004_Thu Dec  1 104621 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:46:21", 
                "dataset": "indochina-2004", 
                "m_teps": 338.67218017578125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 201.7503023147583, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_indochina-2004_Tue Nov 29 095757 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:57:57", 
                "dataset": "indochina-2004", 
                "m_teps": 1496.7493896484375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 541.7407274246216, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_indochina-2004_Tue Nov 29 201229 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:12:29", 
                "dataset": "indochina-2004", 
                "m_teps": 557.4061889648438, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 1095.3566074371338, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_indochina-2004_Wed Nov 30 142131 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:21:31", 
                "dataset": "indochina-2004", 
                "m_teps": 275.68157958984375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 195.5333948135376, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rgg_n24_0.000548_Thu Dec  1 102243 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:22:43", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 1357.5457763671875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 365.0212049484253, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rgg_n24_0.000548_Thu Dec  1 105823 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:58:23", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 727.2393188476562, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 117.90096759796143, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rgg_n24_0.000548_Tue Nov 29 100931 2016.json\">JSON output</a>", 
                "time": "2016-11-29 10:09:31", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 2251.191162109375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 192.7088975906372, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rgg_n24_0.000548_Tue Nov 29 202349 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:23:49", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 1377.255615234375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 490.33589363098145, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rgg_n24_0.000548_Wed Nov 30 143320 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:33:20", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 541.2537231445312, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 249.36792850494385, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rmat_n22_e64_Thu Dec  1 101150 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:11:50", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 1941.1944580078125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 436.32118701934814, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rmat_n22_e64_Thu Dec  1 104739 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:47:39", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 1109.45654296875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 116.58234596252441, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rmat_n22_e64_Tue Nov 29 095908 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:59:08", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 4152.36279296875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 264.2266035079956, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rmat_n22_e64_Tue Nov 29 201343 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:13:43", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 1832.0345458984375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 561.6445064544678, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rmat_n22_e64_Wed Nov 30 142252 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:22:52", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 861.90966796875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 335.6870412826538, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rmat_n23_e32_Thu Dec  1 101508 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:15:08", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 1509.8446044921875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 546.5616226196289, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rmat_n23_e32_Thu Dec  1 105045 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:50:45", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 927.3080444335938, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 155.15625476837158, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rmat_n23_e32_Tue Nov 29 100201 2016.json\">JSON output</a>", 
                "time": "2016-11-29 10:02:01", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 3266.63330078125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 390.45329093933105, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rmat_n23_e32_Tue Nov 29 201655 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:16:55", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 1298.04638671875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 694.2970752716064, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rmat_n23_e32_Wed Nov 30 142543 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:25:43", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 730.0156860351562, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 421.7539310455322, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rmat_n24_e16_Thu Dec  1 101832 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:18:32", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 1234.754150390625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 709.6371173858643, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rmat_n24_e16_Thu Dec  1 105400 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:54:00", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 733.84130859375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 202.55732536315918, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rmat_n24_e16_Tue Nov 29 100517 2016.json\">JSON output</a>", 
                "time": "2016-11-29 10:05:17", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 2570.96826171875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 479.16111946105957, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rmat_n24_e16_Tue Nov 29 202005 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:20:05", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 1086.8001708984375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 841.269850730896, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_rmat_n24_e16_Wed Nov 30 142859 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:28:59", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 619.019775390625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 129.1722297668457, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_road_usa_Thu Dec  1 102203 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:22:03", 
                "dataset": "road_usa", 
                "m_teps": 446.7572021484375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 211.23318672180176, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_road_usa_Thu Dec  1 105741 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:57:41", 
                "dataset": "road_usa", 
                "m_teps": 273.19866943359375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 74.09512996673584, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_road_usa_Tue Nov 29 100851 2016.json\">JSON output</a>", 
                "time": "2016-11-29 10:08:51", 
                "dataset": "road_usa", 
                "m_teps": 778.8450317382812, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 127.68609523773193, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_road_usa_Tue Nov 29 202311 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:23:11", 
                "dataset": "road_usa", 
                "m_teps": 451.9570007324219, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 324.00739192962646, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_road_usa_Wed Nov 30 143239 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:32:39", 
                "dataset": "road_usa", 
                "m_teps": 178.10897827148438, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 61.676716804504395, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_soc-LiveJournal1_Thu Dec  1 100802 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:08:02", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 1389.5433349609375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 93.80168914794922, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_soc-LiveJournal1_Thu Dec  1 104353 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:43:53", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 913.656005859375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 31.627488136291504, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_soc-LiveJournal1_Tue Nov 29 095523 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:55:23", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 2709.746337890625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 66.1074161529541, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_soc-LiveJournal1_Tue Nov 29 201017 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:10:17", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 1296.412353515625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 122.98049926757812, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_soc-LiveJournal1_Wed Nov 30 141907 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:19:07", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 696.8785400390625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 111.87613010406494, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_soc-orkut_Thu Dec  1 100839 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:08:39", 
                "dataset": "soc-orkut", 
                "m_teps": 1901.1956787109375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 218.8448667526245, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_soc-orkut_Thu Dec  1 104429 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:44:29", 
                "dataset": "soc-orkut", 
                "m_teps": 971.9141235351562, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 54.878973960876465, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_soc-orkut_Tue Nov 29 095602 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:56:02", 
                "dataset": "soc-orkut", 
                "m_teps": 3875.7724609375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 131.7312479019165, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_soc-orkut_Tue Nov 29 201049 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:10:49", 
                "dataset": "soc-orkut", 
                "m_teps": 1614.6390380859375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "CC", 
                "elapsed": 259.1484069824219, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/CC_soc-orkut_Wed Nov 30 141945 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:19:45", 
                "dataset": "soc-orkut", 
                "m_teps": 820.7590942382812, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 301.452374458313, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_hollywood-2009_Thu Dec  1 100401 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:04:01", 
                "dataset": "hollywood-2009", 
                "m_teps": 8976.655517578125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 486.79449558258057, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_hollywood-2009_Thu Dec  1 103730 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:37:30", 
                "dataset": "hollywood-2009", 
                "m_teps": 5558.8839111328125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 363.3931636810303, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_hollywood-2009_Wed Nov 30 143652 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:36:52", 
                "dataset": "hollywood-2009", 
                "m_teps": 7446.57421875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 447.34790325164795, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_hollywood-2009_Wed Nov 30 144258 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:42:58", 
                "dataset": "hollywood-2009", 
                "m_teps": 6049.0594482421875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 159.6487045288086, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_hollywood-2009_Wed Nov 30 175141 2016.json\">JSON output</a>", 
                "time": "2016-11-30 17:51:41", 
                "dataset": "hollywood-2009", 
                "m_teps": 16949.92822265625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 785.4051828384399, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_indochina-2004_Thu Dec  1 100406 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:04:06", 
                "dataset": "indochina-2004", 
                "m_teps": 9996.382690429688, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 1121.0275411605835, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_indochina-2004_Thu Dec  1 103737 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:37:37", 
                "dataset": "indochina-2004", 
                "m_teps": 7003.584167480469, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 948.687219619751, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_indochina-2004_Wed Nov 30 143722 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:37:22", 
                "dataset": "indochina-2004", 
                "m_teps": 8275.868713378906, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 1019.5635080337524, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_indochina-2004_Wed Nov 30 144307 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:43:07", 
                "dataset": "indochina-2004", 
                "m_teps": 7700.560791015625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 388.947057723999, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_indochina-2004_Wed Nov 30 175147 2016.json\">JSON output</a>", 
                "time": "2016-11-30 17:51:47", 
                "dataset": "indochina-2004", 
                "m_teps": 20185.80712890625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 1952.9282093048096, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rgg_n24_0.000548_Thu Dec  1 100740 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:07:40", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 2582.404586791992, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 3512.7217531204224, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rgg_n24_0.000548_Thu Dec  1 104315 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:43:15", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 1435.7117080688477, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 2171.1068153381348, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rgg_n24_0.000548_Wed Nov 30 144141 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:41:41", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 2322.553871154785, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 2648.910665512085, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rgg_n24_0.000548_Wed Nov 30 144810 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:48:10", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 1903.9076461791992, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 1061.9746923446655, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rgg_n24_0.000548_Wed Nov 30 175347 2016.json\">JSON output</a>", 
                "time": "2016-11-30 17:53:47", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 4749.027908325195, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 2733.8268756866455, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rmat_n22_e64_Thu Dec  1 100433 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:04:33", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 3364.303176879883, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 5755.060863494873, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rmat_n22_e64_Thu Dec  1 103808 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:38:08", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 1598.1565475463867, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 3196.475100517273, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rmat_n22_e64_Wed Nov 30 143754 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:37:54", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 2877.3841094970703, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 4763.141846656799, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rmat_n22_e64_Wed Nov 30 144337 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:43:37", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 1930.9824142456055, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 1050.5645990371704, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rmat_n22_e64_Wed Nov 30 175208 2016.json\">JSON output</a>", 
                "time": "2016-11-30 17:52:08", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 8754.96957397461, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 4362.9618883132935, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rmat_n23_e32_Thu Dec  1 100518 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:05:18", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 2323.3816528320312, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 7673.883318901062, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rmat_n23_e32_Thu Dec  1 103925 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:39:25", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 1254.887580871582, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 4961.120271682739, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rmat_n23_e32_Wed Nov 30 143850 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:38:50", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 1941.0651473999023, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 6681.145262718201, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rmat_n23_e32_Wed Nov 30 144444 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:44:44", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 1517.1942138671875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 1455.3692817687988, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rmat_n23_e32_Wed Nov 30 175236 2016.json\">JSON output</a>", 
                "time": "2016-11-30 17:52:36", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 6616.79638671875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 5897.6722240448, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rmat_n24_e16_Thu Dec  1 100621 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:06:21", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 1765.9974670410156, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 9973.291683197021, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rmat_n24_e16_Thu Dec  1 104101 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:41:01", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 1044.2986297607422, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 7154.637026786804, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rmat_n24_e16_Wed Nov 30 144003 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:40:03", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 1455.7415771484375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 8257.792735099792, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rmat_n24_e16_Wed Nov 30 144611 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:46:11", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 1261.2461853027344, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 2251.0196208953857, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_rmat_n24_e16_Wed Nov 30 175308 2016.json\">JSON output</a>", 
                "time": "2016-11-30 17:53:08", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 4626.863098144531, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 671.1794137954712, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_road_usa_Thu Dec  1 100722 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:07:22", 
                "dataset": "road_usa", 
                "m_teps": 1805.5992965698242, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 2031.6614151000977, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_road_usa_Thu Dec  1 104243 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:42:43", 
                "dataset": "road_usa", 
                "m_teps": 596.4975643157959, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 791.7766571044922, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_road_usa_Wed Nov 30 144121 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:41:21", 
                "dataset": "road_usa", 
                "m_teps": 1530.5845642089844, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 2024.5991468429565, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_road_usa_Wed Nov 30 144738 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:47:38", 
                "dataset": "road_usa", 
                "m_teps": 598.5783061981201, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 263.77623081207275, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_road_usa_Wed Nov 30 175333 2016.json\">JSON output</a>", 
                "time": "2016-11-30 17:53:33", 
                "dataset": "road_usa", 
                "m_teps": 4594.353057861328, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 857.5848817825317, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_soc-LiveJournal1_Thu Dec  1 100323 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:03:23", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 2398.4324340820312, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 1321.3572978973389, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_soc-LiveJournal1_Thu Dec  1 103633 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:36:33", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 1556.6260986328125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 1027.8730392456055, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_soc-LiveJournal1_Wed Nov 30 143544 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:35:44", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 2001.0831298828125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 1069.442105293274, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_soc-LiveJournal1_Wed Nov 30 144209 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:42:09", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 1923.3012084960938, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 317.6291227340698, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_soc-LiveJournal1_Wed Nov 30 175122 2016.json\">JSON output</a>", 
                "time": "2016-11-30 17:51:22", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 6475.663330078125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 2443.280076980591, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_soc-orkut_Thu Dec  1 100334 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:03:34", 
                "dataset": "soc-orkut", 
                "m_teps": 1915.1980895996094, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 3820.559811592102, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_soc-orkut_Thu Dec  1 103649 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:36:49", 
                "dataset": "soc-orkut", 
                "m_teps": 1224.7851943969727, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 2976.1738538742065, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_soc-orkut_Wed Nov 30 143613 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:36:13", 
                "dataset": "soc-orkut", 
                "m_teps": 1572.275405883789, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 3127.198648452759, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_soc-orkut_Wed Nov 30 144223 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:42:23", 
                "dataset": "soc-orkut", 
                "m_teps": 1496.3440856933594, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "PageRank", 
                "elapsed": 865.3281688690186, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/PageRank_soc-orkut_Wed Nov 30 175129 2016.json\">JSON output</a>", 
                "time": "2016-11-30 17:51:29", 
                "dataset": "soc-orkut", 
                "m_teps": 5407.619201660156, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 77.72362518310547, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_hollywood-2009_Thu Dec  1 102218 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:22:18", 
                "dataset": "hollywood-2009", 
                "m_teps": 1448.8941650390625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 112.57679748535156, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_hollywood-2009_Wed Nov 30 140328 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:03:28", 
                "dataset": "hollywood-2009", 
                "m_teps": 1000.3242797851562, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 444.9159851074219, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_indochina-2004_Thu Dec  1 102255 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:22:55", 
                "dataset": "indochina-2004", 
                "m_teps": 670.0359497070312, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 630.0652465820312, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_indochina-2004_Wed Nov 30 140428 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:04:28", 
                "dataset": "indochina-2004", 
                "m_teps": 473.1410217285156, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 343.1083068847656, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_rgg_n24_0.000548_Thu Dec  1 095728 2016.json\">JSON output</a>", 
                "time": "2016-12-01 09:57:28", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 772.6026611328125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 656.3494262695312, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_rgg_n24_0.000548_Thu Dec  1 103007 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:30:07", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 403.90350341796875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 351.5125732421875, 
                "gpuinfo_name": "Tesla P100-PCIE-16GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_rgg_n24_0.000548_Tue Nov 29 094937 2016.json\">JSON output</a>", 
                "time": "2016-11-29 09:49:37", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 754.1578369140625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 455.1119689941406, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_rgg_n24_0.000548_Tue Nov 29 200422 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:04:22", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 582.5126953125, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 978.1978149414062, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_rgg_n24_0.000548_Wed Nov 30 141218 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:12:18", 
                "dataset": "rgg_n24_0.000548", 
                "m_teps": 270.98675537109375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 584.2050170898438, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_rmat_n22_e64_Thu Dec  1 102356 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:23:56", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 828.6013793945312, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 701.7537231445312, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_rmat_n22_e64_Wed Nov 30 140533 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:05:33", 
                "dataset": "rmat_n22_e64", 
                "m_teps": 689.7913818359375, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 754.8694458007812, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_rmat_n23_e32_Thu Dec  1 102513 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:25:13", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 671.43310546875, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 874.260009765625, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_rmat_n23_e32_Wed Nov 30 140701 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:07:01", 
                "dataset": "rmat_n23_e32", 
                "m_teps": 579.7408447265625, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 909.4984741210938, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_rmat_n24_e16_Thu Dec  1 102639 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:26:39", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 572.5731811523438, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 1047.838623046875, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_rmat_n24_e16_Wed Nov 30 140830 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:08:30", 
                "dataset": "rmat_n24_e16", 
                "m_teps": 496.9857482910156, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 5839.658203125, 
                "gpuinfo_name": "Tesla M40 24GB", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_road_usa_Thu Dec  1 095559 2016.json\">JSON output</a>", 
                "time": "2016-12-01 09:55:59", 
                "dataset": "road_usa", 
                "m_teps": 9.88219165802002, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 9505.5009765625, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_road_usa_Thu Dec  1 102801 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:28:01", 
                "dataset": "road_usa", 
                "m_teps": 6.071076393127441, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 7083.92724609375, 
                "gpuinfo_name": "Tesla M40", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_road_usa_Tue Nov 29 200240 2016.json\">JSON output</a>", 
                "time": "2016-11-29 20:02:40", 
                "dataset": "road_usa", 
                "m_teps": 8.146416664123535, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 11126.2177734375, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_road_usa_Wed Nov 30 140954 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:09:54", 
                "dataset": "road_usa", 
                "m_teps": 5.1867241859436035, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 420.6253662109375, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_soc-LiveJournal1_Thu Dec  1 102055 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:20:55", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 203.72372436523438, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 473.12603759765625, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_soc-LiveJournal1_Wed Nov 30 140139 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:01:39", 
                "dataset": "soc-LiveJournal1", 
                "m_teps": 181.11741638183594, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 839.5776977539062, 
                "gpuinfo_name": "Tesla K40m", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_soc-orkut_Thu Dec  1 102131 2016.json\">JSON output</a>", 
                "time": "2016-12-01 10:21:31", 
                "dataset": "soc-orkut", 
                "m_teps": 253.3397674560547, 
                "gunrock_version": "0.4.0"
            }, 
            {
                "engine": "Gunrock", 
                "algorithm": "SSSP", 
                "elapsed": 954.1339111328125, 
                "gpuinfo_name": "Tesla K80", 
                "details": "<a href=\"https://github.com/gunrock/io/tree/master/gunrock-output/topc/CentOS7.2_XXx1_topc_arch/SSSP_soc-orkut_Wed Nov 30 140232 2016.json\">JSON output</a>", 
                "time": "2016-11-30 14:02:32", 
                "dataset": "soc-orkut", 
                "m_teps": 222.9230194091797, 
                "gunrock_version": "0.4.0"
            }
        ]
    }, 
    "encoding": {
        "y": {
            "field": "m_teps", 
            "scale": {
                "type": "log"
            }, 
            "type": "quantitative", 
            "axis": {
                "title": "MTEPS"
            }
        }, 
        "color": {
            "field": "gpuinfo_name", 
            "type": "nominal", 
            "legend": {
                "title": "GPU"
            }
        }, 
        "shape": {
            "field": "gpuinfo_name", 
            "type": "nominal", 
            "legend": {
                "title": "GPU"
            }
        }, 
        "column": {
            "field": "algorithm", 
            "type": "nominal", 
            "axis": {
                "orient": "top", 
                "title": "Primitive"
            }
        }, 
        "x": {
            "field": "dataset", 
            "type": "nominal", 
            "axis": {
                "title": "Dataset"
            }
        }
    }
}
  var embedSpec = {
    mode: "vega-lite",  // Instruct Vega-Embed to use the Vega-Lite compiler
    spec: vlSpec
  };
  // Embed the visualization in the container with id `vis_gunrock_gpus`
  vg.embed("#vis_gunrock_gpus", embedSpec, function(error, result) {
    // Callback receiving the View instance and parsed Vega spec
    // result.view is the View, which resides under the
    // '#vis_gunrock_gpus' element
  });
  </script>

\endhtmlonly


[Source data](md_stats_gunrock_gpus_table_html.html), with links to the output JSON for each run
