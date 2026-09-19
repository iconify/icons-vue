<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ivWcDIe)" class="sghpbcc-q"/><path fill="url(#iyYnmte)" class="ox0t0tbyw"/><path fill="url(#iUDSZ5b)" class="ox0t0tbyw"/><path fill="url(#iNLTPlc)" class="lzxh7zbhd"/><path fill="url(#i8s27wu)" class="lzxh7zbhd"/><path fill="url(#iEjhPFO)" class="lzxh7zbhd"/><path fill="url(#iIr2zNb)" class="lzxh7zbhd"/><path fill="url(#i6IymKc)" class="vzhel1b-t"/><path fill="url(#icbfzYc)" class="vzhel1b-t"/><path fill="url(#iD7xuyW)" class="vzhel1b-t"/><path fill="url(#iokG4Xd)" class="vzhel1b-t"/><g filter="url(#iAgKucb)"><path fill="url(#iPm6Z8c)" class="hjxoqcl0v"/></g><g filter="url(#iwBQMGd)"><path fill="url(#iBCBk6c)" class="nw8wqqnto"/></g><g filter="url(#iWvv0Dd)"><path fill="url(#ic5ISlz)" class="ue9z25r5u"/></g><path fill="url(#iXMjlYd)" class="j1xrp0vsi"/><path fill="url(#iuMA8qd)" class="j1xrp0vsi"/><path fill="url(#i3Tf6Wx)" class="j1xrp0vsi"/><path fill="url(#i3bFchc)" class="j1xrp0vsi"/><path fill="url(#iTzbEqb)" class="j1xrp0vsi"/><path fill="url(#iziRMXb)" class="mx_0g-cbx"/><path fill="url(#iWWrm2c)" class="mx_0g-cbx"/><path fill="url(#iYC5CUv)" class="mx_0g-cbx"/><path fill="url(#iOYmIxc)" class="mx_0g-cbx"/><path fill="url(#iV5Qwac)" class="nw8wqqnto"/><path fill="url(#iEtcdkc)" class="lceri-vrq"/><path fill="url(#i5KOZnc)" class="lceri-vrq"/><path fill="url(#ivWcDIe)" class="sghpbcc-q"/><g filter="url(#ihviVyd)"><path fill="url(#idV101R)" class="ftb0dac9p"/><path fill="url(#iptclcx)" class="ftb0dac9p"/></g><path fill="url(#iWztw3c)" class="gip5y3buk"/><path fill="url(#irkrorb)" class="gip5y3buk"/><path fill="url(#ixATofe)" class="a0q7e-rbb"/><path fill="url(#iIN33ps)" class="a0q7e-rbb"/><path fill="url(#iMD4Akd)" class="a0q7e-rbb"/><g filter="url(#iTYsQmb)"><rect class="rxsc4xb2z"/><rect fill="url(#in80oDb)" class="q3ap7obeh"/><rect fill="url(#iEsINHM)" class="q3ap7obeh"/><rect fill="url(#imH7Vqd)" class="q3ap7obeh"/></g><path fill="url(#itN89Zb)" class="min4o96wl"/><path fill="url(#iWn83Lb)" class="min4o96wl"/><path fill="url(#i6aufrd)" class="min4o96wl"/><path fill="url(#i4MNM9d)" class="min4o96wl"/><path fill="url(#idoLaid)" class="fn5mc_bpm"/><path fill="url(#iwOSsec)" class="cjh4xuujf"/><g filter="url(#iR1mGic)"><path fill="url(#i3WvLnd)" class="muhausb9b"/><path fill="url(#iYr92lc)" class="muhausb9b"/><path fill="url(#i1jgyLc)" class="muhausb9b"/><path fill="url(#iFUTy9T)" class="muhausb9b"/><path fill="url(#iiildib)" class="muhausb9b"/></g><g filter="url(#ibMlZ0c)"><path stroke="url(#iZYH9pc)" class="ql-d_bcrc"/></g><g filter="url(#i8vczAd)"><path stroke="url(#iq0kW6b)" class="dkh21gill"/></g><g filter="url(#ifhjp5m)"><path stroke="url(#im8NDfc)" class="c7dra70nl"/></g><g filter="url(#i9eioKR)"><circle fill="url(#iv39KBb)" class="luigpo9yy"/></g><g filter="url(#i4H84Je)"><circle fill="url(#iaZZ9Ic)" class="yfm2n9bqy"/></g><g filter="url(#i2Ao6cb)"><circle fill="url(#ib2JKye)" class="urcxffbma"/><circle fill="url(#iwlX86t)" class="urcxffbma"/></g><g filter="url(#iFzWkic)"><circle class="iog_p5bzi"/><circle fill="url(#iNUCjbc)" class="r2srh5bmb"/><circle fill="url(#iQDnIzc)" class="r2srh5bmb"/></g><g filter="url(#iNSw3Ic)"><path fill="url(#iRfadwM)" class="z5vky0btk"/><path fill="url(#iUmaEVn)" class="z5vky0btk"/><path fill="url(#iNNt1FI)" class="z5vky0btk"/></g><path fill="url(#ibpZzsc)" class="pghrmkbuz"/><path fill="url(#iu7bUqd)" class="pghrmkbuz"/><path fill="url(#i09Ksmd)" class="pghrmkbuz"/><path fill="url(#iuH2gNX)" class="pghrmkbuz"/><path fill="url(#iZuMlle)" class="pghrmkbuz"/><g filter="url(#imGLvFe)"><path fill="url(#ib7Uy9c)" class="zqwukdh4o"/></g><g filter="url(#iBOq3Td)"><path class="hqkmlcjrp"/><path fill="url(#ixiocMe)" class="ugp1co_qm"/><path fill="url(#i4RMidy)" class="ugp1co_qm"/><path fill="url(#iR50yZp)" class="ugp1co_qm"/><path fill="url(#iojjVTc)" class="ugp1co_qm"/></g><g filter="url(#ibPSstd)"><path class="hg5yv2_wd"/></g><g filter="url(#i33yZvd)"><path class="bofdlrnoj"/><path fill="url(#idbBhee)" class="du024pb0h"/><path fill="url(#irrc9ze)" class="du024pb0h"/><path fill="url(#ikNthzL)" class="du024pb0h"/><path fill="url(#iAADvjM)" class="du024pb0h"/></g><path fill="url(#iSJii4x)" class="du024pb0h"/><path stroke="url(#iTONjHe)" class="z9ohlqbzd"/><g filter="url(#iR7vvmb)"><path class="gkqsxbb6j"/><path fill="url(#i6bhB3b)" class="emhh1nb2t"/></g><g filter="url(#il0d75f)"><path class="luqxnk8ru"/><path fill="url(#iImyJJb)" class="mj2yjgbpz"/></g><path class="y7uo9pa4k"/><path fill="url(#iCngzNd)" class="vj-z_k0mv"/><path class="abm4ipbvo"/><g filter="url(#ieNP2QW)"><path class="v5bz9nbam"/><path fill="url(#i1W1VTW)" class="lkjxpmb6t"/></g><g filter="url(#idOXPKs)"><path fill="url(#iBEKKrc)" class="zzx1n12cg"/></g><path class="o1zpkw-ti"/><path fill="url(#it87QTd)" class="eweutccfe"/><path class="m3r90ybqp"/><g filter="url(#iao3Wxc)"><path fill="url(#ilNzURD)" class="u3mn6obsi"/></g><g filter="url(#i87vnVd)"><ellipse transform="rotate(-27.914 12.96 9.843)" class="hitogzb_c"/><ellipse fill="url(#iadUVcc)" transform="rotate(-27.914 12.96 9.843)" class="o_p71tb4b"/></g><g filter="url(#imgPSrd)"><path stroke="url(#iLNWhCe)" class="dqffkqz-g"/></g><g filter="url(#inFyj5b)"><path stroke="url(#iqrvBDd)" class="r67fhmbqh"/></g><g filter="url(#i41yeCb)"><path stroke="url(#iEAhlwc)" class="evqrzqn_f"/></g><path fill="url(#iKGBSRd)" class="lqqx9ouzy"/><g filter="url(#i2CYdmb)"><path clip-rule="evenodd" class="d32l4nd3w"/></g><defs><radialGradient id="iyYnmte" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.8125 -3.29991 0 15.446 18.316)" gradientUnits="userSpaceOnUse"><stop class="h-vnc5n6a"/><stop offset="1" class="buwur_dqz"/></radialGradient><radialGradient id="iUDSZ5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.65625 6.93357 0 15.446 30.316)" gradientUnits="userSpaceOnUse"><stop class="iufxq5boh"/><stop offset="1" class="w4j6xtngg"/></radialGradient><radialGradient id="iNLTPlc" cx="0" cy="0" r="1" gradientTransform="rotate(161.686 4.493 14.56)scale(4.67425 7.57955)" gradientUnits="userSpaceOnUse"><stop class="d-w3_abhe"/><stop offset="1" class="bqs6izbmd"/></radialGradient><radialGradient id="iIr2zNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.375 -2.57376 0 9.302 17.41)" gradientUnits="userSpaceOnUse"><stop class="x3hlfcbwc"/><stop offset="1" class="sfpaimhix"/></radialGradient><radialGradient id="i6IymKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.15073 2.71782 0 21.206 30.285)" gradientUnits="userSpaceOnUse"><stop class="rfuz_acet"/><stop offset="1" class="q-fl22tnr"/></radialGradient><radialGradient id="icbfzYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -3.9375 0 22.77 18.535)" gradientUnits="userSpaceOnUse"><stop class="n8vj2kb3y"/><stop offset="1" class="irjqokbks"/></radialGradient><radialGradient id="iBCBk6c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7279 1.31251 -2.69681 -7.65971 14.999 21.91)" gradientUnits="userSpaceOnUse"><stop class="iezv8nbum"/><stop offset="1" class="ry-6rkb7q"/></radialGradient><radialGradient id="iXMjlYd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74796 3.71877 -3.74799 -3.7774 22.49 17.691)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="t0qf5rbqk"/></radialGradient><radialGradient id="iuMA8qd" cx="0" cy="0" r="1" gradientTransform="rotate(-64.11 29.307 -.255)scale(8.30198 11.1931)" gradientUnits="userSpaceOnUse"><stop class="mvrro-b_u"/><stop offset=".93" class="ocku6nzyd"/></radialGradient><radialGradient id="i3Tf6Wx" cx="0" cy="0" r="1" gradientTransform="rotate(111.826 5.238 14.38)scale(3.56729 6.41649)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="ycu0bme2d"/><stop offset="1" class="zt127j5os"/></radialGradient><radialGradient id="iziRMXb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95848 0 0 -8.5991 8.226 26.113)" gradientUnits="userSpaceOnUse"><stop class="xoi7hsb-w"/><stop offset="1" class="hkq9astav"/></radialGradient><radialGradient id="iYC5CUv" cx="0" cy="0" r="1" gradientTransform="matrix(-7.51743 0 0 -10.8202 10.005 28.968)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="c1dciy28n"/><stop offset="1" class="vxd8ts5kx"/></radialGradient><radialGradient id="iV5Qwac" cx="0" cy="0" r="1" gradientTransform="rotate(114.365 1.783 11.823)scale(4.20765 8.70789)" gradientUnits="userSpaceOnUse"><stop class="zqbntluns"/><stop offset="1" class="v6bhjtbbk"/></radialGradient><radialGradient id="iEtcdkc" cx="0" cy="0" r="1" gradientTransform="matrix(.41584 12.10916 -8.52544 .29277 24.177 17.879)" gradientUnits="userSpaceOnUse"><stop class="v6ge5bcpf"/><stop offset="1" class="z78o0obou"/></radialGradient><radialGradient id="idV101R" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.05068 -2.55638 0 15.426 16.567)" gradientUnits="userSpaceOnUse"><stop class="rholibcnu"/><stop offset=".632" class="i2_ciebsc"/></radialGradient><radialGradient id="iptclcx" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.25 -.875 0 13.766 15.929)" gradientUnits="userSpaceOnUse"><stop class="jo24jebsd"/><stop offset="1" class="b_w609b1g"/></radialGradient><radialGradient id="iWztw3c" cx="0" cy="0" r="1" gradientTransform="rotate(140.55 9.491 16.735)scale(2.18272 2.14492)" gradientUnits="userSpaceOnUse"><stop offset=".354" class="b5vuh20co"/><stop offset="1" class="hrswh-pmg"/></radialGradient><radialGradient id="irkrorb" cx="0" cy="0" r="1" gradientTransform="matrix(.80395 -.6129 .32018 .41998 27.206 23.466)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="wyf8ygbxi"/><stop offset="1" class="i6hs9gb9s"/></radialGradient><radialGradient id="iMD4Akd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54688 -.39416 0 25.571 19.379)" gradientUnits="userSpaceOnUse"><stop class="hkh0bccgk"/><stop offset="1" class="sfa02aclf"/></radialGradient><radialGradient id="in80oDb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91833 0 0 -.20741 25.177 19.066)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="afeb8bsjy"/><stop offset="1" class="rced3uh7f"/></radialGradient><radialGradient id="iEsINHM" cx="0" cy="0" r="1" gradientTransform="matrix(-.28516 .14844 -.12607 -.24218 27.005 18.918)" gradientUnits="userSpaceOnUse"><stop class="p4k8mjbje"/><stop offset="1" class="e1oaafz6u"/></radialGradient><radialGradient id="imH7Vqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .13281 -.08816 -.11928 23.407 19.277)" gradientUnits="userSpaceOnUse"><stop class="bj_z41bxg"/><stop offset="1" class="boi6rx35q"/></radialGradient><radialGradient id="i4MNM9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -.51563 0 26.227 21.223)" gradientUnits="userSpaceOnUse"><stop class="tsloro5fn"/><stop offset="1" class="p9rinuedy"/></radialGradient><radialGradient id="iYr92lc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.574 25.293)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="i1jgyLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.574 26.587)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iFUTy9T" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.574 27.837)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iiildib" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.574 29.189)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iv39KBb" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 8.994 10.621)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iwlX86t" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 20.56 10.356)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="iNUCjbc" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.145 11.443)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iQDnIzc" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.187 10.62)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iUmaEVn" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 17.765 9.348)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iNNt1FI" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37541 1.71044 0 13.203 9.483)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="i09Ksmd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8549 -12.0201 0 15.115 8.845)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="rko8b-bmk"/><stop offset="1" class="whxihzpaf"/></radialGradient><radialGradient id="iuH2gNX" cx="0" cy="0" r="1" gradientTransform="rotate(-146.07 12.365 5.27)scale(2.07148 1.17905)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="iZuMlle" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 -.54454 .34491 1.64288 11.778 17.575)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="ixiocMe" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.42495 .3845 19.767 6.511)" gradientUnits="userSpaceOnUse"><stop offset=".492" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="i4RMidy" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 18.122 4.75)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="iR50yZp" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 15.417 2.012)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="iojjVTc" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 8.962 8.837)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="iAADvjM" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 15.745 12.23)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="i6bhB3b" cx="0" cy="0" r="1" gradientTransform="matrix(.1043 -.60384 1.78641 .30854 17.862 8.535)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iImyJJb" cx="0" cy="0" r="1" gradientTransform="matrix(.1043 -.60384 1.7865 .30858 12.71 8.535)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iCngzNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 17.598 9.939)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i1W1VTW" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.37 10.024)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="it87QTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.23 9.938)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iadUVcc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.472 -1.293)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="ivWcDIe" x1="8.23" x2="22.659" y1="15.296" y2="15.296" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i8s27wu" x1="11.239" x2="11.239" y1="30.41" y2="29.098" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iEjhPFO" x1="15.177" x2="14.208" y1="29.098" y2="29.098" gradientUnits="userSpaceOnUse"><stop offset=".129" class="hu0w8ibzb"/><stop offset="1" class="q4mowll4q"/></linearGradient><linearGradient id="iD7xuyW" x1="19.74" x2="19.74" y1="30.41" y2="29.098" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iokG4Xd" x1="15.802" x2="16.505" y1="27.973" y2="27.973" gradientUnits="userSpaceOnUse"><stop class="o77zymbyt"/><stop offset="1" class="i4kgizoks"/></linearGradient><linearGradient id="iPm6Z8c" x1="10.677" x2="12.896" y1="17.941" y2="24.629" gradientUnits="userSpaceOnUse"><stop class="v4-zmrbyl"/><stop offset="1" class="r-0tl8b_g"/></linearGradient><linearGradient id="ic5ISlz" x1="20.45" x2="18.099" y1="18.97" y2="23.671" gradientUnits="userSpaceOnUse"><stop class="z4xhuybyb"/><stop offset="1" class="lkjzf4omc"/></linearGradient><linearGradient id="i3bFchc" x1="18.958" x2="17.552" y1="24.098" y2="22.598" gradientUnits="userSpaceOnUse"><stop class="dhui3nlqd"/><stop offset="1" class="ifg4wbcuq"/><stop offset="1" class="kzdc46tfj"/></linearGradient><linearGradient id="iTzbEqb" x1="17.146" x2="17.974" y1="18.879" y2="19.223" gradientUnits="userSpaceOnUse"><stop offset=".081" class="foy77stiz"/><stop offset="1" class="i3p8g97ol"/></linearGradient><linearGradient id="iWWrm2c" x1="6.567" x2="6.567" y1="30.353" y2="29.219" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iOYmIxc" x1="8.38" x2="7.935" y1="29.387" y2="29.384" gradientUnits="userSpaceOnUse"><stop offset=".175" class="w01lnqx9a"/><stop offset="1" class="xx10debny"/></linearGradient><linearGradient id="i5KOZnc" x1="22.753" x2="23.162" y1="27.66" y2="27.644" gradientUnits="userSpaceOnUse"><stop class="ckzhu0bvt"/><stop offset="1" class="dtqi4cbss"/></linearGradient><linearGradient id="ixATofe" x1="23.825" x2="26.529" y1="20.848" y2="20.848" gradientUnits="userSpaceOnUse"><stop offset=".253" class="cpykpvzxv"/><stop offset=".773" class="ahix7mbin"/></linearGradient><linearGradient id="iIN33ps" x1="26.529" x2="26.18" y1="20.832" y2="20.832" gradientUnits="userSpaceOnUse"><stop class="g1a66we9o"/><stop offset="1" class="c3eiz-bza"/></linearGradient><linearGradient id="itN89Zb" x1="26.529" x2="25.177" y1="23.16" y2="23.16" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ubsir5m6c"/><stop offset="1" class="v0fk_zbwr"/></linearGradient><linearGradient id="iWn83Lb" x1="26.529" x2="26.129" y1="23.308" y2="23.308" gradientUnits="userSpaceOnUse"><stop class="bywelvb6j"/><stop offset="1" class="s44sum5km"/></linearGradient><linearGradient id="i6aufrd" x1="23.696" x2="24.227" y1="23.308" y2="23.308" gradientUnits="userSpaceOnUse"><stop class="jr9zsmblm"/><stop offset="1" class="r1tra0r1f"/></linearGradient><linearGradient id="idoLaid" x1="24.782" x2="23.892" y1="21.801" y2="21.801" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iwOSsec" x1="24.782" x2="23.892" y1="23.582" y2="23.582" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="i3WvLnd" x1="27.165" x2="23.137" y1="28.051" y2="28.051" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="fusa66-jk"/></linearGradient><linearGradient id="iZYH9pc" x1="23.754" x2="25.463" y1="26.068" y2="26.068" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="iq0kW6b" x1="23.676" x2="25.385" y1="27.373" y2="27.373" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="im8NDfc" x1="23.754" x2="25.463" y1="28.678" y2="28.678" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="iaZZ9Ic" x1="10.665" x2="10.023" y1="10.9" y2="10.9" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="ib2JKye" x1="21.274" x2="20.455" y1="9.529" y2="12.067" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="iRfadwM" x1="19.457" x2="11.813" y1="11.011" y2="12.15" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="ibpZzsc" x1="10.016" x2="11.899" y1="13.71" y2="13.642" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iu7bUqd" x1="20.286" x2="19.229" y1="12.871" y2="12.77" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="ib7Uy9c" x1="14.885" x2="23.037" y1="8.023" y2="5.105" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="idbBhee" x1="14.552" x2="15.491" y1="11.671" y2="11.671" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="irrc9ze" x1="16.356" x2="15.33" y1="11.994" y2="11.979" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="ikNthzL" x1="15.612" x2="15.612" y1="12.737" y2="12.163" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="iSJii4x" x1="15.543" x2="15.543" y1="12.779" y2="12.611" gradientUnits="userSpaceOnUse"><stop class="ahyqmxbmp"/><stop offset="1" class="g67mx8b1h"/></linearGradient><linearGradient id="iTONjHe" x1="14.379" x2="14.814" y1="14.353" y2="13.665" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iBEKKrc" x1="18.377" x2="18.063" y1="9.992" y2="10.186" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilNzURD" x1="13.975" x2="13.661" y1="9.992" y2="10.186" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLNWhCe" x1="18.392" x2="17.971" y1="7.851" y2="6.991" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="iqrvBDd" x1="13.082" x2="11.892" y1="7.723" y2="7.224" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="iEAhlwc" x1="10.751" x2="10.751" y1="5.706" y2="7.866" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><linearGradient id="iKGBSRd" x1="10.917" x2="22.177" y1="9.6" y2="9.6" gradientUnits="userSpaceOnUse"><stop class="havx3otga"/><stop offset=".099" class="fzgz80bxw"/><stop offset=".374" class="fzgz80bxw"/><stop offset="1" class="t5bid5bsq"/></linearGradient><filter id="iAgKucb" width="7.023" height="11.703" x="8.591" y="15.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2171" stdDeviation=".375"/></filter><filter id="iwBQMGd" width="5.673" height="10.453" x="9.476" y="15.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.721569 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2171"/></filter><filter id="iWvv0Dd" width="6.388" height="10.529" x="15.499" y="16.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2171" stdDeviation=".375"/></filter><filter id="ihviVyd" width="4.32" height="3.6" x="13.316" y="15.018" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.207843 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2171"/></filter><filter id="iTYsQmb" width="4.008" height=".781" x="23.173" y="18.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.796078 0 0 0 0 0.94902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2171"/></filter><filter id="iR1mGic" width="4.468" height="5.556" x="23.137" y="24.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.211765 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2171"/></filter><filter id="ibMlZ0c" width="2.097" height=".3" x="23.604" y="25.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2171" stdDeviation=".05"/></filter><filter id="i8vczAd" width="2.097" height=".3" x="23.526" y="27.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2171" stdDeviation=".05"/></filter><filter id="ifhjp5m" width="2.097" height=".3" x="23.604" y="28.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2171" stdDeviation=".05"/></filter><filter id="i9eioKR" width="3.542" height="3.342" x="8.994" y="8.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2171"/></filter><filter id="i4H84Je" width="2.992" height="2.992" x="9.169" y="9.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2171" stdDeviation=".25"/></filter><filter id="i2Ao6cb" width="3.592" height="3.592" x="18.516" y="8.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2171"/></filter><filter id="iFzWkic" width="2.992" height="2.992" x="18.691" y="9.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2171" stdDeviation=".25"/></filter><filter id="iNSw3Ic" width="10.383" height="12.189" x="10.254" y="4.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2171"/></filter><filter id="imGLvFe" width="8.25" height="7.07" x="13.587" y="2.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2171" stdDeviation="1"/></filter><filter id="iBOq3Td" width="12.614" height="8.551" x="9.11" y="1.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2171"/></filter><filter id="ibPSstd" width="3.262" height="4.184" x="13.547" y="9.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2171" stdDeviation=".375"/></filter><filter id="i33yZvd" width="2.379" height="3.184" x="14.228" y="9.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2171" stdDeviation=".125"/></filter><filter id="iR7vvmb" width="2.982" height="1.874" x="16.6" y="6.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2171"/></filter><filter id="il0d75f" width="2.982" height="1.874" x="11.447" y="6.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2171"/></filter><filter id="ieNP2QW" width=".787" height=".697" x="16.863" y="9.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2171" stdDeviation=".05"/></filter><filter id="idOXPKs" width=".892" height=".914" x="17.704" y="9.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2171" stdDeviation=".1"/></filter><filter id="iao3Wxc" width=".987" height="1.041" x="13.258" y="9.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2171" stdDeviation=".1"/></filter><filter id="i87vnVd" width=".914" height=".705" x="12.502" y="9.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2171" stdDeviation=".05"/></filter><filter id="imgPSrd" width="2.601" height="1.182" x="16.704" y="7.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2171" stdDeviation=".125"/></filter><filter id="inFyj5b" width="2.679" height="1.239" x="11.48" y="7.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2171" stdDeviation=".125"/></filter><filter id="i41yeCb" width="1.008" height="2.271" x="10.246" y="5.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2171" stdDeviation=".125"/></filter><filter id="i2CYdmb" width="11.479" height="6.324" x="9.611" y="5.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.537255 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2171"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.760784 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2171" result="effect2_innerShadow_4002_2171"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-scientist-medium-dark" /></template>
<style>
.a0q7e-rbb {
  d: path("M23.825 19.457h2.703v5.938h-2.703z");
}

.abm4ipbvo {
  fill: var(--svg-color--000, #000);
  d: path("M17.089 10.354a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.747h-.906a.46.46 0 0 1-.06-.236");
}

.afeb8bsjy {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ahix7mbin {
  stop-color: var(--svg-color--bff0ff, #BFF0FF);
}

.ahyqmxbmp {
  stop-color: var(--svg-color--743b4a, #743B4A);
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.b_w609b1g {
  stop-color: var(--svg-color--744a4d, #744A4D);
  stop-opacity: 0;
}

.b5vuh20co {
  stop-color: var(--svg-color--8b655b, #8B655B);
}

.bj_z41bxg {
  stop-color: var(--svg-color--caedff, #CAEDFF);
}

.bofdlrnoj {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.034 10.336l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.531-1.701c-.114-.377-.646-.377-.766 0");
}

.boi6rx35q {
  stop-color: var(--svg-color--caedff, #CAEDFF);
  stop-opacity: 0;
}

.bqs6izbmd {
  stop-color: var(--svg-color--cdc1db, #CDC1DB);
}

.buwur_dqz {
  stop-color: var(--svg-color--2f649d, #2F649D);
}

.bywelvb6j {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c1dciy28n {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
  stop-opacity: 0;
}

.c3eiz-bza {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
  stop-opacity: 0;
}

.c7dra70nl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 28.6h1.797");
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.cjh4xuujf {
  d: path("M23.825 23.816v-.468h.805a.234.234 0 0 1 0 .468z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ckzhu0bvt {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cpykpvzxv {
  stop-color: var(--svg-color--a3d3ff, #A3D3FF);
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d-w3_abhe {
  stop-color: var(--svg-color--e3d3fa, #E3D3FA);
}

.d32l4nd3w {
  fill: var(--svg-color--ada3b0, #ADA3B0);
  fill-rule: evenodd;
  d: path("M9.761 9.042c.012-1.676 1.389-3.005 3.047-3.005h5.275a3.01 3.01 0 0 1 3.007 3.04v.001c-.022 1.567-1.339 2.918-2.907 2.973h-.002a3.06 3.06 0 0 1-2.63-1.342c-.045-.065-.09-.076-.112-.076s-.067.01-.112.076a3.08 3.08 0 0 1-2.549 1.352a3.02 3.02 0 0 1-3.017-3.017zm.6.003a2.42 2.42 0 0 0 2.417 2.416c.841 0 1.62-.435 2.05-1.085l.002-.003a.74.74 0 0 1 .609-.34c.243 0 .465.128.609.34v.001a2.46 2.46 0 0 0 2.114 1.077c1.248-.044 2.31-1.133 2.328-2.381a2.41 2.41 0 0 0-2.407-2.433h-5.275c-1.336 0-2.437 1.07-2.447 2.408");
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.d7d_80btw {
  stop-color: var(--svg-color--0e7268, #0E7268);
}

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dhui3nlqd {
  stop-color: var(--svg-color--d6baf6, #D6BAF6);
}

.dkh21gill {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.676 27.295h1.797");
}

.dqffkqz-g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.08 7.754c.43-.075 1.27-.054 1.85.398");
}

.dtqi4cbss {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
  stop-opacity: 0;
}

.du024pb0h {
  d: path("m15.034 10.336l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.531-1.701c-.114-.377-.646-.377-.766 0");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1oaafz6u {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
  stop-opacity: 0;
}

.emhh1nb2t {
  d: path("m19.14 7.899l-.001-.001l-.002-.002l-.005-.004l-.012-.01l-.036-.026a2.6 2.6 0 0 0-.54-.291a2.84 2.84 0 0 0-1.493-.159a.534.534 0 0 0 .167 1.055c.398-.063.717.01.934.097a1.5 1.5 0 0 1 .309.165a.534.534 0 0 0 .679-.824");
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.evqrzqn_f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.88 5.805v.899c-.008.148-.07.481-.259.622");
}

.eweutccfe {
  d: path("M13.229 9.461a.893.893 0 0 0-.861 1.129h1.725a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.893");
}

.fn5mc_bpm {
  d: path("M23.825 22.035v-.469h.805a.234.234 0 1 1 0 .469z");
}

.foy77stiz {
  stop-color: var(--svg-color--9f98a7, #9F98A7);
}

.ft5dv1b6b {
  fill: none;
}

.ftb0dac9p {
  d: path("M15.426 18.618a2.11 2.11 0 0 1-2.11-2.11v-1.39h4.22v1.39c0 1.17-.95 2.11-2.11 2.11");
}

.fusa66-jk {
  stop-color: var(--svg-color--704b4b, #704B4B);
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.fzgz80bxw {
  stop-color: var(--svg-color--448579, #448579);
}

.g1a66we9o {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
}

.g67mx8b1h {
  stop-color: var(--svg-color--743b4a, #743B4A);
  stop-opacity: 0;
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gip5y3buk {
  d: path("M26.434 22.958c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.gkqsxbb6j {
  fill: var(--svg-color--352827, #352827);
  d: path("m19.14 7.899l-.001-.001l-.002-.002l-.005-.004l-.012-.01l-.036-.026a2.6 2.6 0 0 0-.54-.291a2.84 2.84 0 0 0-1.493-.159a.534.534 0 0 0 .167 1.055c.398-.063.717.01.934.097a1.5 1.5 0 0 1 .309.165a.534.534 0 0 0 .679-.824");
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h-vnc5n6a {
  stop-color: var(--svg-color--3a6fb4, #3A6FB4);
}

.havx3otga {
  stop-color: var(--svg-color--7cb6ab, #7CB6AB);
}

.hg5yv2_wd {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.141 10.499l-.82 1.701c-.103.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.701c-.107-.377-.284-.377-.396 0");
}

.hitogzb_c {
  cx: 12.959px;
  cy: 9.843px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.hjxoqcl0v {
  d: path("m9.474 17.72l-.131 1.733a.6.6 0 0 0 .494.637l.48.084a.15.15 0 0 1 .084.249l-.626.69a.5.5 0 0 0 .015.687l4.732 4.808a.2.2 0 0 0 .343-.14v-3.38c0-.283-.06-.562-.176-.82l-2.605-5.803c-.93.298-1.807.722-2.61 1.256");
}

.hkh0bccgk {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
}

.hkq9astav {
  stop-color: var(--svg-color--d6cbe2, #D6CBE2);
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hqkmlcjrp {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m20.24 4.137l.43.214c.752.374 1.181 1.228 1.02 2.135L21.1 9.53c-.053.314-.26.526-.573.534h-.018s.054-.908.107-1.441c.044-.434-.032-.566-.43-.961c-.214-.214-.375-.534-.375-.854v-.855c0-.267-.215-.48-.43-.533c-.644-.16-1.986-.428-3.919-.428s-3.275.267-3.92.428a.52.52 0 0 0-.429.533v.855c0 .32-.107.64-.376.854l-.16.16c-.216.16-.323.48-.323.747c.054.587.107 1.442.107 1.442l-.049-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.322-1.708 1.073-2.082l.43-.214a8 8 0 0 0 .805-.587l.967-1.014c.59-.534 1.45-.694 2.201-.32c.537.16 1.127.16 1.664 0c.806-.267 1.718-.054 2.363.533l.805.801c.215.267.483.427.805.587");
}

.hrswh-pmg {
  stop-color: var(--svg-color--673a32, #673A32);
}

.hu0w8ibzb {
  stop-color: var(--svg-color--b5a2c9, #B5A2C9);
}

.i2_ciebsc {
  stop-color: var(--svg-color--794b57, #794B57);
}

.i3p8g97ol {
  stop-color: var(--svg-color--e2d6f0, #E2D6F0);
  stop-opacity: 0;
}

.i4kgizoks {
  stop-color: var(--svg-color--d1bee7, #D1BEE7);
  stop-opacity: 0;
}

.i6hs9gb9s {
  stop-color: var(--svg-color--997c73, #997C73);
  stop-opacity: 0;
}

.iezv8nbum {
  stop-color: var(--svg-color--fcefff, #FCEFFF);
}

.ifg4wbcuq {
  stop-color: var(--svg-color--e2d2ee, #E2D2EE);
  stop-opacity: 0;
}

.iog_p5bzi {
  cx: 20.187px;
  cy: 10.621px;
  r: 0.996px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.irjqokbks {
  stop-color: var(--svg-color--d7ccea, #D7CCEA);
  stop-opacity: 0;
}

.iufxq5boh {
  stop-color: var(--svg-color--3971d9, #3971D9);
}

.j1xrp0vsi {
  d: path("m21.37 17.112l.132 1.733a.6.6 0 0 1-.494.636l-.48.085a.15.15 0 0 0-.085.248l.626.691a.5.5 0 0 1-.014.687L16.323 26a.2.2 0 0 1-.343-.14v-3.381a2 2 0 0 1 .175-.82l2.606-5.803c.929.299 1.807.723 2.61 1.256");
}

.jo24jebsd {
  stop-color: var(--svg-color--744a4d, #744A4D);
}

.jr9zsmblm {
  stop-color: var(--svg-color--a4c098, #A4C098);
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.kzdc46tfj {
  stop-color: var(--svg-color--e7cfff, #E7CFFF);
  stop-opacity: 0;
}

.kzk-_ccou {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lceri-vrq {
  d: path("M22.753 29.988v-11.79c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07z");
}

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkjxpmb6t {
  d: path("M17.534 9.65c.064.085-.07.189-.22.302c-.151.113-.264.193-.327.107c-.064-.085.007-.245.158-.358c.152-.113.326-.136.39-.051");
}

.lkjzf4omc {
  stop-color: var(--svg-color--c5b2dd, #C5B2DD);
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lqqx9ouzy {
  d: path("M18.083 6.337h-5.275c-1.497 0-2.737 1.2-2.746 2.707a2.72 2.72 0 0 0 2.716 2.717c.942 0 1.814-.486 2.3-1.22c.189-.277.533-.277.721 0a2.76 2.76 0 0 0 2.373 1.21c1.408-.05 2.598-1.27 2.618-2.677a2.71 2.71 0 0 0-2.707-2.737");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.luigpo9yy {
  cx: 10.665px;
  cy: 10.621px;
  r: 1.671px;
}

.luqxnk8ru {
  fill: var(--svg-color--352827, #352827);
  d: path("m11.64 7.899l.001-.001l.002-.002l.005-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.24-.14.42-.21c.36-.143.872-.257 1.494-.159a.534.534 0 1 1-.167 1.055a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.309.165a.534.534 0 0 1-.68-.824");
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lzxh7zbhd {
  d: path("M11.114 16.28a10.5 10.5 0 0 0-2.878 1.918v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h10.453v-6.52z");
}

.m13zyzbuk {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
}

.m3r90ybqp {
  fill: var(--svg-color--000, #000);
  d: path("M13.74 10.354a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .061-.236");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.min4o96wl {
  d: path("M26.529 21.223v4.171h-2.704v-4.171z");
}

.mj2yjgbpz {
  d: path("m11.64 7.899l.001-.001l.002-.002l.005-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.24-.14.42-.21c.36-.143.872-.257 1.494-.159a.534.534 0 1 1-.167 1.055a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.309.165a.534.534 0 0 1-.68-.824");
}

.muhausb9b {
  d: path("M23.137 25.314c0-.401.325-.732.726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.406-.657");
}

.mvrro-b_u {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
}

.mx_0g-cbx {
  d: path("M8.226 29.988v-11.79c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07z");
}

.n8vj2kb3y {
  stop-color: var(--svg-color--f6f4ff, #F6F4FF);
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nw8wqqnto {
  d: path("m9.608 17.112l-.13 1.733a.6.6 0 0 0 .493.636l.48.085a.15.15 0 0 1 .085.248l-.626.691a.5.5 0 0 0 .014.687L14.656 26a.2.2 0 0 0 .343-.14v-3.381a2 2 0 0 0-.176-.82l-2.605-5.803c-.93.299-1.807.723-2.61 1.256");
}

.o_p71tb4b {
  cx: 12.959px;
  cy: 9.843px;
  rx: 0.39px;
  ry: 0.197px;
}

.o1zpkw-ti {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.022 9.19c-.654 0-1.206.45-1.356 1.059a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.129");
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o77zymbyt {
  stop-color: var(--svg-color--a588b8, #A588B8);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.ocku6nzyd {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ox0t0tbyw {
  d: path("M15.466 15.348c-2.75 0-5.32 1.06-7.23 2.85v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h21.79l.01-2.03c.01-1.76-.25-3.51-.77-5.18c-.57-1.81-1.59-3.38-2.91-4.61a10.62 10.62 0 0 0-7.2-2.82");
}

.p4k8mjbje {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
}

.p9rinuedy {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
  stop-opacity: 0;
}

.pclg_efwa {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
}

.pghrmkbuz {
  d: path("M10.254 8.568c0-.267.107-.587.322-.747l.161-.16c.269-.214.376-.534.376-.855v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.919-.427s3.275.267 3.92.427c.214.054.429.267.429.534v.854c0 .32.161.641.376.855c.502.352.471.545.43.96a47 47 0 0 0-.108 1.442h.018l-.266 3.962c-.16 1.771-1.553 3.006-3.213 3.006h-3.214c-1.714 0-3.053-1.235-3.213-3.006c-.14-1.818-.201-3.642-.367-5.457");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.q-fl22tnr {
  stop-color: var(--svg-color--cfbce6, #CFBCE6);
}

.q3ap7obeh {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.676px;
  rx: 0.391px;
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q4mowll4q {
  stop-color: var(--svg-color--e2d2f8, #E2D2F8);
  stop-opacity: 0;
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.ql-d_bcrc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 25.99h1.797");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-0tl8b_g {
  stop-color: var(--svg-color--bfa7d3, #BFA7D3);
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
}

.r1tra0r1f {
  stop-color: var(--svg-color--a4c098, #A4C098);
  stop-opacity: 0;
}

.r2srh5bmb {
  cx: 20.187px;
  cy: 10.621px;
  r: 0.996px;
}

.r67fhmbqh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.855 8.273c.327-.29 1.042-.594 1.929-.453");
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rced3uh7f {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
  stop-opacity: 0;
}

.rfuz_acet {
  stop-color: var(--svg-color--c3a5dc, #C3A5DC);
}

.rholibcnu {
  stop-color: var(--svg-color--743d58, #743D58);
}

.rko8b-bmk {
  stop-color: var(--svg-color--714250, #714250);
  stop-opacity: 0;
}

.rxsc4xb2z {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.676px;
  fill: var(--svg-color--addaff, #ADDAFF);
  rx: 0.391px;
}

.ry-6rkb7q {
  stop-color: var(--svg-color--e6d7e3, #E6D7E3);
}

.s44sum5km {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
  stop-opacity: 0;
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.sfa02aclf {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
  stop-opacity: 0;
}

.sfpaimhix {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
  stop-opacity: 0;
}

.sghpbcc-q {
  d: path("M15.466 15.298h-.04c.1 0 .19 0 .3.01c-.09-.01-.18-.01-.26-.01");
}

.t0qf5rbqk {
  stop-color: var(--svg-color--e6d2de, #E6D2DE);
}

.t5bid5bsq {
  stop-color: var(--svg-color--a9ff93, #A9FF93);
  stop-opacity: 0.5;
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tsloro5fn {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u3mn6obsi {
  d: path("M14.045 10.25c0-.29-.235-.482-.299-.54l-.288.28l.178.36z");
}

.ubsir5m6c {
  stop-color: var(--svg-color--ccff86, #CCFF86);
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.ue9z25r5u {
  d: path("m21.02 18.142l.115 1.534a.53.53 0 0 1-.437.562l-.424.075a.133.133 0 0 0-.076.22l.554.612a.44.44 0 0 1-.012.607l-4.188 4.255a.177.177 0 0 1-.303-.125v-2.99c0-.25.053-.498.155-.726l2.306-5.135a9.4 9.4 0 0 1 2.31 1.11");
}

.ugp1co_qm {
  d: path("m20.24 4.137l.43.214c.752.374 1.181 1.228 1.02 2.135L21.1 9.53c-.053.314-.26.526-.573.534h-.018s.054-.908.107-1.441c.044-.434-.032-.566-.43-.961c-.214-.214-.375-.534-.375-.854v-.855c0-.267-.215-.48-.43-.533c-.644-.16-1.986-.428-3.919-.428s-3.275.267-3.92.428a.52.52 0 0 0-.429.533v.855c0 .32-.107.64-.376.854l-.16.16c-.216.16-.323.48-.323.747c.054.587.107 1.442.107 1.442l-.049-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.322-1.708 1.073-2.082l.43-.214a8 8 0 0 0 .805-.587l.967-1.014c.59-.534 1.45-.694 2.201-.32c.537.16 1.127.16 1.664 0c.806-.267 1.718-.054 2.363.533l.805.801c.215.267.483.427.805.587");
}

.urcxffbma {
  cx: 20.187px;
  cy: 10.621px;
  r: 1.671px;
}

.v0fk_zbwr {
  stop-color: var(--svg-color--83b651, #83B651);
}

.v4-zmrbyl {
  stop-color: var(--svg-color--b0a6b5, #B0A6B5);
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v5bz9nbam {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.534 9.65c.064.085-.07.189-.22.302c-.151.113-.264.193-.327.107c-.064-.085.007-.245.158-.358c.152-.113.326-.136.39-.051");
}

.v6bhjtbbk {
  stop-color: var(--svg-color--a8a1ad, #A8A1AD);
  stop-opacity: 0;
}

.v6ge5bcpf {
  stop-color: var(--svg-color--faf8fe, #FAF8FE);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vj-z_k0mv {
  d: path("M17.6 9.461a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.13");
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.vxd8ts5kx {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
}

.vzhel1b-t {
  d: path("M19.865 16.28a10.5 10.5 0 0 1 2.878 1.918v.014l.01-.014c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07H15.98v-6.52z");
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w01lnqx9a {
  stop-color: var(--svg-color--bfa6da, #BFA6DA);
}

.w4j6xtngg {
  stop-color: var(--svg-color--3971d9, #3971D9);
  stop-opacity: 0;
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.whxihzpaf {
  stop-color: var(--svg-color--5f3e52, #5F3E52);
}

.wyf8ygbxi {
  stop-color: var(--svg-color--997c73, #997C73);
}

.x3hlfcbwc {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
}

.x3pdtmzbl {
  stop-color: var(--svg-color--29615d, #29615D);
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xoi7hsb-w {
  stop-color: var(--svg-color--ddcef1, #DDCEF1);
}

.xx10debny {
  stop-color: var(--svg-color--c0a9d9, #C0A9D9);
  stop-opacity: 0;
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.y7uo9pa4k {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.807 9.19c.654 0 1.206.45 1.356 1.059a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ycu0bme2d {
  stop-color: var(--svg-color--c2bfc3, #C2BFC3);
}

.yfm2n9bqy {
  cx: 10.665px;
  cy: 10.621px;
  r: 0.996px;
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.z4xhuybyb {
  stop-color: var(--svg-color--c8c2cc, #C8C2CC);
}

.z5vky0btk {
  d: path("m10.312 10.008l.05.002s-.054-.855-.108-1.442c0-.267.107-.587.322-.747l.161-.16c.269-.214.376-.534.376-.855v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.919-.427s3.275.267 3.92.427c.214.054.429.267.429.534v.854c0 .32.161.641.376.855c.502.352.471.545.43.96a47 47 0 0 0-.108 1.442h.018l-.266 3.962c-.16 1.771-1.553 3.006-3.213 3.006h-3.214c-1.714 0-3.053-1.235-3.213-3.006z");
}

.z78o0obou {
  stop-color: var(--svg-color--c6a5e0, #C6A5E0);
}

.z9ohlqbzd {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.054 13.381c.393.205.863.323 1.363.323c.505 0 .97-.118 1.363-.323a.204.204 0 0 1 .242.04c.058.06.079.155.021.241m-2.99-.281l2.948.253m-2.947-.253a.2.2 0 0 0-.243.042a.19.19 0 0 0-.02.24m.263-.282l-.222.253m3.211.028l-.042-.028m.042.028l-.042-.028m.042.028a1.95 1.95 0 0 1-1.626.87a1.95 1.95 0 0 1-1.626-.87m3.21-.028c-.335.508-.919.847-1.584.847s-1.25-.339-1.585-.847m-.041.028v.001l.041-.029m-.041.028l.041-.028");
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zpmhxsbxd {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
  stop-opacity: 0;
}

.zqbntluns {
  stop-color: var(--svg-color--746e77, #746E77);
}

.zqwukdh4o {
  d: path("m19.384 4.991l-3.08 1.027a1.048 1.048 0 0 0 .47 2.034l3.063-.41z");
}

.zt127j5os {
  stop-color: var(--svg-color--ddd8e2, #DDD8E2);
  stop-opacity: 0;
}

.zzx1n12cg {
  d: path("M18.396 10.237a.84.84 0 0 0-.232-.463l-.26.285l.117.228z");
}

</style>
