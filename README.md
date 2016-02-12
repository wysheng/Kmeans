# Kmeans
一个数据挖掘里的简单聚类算法，使用了JFreeChart用于对分类结果的展示。

![alt text](https://github.com/MeninaChimp/Kmeans/blob/master/Cluster.jpg)

数据集：
1.658985	4.285136
-3.453687	3.424321
4.838138	-1.151539
-5.379713	-3.362104
0.972564	2.924086
-3.567919	1.531611
0.450614	-3.302219
-3.487105	-1.724432
2.668759	1.594842
-3.156485	3.191137
3.165506	-3.999838
-2.786837	-3.099354
4.208187	2.984927
-2.123337	2.943366
0.704199	-0.479481
-0.392370	-3.963704
2.831667	1.574018
-0.790153	3.343144
2.943496	-3.357075
-3.195883	-2.283926
2.336445	2.875106
-1.786345	2.554248
2.190101	-1.906020
-3.403367	-2.778288
1.778124	3.880832
-1.688346	2.230267
2.592976	-2.054368
-4.007257	-3.207066
3.275154	2.957587
-3.344465	2.603513
0.355083	-3.376585
1.852435	3.547351
-2.078973	2.552013
-0.993756	-0.884433
2.682252	4.007573
-3.087776	2.878713
-1.565978	-1.256985
2.441611	0.444826
-0.659487	3.111284
-0.459601	-2.618005
2.177680	2.387793
-2.920969	2.917485
-0.028814	-4.168078
3.625746	2.119041
-3.912363	1.325108
-0.551694	-2.814223
2.855808	3.483301
-3.594448	2.856651
0.421993	-2.372646
1.650821	3.407572
-2.082902	3.384412
-0.718809	-2.492514
4.513623	3.841029
-4.822011	4.607049
-0.656297	-1.449872
1.919901	4.439368
-3.287749	3.918836
-1.576936	-2.977622
3.598143	1.975970
-3.977329	4.900932
-1.791080	-2.184517
3.914654	3.559303
-1.910108	4.166946
-1.226597	-3.317889
1.148946	3.345138
-2.113864	3.548172
0.845762	-3.589788
2.629062	3.535831
-1.640717	2.990517
-1.881012	-2.485405
4.606999	3.510312
-4.366462	4.023316
0.765015	-3.001270
3.121904	2.173988
-4.025139	4.652310
-0.559558	-3.840539
4.376754	4.863579
-1.874308	4.032237
-0.089337	-3.026809
3.997787	2.518662
-3.082978	2.884822
0.845235	-3.454465
1.327224	3.358778
-2.889949	3.596178
-0.966018	-2.839827
2.960769	3.079555
-3.275518	1.577068
0.639276	-3.412840

2.257734	3.387564
-2.679011	0.785119
0.939512	-4.023563
-3.674424	-2.261084
2.046259	2.735279
-3.189470	1.780269
4.372646	-0.822248
-2.579316	-3.497576
1.889034	5.190400
-0.798747	2.185588
2.836520	-2.658556
-3.837877	-3.253815
2.096701	3.886007
-2.709034	2.923887
3.367037	-3.184789
-2.121479	-4.232586
2.329546	3.179764
-3.284816	3.273099
3.091414	-3.815232
-3.762093	-2.432191
3.542056	2.778832
-1.736822	4.241041
2.127073	-2.983680
-4.323818	-3.938116
3.792121	5.135768
-4.786473	3.358547
2.624081	-3.260715
-4.009299	-2.978115
2.493525	1.963710
-2.513661	2.642162
1.864375	-3.176309
-3.171184	-3.572452
2.894220	2.489128
-2.562539	2.884438
3.491078	-3.947487
-2.565729	-2.012114
3.332948	3.983102
-1.616805	3.573188
2.280615	-2.559444
-2.651229	-3.103198
2.321395	3.154987
-1.685703	2.939697
3.031012	-3.620252
-4.599622	-2.185829
4.196223	1.126677
-2.133863	3.093686
4.668892	-2.562705
-2.793241	-2.149706
2.884105	3.043438
-2.967647	2.848696
4.479332	-1.764772
-4.905566	-2.911070
3.275154	2.957587
-3.344465	2.603513
0.355083	-3.376585
1.852435	3.547351
-2.078973	2.552013
-0.993756	-0.884433
2.682252	4.007573
-3.087776	2.878713
-1.565978	-1.256985
2.441611	0.444826
-0.659487	3.111284
-0.459601	-2.618005
2.177680	2.387793
-2.920969	2.917485
-0.028814	-4.168078
3.625746	2.119041
-3.912363	1.325108
-0.551694	-2.814223
2.855808	3.483301
-3.594448	2.856651
0.421993	-2.372646
1.650821	3.407572
-2.082902	3.384412
-0.718809	-2.492514
4.513623	3.841029
-4.822011	4.607049
-0.656297	-1.449872
1.919901	4.439368
-3.287749	3.918836
-1.576936	-2.977622
3.598143	1.975970
-3.977329	4.900932
-1.791080	-2.184517
3.914654	3.559303
-1.910108	4.166946
-1.226597	-3.317889
1.148946	3.345138
-2.113864	3.548172
0.845762	-3.589788
2.629062	3.535831
-1.640717	2.990517
-1.881012	-2.485405
4.606999	3.510312
-4.366462	4.023316
0.765015	-3.001270
3.121904	2.173988
-4.025139	4.652310
-0.559558	-3.840539
4.376754	4.863579
-1.874308	4.032237
-0.089337	-3.026809
3.997787	2.518662
-3.082978	2.884822
0.845235	-3.454465
1.327224	3.358778
-2.889949	3.596178
-0.966018	-2.839827
2.960769	3.079555
-3.275518	1.577068
0.639276	-3.412840

