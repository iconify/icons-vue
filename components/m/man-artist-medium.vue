<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iQiRM2d)" class="zbs2xvbkg"/><path fill="url(#inA3Tpe)" class="zbs2xvbkg"/><path fill="url(#iP1im0c)" class="zbs2xvbkg"/><path fill="url(#i04jDnj)" class="zbs2xvbkg"/><g filter="url(#imZKzXb)"><path class="wwkh3zbvl"/></g><ellipse fill="url(#iH5vZSd)" class="kfex23bvh"/><ellipse fill="url(#imcDDId)" class="kfex23bvh"/><g filter="url(#iR5JtWd)"><ellipse stroke="url(#iegz2Cc)" class="n39vpub1b"/></g><g filter="url(#itYkbtb)"><path fill="url(#iZYJJTd)" class="fawsh83wa"/><path fill="url(#in5HY3d)" class="fawsh83wa"/></g><g filter="url(#i5rnmIb)"><path fill="url(#iCgYo9c)" class="qs7c013mg"/><path fill="url(#izKufic)" class="qs7c013mg"/><path fill="url(#i8efCLe)" class="qs7c013mg"/></g><path fill="url(#iNVDMJc)" class="ekxbkpvzc"/><g filter="url(#iKogaqc)"><path fill="url(#iIo36rp)" class="pepvmtr_g"/><path fill="url(#ignAelv)" class="pepvmtr_g"/></g><path fill="url(#iqkeVzb)" class="l29svp3cg"/><path fill="url(#ib6zMLd)" class="l29svp3cg"/><g filter="url(#in2gR0b)"><path fill="url(#izcCUib)" class="vx8yiwdcw"/></g><g filter="url(#iIFkxtc)"><path class="oh_l9db2x"/></g><g filter="url(#i50ZSZd)"><path class="teu3yl5ky"/></g><g filter="url(#iXFLAbc)"><path class="waw2uhbiy"/></g><g filter="url(#ivQ05Vb)"><path fill="url(#iea8yte)" class="r7o-r9bxt"/></g><path fill="url(#iYATpic)" class="r7o-r9bxt"/><g filter="url(#iHAZ4LP)"><path fill="url(#iyQIgyc)" class="k1aaqobwu"/></g><g filter="url(#iDBJTld)"><path fill="url(#iO8TsTc)" class="i20220bfm"/></g><path fill="url(#i4gM3yb)" class="i20220bfm"/><g filter="url(#iu6Bhvd)"><path fill="url(#i8cCt7d)" class="fomm8__lp"/></g><path fill="url(#i5sdV9b)" class="hfzp6f8qe"/><path fill="url(#ipDnGwe)" class="hfzp6f8qe"/><path fill="url(#iTfdAvb)" class="kb0m86bqf"/><path fill="url(#iTkYgvd)" class="kb0m86bqf"/><path fill="url(#iqMfzad)" class="kb0m86bqf"/><path fill="url(#ikQR2ae)" class="s80w1fafw"/><path fill="url(#iMs2ZOe)" class="s80w1fafw"/><g filter="url(#iqqGUXp)"><path fill="url(#i1FSYJc)" class="iouks0fsc"/><path fill="url(#iZLdWle)" class="iouks0fsc"/><path fill="url(#iZaoaBd)" class="iouks0fsc"/><path fill="url(#iP3rqkj)" class="iouks0fsc"/></g><path fill="url(#ieEgdTd)" class="yf6m5abnn"/><g filter="url(#i82iWBp)"><path fill="url(#iSbgAfc)" class="uhuv92bap"/><path fill="url(#ibiMAze)" class="uhuv92bap"/><path fill="url(#iR3m9Xd)" class="uhuv92bap"/><path fill="url(#ixbEKEd)" class="uhuv92bap"/></g><g filter="url(#ihJF0xd)"><path fill="url(#iZhxhxc)" class="m2-b5ia7e"/><path fill="url(#i7IXbwv)" class="m2-b5ia7e"/><path fill="url(#iKkzrpi)" class="m2-b5ia7e"/><path fill="url(#ibg8boe)" class="m2-b5ia7e"/><path fill="url(#iLHHOUb)" class="m2-b5ia7e"/></g><g filter="url(#ij7XIPc)"><path stroke="url(#iLqYavd)" class="ct65j078y"/></g><g filter="url(#iSCXlZI)"><path stroke="url(#i1gnNXd)" class="ze5nteb_r"/></g><g filter="url(#ibGhYdc)"><path stroke="url(#ipiokXd)" class="jz78atb4u"/></g><g filter="url(#inTQPVd)"><circle fill="url(#io6yS1b)" class="wv27mz0pi"/></g><circle fill="url(#ilf9uJe)" class="wv27mz0pi"/><g filter="url(#ioCiC2l)"><circle fill="url(#i4vEbLc)" class="texw1bcue"/></g><g filter="url(#iaZWjOc)"><circle fill="url(#io7Hkgd)" class="lv1npcbsj"/><circle fill="url(#iUIKnqW)" class="lv1npcbsj"/></g><g filter="url(#ihjSrQe)"><circle class="leyigij6x"/><circle fill="url(#ipvMsJb)" class="exojo5a8m"/><circle fill="url(#iCEk2Ec)" class="exojo5a8m"/></g><g filter="url(#ikwdEzc)"><path fill="url(#iJ3IYxc)" class="wc--hsb7w"/></g><path fill="url(#i1OeKvc)" class="ir0pz063d"/><g filter="url(#imvUUJe)"><path fill="url(#iwZwMJd)" class="ksnzfuvpq"/><path fill="url(#iGA0chd)" class="ksnzfuvpq"/><path fill="url(#iX7QZdt)" class="ksnzfuvpq"/></g><path fill="url(#iFluf7c)" class="fi19pcb6g"/><path fill="url(#icwDUPd)" class="fi19pcb6g"/><path fill="url(#iwHC5Hb)" class="fi19pcb6g"/><g filter="url(#iUWUtOJ)"><path fill="url(#iesUUJe)" class="lyih03bvp"/></g><g filter="url(#iGA1NBb)"><path class="lodz1sy7q"/></g><g filter="url(#iUSDKlb)"><path class="cvqcwxbfq"/><path fill="url(#iVJCUIw)" class="y-qxhx9ay"/><path fill="url(#itutUJc)" class="y-qxhx9ay"/><path fill="url(#i3A38He)" class="y-qxhx9ay"/><path fill="url(#iH0C3Jb)" class="y-qxhx9ay"/></g><path fill="url(#ic22FVs)" class="y-qxhx9ay"/><path stroke="url(#ieEdsAe)" class="mkl0r8bng"/><g filter="url(#iWGxgkc)"><path class="l4wjmrs5x"/><path fill="url(#ikGhOyb)" class="z4b94lb8c"/></g><g filter="url(#ilwo8kc)"><path class="ouhqh83ix"/><path fill="url(#igmY1SL)" class="wufia9b2s"/></g><path class="knc82vlsg"/><path fill="url(#izjjhFe)" class="bgh3macub"/><path class="ryd5b_bne"/><g filter="url(#ibR84Ge)"><path class="apk9rvb8y"/><path fill="url(#iwELFdd)" class="bp5y5pbyn"/></g><g filter="url(#i4YLAhe)"><path fill="url(#iTczUKb)" class="pjlu7m_qy"/></g><path class="olk_5de9e"/><path fill="url(#iThjnGe)" class="u041s1kzn"/><path class="vso1ahb2m"/><g filter="url(#is8Kpbd)"><path fill="url(#i1WDBjd)" class="wxv9-xfzb"/></g><g filter="url(#iUwbNhe)"><ellipse transform="rotate(-27.914 13.678 9.873)" class="po_n49r6a"/><ellipse fill="url(#itA57ce)" transform="rotate(-27.914 13.678 9.873)" class="kv4hz_bvz"/></g><g filter="url(#i9XAVvb)"><path stroke="url(#ipj3YZd)" class="isuxr-mqn"/></g><g filter="url(#ihCfSMe)"><path stroke="url(#iK9v5ab)" class="kl6jbhbtl"/></g><path class="mk9cbeb_z"/><path fill="url(#iLkxb5d)" class="tpv18l7lf"/><g filter="url(#iyIgd2c)"><path fill="url(#iwfm65c)" class="s3g09k5mk"/></g><g filter="url(#i8qDHde)"><path fill="url(#in6AZkm)" class="a3lgdnbbr"/></g><defs><radialGradient id="iQiRM2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5008 14.4291 0 19.814 29.974)" gradientUnits="userSpaceOnUse"><stop class="vq38zyg1v"/><stop offset=".574" class="xc8aunbib"/></radialGradient><radialGradient id="inA3Tpe" cx="0" cy="0" r="1" gradientTransform="matrix(6.25665 1.2745 -1.23055 6.0409 8.305 19.512)" gradientUnits="userSpaceOnUse"><stop class="wb9dsybrx"/><stop offset="1" class="ahmnpcbvc"/></radialGradient><radialGradient id="iP1im0c" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6815 -14.49994 16.74587 -7.7164 19.235 29.974)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="ue4dcor2v"/><stop offset="1" class="l7qllmb5o"/></radialGradient><radialGradient id="i04jDnj" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.5561 -3.36712 0 23.143 21.212)" gradientUnits="userSpaceOnUse"><stop class="smyxk1pmd"/><stop offset="1" class="g5cj4-btu"/></radialGradient><radialGradient id="imcDDId" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.9375 -5.90625 0 16.143 16.723)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ta7eky02w"/><stop offset="1" class="j0piksb8i"/></radialGradient><radialGradient id="iZYJJTd" cx="0" cy="0" r="1" gradientTransform="rotate(121.17 1.805 14.742)scale(3.39503 1.76158)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="b_wctrb8k"/><stop offset=".826" class="q90xsjbgn"/></radialGradient><radialGradient id="in5HY3d" cx="0" cy="0" r="1" gradientTransform="rotate(68.848 -6.421 21.023)scale(1.84199 .94148)" gradientUnits="userSpaceOnUse"><stop offset=".43" class="jvqqj3hdm"/><stop offset="1" class="w_jg8bumh"/></radialGradient><radialGradient id="iCgYo9c" cx="0" cy="0" r="1" gradientTransform="rotate(62.84 -7.503 24.694)scale(4.03912 1.93026)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="ccy1m_asd"/><stop offset="1" class="yan0zenen"/></radialGradient><radialGradient id="i8efCLe" cx="0" cy="0" r="1" gradientTransform="matrix(.66907 .71875 -.43642 .40625 18.111 20.55)" gradientUnits="userSpaceOnUse"><stop class="pjwz_ic9q"/><stop offset="1" class="acw_xab5u"/></radialGradient><radialGradient id="iNVDMJc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.439 22.105 5.06)scale(4.7509 1.9254)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="glav2bc0u"/><stop offset="1" class="p_p7u6byq"/></radialGradient><radialGradient id="ignAelv" cx="0" cy="0" r="1" gradientTransform="matrix(-.44275 1.19364 -.36328 -.13475 17.117 19.488)" gradientUnits="userSpaceOnUse"><stop class="eq8448bna"/><stop offset="1" class="qn-z6_0fu"/></radialGradient><radialGradient id="iea8yte" cx="0" cy="0" r="1" gradientTransform="matrix(-.26 1.96876 -1.77419 -.2343 8.643 23.315)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="f82vlntau"/><stop offset="1" class="d1l_oobjb"/></radialGradient><radialGradient id="iYATpic" cx="0" cy="0" r="1" gradientTransform="rotate(-39.218 38.122 .876)scale(1.7546 2.0006)" gradientUnits="userSpaceOnUse"><stop offset=".574" class="mbdolbbcq"/><stop offset="1" class="hdm7u0bdo"/></radialGradient><radialGradient id="iyQIgyc" cx="0" cy="0" r="1" gradientTransform="matrix(1.23999 2.33168 -1.89085 1.00556 11.383 25.784)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="j-p-7tbjt"/><stop offset="1" class="ku_74wg1j"/></radialGradient><radialGradient id="iO8TsTc" cx="0" cy="0" r="1" gradientTransform="rotate(133.958 -1.608 15.312)scale(2.43108 1.88477)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="ukhbhfbdb"/><stop offset="1" class="ngwdu-l5j"/></radialGradient><radialGradient id="i4gM3yb" cx="0" cy="0" r="1" gradientTransform="matrix(1.8081 -.98438 1.04155 1.91313 6.814 28.363)" gradientUnits="userSpaceOnUse"><stop offset=".819" class="tx_tdxoal"/><stop offset="1" class="j_c7fcbhg"/></radialGradient><radialGradient id="i8cCt7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42193 -3.27267 0 16.143 17.096)" gradientUnits="userSpaceOnUse"><stop offset=".395" class="k_7ebwbkf"/><stop offset="1" class="pewrncjnt"/></radialGradient><radialGradient id="i5sdV9b" cx="0" cy="0" r="1" gradientTransform="rotate(145.688 10.869 16.305)scale(2.34093 2.29861)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="ipDnGwe" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .44475 .58411 28.466 23.5)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="iTfdAvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.44558 -1.78271 0 25.143 23.529)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="nqi0jc4ki"/><stop offset="1" class="vbxkmpbas"/></radialGradient><radialGradient id="ikQR2ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.03125 -1.25369 0 27.018 21.785)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="jujuy5bla"/><stop offset="1" class="e7xip1bbn"/></radialGradient><radialGradient id="iZLdWle" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.22231 -.54688 0 26.69 18.735)" gradientUnits="userSpaceOnUse"><stop class="qbo0gacsu"/><stop offset="1" class="codu-dcmv"/></radialGradient><radialGradient id="iZaoaBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.03572 .55078 -.83966 -.05446 26.389 18.816)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="y3oq4nb4y"/><stop offset="1" class="js7kctros"/></radialGradient><radialGradient id="ieEgdTd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38869 -2.63745 3.16971 -1.66894 27.232 19.125)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="d7q2h2w-e"/><stop offset="1" class="wxo_vcdjw"/></radialGradient><radialGradient id="iSbgAfc" cx="0" cy="0" r="1" gradientTransform="rotate(149.211 11.54 12.328)scale(2.25809 2.54697)" gradientUnits="userSpaceOnUse"><stop class="tm2bmw9uh"/><stop offset="1" class="zxeleub3j"/></radialGradient><radialGradient id="ibiMAze" cx="0" cy="0" r="1" gradientTransform="rotate(-157.433 16.015 5.594)scale(2.84995 2.97831)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="l21dfeb9j"/><stop offset="1" class="el-cg1bcl"/></radialGradient><radialGradient id="iR3m9Xd" cx="0" cy="0" r="1" gradientTransform="matrix(.68035 .40317 -.6454 1.0891 28.672 15.612)" gradientUnits="userSpaceOnUse"><stop offset=".642" class="vn0ta5bom"/><stop offset="1" class="y_e8mrzhh"/></radialGradient><radialGradient id="ixbEKEd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0009 1.0903 -.16655 -.1529 28.4 14.736)" gradientUnits="userSpaceOnUse"><stop class="jyboxmbnp"/><stop offset="1" class="v3wx_yddl"/></radialGradient><radialGradient id="i7IXbwv" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.47311 0 26.656 25.28)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iKkzrpi" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.57908 0 26.656 26.573)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="ibg8boe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.32068 0 26.656 27.823)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iLHHOUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.8787 0 26.656 29.175)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="io6yS1b" cx="0" cy="0" r="1" gradientTransform="matrix(1.75472 0 0 3.07077 9.716 10.651)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="ilf9uJe" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 8.9 3.196)scale(1.6566)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="iUIKnqW" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 21.27 10.386)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="ipvMsJb" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.857 11.472)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="iCEk2Ec" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.501 30.735)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iJ3IYxc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.59375 -.72995 0 21.234 6.957)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="n8uelqbwq"/><stop offset="1" class="s0afa-bxm"/></radialGradient><radialGradient id="i1OeKvc" cx="0" cy="0" r="1" gradientTransform="matrix(.125 2.15625 -.9303 .05393 11.362 8.894)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="jaxy4fb6n"/><stop offset="1" class="c4mux-6nt"/></radialGradient><radialGradient id="iGA0chd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 18.479 9.38)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="iX7QZdt" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37399 1.70868 0 13.921 9.514)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="iwHC5Hb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.32774 -10.3217 0 16.005 9.118)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="j_3ppvb6l"/><stop offset=".91" class="n9i8amb2u"/><stop offset=".985" class="q8-s_d5vk"/></radialGradient><radialGradient id="iH0C3Jb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 16.46 12.258)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="ikGhOyb" cx="0" cy="0" r="1" gradientTransform="matrix(.10418 -.60322 1.78457 .30822 18.576 8.567)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="igmY1SL" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 11.8 -3.69)scale(.61215 1.81109)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="izjjhFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 18.312 9.969)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iwELFdd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 18.084 10.053)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iThjnGe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 13.949 9.969)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="itA57ce" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.846 -1.631)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iLkxb5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.66487 -5.81608 0 15.975 6.574)" gradientUnits="userSpaceOnUse"><stop class="j-4y6njnd"/><stop offset="1" class="mywg7wbjh"/></radialGradient><radialGradient id="iwfm65c" cx="0" cy="0" r="1" gradientTransform="matrix(8.99875 0 0 2.97087 15.952 4.37)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><radialGradient id="in6AZkm" cx="0" cy="0" r="1" gradientTransform="rotate(170.731 6.377 3.233)scale(6.59378 2.26941)" gradientUnits="userSpaceOnUse"><stop class="b45v6hbpx"/><stop offset="1" class="n2f566bzz"/></radialGradient><filter id="imZKzXb" width="10.518" height="10.531" x="10.051" y="14.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".75"/></filter><filter id="iR5JtWd" width="8.987" height="5.737" x="11.649" y="14.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".2"/></filter><filter id="itYkbtb" width="2.812" height="4.17" x="13.354" y="19.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.0588235 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2393"/></filter><filter id="i5rnmIb" width="2.762" height="4.17" x="16.118" y="19.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.0470588 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2393"/></filter><filter id="iKogaqc" width="2.05" height="1.794" x="15.167" y="18.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.0941176 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2393"/></filter><filter id="in2gR0b" width="10.434" height="8.872" x="4.246" y="21.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.988235 0 0 0 0 0.678431 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.832289 0 0 0 0 0.679486 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2393" result="effect2_innerShadow_4002_2393"/></filter><filter id="iIFkxtc" width="2.78" height="2.78" x="6.922" y="22.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".075"/></filter><filter id="i50ZSZd" width="2.78" height="2.78" x="9.93" y="25.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".075"/></filter><filter id="iXFLAbc" width="2.78" height="2.78" x="5.919" y="26.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".075"/></filter><filter id="ivQ05Vb" width="2.58" height="2.68" x="7.143" y="22.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.290196 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2393" result="effect2_innerShadow_4002_2393"/></filter><filter id="iHAZ4LP" width="2.58" height="2.68" x="10.143" y="25.684" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.615686 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.427451 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2393" result="effect2_innerShadow_4002_2393"/></filter><filter id="iDBJTld" width="2.58" height="2.68" x="6.143" y="26.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.733333 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2393"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.596078 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2393" result="effect2_innerShadow_4002_2393"/></filter><filter id="iu6Bhvd" width="3.818" height="6.2" x="14.233" y="12.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.180392 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2393"/></filter><filter id="iqqGUXp" width="2.15" height="1.99" x="25.327" y="18.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2393"/></filter><filter id="i82iWBp" width="3.363" height="3.394" x="25.088" y="14.774" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.501961 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2393"/></filter><filter id="ihJF0xd" width="4.846" height="5.556" x="24.005" y="24.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.352941 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2393"/></filter><filter id="ij7XIPc" width="2.097" height=".3" x="24.375" y="25.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".05"/></filter><filter id="iSCXlZI" width="2.097" height=".3" x="24.297" y="27.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".05"/></filter><filter id="ibGhYdc" width="2.097" height=".3" x="24.375" y="28.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".05"/></filter><filter id="inTQPVd" width="3.539" height="3.339" x="9.716" y="8.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2393"/></filter><filter id="ioCiC2l" width="2.99" height="2.99" x="9.89" y="9.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".25"/></filter><filter id="iaZWjOc" width="3.589" height="3.589" x="19.229" y="8.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2393"/></filter><filter id="ihjSrQe" width="2.99" height="2.99" x="19.403" y="9.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".25"/></filter><filter id="ikwdEzc" width="2.025" height="4.023" x="20.504" y="6.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.105882 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2393"/></filter><filter id="imvUUJe" width="10.373" height="12.127" x="10.975" y="5.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2393"/></filter><filter id="iUWUtOJ" width="8.246" height="7.066" x="14.303" y="3.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation="1"/></filter><filter id="iGA1NBb" width="3.26" height="4.181" x="14.264" y="9.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".375"/></filter><filter id="iUSDKlb" width="2.377" height="3.181" x="14.945" y="9.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".125"/></filter><filter id="iWGxgkc" width="2.979" height="1.873" x="17.315" y="7.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2393"/></filter><filter id="ilwo8kc" width="2.98" height="1.873" x="12.168" y="7.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2393"/></filter><filter id="ibR84Ge" width=".787" height=".696" x="17.578" y="9.529" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".05"/></filter><filter id="i4YLAhe" width=".891" height=".913" x="18.417" y="9.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".1"/></filter><filter id="is8Kpbd" width=".986" height="1.04" x="13.976" y="9.541" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".1"/></filter><filter id="iUwbNhe" width=".913" height=".704" x="13.221" y="9.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".05"/></filter><filter id="i9XAVvb" width="2.449" height="1.031" x="17.493" y="7.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".1"/></filter><filter id="ihCfSMe" width="2.527" height="1.088" x="12.274" y="7.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".1"/></filter><filter id="iyIgd2c" width="9.346" height="5.558" x="14.326" y="1.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".5"/></filter><filter id="i8qDHde" width="7.084" height="4.956" x="8.009" y="3.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2393" stdDeviation=".75"/></filter><linearGradient id="iH5vZSd" x1="15.111" x2="19.58" y1="17.879" y2="17.879" gradientUnits="userSpaceOnUse"><stop class="qob7fubko"/><stop offset="1" class="g9vtwf9nq"/></linearGradient><linearGradient id="iegz2Cc" x1="13.162" x2="19.751" y1="17.691" y2="17.691" gradientUnits="userSpaceOnUse"><stop class="pr-l-mb5c"/><stop offset="1" class="bfk53cc2r"/></linearGradient><linearGradient id="izKufic" x1="16.549" x2="17.449" y1="19.058" y2="20.785" gradientUnits="userSpaceOnUse"><stop offset=".106" class="a4kimk95l"/><stop offset="1" class="z6d28bbdt"/></linearGradient><linearGradient id="iIo36rp" x1="16.342" x2="16.342" y1="20.414" y2="18.988" gradientUnits="userSpaceOnUse"><stop class="rcioyubpk"/><stop offset=".514" class="idowujb9l"/><stop offset="1" class="hhz1a6b2j"/></linearGradient><linearGradient id="iqkeVzb" x1="8.366" x2="8.366" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="ejom4oo7z"/><stop offset=".389" class="qmqo746eg"/><stop offset="1" class="kprsiwbrh"/></linearGradient><linearGradient id="ib6zMLd" x1="5.346" x2="5.346" y1="29.975" y2="29.6" gradientUnits="userSpaceOnUse"><stop class="gnozolbql"/><stop offset="1" class="vnvkvjbds"/></linearGradient><linearGradient id="izcCUib" x1="9.413" x2="9.413" y1="21.103" y2="29.975" gradientUnits="userSpaceOnUse"><stop class="n4l67hb-g"/><stop offset="1" class="lacq-oqha"/></linearGradient><linearGradient id="iTkYgvd" x1="22.942" x2="24.912" y1="24.61" y2="24.456" gradientUnits="userSpaceOnUse"><stop class="juq22w2kb"/><stop offset="1" class="c5twxuzif"/></linearGradient><linearGradient id="iqMfzad" x1="23.831" x2="23.831" y1="30.674" y2="28.202" gradientUnits="userSpaceOnUse"><stop class="u8zhdtbla"/><stop offset="1" class="izb4o5hjh"/></linearGradient><linearGradient id="iMs2ZOe" x1="26.353" x2="26.353" y1="20.724" y2="20.808" gradientUnits="userSpaceOnUse"><stop class="m9kxmpbyp"/><stop offset="1" class="nofcsmmpr"/></linearGradient><linearGradient id="i1FSYJc" x1="26.353" x2="27.83" y1="19.379" y2="19.379" gradientUnits="userSpaceOnUse"><stop class="fbd1ljb8v"/><stop offset="1" class="rubvd1wqd"/></linearGradient><linearGradient id="iP3rqkj" x1="26.502" x2="26.502" y1="20.724" y2="20.664" gradientUnits="userSpaceOnUse"><stop class="af9b0l-ho"/><stop offset="1" class="yck9m-swa"/></linearGradient><linearGradient id="iZhxhxc" x1="28.386" x2="24.005" y1="28.037" y2="28.037" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="a87gyab7w"/></linearGradient><linearGradient id="iLqYavd" x1="24.525" x2="26.234" y1="26.03" y2="26.03" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="i1gnNXd" x1="24.447" x2="26.156" y1="27.335" y2="27.335" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="ipiokXd" x1="24.525" x2="26.234" y1="28.64" y2="28.64" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="i4vEbLc" x1="11.385" x2="10.745" y1="10.93" y2="10.93" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="io7Hkgd" x1="21.984" x2="21.166" y1="9.56" y2="12.096" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="iwZwMJd" x1="20.169" x2="12.532" y1="11.04" y2="12.178" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="iFluf7c" x1="10.738" x2="12.619" y1="13.736" y2="13.669" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="icwDUPd" x1="21.053" x2="19.941" y1="12.895" y2="12.798" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="iesUUJe" x1="15.601" x2="23.745" y1="8.056" y2="5.14" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="iVJCUIw" x1="15.269" x2="16.207" y1="11.7" y2="11.7" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="itutUJc" x1="17.071" x2="16.046" y1="12.022" y2="12.007" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="i3A38He" x1="16.327" x2="16.327" y1="12.764" y2="12.191" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="ic22FVs" x1="16.259" x2="16.259" y1="12.806" y2="12.639" gradientUnits="userSpaceOnUse"><stop class="kpt7nxbeg"/><stop offset="1" class="c70lx944e"/></linearGradient><linearGradient id="ieEdsAe" x1="15.096" x2="15.531" y1="14.379" y2="13.692" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iTczUKb" x1="19.089" x2="18.776" y1="10.023" y2="10.216" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1WDBjd" x1="14.693" x2="14.379" y1="10.023" y2="10.216" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ipj3YZd" x1="19.105" x2="18.685" y1="7.884" y2="7.025" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iK9v5ab" x1="13.801" x2="12.612" y1="7.756" y2="7.257" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-artist-medium" /></template>
<style>
.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a3lgdnbbr {
  d: path("M13.015 4.726c-.973-.093-2.504.103-3.147.212c-.174.136-.48.541-.31 1.082c.17.54.574.65.754.637c3.302-.637 3.92-1.815 2.703-1.931");
}

.a4kimk95l {
  stop-color: var(--svg-color--e73a62, #E73A62);
}

.a87gyab7w {
  stop-color: var(--svg-color--a57c6f, #A57C6F);
}

.acw_xab5u {
  stop-color: var(--svg-color--ed577d, #ED577D);
  stop-opacity: 0;
}

.af9b0l-ho {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
}

.ahmnpcbvc {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
  stop-opacity: 0;
}

.apk9rvb8y {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.248 9.68c.064.086-.07.19-.22.302c-.151.113-.263.193-.327.108s.007-.246.159-.359c.15-.113.325-.135.388-.05");
}

.b_wctrb8k {
  stop-color: var(--svg-color--d2418b, #D2418B);
}

.b45v6hbpx {
  stop-color: var(--svg-color--66606e, #66606E);
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bfk53cc2r {
  stop-color: var(--svg-color--f4527c, #F4527C);
}

.bgh3macub {
  d: path("M18.314 9.492a.892.892 0 0 1 .86 1.127H17.45a.896.896 0 0 1 .864-1.127");
}

.bp5y5pbyn {
  d: path("M18.248 9.68c.064.086-.07.19-.22.302c-.151.113-.263.193-.327.108s.007-.246.159-.359c.15-.113.325-.135.388-.05");
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c4mux-6nt {
  stop-color: var(--svg-color--352c2e, #352C2E);
}

.c5twxuzif {
  stop-color: var(--svg-color--cfc7d3, #CFC7D3);
  stop-opacity: 0;
}

.c70lx944e {
  stop-color: var(--svg-color--8e5263, #8E5263);
  stop-opacity: 0;
}

.ccy1m_asd {
  stop-color: var(--svg-color--e2457f, #E2457F);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.codu-dcmv {
  stop-color: var(--svg-color--c2b7cb, #C2B7CB);
  stop-opacity: 0;
}

.ct65j078y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.525 25.952h1.797");
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.cvqcwxbfq {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m15.75 10.366l-.53 1.7a.538.538 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.d1l_oobjb {
  stop-color: var(--svg-color--f52884, #F52884);
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.d7q2h2w-e {
  stop-color: var(--svg-color--eba287, #EBA287);
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.e7xip1bbn {
  stop-color: var(--svg-color--7a424b, #7A424B);
}

.ejom4oo7z {
  stop-color: var(--svg-color--d6a87f, #D6A87F);
}

.ekxbkpvzc {
  d: path("M5.143 26.475c-.02-3.41 1.582-6.47 4-8.5v11.98l-3.98.02z");
}

.el-cg1bcl {
  stop-color: var(--svg-color--499da3, #499DA3);
}

.eq8448bna {
  stop-color: var(--svg-color--e44c6d, #E44C6D);
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.exojo5a8m {
  cx: 20.898px;
  cy: 10.651px;
  r: 0.995px;
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.f82vlntau {
  stop-color: var(--svg-color--ff54ab, #FF54AB);
}

.fawsh83wa {
  d: path("M14.064 19.957c.824-.79 1.717-.938 2.058-.89c.133 1.792-.012 2.527-.723 3.308c-.424.466-1.054.723-1.51.843c-.203.054-.387-.107-.384-.318c.004-.362.011-.844.016-1.103c0-.63.02-1.309.543-1.84");
}

.fbd1ljb8v {
  stop-color: var(--svg-color--9689a5, #9689A5);
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.fi19pcb6g {
  d: path("M10.975 8.6c0-.267.108-.587.322-.747l.161-.16c.268-.213.376-.533.376-.853v-.853c0-.267.16-.48.429-.533c.643-.16 1.984-.427 3.915-.427c1.93 0 3.272.267 3.915.427c.215.053.43.266.43.533v.853c0 .32.16.64.375.853c.502.352.47.546.429.96c-.054.534-.107 1.44-.107 1.44h.018l-.266 3.958c-.16 1.77-1.552 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.233-3.21-3.003c-.14-1.816-.2-3.638-.367-5.451");
}

.fomm8__lp {
  d: path("M16.142 18.394c-1.05 0-1.908-.507-1.908-1.291V14.41c0-1.109.858-2.016 1.908-2.016s1.91.907 1.91 2.017v2.692c0 .796-.86 1.29-1.91 1.29");
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.g5cj4-btu {
  stop-color: var(--svg-color--d5c0de, #D5C0DE);
  stop-opacity: 0;
}

.g9vtwf9nq {
  stop-color: var(--svg-color--f22749, #F22749);
}

.glav2bc0u {
  stop-color: var(--svg-color--b0aaae, #B0AAAE);
}

.gnozolbql {
  stop-color: var(--svg-color--dd929a, #DD929A);
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hdm7u0bdo {
  stop-color: var(--svg-color--ff87c1, #FF87C1);
}

.hfzp6f8qe {
  d: path("M27.734 23.018a.97.97 0 0 1 .967.967V26.2h-1.934v-2.215a.976.976 0 0 1 .967-.967");
}

.hhz1a6b2j {
  stop-color: var(--svg-color--d72a4d, #D72A4D);
}

.i20220bfm {
  d: path("M7.383 29.104a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.idowujb9l {
  stop-color: var(--svg-color--d83864, #D83864);
}

.iouks0fsc {
  d: path("M27.277 20.725a.1.1 0 0 0 .098-.115c-.099-.66-.234-1.26-.432-1.875h-1.2a10.3 10.3 0 0 0-.415 1.878a.1.1 0 0 0 .098.111z");
}

.ir0pz063d {
  d: path("M9.878 6.073q-.012.196.012.395l.59 3.043a.634.634 0 0 0 .596.533c-.013-.197-.024-.54-.035-.842c-.01-.271-.018-.51-.024-.584c0-.267.108-.601.323-.762l.16-.16c.27-.213.377-.534.377-.854v-.77z");
}

.isuxr-mqn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.794 7.787c.43-.075 1.268-.054 1.849.398");
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.izb4o5hjh {
  stop-color: var(--svg-color--aa8bc0, #AA8BC0);
  stop-opacity: 0;
}

.j_3ppvb6l {
  stop-color: var(--svg-color--9b6f69, #9B6F69);
  stop-opacity: 0;
}

.j_c7fcbhg {
  stop-color: var(--svg-color--67ffa4, #67FFA4);
}

.j-4y6njnd {
  stop-color: var(--svg-color--41225a, #41225A);
}

.j-p-7tbjt {
  stop-color: var(--svg-color--5eccf3, #5ECCF3);
}

.j0piksb8i {
  stop-color: var(--svg-color--a92f4c, #A92F4C);
}

.jaxy4fb6n {
  stop-color: var(--svg-color--32182d, #32182D);
}

.js7kctros {
  stop-color: var(--svg-color--97769c, #97769C);
  stop-opacity: 0;
}

.jujuy5bla {
  stop-color: var(--svg-color--8e5e5c, #8E5E5C);
}

.juq22w2kb {
  stop-color: var(--svg-color--ab95b9, #AB95B9);
}

.jvqqj3hdm {
  stop-color: var(--svg-color--c01b54, #C01B54);
}

.jyboxmbnp {
  stop-color: var(--svg-color--4ecdee, #4ECDEE);
}

.jz78atb4u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.525 28.562h1.797");
}

.k_7ebwbkf {
  stop-color: var(--svg-color--995067, #995067);
}

.k1aaqobwu {
  d: path("M11.383 28.264a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.kb0m86bqf {
  d: path("M23.143 29.975v-12c2.44 2.023 4 5.078 4 8.494v3.505z");
}

.kfex23bvh {
  cx: 16.143px;
  cy: 17.314px;
  rx: 4.489px;
  ry: 3.08px;
}

.kl6jbhbtl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.574 8.305c.328-.29 1.042-.594 1.927-.452");
}

.knc82vlsg {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.52 9.22c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.227-.271c.126-.64.69-1.127 1.37-1.127");
}

.kprsiwbrh {
  stop-color: var(--svg-color--e2a291, #E2A291);
}

.kpt7nxbeg {
  stop-color: var(--svg-color--8e5263, #8E5263);
}

.ksnzfuvpq {
  d: path("m11.034 10.038l.049.002s-.054-.853-.108-1.44c0-.267.108-.587.322-.747l.161-.16c.268-.213.376-.533.376-.853v-.853c0-.267.16-.48.429-.533c.643-.16 1.984-.427 3.915-.427c1.93 0 3.272.267 3.915.427c.215.053.43.266.43.533v.853c0 .32.16.64.375.853c.502.352.47.546.429.96c-.054.534-.107 1.44-.107 1.44h.018l-.266 3.958c-.16 1.77-1.552 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.233-3.21-3.003z");
}

.ku_74wg1j {
  stop-color: var(--svg-color--4a96ee, #4A96EE);
}

.kv4hz_bvz {
  cx: 13.678px;
  cy: 9.873px;
  rx: 0.389px;
  ry: 0.197px;
}

.l21dfeb9j {
  stop-color: var(--svg-color--499da3, #499DA3);
  stop-opacity: 0;
}

.l29svp3cg {
  d: path("M4.59 29.975h8.843l-2.031-5.805c-.602-1.791-.32-3.532-4.61-2.954c-2.718.334-4.203 3.217-3.156 6.123z");
}

.l4wjmrs5x {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("M19.852 7.931h-.001l-.002-.002l-.005-.004l-.012-.01a1.4 1.4 0 0 0-.154-.107c-.1-.062-.241-.14-.42-.21a2.83 2.83 0 0 0-1.493-.159a.534.534 0 0 0 .167 1.054c.398-.062.716.01.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.824");
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l7qllmb5o {
  stop-color: var(--svg-color--afa1a1, #AFA1A1);
}

.lacq-oqha {
  stop-color: var(--svg-color--ffc8a9, #FFC8A9);
}

.leyigij6x {
  cx: 20.898px;
  cy: 10.651px;
  r: 0.995px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lodz1sy7q {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m15.858 10.529l-.82 1.7c-.102.349.142.698.487.698h.737c.346 0 .59-.354.489-.699l-.499-1.7c-.106-.376-.283-.376-.394 0");
}

.lv1npcbsj {
  cx: 20.898px;
  cy: 10.651px;
  r: 1.669px;
}

.lyih03bvp {
  d: path("M20.096 5.027L17.02 6.053a1.047 1.047 0 0 0 .47 2.031l3.06-.41z");
}

.m2-b5ia7e {
  d: path("M24.005 25.3c0-.401.325-.732.726-.732h2.77a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.97a.731.731 0 0 1-.319-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.m9kxmpbyp {
  stop-color: var(--svg-color--603a3e, #603A3E);
}

.mbdolbbcq {
  stop-color: var(--svg-color--ff5aaa, #FF5AAA);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mk9cbeb_z {
  fill: var(--svg-color--352b40, #352B40);
  d: path("M9.007 5.835c0-.45.344-.983.734-1.213c1.816-1.27 5.57-2.66 8.778-2.594c2.738.149 4.324 1.636 4.424 4.156c.019.49-.534.79-.934.79H10.264c-.685 0-1.257-.429-1.257-1.139");
}

.mkl0r8bng {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.771 13.408a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24c.343.52.942.867 1.624.867s1.28-.347 1.624-.868a.19.19 0 0 0-.02-.241a.2.2 0 0 0-.242-.04a2.94 2.94 0 0 1-1.362.323c-.5 0-.969-.118-1.362-.323Z");
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.mywg7wbjh {
  stop-color: var(--svg-color--41225a, #41225A);
  stop-opacity: 0;
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n2f566bzz {
  stop-color: var(--svg-color--66606e, #66606E);
  stop-opacity: 0;
}

.n39vpub1b {
  cx: 16.142px;
  cy: 17.066px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  rx: 3.844px;
  ry: 2.219px;
}

.n4l67hb-g {
  stop-color: var(--svg-color--ffcdab, #FFCDAB);
}

.n8uelqbwq {
  stop-color: var(--svg-color--523e40, #523E40);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.n9i8amb2u {
  stop-color: var(--svg-color--a1627b, #A1627B);
}

.ngwdu-l5j {
  stop-color: var(--svg-color--4fdda1, #4FDDA1);
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nofcsmmpr {
  stop-color: var(--svg-color--603a3e, #603A3E);
  stop-opacity: 0;
}

.nqi0jc4ki {
  stop-color: var(--svg-color--e5dfed, #E5DFED);
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh_l9db2x {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M8.312 25.293a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.olk_5de9e {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.74 9.22c-.653 0-1.204.45-1.354 1.059a.273.273 0 0 0 .267.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.ouhqh83ix {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("M12.36 7.932V7.93h.001l.002-.002l.005-.004l.012-.01a1.4 1.4 0 0 1 .154-.107c.1-.062.241-.14.42-.21a2.83 2.83 0 0 1 1.493-.159a.534.534 0 0 1-.167 1.054a1.77 1.77 0 0 0-.933.097a1.5 1.5 0 0 0-.309.165a.534.534 0 0 1-.678-.823");
}

.p_p7u6byq {
  stop-color: var(--svg-color--989295, #989295);
}

.pepvmtr_g {
  d: path("M15.413 19.097a2.4 2.4 0 0 1 .729-.11c.297 0 .546.052.729.11c.185.06.277.251.236.441a4 4 0 0 1-.222.714a.69.69 0 0 1-.609.426c-.12.005-.148.005-.27 0a.69.69 0 0 1-.607-.426a4 4 0 0 1-.223-.714c-.04-.19.052-.382.237-.441");
}

.pewrncjnt {
  stop-color: var(--svg-color--974e6e, #974E6E);
}

.pjlu7m_qy {
  d: path("M19.108 10.267a.84.84 0 0 0-.23-.463l-.26.285l.117.229z");
}

.pjwz_ic9q {
  stop-color: var(--svg-color--ed577d, #ED577D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.po_n49r6a {
  cx: 13.678px;
  cy: 9.873px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.pr-l-mb5c {
  stop-color: var(--svg-color--cf316b, #CF316B);
}

.q8-s_d5vk {
  stop-color: var(--svg-color--a25082, #A25082);
}

.q90xsjbgn {
  stop-color: var(--svg-color--c33c63, #C33C63);
}

.qbo0gacsu {
  stop-color: var(--svg-color--c2b7cb, #C2B7CB);
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qmqo746eg {
  stop-color: var(--svg-color--e0ad88, #E0AD88);
}

.qn-z6_0fu {
  stop-color: var(--svg-color--e44c6d, #E44C6D);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qob7fubko {
  stop-color: var(--svg-color--d42045, #D42045);
}

.qs7c013mg {
  d: path("M18.221 19.957c-.824-.79-1.717-.938-2.058-.89c-.133 1.792.011 2.527.722 3.308c.425.466 1.055.723 1.51.843c.204.054.388-.107.385-.318c-.004-.362-.012-.844-.016-1.103c0-.63-.02-1.309-.543-1.84");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.r7o-r9bxt {
  d: path("M8.383 25.215a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.rcioyubpk {
  stop-color: var(--svg-color--ca225e, #CA225E);
}

.rubvd1wqd {
  stop-color: var(--svg-color--bab5c0, #BAB5C0);
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.ryd5b_bne {
  fill: var(--svg-color--000, #000);
  d: path("M17.803 10.384c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.236");
}

.s0afa-bxm {
  stop-color: var(--svg-color--3a272d, #3A272D);
}

.s3g09k5mk {
  d: path("M20.307 2.79c2.008.772 2.24 2.384 2.365 3.36c-3.464-.783-5.749-1.178-7.035-1.406c-.31-.055-.423-.42-.179-.617c1.12-.91 3.16-1.987 4.849-1.338");
}

.s80w1fafw {
  d: path("M25.378 20.725a.1.1 0 0 0-.098.082c-.23 1.338-.199 2.695-.107 4.134l.61 4.304c.04.28.286.5.571.5c.297 0 .541-.21.572-.5l.63-4.35c.06-1.493.092-2.753-.137-4.088a.1.1 0 0 0-.098-.082z");
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.smyxk1pmd {
  stop-color: var(--svg-color--e9dfee, #E9DFEE);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.ta7eky02w {
  stop-color: var(--svg-color--a92f4c, #A92F4C);
  stop-opacity: 0;
}

.teu3yl5ky {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M11.32 28.314a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.texw1bcue {
  cx: 11.385px;
  cy: 10.651px;
  r: 0.995px;
}

.tm2bmw9uh {
  stop-color: var(--svg-color--4cc6ef, #4CC6EF);
}

.tpv18l7lf {
  d: path("M9.007 5.835c0-.45.344-.983.734-1.213c1.816-1.27 5.57-2.66 8.778-2.594c2.738.149 4.324 1.636 4.424 4.156c.019.49-.534.79-.934.79H10.264c-.685 0-1.257-.429-1.257-1.139");
}

.tx_tdxoal {
  stop-color: var(--svg-color--67ffa4, #67FFA4);
  stop-opacity: 0;
}

.u041s1kzn {
  d: path("M13.947 9.492a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.u8zhdtbla {
  stop-color: var(--svg-color--aa8bc0, #AA8BC0);
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.ue4dcor2v {
  stop-color: var(--svg-color--c3aebd, #C3AEBD);
  stop-opacity: 0;
}

.uhuv92bap {
  d: path("M28.293 14.9a.33.33 0 0 0-.215-.076c-1.248.083-2.375.65-2.978 1.74a.096.096 0 0 0 .086.142h.634c.322 0 .58.258.58.58c0 .473.366.882.839.882c.473.01.85-.366.87-.828c0-.054-.01-.107-.02-.161v-.01c-.162-.7-.054-1.291.279-1.882a.33.33 0 0 0-.075-.387");
}

.ukhbhfbdb {
  stop-color: var(--svg-color--68faa7, #68FAA7);
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.v3wx_yddl {
  stop-color: var(--svg-color--4ecdee, #4ECDEE);
  stop-opacity: 0;
}

.vbxkmpbas {
  stop-color: var(--svg-color--cfcbd2, #CFCBD2);
}

.vn0ta5bom {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
}

.vnvkvjbds {
  stop-color: var(--svg-color--dd929a, #DD929A);
  stop-opacity: 0;
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vq38zyg1v {
  stop-color: var(--svg-color--c6a0e4, #C6A0E4);
}

.vso1ahb2m {
  fill: var(--svg-color--000, #000);
  d: path("M14.458 10.384a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.236");
}

.vx8yiwdcw {
  d: path("M5.636 29.975h8.844l-2.031-5.852c-.602-1.805-2.022-3.296-4.61-2.976c-2.718.336-4.203 3.242-3.156 6.171z");
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w_jg8bumh {
  stop-color: var(--svg-color--c01b54, #C01B54);
  stop-opacity: 0;
}

.waw2uhbiy {
  fill: var(--svg-color--f99e93, #F99E93);
  d: path("M7.309 29.175a1.24 1.24 0 1 0 0-2.48a1.24 1.24 0 0 0 0 2.48");
}

.wb9dsybrx {
  stop-color: var(--svg-color--c1b3bb, #C1B3BB);
}

.wc--hsb7w {
  d: path("M20.504 6.073v.77c0 .32.15.65.366.864c.4.395.481.512.437.945c-.045.45-.083.975-.116 1.444a.62.62 0 0 0 .61-.531l.594-3.043q.04-.228.033-.45z");
}

.wufia9b2s {
  d: path("M12.36 7.932V7.93h.001l.002-.002l.005-.004l.012-.01a1.4 1.4 0 0 1 .154-.107c.1-.062.241-.14.42-.21a2.83 2.83 0 0 1 1.493-.159a.534.534 0 0 1-.167 1.054a1.77 1.77 0 0 0-.933.097a1.5 1.5 0 0 0-.309.165a.534.534 0 0 1-.678-.823");
}

.wv27mz0pi {
  cx: 11.385px;
  cy: 10.651px;
  r: 1.669px;
}

.wwkh3zbvl {
  fill: var(--svg-color--b693a1, #B693A1);
  d: path("M17.101 20.81c1.172-.436 1.967-1.288 1.967-2.267c0-1.424-1.683-2.579-3.759-2.579s-3.758 1.155-3.758 2.579c0 .979.795 1.83 1.967 2.267c-.389.437-.404.981-.404 1.486l-.014.924c-.002.177.152.312.323.267c.381-.101.909-.316 1.264-.707c.378-.414.565-.813.622-1.433c.058.62.245 1.019.622 1.433c.356.391.883.606 1.265.706c.17.046.324-.09.322-.266c-.003-.303-.01-.707-.013-.924c0-.505-.015-1.05-.404-1.486");
}

.wxo_vcdjw {
  stop-color: var(--svg-color--e3966a, #E3966A);
}

.wxv9-xfzb {
  d: path("M14.762 10.28c0-.289-.234-.481-.298-.54l-.288.28l.177.36z");
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xc8aunbib {
  stop-color: var(--svg-color--d7bedc, #D7BEDC);
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.y_e8mrzhh {
  stop-color: var(--svg-color--45a5d4, #45A5D4);
  stop-opacity: 0;
}

.y-qxhx9ay {
  d: path("m15.75 10.366l-.53 1.7a.538.538 0 0 0 .52.698h.786a.54.54 0 0 0 .52-.699l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.y3oq4nb4y {
  stop-color: var(--svg-color--97769c, #97769C);
}

.yan0zenen {
  stop-color: var(--svg-color--c02b72, #C02B72);
}

.yck9m-swa {
  stop-color: var(--svg-color--6e5a7e, #6E5A7E);
  stop-opacity: 0;
}

.yf6m5abnn {
  d: path("m25.169 16.58l.685-.093c.322 0 .735.472.735.794c0 .473.136.55.609.55c.454.01.86 0 .907-.436q.005.059.005.117a1.61 1.61 0 0 1-1.613 1.613a1.61 1.61 0 0 1-1.43-2.355c.01-.021.091-.17.102-.19");
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.z4b94lb8c {
  d: path("M19.852 7.931h-.001l-.002-.002l-.005-.004l-.012-.01a1.4 1.4 0 0 0-.154-.107c-.1-.062-.241-.14-.42-.21a2.83 2.83 0 0 0-1.493-.159a.534.534 0 0 0 .167 1.054c.398-.062.716.01.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.824");
}

.z6d28bbdt {
  stop-color: var(--svg-color--e73a62, #E73A62);
  stop-opacity: 0;
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.zbs2xvbkg {
  d: path("M9.143 17.989a10.96 10.96 0 0 1 7-2.514c2.658 0 5.097.943 7 2.514v11.985h-14z");
}

.ze5nteb_r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.447 27.257h1.797");
}

.zxeleub3j {
  stop-color: var(--svg-color--3e9fe4, #3E9FE4);
}

</style>
