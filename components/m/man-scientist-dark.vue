<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ivWcDIe)" class="sghpbcc-q"/><path fill="url(#iyYnmte)" class="ox0t0tbyw"/><path fill="url(#iUDSZ5b)" class="ox0t0tbyw"/><path fill="url(#iNLTPlc)" class="lzxh7zbhd"/><path fill="url(#i8s27wu)" class="lzxh7zbhd"/><path fill="url(#iEjhPFO)" class="lzxh7zbhd"/><path fill="url(#iIr2zNb)" class="lzxh7zbhd"/><path fill="url(#i6IymKc)" class="vzhel1b-t"/><path fill="url(#icbfzYc)" class="vzhel1b-t"/><path fill="url(#iD7xuyW)" class="vzhel1b-t"/><path fill="url(#iokG4Xd)" class="vzhel1b-t"/><g filter="url(#iL0LK0D)"><path fill="url(#iPm6Z8c)" class="hjxoqcl0v"/></g><g filter="url(#i8z6RPd)"><path fill="url(#iBCBk6c)" class="nw8wqqnto"/></g><g filter="url(#iOiaX4c)"><path fill="url(#ic5ISlz)" class="ue9z25r5u"/></g><path fill="url(#iXMjlYd)" class="j1xrp0vsi"/><path fill="url(#iuMA8qd)" class="j1xrp0vsi"/><path fill="url(#i3Tf6Wx)" class="j1xrp0vsi"/><path fill="url(#i3bFchc)" class="j1xrp0vsi"/><path fill="url(#iTzbEqb)" class="j1xrp0vsi"/><path fill="url(#iziRMXb)" class="mx_0g-cbx"/><path fill="url(#iWWrm2c)" class="mx_0g-cbx"/><path fill="url(#iYC5CUv)" class="mx_0g-cbx"/><path fill="url(#iOYmIxc)" class="mx_0g-cbx"/><path fill="url(#iV5Qwac)" class="nw8wqqnto"/><path fill="url(#iEtcdkc)" class="lceri-vrq"/><path fill="url(#i5KOZnc)" class="lceri-vrq"/><path fill="url(#ivWcDIe)" class="sghpbcc-q"/><g filter="url(#it0RYfU)"><path fill="url(#iFFQCQc)" class="ftb0dac9p"/><path fill="url(#iEl0mxc)" class="ftb0dac9p"/></g><path fill="url(#iIfUsnd)" class="gip5y3buk"/><path fill="url(#iGWro6b)" class="gip5y3buk"/><path fill="url(#ixATofe)" class="a0q7e-rbb"/><path fill="url(#iIN33ps)" class="a0q7e-rbb"/><path fill="url(#iMD4Akd)" class="a0q7e-rbb"/><g filter="url(#iwVNUVc)"><rect class="rxsc4xb2z"/><rect fill="url(#in80oDb)" class="q3ap7obeh"/><rect fill="url(#iEsINHM)" class="q3ap7obeh"/><rect fill="url(#imH7Vqd)" class="q3ap7obeh"/></g><path fill="url(#itN89Zb)" class="min4o96wl"/><path fill="url(#iWn83Lb)" class="min4o96wl"/><path fill="url(#i6aufrd)" class="min4o96wl"/><path fill="url(#i4MNM9d)" class="min4o96wl"/><path fill="url(#idoLaid)" class="fn5mc_bpm"/><path fill="url(#iwOSsec)" class="cjh4xuujf"/><g filter="url(#iQpzUHW)"><path fill="url(#iYTXx0b)" class="hjy6wxw2l"/><path fill="url(#iRgB2ad)" class="hjy6wxw2l"/><path fill="url(#iY8dWvc)" class="hjy6wxw2l"/><path fill="url(#i4VsJQB)" class="hjy6wxw2l"/><path fill="url(#iywKV1d)" class="hjy6wxw2l"/></g><g filter="url(#ircwXPl)"><path stroke="url(#ie9wmVD)" class="ql-d_bcrc"/></g><g filter="url(#i6QMKVd)"><path stroke="url(#i6jhY6d)" class="dkh21gill"/></g><g filter="url(#itegigK)"><path stroke="url(#iKdTfLn)" class="c7dra70nl"/></g><g filter="url(#iGJ4yPc)"><circle fill="url(#iKssdRd)" class="luigpo9yy"/></g><g filter="url(#iP2zC7d)"><circle fill="url(#inSIsre)" class="yfm2n9bqy"/></g><g filter="url(#iQB6AJc)"><circle fill="url(#iL5S0Ac)" class="urcxffbma"/><circle fill="url(#iiBNEHd)" class="urcxffbma"/></g><g filter="url(#ir2lFad)"><circle class="zfp6bnboq"/><circle fill="url(#i0LEZab)" class="r2srh5bmb"/><circle fill="url(#iFsuGXH)" class="r2srh5bmb"/></g><g filter="url(#iDs31sd)"><path fill="url(#iPQvqAd)" class="n-0ptbwav"/><path fill="url(#iXzeZfb)" class="n-0ptbwav"/><path fill="url(#iKGGijb)" class="n-0ptbwav"/><path fill="url(#itwawBc)" class="n-0ptbwav"/><path fill="url(#iINcekd)" class="n-0ptbwav"/><path fill="url(#iKd6Mgd)" class="n-0ptbwav"/></g><path fill="url(#iVN2icd)" class="n-0ptbwav"/><g filter="url(#igPuimr)"><path fill="url(#iGNpFhd)" class="zqwukdh4o"/></g><g filter="url(#iFHvTjc)"><path class="plxhn8bxy"/><path fill="url(#iwltAKd)" class="lk22h7bpl"/><path fill="url(#iBRxb5c)" class="lk22h7bpl"/><path fill="url(#iSICeie)" class="lk22h7bpl"/><path fill="url(#iS7CLyd)" class="lk22h7bpl"/></g><g filter="url(#irO0cme)"><path class="eol98cbuk"/></g><g filter="url(#imGsPeS)"><path class="ghgvurblv"/><path fill="url(#inSNYLc)" class="qezr3pb3g"/><path fill="url(#iwW4Zbd)" class="qezr3pb3g"/><path fill="url(#iFb8EKd)" class="qezr3pb3g"/><path fill="url(#iwoF65d)" class="qezr3pb3g"/></g><path fill="url(#iwNSQQc)" class="qezr3pb3g"/><path stroke="url(#isgFN0d)" class="vy1opz4il"/><g filter="url(#i4nKWsc)"><path class="a98f88fau"/></g><g filter="url(#isGP2ae)"><path class="pxe2ysbzj"/></g><path class="y7uo9pa4k"/><path fill="url(#iEkS8Me)" class="vj-z_k0mv"/><path class="d008bobtx"/><g filter="url(#i9o6VHc)"><path class="v5bz9nbam"/><path fill="url(#i1W1VTW)" class="lkjxpmb6t"/></g><g filter="url(#iVutUrd)"><path fill="url(#ic0Iy9b)" class="tmj1tjbgv"/></g><path class="o1zpkw-ti"/><path fill="url(#it87QTd)" class="coy2v6bus"/><path class="m3r90ybqp"/><g filter="url(#iGbMsKV)"><path fill="url(#ilNzURD)" class="thi4f1btc"/></g><g filter="url(#itNRaVb)"><ellipse transform="rotate(-27.914 12.96 9.843)" class="hitogzb_c"/><ellipse fill="url(#iadUVcc)" transform="rotate(-27.914 12.96 9.843)" class="o_p71tb4b"/></g><g filter="url(#iFZb0Dc)"><path stroke="url(#iIla2hb)" class="dqffkqz-g"/></g><g filter="url(#iXTLa8d)"><path stroke="url(#ip5MKAb)" class="r67fhmbqh"/></g><g filter="url(#iVxDW8b)"><path stroke="url(#iUloqnc)" class="evqrzqn_f"/></g><path fill="url(#iAk34Qd)" class="lqqx9ouzy"/><g filter="url(#iplupjV)"><path clip-rule="evenodd" class="d32l4nd3w"/></g><defs><radialGradient id="iyYnmte" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.8125 -3.29991 0 15.446 18.316)" gradientUnits="userSpaceOnUse"><stop class="h-vnc5n6a"/><stop offset="1" class="buwur_dqz"/></radialGradient><radialGradient id="iUDSZ5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.65625 6.93357 0 15.446 30.316)" gradientUnits="userSpaceOnUse"><stop class="iufxq5boh"/><stop offset="1" class="w4j6xtngg"/></radialGradient><radialGradient id="iNLTPlc" cx="0" cy="0" r="1" gradientTransform="rotate(161.686 4.493 14.56)scale(4.67425 7.57955)" gradientUnits="userSpaceOnUse"><stop class="d-w3_abhe"/><stop offset="1" class="bqs6izbmd"/></radialGradient><radialGradient id="iIr2zNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.375 -2.57376 0 9.302 17.41)" gradientUnits="userSpaceOnUse"><stop class="x3hlfcbwc"/><stop offset="1" class="sfpaimhix"/></radialGradient><radialGradient id="i6IymKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.15073 2.71782 0 21.206 30.285)" gradientUnits="userSpaceOnUse"><stop class="rfuz_acet"/><stop offset="1" class="q-fl22tnr"/></radialGradient><radialGradient id="icbfzYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -3.9375 0 22.77 18.535)" gradientUnits="userSpaceOnUse"><stop class="n8vj2kb3y"/><stop offset="1" class="irjqokbks"/></radialGradient><radialGradient id="iBCBk6c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7279 1.31251 -2.69681 -7.65971 14.999 21.91)" gradientUnits="userSpaceOnUse"><stop class="iezv8nbum"/><stop offset="1" class="ry-6rkb7q"/></radialGradient><radialGradient id="iXMjlYd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74796 3.71877 -3.74799 -3.7774 22.49 17.691)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="t0qf5rbqk"/></radialGradient><radialGradient id="iuMA8qd" cx="0" cy="0" r="1" gradientTransform="rotate(-64.11 29.307 -.255)scale(8.30198 11.1931)" gradientUnits="userSpaceOnUse"><stop class="mvrro-b_u"/><stop offset=".93" class="ocku6nzyd"/></radialGradient><radialGradient id="i3Tf6Wx" cx="0" cy="0" r="1" gradientTransform="rotate(111.826 5.238 14.38)scale(3.56729 6.41649)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="ycu0bme2d"/><stop offset="1" class="zt127j5os"/></radialGradient><radialGradient id="iziRMXb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95848 0 0 -8.5991 8.226 26.113)" gradientUnits="userSpaceOnUse"><stop class="xoi7hsb-w"/><stop offset="1" class="hkq9astav"/></radialGradient><radialGradient id="iYC5CUv" cx="0" cy="0" r="1" gradientTransform="matrix(-7.51743 0 0 -10.8202 10.005 28.968)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="c1dciy28n"/><stop offset="1" class="vxd8ts5kx"/></radialGradient><radialGradient id="iV5Qwac" cx="0" cy="0" r="1" gradientTransform="rotate(114.365 1.783 11.823)scale(4.20765 8.70789)" gradientUnits="userSpaceOnUse"><stop class="zqbntluns"/><stop offset="1" class="v6bhjtbbk"/></radialGradient><radialGradient id="iEtcdkc" cx="0" cy="0" r="1" gradientTransform="matrix(.41584 12.10916 -8.52544 .29277 24.177 17.879)" gradientUnits="userSpaceOnUse"><stop class="v6ge5bcpf"/><stop offset="1" class="z78o0obou"/></radialGradient><radialGradient id="iFFQCQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.05068 -2.55638 0 15.426 16.567)" gradientUnits="userSpaceOnUse"><stop class="mcxximbde"/><stop offset=".632" class="ixy9j6b2x"/></radialGradient><radialGradient id="iEl0mxc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.25 -.875 0 13.766 15.929)" gradientUnits="userSpaceOnUse"><stop class="b84tk6_fn"/><stop offset="1" class="ow2za2qas"/></radialGradient><radialGradient id="iIfUsnd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7802 1.77747 -2.19627 -2.19964 27.55 23.236)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="k7qyxzbsl"/><stop offset=".946" class="zdypug-8z"/></radialGradient><radialGradient id="iGWro6b" cx="0" cy="0" r="1" gradientTransform="matrix(.80395 -.6129 .32018 .41998 27.206 23.466)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="iMD4Akd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54688 -.39416 0 25.571 19.379)" gradientUnits="userSpaceOnUse"><stop class="hkh0bccgk"/><stop offset="1" class="sfa02aclf"/></radialGradient><radialGradient id="in80oDb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91833 0 0 -.20741 25.177 19.066)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="afeb8bsjy"/><stop offset="1" class="rced3uh7f"/></radialGradient><radialGradient id="iEsINHM" cx="0" cy="0" r="1" gradientTransform="matrix(-.28516 .14844 -.12607 -.24218 27.005 18.918)" gradientUnits="userSpaceOnUse"><stop class="p4k8mjbje"/><stop offset="1" class="e1oaafz6u"/></radialGradient><radialGradient id="imH7Vqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .13281 -.08816 -.11928 23.407 19.277)" gradientUnits="userSpaceOnUse"><stop class="bj_z41bxg"/><stop offset="1" class="boi6rx35q"/></radialGradient><radialGradient id="i4MNM9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -.51563 0 26.227 21.223)" gradientUnits="userSpaceOnUse"><stop class="tsloro5fn"/><stop offset="1" class="p9rinuedy"/></radialGradient><radialGradient id="iRgB2ad" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.574 25.293)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iY8dWvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.574 26.587)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="i4VsJQB" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.574 27.837)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iywKV1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.574 29.189)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iKssdRd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 8.994 10.621)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iiBNEHd" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 20.56 10.356)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="i0LEZab" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.145 11.443)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="iFsuGXH" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.187 10.62)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iKGGijb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.11187 -9.65399 0 15.118 10.426)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="itwawBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 17.765 9.348)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iINcekd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.203 9.315)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="iKd6Mgd" cx="0" cy="0" r="1" gradientTransform="rotate(-166.409 10.845 7.22)scale(2.92567 1.71902)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="iwltAKd" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.09745 .29614 19.766 6.511)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iBRxb5c" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 18.122 4.75)" gradientUnits="userSpaceOnUse"><stop offset=".411" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iSICeie" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 15.417 2.012)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iS7CLyd" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 8.962 8.836)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iwoF65d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 15.745 12.23)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="iEkS8Me" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 17.598 9.938)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i1W1VTW" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.37 10.024)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="it87QTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.23 9.938)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iadUVcc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.472 -1.293)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="ivWcDIe" x1="8.23" x2="22.659" y1="15.296" y2="15.296" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i8s27wu" x1="11.239" x2="11.239" y1="30.41" y2="29.098" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iEjhPFO" x1="15.177" x2="14.208" y1="29.098" y2="29.098" gradientUnits="userSpaceOnUse"><stop offset=".129" class="hu0w8ibzb"/><stop offset="1" class="q4mowll4q"/></linearGradient><linearGradient id="iD7xuyW" x1="19.74" x2="19.74" y1="30.41" y2="29.098" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iokG4Xd" x1="15.802" x2="16.505" y1="27.973" y2="27.973" gradientUnits="userSpaceOnUse"><stop class="o77zymbyt"/><stop offset="1" class="i4kgizoks"/></linearGradient><linearGradient id="iPm6Z8c" x1="10.677" x2="12.896" y1="17.941" y2="24.629" gradientUnits="userSpaceOnUse"><stop class="v4-zmrbyl"/><stop offset="1" class="r-0tl8b_g"/></linearGradient><linearGradient id="ic5ISlz" x1="20.45" x2="18.099" y1="18.97" y2="23.671" gradientUnits="userSpaceOnUse"><stop class="z4xhuybyb"/><stop offset="1" class="lkjzf4omc"/></linearGradient><linearGradient id="i3bFchc" x1="18.958" x2="17.552" y1="24.098" y2="22.598" gradientUnits="userSpaceOnUse"><stop class="dhui3nlqd"/><stop offset="1" class="ifg4wbcuq"/><stop offset="1" class="kzdc46tfj"/></linearGradient><linearGradient id="iTzbEqb" x1="17.146" x2="17.974" y1="18.879" y2="19.223" gradientUnits="userSpaceOnUse"><stop offset=".081" class="foy77stiz"/><stop offset="1" class="i3p8g97ol"/></linearGradient><linearGradient id="iWWrm2c" x1="6.567" x2="6.567" y1="30.353" y2="29.219" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iOYmIxc" x1="8.38" x2="7.935" y1="29.387" y2="29.384" gradientUnits="userSpaceOnUse"><stop offset=".175" class="w01lnqx9a"/><stop offset="1" class="xx10debny"/></linearGradient><linearGradient id="i5KOZnc" x1="22.753" x2="23.162" y1="27.66" y2="27.644" gradientUnits="userSpaceOnUse"><stop class="ckzhu0bvt"/><stop offset="1" class="dtqi4cbss"/></linearGradient><linearGradient id="ixATofe" x1="23.825" x2="26.529" y1="20.848" y2="20.848" gradientUnits="userSpaceOnUse"><stop offset=".253" class="cpykpvzxv"/><stop offset=".773" class="ahix7mbin"/></linearGradient><linearGradient id="iIN33ps" x1="26.529" x2="26.18" y1="20.832" y2="20.832" gradientUnits="userSpaceOnUse"><stop class="g1a66we9o"/><stop offset="1" class="c3eiz-bza"/></linearGradient><linearGradient id="itN89Zb" x1="26.529" x2="25.177" y1="23.16" y2="23.16" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ubsir5m6c"/><stop offset="1" class="v0fk_zbwr"/></linearGradient><linearGradient id="iWn83Lb" x1="26.529" x2="26.129" y1="23.308" y2="23.308" gradientUnits="userSpaceOnUse"><stop class="bywelvb6j"/><stop offset="1" class="s44sum5km"/></linearGradient><linearGradient id="i6aufrd" x1="23.696" x2="24.227" y1="23.308" y2="23.308" gradientUnits="userSpaceOnUse"><stop class="jr9zsmblm"/><stop offset="1" class="r1tra0r1f"/></linearGradient><linearGradient id="idoLaid" x1="24.782" x2="23.892" y1="21.801" y2="21.801" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iwOSsec" x1="24.782" x2="23.892" y1="23.582" y2="23.582" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iYTXx0b" x1="27.165" x2="23.137" y1="28.05" y2="28.05" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="ie9wmVD" x1="23.754" x2="25.463" y1="26.068" y2="26.068" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="i6jhY6d" x1="23.676" x2="25.385" y1="27.373" y2="27.373" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iKdTfLn" x1="23.754" x2="25.463" y1="28.678" y2="28.678" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="inSIsre" x1="10.665" x2="10.023" y1="10.9" y2="10.9" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iL5S0Ac" x1="21.274" x2="20.455" y1="9.529" y2="12.067" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="iPQvqAd" x1="19.457" x2="11.813" y1="11.011" y2="12.15" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="iXzeZfb" x1="10.016" x2="12.283" y1="13.71" y2="13.568" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="iVN2icd" x1="20.271" x2="19.802" y1="13.694" y2="13.648" gradientUnits="userSpaceOnUse"><stop class="dtegydbwv"/><stop offset="1" class="fx5v_x05m"/></linearGradient><linearGradient id="iGNpFhd" x1="16.377" x2="25.002" y1="7.63" y2="4.661" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="inSNYLc" x1="14.552" x2="15.491" y1="11.671" y2="11.671" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iwW4Zbd" x1="16.356" x2="15.33" y1="11.994" y2="11.979" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iFb8EKd" x1="15.612" x2="15.612" y1="12.737" y2="12.163" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="iwNSQQc" x1="15.543" x2="15.543" y1="12.778" y2="12.611" gradientUnits="userSpaceOnUse"><stop class="zoxadnjxe"/><stop offset="1" class="gnvm67mtb"/></linearGradient><linearGradient id="isgFN0d" x1="14.379" x2="14.814" y1="14.353" y2="13.665" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="ic0Iy9b" x1="18.376" x2="18.062" y1="9.992" y2="10.186" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilNzURD" x1="13.975" x2="13.661" y1="9.992" y2="10.186" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iIla2hb" x1="18.392" x2="17.971" y1="7.851" y2="6.991" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ip5MKAb" x1="13.082" x2="11.892" y1="7.723" y2="7.224" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iUloqnc" x1="10.751" x2="10.751" y1="5.706" y2="7.866" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="iAk34Qd" x1="10.917" x2="22.177" y1="9.6" y2="9.6" gradientUnits="userSpaceOnUse"><stop offset=".367" class="ib-sbqbsv"/><stop offset="1" class="exke9fbuy"/></linearGradient><filter id="iL0LK0D" width="7.023" height="11.703" x="8.591" y="15.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2168" stdDeviation=".375"/></filter><filter id="i8z6RPd" width="5.673" height="10.453" x="9.476" y="15.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.721569 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2168"/></filter><filter id="iOiaX4c" width="6.388" height="10.529" x="15.499" y="16.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2168" stdDeviation=".375"/></filter><filter id="it0RYfU" width="4.22" height="3.75" x="13.316" y="14.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.121569 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2168"/></filter><filter id="iwVNUVc" width="4.008" height=".781" x="23.173" y="18.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.796078 0 0 0 0 0.94902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2168"/></filter><filter id="iQpzUHW" width="4.468" height="5.556" x="23.137" y="24.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2168"/></filter><filter id="ircwXPl" width="2.097" height=".3" x="23.604" y="25.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2168" stdDeviation=".05"/></filter><filter id="i6QMKVd" width="2.097" height=".3" x="23.526" y="27.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2168" stdDeviation=".05"/></filter><filter id="itegigK" width="2.097" height=".3" x="23.604" y="28.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2168" stdDeviation=".05"/></filter><filter id="iGJ4yPc" width="3.542" height="3.342" x="8.994" y="8.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2168"/></filter><filter id="iP2zC7d" width="2.992" height="2.992" x="9.169" y="9.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2168" stdDeviation=".25"/></filter><filter id="iQB6AJc" width="3.592" height="3.592" x="18.516" y="8.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2168"/></filter><filter id="ir2lFad" width="2.992" height="2.992" x="18.691" y="9.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2168" stdDeviation=".25"/></filter><filter id="iDs31sd" width="10.383" height="12.189" x="10.254" y="4.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2168"/></filter><filter id="igPuimr" width="6.25" height="5.07" x="14.587" y="3.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2168" stdDeviation=".5"/></filter><filter id="iFHvTjc" width="12.614" height="8.551" x="9.11" y="1.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2168"/></filter><filter id="irO0cme" width="3.262" height="4.184" x="13.547" y="9.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2168" stdDeviation=".375"/></filter><filter id="imGsPeS" width="2.379" height="3.184" x="14.228" y="9.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2168" stdDeviation=".125"/></filter><filter id="i4nKWsc" width="2.982" height="1.874" x="16.6" y="6.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2168"/></filter><filter id="isGP2ae" width="2.982" height="1.874" x="11.447" y="6.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2168"/></filter><filter id="i9o6VHc" width=".787" height=".697" x="16.863" y="9.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2168" stdDeviation=".05"/></filter><filter id="iVutUrd" width=".892" height=".914" x="17.704" y="9.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2168" stdDeviation=".1"/></filter><filter id="iGbMsKV" width=".987" height="1.041" x="13.258" y="9.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2168" stdDeviation=".1"/></filter><filter id="itNRaVb" width=".914" height=".705" x="12.502" y="9.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2168" stdDeviation=".05"/></filter><filter id="iFZb0Dc" width="2.701" height="1.282" x="16.654" y="7.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2168" stdDeviation=".15"/></filter><filter id="iXTLa8d" width="2.779" height="1.339" x="11.43" y="7.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2168" stdDeviation=".15"/></filter><filter id="iVxDW8b" width="1.008" height="2.271" x="10.246" y="5.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2168" stdDeviation=".125"/></filter><filter id="iplupjV" width="11.479" height="6.324" x="9.611" y="5.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.537255 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2168"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.760784 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2168" result="effect2_innerShadow_4002_2168"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-scientist-dark" /></template>
<style>
.a0q7e-rbb {
  d: path("M23.825 19.457h2.703v5.938h-2.703z");
}

.a98f88fau {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m19.14 7.899l-.001-.001l-.002-.002l-.005-.004l-.012-.01a1.3 1.3 0 0 0-.155-.107c-.1-.062-.24-.14-.42-.21a2.84 2.84 0 0 0-1.494-.159a.534.534 0 1 0 .167 1.055c.398-.063.717.01.935.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .68-.824");
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.afeb8bsjy {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ahix7mbin {
  stop-color: var(--svg-color--bff0ff, #BFF0FF);
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.b84tk6_fn {
  stop-color: var(--svg-color--432c2c, #432C2C);
}

.bj_z41bxg {
  stop-color: var(--svg-color--caedff, #CAEDFF);
}

.boi6rx35q {
  stop-color: var(--svg-color--caedff, #CAEDFF);
  stop-opacity: 0;
}

.bqs6izbmd {
  stop-color: var(--svg-color--cdc1db, #CDC1DB);
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.buwur_dqz {
  stop-color: var(--svg-color--2f649d, #2F649D);
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.bywelvb6j {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
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

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cgqcq-bjq {
  stop-color: var(--svg-color--675454, #675454);
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

.coy2v6bus {
  d: path("M13.229 9.461a.893.893 0 0 0-.86 1.129h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.893");
}

.cpykpvzxv {
  stop-color: var(--svg-color--a3d3ff, #A3D3FF);
}

.d-w3_abhe {
  stop-color: var(--svg-color--e3d3fa, #E3D3FA);
}

.d008bobtx {
  fill: var(--svg-color--000, #000);
  d: path("M17.088 10.354a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.747h-.905a.46.46 0 0 1-.06-.236");
}

.d32l4nd3w {
  fill: var(--svg-color--ada3b0, #ADA3B0);
  fill-rule: evenodd;
  d: path("M9.761 9.042c.012-1.676 1.389-3.005 3.047-3.005h5.275a3.01 3.01 0 0 1 3.007 3.04v.001c-.022 1.567-1.339 2.918-2.907 2.973h-.002a3.06 3.06 0 0 1-2.63-1.342c-.045-.065-.09-.076-.112-.076s-.067.01-.112.076a3.08 3.08 0 0 1-2.549 1.352a3.02 3.02 0 0 1-3.017-3.017zm.6.003a2.42 2.42 0 0 0 2.417 2.416c.841 0 1.62-.435 2.05-1.085l.002-.003a.74.74 0 0 1 .609-.34c.243 0 .465.128.609.34v.001a2.46 2.46 0 0 0 2.114 1.077c1.248-.044 2.31-1.133 2.328-2.381a2.41 2.41 0 0 0-2.407-2.433h-5.275c-1.336 0-2.437 1.07-2.447 2.408");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d7d_80btw {
  stop-color: var(--svg-color--0e7268, #0E7268);
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

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.dtegydbwv {
  stop-color: var(--svg-color--5f4b48, #5F4B48);
}

.dtqi4cbss {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1oaafz6u {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
  stop-opacity: 0;
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
}

.eol98cbuk {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.141 10.499l-.82 1.701c-.103.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.701c-.107-.377-.284-.377-.396 0");
}

.evqrzqn_f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.88 5.805v.899c-.008.148-.07.481-.259.622");
}

.exke9fbuy {
  stop-color: var(--svg-color--5fb390, #5FB390);
  stop-opacity: 0.5;
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fn5mc_bpm {
  d: path("M23.825 22.035v-.469h.805a.234.234 0 1 1 0 .469z");
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
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

.fx5v_x05m {
  stop-color: var(--svg-color--5f4b48, #5F4B48);
  stop-opacity: 0;
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g1a66we9o {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.ghgvurblv {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.034 10.336l-.532 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.531-1.7c-.114-.377-.646-.377-.766 0");
}

.gip5y3buk {
  d: path("M26.434 22.958c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.gnvm67mtb {
  stop-color: var(--svg-color--31171f, #31171F);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h-vnc5n6a {
  stop-color: var(--svg-color--3a6fb4, #3A6FB4);
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
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

.hjy6wxw2l {
  d: path("M23.137 25.314a.73.73 0 0 1 .726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.406-.657");
}

.hkh0bccgk {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
}

.hkq9astav {
  stop-color: var(--svg-color--d6cbe2, #D6CBE2);
}

.hu0w8ibzb {
  stop-color: var(--svg-color--b5a2c9, #B5A2C9);
}

.i3p8g97ol {
  stop-color: var(--svg-color--e2d6f0, #E2D6F0);
  stop-opacity: 0;
}

.i4kgizoks {
  stop-color: var(--svg-color--d1bee7, #D1BEE7);
  stop-opacity: 0;
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.ib-sbqbsv {
  stop-color: var(--svg-color--335c55, #335C55);
}

.iezv8nbum {
  stop-color: var(--svg-color--fcefff, #FCEFFF);
}

.ifg4wbcuq {
  stop-color: var(--svg-color--e2d2ee, #E2D2EE);
  stop-opacity: 0;
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.irjqokbks {
  stop-color: var(--svg-color--d7ccea, #D7CCEA);
  stop-opacity: 0;
}

.iufxq5boh {
  stop-color: var(--svg-color--3971d9, #3971D9);
}

.ixy9j6b2x {
  stop-color: var(--svg-color--42272a, #42272A);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j1xrp0vsi {
  d: path("m21.37 17.112l.132 1.733a.6.6 0 0 1-.494.636l-.48.085a.15.15 0 0 0-.085.248l.626.691a.5.5 0 0 1-.014.687L16.323 26a.2.2 0 0 1-.343-.14v-3.381a2 2 0 0 1 .175-.82l2.606-5.803c.929.299 1.807.723 2.61 1.256");
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.jr9zsmblm {
  stop-color: var(--svg-color--a4c098, #A4C098);
}

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kzdc46tfj {
  stop-color: var(--svg-color--e7cfff, #E7CFFF);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lceri-vrq {
  d: path("M22.753 29.988v-11.79c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07z");
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk22h7bpl {
  d: path("m20.24 4.137l.43.214c.752.374 1.181 1.228 1.02 2.135L21.1 9.53c-.053.314-.261.526-.573.534h-.018s.053-.908.107-1.441c.044-.434-.032-.566-.43-.961c-.214-.214-.375-.534-.375-.854v-.855c0-.267-.215-.48-.43-.533c-.644-.16-1.986-.428-3.92-.428c-1.932 0-3.274.267-3.918.428a.52.52 0 0 0-.43.533v.855c0 .32-.107.64-.376.854l-.16.16c-.216.16-.323.48-.323.747c.054.587.107 1.442.107 1.442l-.049-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.322-1.708 1.073-2.082l.43-.214a8 8 0 0 0 .805-.587l.966-1.014c.591-.534 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.806-.267 1.718-.054 2.363.533l.805.801c.215.267.483.427.805.587");
}

.lkjxpmb6t {
  d: path("M17.534 9.65c.064.085-.07.189-.22.302c-.151.113-.264.193-.327.107c-.064-.085.007-.245.158-.358c.152-.113.326-.136.39-.051");
}

.lkjzf4omc {
  stop-color: var(--svg-color--c5b2dd, #C5B2DD);
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

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.lzxh7zbhd {
  d: path("M11.114 16.28a10.5 10.5 0 0 0-2.878 1.918v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h10.453v-6.52z");
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m3r90ybqp {
  fill: var(--svg-color--000, #000);
  d: path("M13.74 10.354a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .061-.236");
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcxximbde {
  stop-color: var(--svg-color--371a2d, #371A2D);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.min4o96wl {
  d: path("M26.529 21.223v4.171h-2.704v-4.171z");
}

.mvrro-b_u {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
}

.mx_0g-cbx {
  d: path("M8.226 29.988v-11.79c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07z");
}

.n-0ptbwav {
  d: path("m10.312 10.008l.05.002s-.054-.855-.108-1.442c0-.267.107-.587.322-.747l.161-.16c.269-.214.376-.534.376-.855v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.214.054.429.267.429.534v.854c0 .32.161.641.376.855c.502.352.471.545.43.96a46 46 0 0 0-.108 1.442h.018l-.266 3.962c-.16 1.771-1.553 3.006-3.213 3.006h-3.214c-1.714 0-3.053-1.235-3.213-3.006z");
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n8vj2kb3y {
  stop-color: var(--svg-color--f6f4ff, #F6F4FF);
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
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

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o1zpkw-ti {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.022 9.19c-.654 0-1.206.45-1.356 1.059a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.129");
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o77zymbyt {
  stop-color: var(--svg-color--a588b8, #A588B8);
}

.ocku6nzyd {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ow2za2qas {
  stop-color: var(--svg-color--432c2c, #432C2C);
  stop-opacity: 0;
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

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plxhn8bxy {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m20.24 4.137l.43.214c.752.374 1.181 1.228 1.02 2.135L21.1 9.53c-.053.314-.261.526-.573.534h-.018s.053-.908.107-1.441c.044-.434-.032-.566-.43-.961c-.214-.214-.375-.534-.375-.854v-.855c0-.267-.215-.48-.43-.533c-.644-.16-1.986-.428-3.92-.428c-1.932 0-3.274.267-3.918.428a.52.52 0 0 0-.43.533v.855c0 .32-.107.64-.376.854l-.16.16c-.216.16-.323.48-.323.747c.054.587.107 1.442.107 1.442l-.049-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.322-1.708 1.073-2.082l.43-.214a8 8 0 0 0 .805-.587l.966-1.014c.591-.534 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.806-.267 1.718-.054 2.363.533l.805.801c.215.267.483.427.805.587");
}

.pxe2ysbzj {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.64 7.899l.001-.001l.002-.002l.005-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.24-.14.42-.21c.36-.143.872-.257 1.494-.159a.534.534 0 1 1-.167 1.055a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.309.165a.534.534 0 0 1-.68-.824");
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

.q4mowll4q {
  stop-color: var(--svg-color--e2d2f8, #E2D2F8);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qezr3pb3g {
  d: path("m15.034 10.336l-.532 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.531-1.7c-.114-.377-.646-.377-.766 0");
}

.ql-d_bcrc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 25.99h1.797");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxb7siz6w {
  stop-color: var(--svg-color--3f282a, #3F282A);
}

.r-0tl8b_g {
  stop-color: var(--svg-color--bfa7d3, #BFA7D3);
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

.rced3uh7f {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
  stop-opacity: 0;
}

.rfuz_acet {
  stop-color: var(--svg-color--c3a5dc, #C3A5DC);
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

.thi4f1btc {
  d: path("M14.045 10.25c0-.29-.235-.482-.298-.54l-.289.28l.178.36z");
}

.tmj1tjbgv {
  d: path("M18.395 10.237a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.tsloro5fn {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
}

.ubsir5m6c {
  stop-color: var(--svg-color--ccff86, #CCFF86);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.ue9z25r5u {
  d: path("m21.02 18.142l.115 1.534a.53.53 0 0 1-.437.562l-.424.075a.133.133 0 0 0-.076.22l.554.612a.44.44 0 0 1-.012.607l-4.188 4.255a.177.177 0 0 1-.303-.125v-2.99c0-.25.053-.498.155-.726l2.306-5.135a9.4 9.4 0 0 1 2.31 1.11");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.ur8e5kbgj {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
  stop-opacity: 0;
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

.vj-z_k0mv {
  d: path("M17.6 9.461a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.13");
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vxd8ts5kx {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
}

.vy1opz4il {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.054 13.381c.393.205.863.323 1.363.323c.505 0 .97-.118 1.363-.323a.204.204 0 0 1 .242.04c.058.06.079.155.021.241m-2.99-.281l2.948.253m-2.947-.253a.2.2 0 0 0-.243.042a.19.19 0 0 0-.02.24m.263-.282l-.222.253m3.211.028l-.042-.028m.042.028l-.042-.028m.042.028a1.95 1.95 0 0 1-1.626.87a1.95 1.95 0 0 1-1.626-.87m3.21-.028c-.335.508-.919.847-1.584.847s-1.25-.338-1.585-.847m-.041.028v.001l.041-.029m-.041.028l.041-.028");
}

.vzhel1b-t {
  d: path("M19.865 16.28a10.5 10.5 0 0 1 2.878 1.918v.014l.01-.014c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07H15.98v-6.52z");
}

.w01lnqx9a {
  stop-color: var(--svg-color--bfa6da, #BFA6DA);
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w4j6xtngg {
  stop-color: var(--svg-color--3971d9, #3971D9);
  stop-opacity: 0;
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
}

.x3hlfcbwc {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
}

.x3pdtmzbl {
  stop-color: var(--svg-color--29615d, #29615D);
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xoi7hsb-w {
  stop-color: var(--svg-color--ddcef1, #DDCEF1);
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.xx10debny {
  stop-color: var(--svg-color--c0a9d9, #C0A9D9);
  stop-opacity: 0;
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.y7uo9pa4k {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.807 9.19c.654 0 1.206.45 1.356 1.059a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.ycu0bme2d {
  stop-color: var(--svg-color--c2bfc3, #C2BFC3);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yfm2n9bqy {
  cx: 10.665px;
  cy: 10.621px;
  r: 0.996px;
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z4xhuybyb {
  stop-color: var(--svg-color--c8c2cc, #C8C2CC);
}

.z78o0obou {
  stop-color: var(--svg-color--c6a5e0, #C6A5E0);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zfp6bnboq {
  cx: 20.187px;
  cy: 10.621px;
  r: 0.996px;
  fill: var(--svg-color--463133, #463133);
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.zoxadnjxe {
  stop-color: var(--svg-color--31171f, #31171F);
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

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
