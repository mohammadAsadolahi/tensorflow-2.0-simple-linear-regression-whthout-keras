# Tensorflow-2.0-simple-linear-regression-whthout-Keras  
simple linear regressor that try to approximate a simple function deployed in tensorflow 2.0 whithout keras   
WRITTEN BY MOHAMMAD ASADOLAHI  
Mohammad.E.Asadolahi@gmail.com  
https://github.com/mohammadAsadolahi    
to do: deploy a simpller version whithout tensorfloow
# weights and bias after 3000 step of Gradient descent 
(<tf.Variable 'Variable:0' shape=(10, 1) dtype=float32, numpy=  
 array([[ 0.68809956],  
        [ 0.23739405],  
        [ 0.99913424],  
        [ 0.2658    ],  
        [ 1.3917546 ],  
        [ 0.09786515],  
        [-0.4495175 ],  
        [-0.4142065 ],  
        [ 0.4129479 ],  
        [-0.05248658]], dtype=float32)>,  
 <tf.Variable 'Variable:0' shape=(1,) dtype=float32, numpy=array([5.763193], dtype=float32)>)  
 
# approximation of function after 2000 step of Gradient descent  
approximate of 10 and 20 that should be 37(10*3+7) and 67(20*3+7)  
approximation of function is : 37.531044 and  69.2989  
<tf.Tensor: shape=(2,), dtype=float32, numpy=array([37.531044, 69.2989  ], dtype=float32)>  

# firt 1000 step of training  

loss of epoch:0 4.2688975  
loss of epoch:1 4.265243  
loss of epoch:2 4.2615976  
loss of epoch:3 4.257954  
loss of epoch:4 4.2543087  
loss of epoch:5 4.2506742  
loss of epoch:6 4.2470384  
loss of epoch:7 4.243407  
loss of epoch:8 4.239779  
loss of epoch:9 4.23615  
loss of epoch:10 4.2325244  
loss of epoch:11 4.22891  
loss of epoch:12 4.2252965  
loss of epoch:13 4.2216787  
loss of epoch:14 4.21807  
loss of epoch:15 4.2144594  
loss of epoch:16 4.2108564  
loss of epoch:17 4.2072563  
loss of epoch:18 4.2036557  
loss of epoch:19 4.200062  
loss of epoch:20 4.1964717  
loss of epoch:21 4.19288  
loss of epoch:22 4.189296  
loss of epoch:23 4.185714  
loss of epoch:24 4.1821337  
loss of epoch:25 4.1785545  
loss of epoch:26 4.174981  
loss of epoch:27 4.171412  
loss of epoch:28 4.1678476  
loss of epoch:29 4.1642804  
loss of epoch:30 4.1607203  
loss of epoch:31 4.1571608  
loss of epoch:32 4.1536055  
loss of epoch:33 4.1500535  
loss of epoch:34 4.146506  
loss of epoch:35 4.14296  
loss of epoch:36 4.1394143  
loss of epoch:37 4.135875  
loss of epoch:38 4.1323395  
loss of epoch:39 4.128801  
loss of epoch:40 4.1252747  
loss of epoch:41 4.121743  
loss of epoch:42 4.118219  
loss of epoch:43 4.1146975  
loss of epoch:44 4.1111794  
loss of epoch:45 4.1076617  
loss of epoch:46 4.1041484  
loss of epoch:47 4.1006403  
loss of epoch:48 4.0971336  
loss of epoch:49 4.0936275  
loss of epoch:50 4.0901284  
loss of epoch:51 4.0866313  
loss of epoch:52 4.083135  
loss of epoch:53 4.079643  
loss of epoch:54 4.076155  
loss of epoch:55 4.0726676  
loss of epoch:56 4.0691824  
loss of epoch:57 4.0657053  
loss of epoch:58 4.0622287  
loss of epoch:59 4.058753  
loss of epoch:60 4.0552835  
loss of epoch:61 4.051814  
loss of epoch:62 4.048351  
loss of epoch:63 4.0448895  
loss of epoch:64 4.0414286  
loss of epoch:65 4.037971  
loss of epoch:66 4.0345182  
loss of epoch:67 4.0310674  
loss of epoch:68 4.0276213  
loss of epoch:69 4.0241766  
loss of epoch:70 4.0207334  
loss of epoch:71 4.017298  
loss of epoch:72 4.013859  
loss of epoch:73 4.01043  
loss of epoch:74 4.0069976  
loss of epoch:75 4.0035696  
loss of epoch:76 4.000146  
loss of epoch:77 3.9967258  
loss of epoch:78 3.9933076  
loss of epoch:79 3.9898903  
loss of epoch:80 3.98648  
loss of epoch:81 3.9830692  
loss of epoch:82 3.9796653  
loss of epoch:83 3.9762635  
loss of epoch:84 3.9728603  
loss of epoch:85 3.9694653  
loss of epoch:86 3.9660676  
loss of epoch:87 3.9626784  
loss of epoch:88 3.9592888  
loss of epoch:89 3.9559033  
loss of epoch:90 3.9525173  
loss of epoch:91 3.9491382  
loss of epoch:92 3.9457593  
loss of epoch:93 3.9423852  
loss of epoch:94 3.939013  
loss of epoch:95 3.9356446  
loss of epoch:96 3.93228  
loss of epoch:97 3.9289188  
loss of epoch:98 3.9255586  
loss of epoch:99 3.9222016  
loss of epoch:100 3.9188435  
loss of epoch:101 3.9154954  
loss of epoch:102 3.9121468  
loss of epoch:103 3.9088008  
loss of epoch:104 3.905456  
loss of epoch:105 3.9021182  
loss of epoch:106 3.89878  
loss of epoch:107 3.8954444  
loss of epoch:108 3.892112  
loss of epoch:109 3.8887868  
loss of epoch:110 3.8854592  
loss of epoch:111 3.8821368  
loss of epoch:112 3.878816  
loss of epoch:113 3.8754997  
loss of epoch:114 3.8721852  
loss of epoch:115 3.8688743  
loss of epoch:116 3.8655655  
loss of epoch:117 3.8622565  
loss of epoch:118 3.8589535  
loss of epoch:119 3.855658  
loss of epoch:120 3.8523622  
loss of epoch:121 3.8490644  
loss of epoch:122 3.845773  
loss of epoch:123 3.8424816  
loss of epoch:124 3.8391957  
loss of epoch:125 3.835917  
loss of epoch:126 3.8326328  
loss of epoch:127 3.8293576  
loss of epoch:128 3.8260803  
loss of epoch:129 3.8228092  
loss of epoch:130 3.819538  
loss of epoch:131 3.816274  
loss of epoch:132 3.8130088  
loss of epoch:133 3.8097472  
loss of epoch:134 3.8064911  
loss of epoch:135 3.8032346  
loss of epoch:136 3.7999828  
loss of epoch:137 3.7967343  
loss of epoch:138 3.7934864  
loss of epoch:139 3.7902405  
loss of epoch:140 3.787  
loss of epoch:141 3.7837608  
loss of epoch:142 3.7805245  
loss of epoch:143 3.7772903  
loss of epoch:144 3.77406  
loss of epoch:145 3.7708344  
loss of epoch:146 3.7676094  
loss of epoch:147 3.7643876  
loss of epoch:148 3.7611663  
loss of epoch:149 3.7579522  
loss of epoch:150 3.7547386  
loss of epoch:151 3.7515252  
loss of epoch:152 3.7483215  
loss of epoch:153 3.7451127  
loss of epoch:154 3.7419105  
loss of epoch:155 3.7387092  
loss of epoch:156 3.735511  
loss of epoch:157 3.7323182  
loss of epoch:158 3.7291248  
loss of epoch:159 3.7259343  
loss of epoch:160 3.7227473  
loss of epoch:161 3.719567  
loss of epoch:162 3.7163854  
loss of epoch:163 3.7132065  
loss of epoch:164 3.7100284  
loss of epoch:165 3.7068603  
loss of epoch:166 3.703687  
loss of epoch:167 3.7005203  
loss of epoch:168 3.6973538  
loss of epoch:169 3.6941934  
loss of epoch:170 3.6910367  
loss of epoch:171 3.6878777  
loss of epoch:172 3.6847243  
loss of epoch:173 3.6815724  
loss of epoch:174 3.6784248  
loss of epoch:175 3.6752782  
loss of epoch:176 3.6721368  
loss of epoch:177 3.6689956  
loss of epoch:178 3.6658573  
loss of epoch:179 3.6627204  
loss of epoch:180 3.6595898  
loss of epoch:181 3.656458  
loss of epoch:182 3.6533318  
loss of epoch:183 3.6502056  
loss of epoch:184 3.6470857  
loss of epoch:185 3.6439698  
loss of epoch:186 3.6408494  
loss of epoch:187 3.6377358  
loss of epoch:188 3.634627  
loss of epoch:189 3.631518  
loss of epoch:190 3.628409  
loss of epoch:191 3.625309  
loss of epoch:192 3.6222062  
loss of epoch:193 3.6191106  
loss of epoch:194 3.6160169  
loss of epoch:195 3.6129231  
loss of epoch:196 3.6098297  
loss of epoch:197 3.6067486  
loss of epoch:198 3.603662  
loss of epoch:199 3.600579  
loss of epoch:200 3.5975013  
loss of epoch:201 3.5944233  
loss of epoch:202 3.5913506  
loss of epoch:203 3.588277  
loss of epoch:204 3.5852077  
loss of epoch:205 3.5821443  
loss of epoch:206 3.5790806  
loss of epoch:207 3.5760217  
loss of epoch:208 3.5729606  
loss of epoch:209 3.5699055  
loss of epoch:210 3.566854  
loss of epoch:211 3.5638022  
loss of epoch:212 3.5607543  
loss of epoch:213 3.5577064  
loss of epoch:214 3.554666  
loss of epoch:215 3.5516243  
loss of epoch:216 3.5485897  
loss of epoch:217 3.5455537  
loss of epoch:218 3.5425217  
loss of epoch:219 3.5394936  
loss of epoch:220 3.536464  
loss of epoch:221 3.533441  
loss of epoch:222 3.5304196  
loss of epoch:223 3.5273976  
loss of epoch:224 3.5243828  
loss of epoch:225 3.5213704  
loss of epoch:226 3.5183594  
loss of epoch:227 3.5153496  
loss of epoch:228 3.512344  
loss of epoch:229 3.509339  
loss of epoch:230 3.5063374  
loss of epoch:231 3.5033383  
loss of epoch:232 3.5003402  
loss of epoch:233 3.497348  
loss of epoch:234 3.4943588  
loss of epoch:235 3.49137  
loss of epoch:236 3.4883835  
loss of epoch:237 3.4854012  
loss of epoch:238 3.4824193  
loss of epoch:239 3.4794402  
loss of epoch:240 3.4764676  
loss of epoch:241 3.4734929  
loss of epoch:242 3.4705215  
loss of epoch:243 3.4675515  
loss of epoch:244 3.4645875  
loss of epoch:245 3.4616253  
loss of epoch:246 3.4586678  
loss of epoch:247 3.4557068  
loss of epoch:248 3.4527512  
loss of epoch:249 3.4497998  
loss of epoch:250 3.4468465  
loss of epoch:251 3.4439003  
loss of epoch:252 3.440955  
loss of epoch:253 3.4380124  
loss of epoch:254 3.4350743  
loss of epoch:255 3.432135  
loss of epoch:256 3.4291978  
loss of epoch:257 3.426267  
loss of epoch:258 3.4233336  
loss of epoch:259 3.4204082  
loss of epoch:260 3.4174824  
loss of epoch:261 3.4145598  
loss of epoch:262 3.411642  
loss of epoch:263 3.4087224  
loss of epoch:264 3.4058068  
loss of epoch:265 3.4028957  
loss of epoch:266 3.3999863  
loss of epoch:267 3.397078  
loss of epoch:268 3.394172  
loss of epoch:269 3.3912685  
loss of epoch:270 3.3883674  
loss of epoch:271 3.3854682  
loss of epoch:272 3.3825755  
loss of epoch:273 3.379683  
loss of epoch:274 3.3767943  
loss of epoch:275 3.3739045  
loss of epoch:276 3.3710182  
loss of epoch:277 3.3681374  
loss of epoch:278 3.3652568  
loss of epoch:279 3.3623786  
loss of epoch:280 3.3595023  
loss of epoch:281 3.3566291  
loss of epoch:282 3.3537593  
loss of epoch:283 3.350891  
loss of epoch:284 3.3480268  
loss of epoch:285 3.3451614  
loss of epoch:286 3.3423018  
loss of epoch:287 3.3394425  
loss of epoch:288 3.3365874  
loss of epoch:289 3.333733  
loss of epoch:290 3.33088  
loss of epoch:291 3.3280346  
loss of epoch:292 3.3251865  
loss of epoch:293 3.3223445  
loss of epoch:294 3.3195012  
loss of epoch:295 3.3166604  
loss of epoch:296 3.3138263  
loss of epoch:297 3.3109894  
loss of epoch:298 3.30816  
loss of epoch:299 3.3053315  
loss of epoch:300 3.3025048  
loss of epoch:301 3.2996807  
loss of epoch:302 3.296859  
loss of epoch:303 3.2940388  
loss of epoch:304 3.2912216  
loss of epoch:305 3.288409  
loss of epoch:306 3.2855942  
loss of epoch:307 3.2827868  
loss of epoch:308 3.2799802  
loss of epoch:309 3.2771707  
loss of epoch:310 3.2743726  
loss of epoch:311 3.2715726  
loss of epoch:312 3.2687736  
loss of epoch:313 3.2659802  
loss of epoch:314 3.263184  
loss of epoch:315 3.2603924  
loss of epoch:316 3.257605  
loss of epoch:317 3.2548213  
loss of epoch:318 3.252037  
loss of epoch:319 3.2492566  
loss of epoch:320 3.2464771  
loss of epoch:321 3.243702  
loss of epoch:322 3.2409234  
loss of epoch:323 3.238154  
loss of epoch:324 3.235387  
loss of epoch:325 3.2326214  
loss of epoch:326 3.2298546  
loss of epoch:327 3.2270932  
loss of epoch:328 3.2243328  
loss of epoch:329 3.2215772  
loss of epoch:330 3.2188194  
loss of epoch:331 3.2160676  
loss of epoch:332 3.2133174  
loss of epoch:333 3.210567  
loss of epoch:334 3.2078242  
loss of epoch:335 3.2050781  
loss of epoch:336 3.2023392  
loss of epoch:337 3.1995993  
loss of epoch:338 3.196864  
loss of epoch:339 3.1941295  
loss of epoch:340 3.1914  
loss of epoch:341 3.1886675  
loss of epoch:342 3.18594  
loss of epoch:343 3.1832173  
loss of epoch:344 3.1804929  
loss of epoch:345 3.1777737  
loss of epoch:346 3.1750572  
loss of epoch:347 3.1723409  
loss of epoch:348 3.1696286  
loss of epoch:349 3.166918  
loss of epoch:350 3.1642072  
loss of epoch:351 3.1615033  
loss of epoch:352 3.158799  
loss of epoch:353 3.1561  
loss of epoch:354 3.1534  
loss of epoch:355 3.1507018  
loss of epoch:356 3.1480088  
loss of epoch:357 3.1453161  
loss of epoch:358 3.1426263  
loss of epoch:359 3.1399357  
loss of epoch:360 3.1372528  
loss of epoch:361 3.1345694  
loss of epoch:362 3.1318882  
loss of epoch:363 3.1292114  
loss of epoch:364 3.126534  
loss of epoch:365 3.1238606  
loss of epoch:366 3.1211886  
loss of epoch:367 3.1185174  
loss of epoch:368 3.1158528  
loss of epoch:369 3.1131864  
loss of epoch:370 3.1105254  
loss of epoch:371 3.1078632  
loss of epoch:372 3.1052077  
loss of epoch:373 3.102552  
loss of epoch:374 3.099895  
loss of epoch:375 3.0972447  
loss of epoch:376 3.0945976  
loss of epoch:377 3.0919535  
loss of epoch:378 3.089307  
loss of epoch:379 3.0866654  
loss of epoch:380 3.084025  
loss of epoch:381 3.0813909  
loss of epoch:382 3.0787532  
loss of epoch:383 3.07612  
loss of epoch:384 3.0734909  
loss of epoch:385 3.0708623  
loss of epoch:386 3.068234  
loss of epoch:387 3.0656085  
loss of epoch:388 3.062987  
loss of epoch:389 3.0603707  
loss of epoch:390 3.0577521  
loss of epoch:391 3.055138  
loss of epoch:392 3.0525239  
loss of epoch:393 3.0499141  
loss of epoch:394 3.0473049  
loss of epoch:395 3.044701  
loss of epoch:396 3.042092  
loss of epoch:397 3.0394907  
loss of epoch:398 3.0368946  
loss of epoch:399 3.0342984  
loss of epoch:400 3.0317028  
loss of epoch:401 3.0291078  
loss of epoch:402 3.026519  
loss of epoch:403 3.0239303  
loss of epoch:404 3.0213459  
loss of epoch:405 3.0187602  
loss of epoch:406 3.0161793  
loss of epoch:407 3.013599  
loss of epoch:408 3.0110211  
loss of epoch:409 3.0084462  
loss of epoch:410 3.0058734  
loss of epoch:411 3.003303  
loss of epoch:412 3.0007334  
loss of epoch:413 2.9981675  
loss of epoch:414 2.9956036  
loss of epoch:415 2.9930444  
loss of epoch:416 2.990484  
loss of epoch:417 2.987924  
loss of epoch:418 2.9853704  
loss of epoch:419 2.982819  
loss of epoch:420 2.9802659  
loss of epoch:421 2.977717  
loss of epoch:422 2.975169  
loss of epoch:423 2.9726267  
loss of epoch:424 2.9700837  
loss of epoch:425 2.9675436  
loss of epoch:426 2.9650068  
loss of epoch:427 2.96247  
loss of epoch:428 2.9599388  
loss of epoch:429 2.9574075  
loss of epoch:430 2.9548771  
loss of epoch:431 2.952348  
loss of epoch:432 2.9498236  
loss of epoch:433 2.9473045  
loss of epoch:434 2.9447796  
loss of epoch:435 2.9422622  
loss of epoch:436 2.9397466  
loss of epoch:437 2.9372323  
loss of epoch:438 2.9347205  
loss of epoch:439 2.9322112  
loss of epoch:440 2.9297023  
loss of epoch:441 2.927196  
loss of epoch:442 2.9246926  
loss of epoch:443 2.9221935  
loss of epoch:444 2.919696  
loss of epoch:445 2.9171965  
loss of epoch:446 2.914702  
loss of epoch:447 2.9122095  
loss of epoch:448 2.9097176  
loss of epoch:449 2.907231  
loss of epoch:450 2.9047432  
loss of epoch:451 2.9022596  
loss of epoch:452 2.8997788  
loss of epoch:453 2.8972976  
loss of epoch:454 2.8948178  
loss of epoch:455 2.8923442  
loss of epoch:456 2.8898702  
loss of epoch:457 2.8873978  
loss of epoch:458 2.8849282  
loss of epoch:459 2.8824623  
loss of epoch:460 2.8799963  
loss of epoch:461 2.8775337  
loss of epoch:462 2.875071  
loss of epoch:463 2.8726137  
loss of epoch:464 2.8701575  
loss of epoch:465 2.867702  
loss of epoch:466 2.8652525  
loss of epoch:467 2.8627987  
loss of epoch:468 2.8603532  
loss of epoch:469 2.857904  
loss of epoch:470 2.8554585  
loss of epoch:471 2.8530219  
loss of epoch:472 2.8505807  
loss of epoch:473 2.8481424  
loss of epoch:474 2.8457065  
loss of epoch:475 2.8432708  
loss of epoch:476 2.840843  
loss of epoch:477 2.8384109  
loss of epoch:478 2.8359826  
loss of epoch:479 2.8335567  
loss of epoch:480 2.8311348  
loss of epoch:481 2.8287146  
loss of epoch:482 2.8262935  
loss of epoch:483 2.8238785  
loss of epoch:484 2.821462  
loss of epoch:485 2.8190498  
loss of epoch:486 2.8166382  
loss of epoch:487 2.8142307  
loss of epoch:488 2.8118205  
loss of epoch:489 2.8094165  
loss of epoch:490 2.8070145  
loss of epoch:491 2.804613  
loss of epoch:492 2.802217  
loss of epoch:493 2.7998192  
loss of epoch:494 2.797426  
loss of epoch:495 2.7950325  
loss of epoch:496 2.7926428  
loss of epoch:497 2.790254  
loss of epoch:498 2.7878704  
loss of epoch:499 2.7854843  
loss of epoch:500 2.783101  
loss of epoch:501 2.780721  
loss of epoch:502 2.7783442  
loss of epoch:503 2.7759671  
loss of epoch:504 2.7735934  
loss of epoch:505 2.7712238  
loss of epoch:506 2.7688518  
loss of epoch:507 2.766482  
loss of epoch:508 2.7641172  
loss of epoch:509 2.7617514  
loss of epoch:510 2.7593904  
loss of epoch:511 2.7570305  
loss of epoch:512 2.7546735  
loss of epoch:513 2.7523162  
loss of epoch:514 2.7499635  
loss of epoch:515 2.7476122  
loss of epoch:516 2.745262  
loss of epoch:517 2.7429187  
loss of epoch:518 2.7405677  
loss of epoch:519 2.7382245  
loss of epoch:520 2.7358842  
loss of epoch:521 2.7335453  
loss of epoch:522 2.7312057  
loss of epoch:523 2.7288716  
loss of epoch:524 2.726539  
loss of epoch:525 2.724204  
loss of epoch:526 2.7218754  
loss of epoch:527 2.7195456  
loss of epoch:528 2.7172222  
loss of epoch:529 2.7148974  
loss of epoch:530 2.7125773  
loss of epoch:531 2.7102542  
loss of epoch:532 2.7079399  
loss of epoch:533 2.7056231  
loss of epoch:534 2.7033086  
loss of epoch:535 2.7009952  
loss of epoch:536 2.6986868  
loss of epoch:537 2.696378  
loss of epoch:538 2.6940732  
loss of epoch:539 2.691771  
loss of epoch:540 2.689467  
loss of epoch:541 2.687167  
loss of epoch:542 2.6848686  
loss of epoch:543 2.6825724  
loss of epoch:544 2.6802776  
loss of epoch:545 2.677985  
loss of epoch:546 2.6756957  
loss of epoch:547 2.6734054  
loss of epoch:548 2.6711204  
loss of epoch:549 2.668836  
loss of epoch:550 2.6665533  
loss of epoch:551 2.6642737  
loss of epoch:552 2.6619947  
loss of epoch:553 2.6597195  
loss of epoch:554 2.6574454  
loss of epoch:555 2.6551702  
loss of epoch:556 2.6528995  
loss of epoch:557 2.6506321  
loss of epoch:558 2.648365  
loss of epoch:559 2.6461003  
loss of epoch:560 2.6438365  
loss of epoch:561 2.6415737  
loss of epoch:562 2.639318  
loss of epoch:563 2.6370578  
loss of epoch:564 2.634805  
loss of epoch:565 2.6325505  
loss of epoch:566 2.6303008  
loss of epoch:567 2.6280513  
loss of epoch:568 2.625803  
loss of epoch:569 2.623558  
loss of epoch:570 2.6213145  
loss of epoch:571 2.6190708  
loss of epoch:572 2.6168284  
loss of epoch:573 2.6145942  
loss of epoch:574 2.6123586  
loss of epoch:575 2.6101227  
loss of epoch:576 2.6078916  
loss of epoch:577 2.60566  
loss of epoch:578 2.6034312  
loss of epoch:579 2.6012058  
loss of epoch:580 2.5989802  
loss of epoch:581 2.5967584  
loss of epoch:582 2.5945385  
loss of epoch:583 2.592321  
loss of epoch:584 2.5901027  
loss of epoch:585 2.5878878  
loss of epoch:586 2.5856743  
loss of epoch:587 2.5834627  
loss of epoch:588 2.5812538  
loss of epoch:589 2.5790458  
loss of epoch:590 2.576842  
loss of epoch:591 2.574636  
loss of epoch:592 2.572435  
loss of epoch:593 2.5702367  
loss of epoch:594 2.5680366  
loss of epoch:595 2.565841  
loss of epoch:596 2.5636463  
loss of epoch:597 2.5614529  
loss of epoch:598 2.5592637  
loss of epoch:599 2.5570755  
loss of epoch:600 2.5548873  
loss of epoch:601 2.5527036  
loss of epoch:602 2.5505192  
loss of epoch:603 2.5483375  
loss of epoch:604 2.5461586  
loss of epoch:605 2.543981  
loss of epoch:606 2.5418067  
loss of epoch:607 2.5396333  
loss of epoch:608 2.5374608  
loss of epoch:609 2.5352905  
loss of epoch:610 2.5331225  
loss of epoch:611 2.5309563  
loss of epoch:612 2.528791  
loss of epoch:613 2.5266292  
loss of epoch:614 2.5244663  
loss of epoch:615 2.522308  
loss of epoch:616 2.520151  
loss of epoch:617 2.5179949  
loss of epoch:618 2.5158439  
loss of epoch:619 2.513691  
loss of epoch:620 2.5115404  
loss of epoch:621 2.5093942  
loss of epoch:622 2.507247  
loss of epoch:623 2.505104  
loss of epoch:624 2.5029604  
loss of epoch:625 2.5008206  
loss of epoch:626 2.4986813  
loss of epoch:627 2.4965425  
loss of epoch:628 2.494411  
loss of epoch:629 2.4922762  
loss of epoch:630 2.490144  
loss of epoch:631 2.4880161  
loss of epoch:632 2.4858885  
loss of epoch:633 2.4837613  
loss of epoch:634 2.4816365  
loss of epoch:635 2.4795148  
loss of epoch:636 2.4773965  
loss of epoch:637 2.4752753  
loss of epoch:638 2.4731586  
loss of epoch:639 2.4710436  
loss of epoch:640 2.468931  
loss of epoch:641 2.4668198  
loss of epoch:642 2.4647093  
loss of epoch:643 2.4625998  
loss of epoch:644 2.4604955  
loss of epoch:645 2.458391  
loss of epoch:646 2.456288  
loss of epoch:647 2.4541893  
loss of epoch:648 2.4520888  
loss of epoch:649 2.4499896  
loss of epoch:650 2.4478965  
loss of epoch:651 2.4458034  
loss of epoch:652 2.4437118  
loss of epoch:653 2.4416206  
loss of epoch:654 2.4395328  
loss of epoch:655 2.437446  
loss of epoch:656 2.4353633  
loss of epoch:657 2.4332795  
loss of epoch:658 2.4311981  
loss of epoch:659 2.4291215  
loss of epoch:660 2.427041  
loss of epoch:661 2.4249656  
loss of epoch:662 2.422892  
loss of epoch:663 2.4208226  
loss of epoch:664 2.4187498  
loss of epoch:665 2.4166825  
loss of epoch:666 2.4146156  
loss of epoch:667 2.412552  
loss of epoch:668 2.4104874  
loss of epoch:669 2.4084268  
loss of epoch:670 2.4063647  
loss of epoch:671 2.4043088  
loss of epoch:672 2.4022503  
loss of epoch:673 2.400196  
loss of epoch:674 2.3981452  
loss of epoch:675 2.3960958  
loss of epoch:676 2.3940449  
loss of epoch:677 2.3919992  
loss of epoch:678 2.3899512  
loss of epoch:679 2.3879068  
loss of epoch:680 2.3858652  
loss of epoch:681 2.3838258  
loss of epoch:682 2.3817866  
loss of epoch:683 2.3797495  
loss of epoch:684 2.377715  
loss of epoch:685 2.3756824  
loss of epoch:686 2.3736482  
loss of epoch:687 2.3716178  
loss of epoch:688 2.3695903  
loss of epoch:689 2.3675637  
loss of epoch:690 2.36554  
loss of epoch:691 2.3635173  
loss of epoch:692 2.3614955  
loss of epoch:693 2.3594766  
loss of epoch:694 2.3574584  
loss of epoch:695 2.3554416  
loss of epoch:696 2.3534284  
loss of epoch:697 2.3514132  
loss of epoch:698 2.3494053  
loss of epoch:699 2.3473935  
loss of epoch:700 2.345387  
loss of epoch:701 2.3433793  
loss of epoch:702 2.341378  
loss of epoch:703 2.339374  
loss of epoch:704 2.3373752  
loss of epoch:705 2.335375  
loss of epoch:706 2.3333776  
loss of epoch:707 2.3313804  
loss of epoch:708 2.3293865  
loss of epoch:709 2.3273973  
loss of epoch:710 2.325405  
loss of epoch:711 2.3234181  
loss of epoch:712 2.3214307  
loss of epoch:713 2.3194447  
loss of epoch:714 2.3174615  
loss of epoch:715 2.3154793  
loss of epoch:716 2.3134983  
loss of epoch:717 2.311522  
loss of epoch:718 2.309544  
loss of epoch:719 2.3075686  
loss of epoch:720 2.305595  
loss of epoch:721 2.303624  
loss of epoch:722 2.3016522  
loss of epoch:723 2.299684  
loss of epoch:724 2.2977202  
loss of epoch:725 2.295753  
loss of epoch:726 2.2937903  
loss of epoch:727 2.2918274  
loss of epoch:728 2.2898684  
loss of epoch:729 2.28791  
loss of epoch:730 2.2859514  
loss of epoch:731 2.283998  
loss of epoch:732 2.2820437  
loss of epoch:733 2.2800949  
loss of epoch:734 2.2781436  
loss of epoch:735 2.2761958  
loss of epoch:736 2.2742476  
loss of epoch:737 2.2723038  
loss of epoch:738 2.2703595  
loss of epoch:739 2.2684183  
loss of epoch:740 2.2664766  
loss of epoch:741 2.26454  
loss of epoch:742 2.2626023  
loss of epoch:743 2.2606695  
loss of epoch:744 2.258735  
loss of epoch:745 2.2568028  
loss of epoch:746 2.2548733  
loss of epoch:747 2.2529428  
loss of epoch:748 2.2510183  
loss of epoch:749 2.249093  
loss of epoch:750 2.2471676  
loss of epoch:751 2.245246  
loss of epoch:752 2.243327  
loss of epoch:753 2.241408  
loss of epoch:754 2.2394915  
loss of epoch:755 2.2375753  
loss of epoch:756 2.235662  
loss of epoch:757 2.2337508  
loss of epoch:758 2.2318404  
loss of epoch:759 2.2299333  
loss of epoch:760 2.228025  
loss of epoch:761 2.226119  
loss of epoch:762 2.2242157  
loss of epoch:763 2.2223125  
loss of epoch:764 2.220412  
loss of epoch:765 2.2185142  
loss of epoch:766 2.2166176  
loss of epoch:767 2.2147217  
loss of epoch:768 2.2128286  
loss of epoch:769 2.2109334  
loss of epoch:770 2.209044  
loss of epoch:771 2.2071538  
loss of epoch:772 2.2052655  
loss of epoch:773 2.2033813  
loss of epoch:774 2.201496  
loss of epoch:775 2.1996145  
loss of epoch:776 2.197732  
loss of epoch:777 2.1958518  
loss of epoch:778 2.193974  
loss of epoch:779 2.1920998  
loss of epoch:780 2.1902213  
loss of epoch:781 2.1883502  
loss of epoch:782 2.186479  
loss of epoch:783 2.184609  
loss of epoch:784 2.1827407  
loss of epoch:785 2.180875  
loss of epoch:786 2.1790097  
loss of epoch:787 2.1771462  
loss of epoch:788 2.1752841  
loss of epoch:789 2.173425  
loss of epoch:790 2.1715665  
loss of epoch:791 2.1697078  
loss of epoch:792 2.1678538  
loss of epoch:793 2.1659985  
loss of epoch:794 2.164145  
loss of epoch:795 2.1622968  
loss of epoch:796 2.160446  
loss of epoch:797 2.1585977  
loss of epoch:798 2.1567514  
loss of epoch:799 2.1549082  
loss of epoch:800 2.1530643  
loss of epoch:801 2.151225  
loss of epoch:802 2.1493824  
loss of epoch:803 2.1475444  
loss of epoch:804 2.1457086  
loss of epoch:805 2.1438754  
loss of epoch:806 2.1420398  
loss of epoch:807 2.1402087  
loss of epoch:808 2.1383796  
loss of epoch:809 2.1365485  
loss of epoch:810 2.1347213  
loss of epoch:811 2.132896  
loss of epoch:812 2.1310744  
loss of epoch:813 2.1292503  
loss of epoch:814 2.1274266  
loss of epoch:815 2.125608  
loss of epoch:816 2.1237917  
loss of epoch:817 2.121977  
loss of epoch:818 2.1201613  
loss of epoch:819 2.1183486  
loss of epoch:820 2.116536  
loss of epoch:821 2.1147265  
loss of epoch:822 2.112917  
loss of epoch:823 2.1111112  
loss of epoch:824 2.1093051  
loss of epoch:825 2.1074996  
loss of epoch:826 2.105698  
loss of epoch:827 2.1038988  
loss of epoch:828 2.102098  
loss of epoch:829 2.1003003  
loss of epoch:830 2.0985038  
loss of epoch:831 2.0967083  
loss of epoch:832 2.094917  
loss of epoch:833 2.093125  
loss of epoch:834 2.091335  
loss of epoch:835 2.0895476  
loss of epoch:836 2.08776  
loss of epoch:837 2.0859742  
loss of epoch:838 2.0841908  
loss of epoch:839 2.0824084  
loss of epoch:840 2.080627  
loss of epoch:841 2.0788474  
loss of epoch:842 2.077071  
loss of epoch:843 2.0752943  
loss of epoch:844 2.0735185  
loss of epoch:845 2.0717459  
loss of epoch:846 2.069972  
loss of epoch:847 2.0682034  
loss of epoch:848 2.0664353  
loss of epoch:849 2.0646682  
loss of epoch:850 2.0629022  
loss of epoch:851 2.061138  
loss of epoch:852 2.0593762  
loss of epoch:853 2.057612  
loss of epoch:854 2.0558524  
loss of epoch:855 2.0540957  
loss of epoch:856 2.0523384  
loss of epoch:857 2.0505834  
loss of epoch:858 2.04883  
loss of epoch:859 2.0470767  
loss of epoch:860 2.0453277  
loss of epoch:861 2.0435767  
loss of epoch:862 2.0418317  
loss of epoch:863 2.0400836  
loss of epoch:864 2.0383396  
loss of epoch:865 2.036597  
loss of epoch:866 2.0348544  
loss of epoch:867 2.033114  
loss of epoch:868 2.0313725  
loss of epoch:869 2.0296385  
loss of epoch:870 2.0279016  
loss of epoch:871 2.0261688  
loss of epoch:872 2.0244339  
loss of epoch:873 2.0227032  
loss of epoch:874 2.0209737  
loss of epoch:875 2.0192437  
loss of epoch:876 2.017517  
loss of epoch:877 2.0157914  
loss of epoch:878 2.0140681  
loss of epoch:879 2.0123475  
loss of epoch:880 2.0106254  
loss of epoch:881 2.008905  
loss of epoch:882 2.0071874  
loss of epoch:883 2.0054734  
loss of epoch:884 2.003757  
loss of epoch:885 2.0020432  
loss of epoch:886 2.0003304  
loss of epoch:887 1.9986191  
loss of epoch:888 1.9969124  
loss of epoch:889 1.9952036  
loss of epoch:890 1.9934963  
loss of epoch:891 1.9917911  
loss of epoch:892 1.9900875  
loss of epoch:893 1.988385  
loss of epoch:894 1.9866848  
loss of epoch:895 1.9849854  
loss of epoch:896 1.9832901  
loss of epoch:897 1.9815929  
loss of epoch:898 1.9798973  
loss of epoch:899 1.9782045  
loss of epoch:900 1.9765141  
loss of epoch:901 1.9748211  
loss of epoch:902 1.9731343  
loss of epoch:903 1.9714489  
loss of epoch:904 1.9697602  
loss of epoch:905 1.9680765  
loss of epoch:906 1.9663947  
loss of epoch:907 1.9647114  
loss of epoch:908 1.9630312  
loss of epoch:909 1.961353  
loss of epoch:910 1.9596736  
loss of epoch:911 1.9579973  
loss of epoch:912 1.9563224  
loss of epoch:913 1.9546516  
loss of epoch:914 1.9529778  
loss of epoch:915 1.951308  
loss of epoch:916 1.9496393  
loss of epoch:917 1.9479725  
loss of epoch:918 1.9463075  
loss of epoch:919 1.9446414  
loss of epoch:920 1.9429792  
loss of epoch:921 1.9413185  
loss of epoch:922 1.9396584  
loss of epoch:923 1.9379995  
loss of epoch:924 1.9363407  
loss of epoch:925 1.9346844  
loss of epoch:926 1.9330313  
loss of epoch:927 1.9313778  
loss of epoch:928 1.9297266  
loss of epoch:929 1.9280758  
loss of epoch:930 1.9264256  
loss of epoch:931 1.9247792  
loss of epoch:932 1.9231342  
loss of epoch:933 1.9214885  
loss of epoch:934 1.9198459  
loss of epoch:935 1.9182026  
loss of epoch:936 1.9165637  
loss of epoch:937 1.9149239  
loss of epoch:938 1.9132874  
loss of epoch:939 1.9116509  
loss of epoch:940 1.9100158  
loss of epoch:941 1.908382  
loss of epoch:942 1.906748  
loss of epoch:943 1.905119  
loss of epoch:944 1.9034903  
loss of epoch:945 1.9018608  
loss of epoch:946 1.900234  
loss of epoch:947 1.8986107  
loss of epoch:948 1.8969872  
loss of epoch:949 1.8953645  
loss of epoch:950 1.8937432  
loss of epoch:951 1.8921232  
loss of epoch:952 1.8905051  
loss of epoch:953 1.8888891  
loss of epoch:954 1.8872732  
loss of epoch:955 1.8856598  
loss of epoch:956 1.8840477  
loss of epoch:957 1.8824329  
loss of epoch:958 1.880825  
loss of epoch:959 1.8792171  
loss of epoch:960 1.8776115  
loss of epoch:961 1.8760014  
loss of epoch:962 1.8743998  
loss of epoch:963 1.8727987  
loss of epoch:964 1.8711939  
loss of epoch:965 1.8695949  
loss of epoch:966 1.8679974  
loss of epoch:967 1.8663985  
loss of epoch:968 1.8648036  
loss of epoch:969 1.8632065  
loss of epoch:970 1.8616135  
loss of epoch:971 1.8600212  
loss of epoch:972 1.8584316  
loss of epoch:973 1.8568414  
loss of epoch:974 1.8552551  
loss of epoch:975 1.8536685  
loss of epoch:976 1.8520826  
loss of epoch:977 1.850497  
loss of epoch:978 1.8489163  
loss of epoch:979 1.8473351  
loss of epoch:980 1.8457537  
loss of epoch:981 1.8441753  
loss of epoch:982 1.8425993  
loss of epoch:983 1.8410227  
loss of epoch:984 1.8394489  
loss of epoch:985 1.8378757  
loss of epoch:986 1.8363028  
loss of epoch:987 1.8347323  
loss of epoch:988 1.833163  
loss of epoch:989 1.831596  
loss of epoch:990 1.830031  
loss of epoch:991 1.8284651  
loss of epoch:992 1.8269017  
loss of epoch:993 1.8253391  
loss of epoch:994 1.8237774  
loss of epoch:995 1.8222183  
loss of epoch:996 1.8206571  
loss of epoch:997 1.8191016  
loss of epoch:998 1.8175468  
loss of epoch:999 1.8159921  
