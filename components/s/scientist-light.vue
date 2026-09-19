<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ivWcDIe)" class="sghpbcc-q"/><path fill="url(#iF2xL7c)" class="ox0t0tbyw"/><path fill="url(#iJex2Eb)" class="ox0t0tbyw"/><path fill="url(#i0x9rSc)" class="lzxh7zbhd"/><path fill="url(#iqijBdb)" class="lzxh7zbhd"/><path fill="url(#iTXvIeu)" class="lzxh7zbhd"/><path fill="url(#iIr2zNb)" class="lzxh7zbhd"/><path fill="url(#idCIDmb)" class="vzhel1b-t"/><path fill="url(#icbfzYc)" class="vzhel1b-t"/><path fill="url(#iYuCe2d)" class="vzhel1b-t"/><path fill="url(#iDWkYOd)" class="vzhel1b-t"/><g filter="url(#iEqIOab)"><path fill="url(#iZ6dTnd)" class="vmc-iabjh"/></g><g filter="url(#iFM6Nuc)"><path fill="url(#iBCBk6c)" class="ainf1jcmz"/></g><g filter="url(#iqpBnSd)"><path fill="url(#ic5ISlz)" class="dgtwjnbll"/></g><path fill="url(#iYFpHob)" class="bew_bibae"/><path fill="url(#iuMA8qd)" class="bew_bibae"/><path fill="url(#i9zEBle)" class="bew_bibae"/><path fill="url(#iL0OQae)" class="bew_bibae"/><path fill="url(#iU0Zedb)" class="bew_bibae"/><path fill="url(#ikhTrkd)" class="mx_0g-cbx"/><path fill="url(#inx4RRc)" class="mx_0g-cbx"/><path fill="url(#iYC5CUv)" class="mx_0g-cbx"/><path fill="url(#isL6aLe)" class="mx_0g-cbx"/><path fill="url(#iKGtVBM)" class="ainf1jcmz"/><path fill="url(#iTZvVue)" class="lceri-vrq"/><path fill="url(#i5KOZnc)" class="lceri-vrq"/><path fill="url(#ivWcDIe)" class="sghpbcc-q"/><path fill="url(#itTjdXb)" class="l69inwbok"/><path fill="url(#iK0HGSc)" class="l69inwbok"/><path fill="url(#i2hcoXd)" class="gip5y3buk"/><path fill="url(#ihXXnId)" class="gip5y3buk"/><path fill="url(#ixdtEFe)" class="wpy995b9j"/><path fill="url(#iF1k9Ki)" class="wpy995b9j"/><path fill="url(#ilUA1Ec)" class="wpy995b9j"/><g filter="url(#ifPOLWb)"><rect class="b_wzmzbwq"/><rect fill="url(#in80oDb)" class="tkgx_8bnk"/><rect fill="url(#iEsINHM)" class="tkgx_8bnk"/><rect fill="url(#imH7Vqd)" class="tkgx_8bnk"/></g><path fill="url(#itN89Zb)" class="a124lcdye"/><path fill="url(#iWn83Lb)" class="a124lcdye"/><path fill="url(#i6aufrd)" class="a124lcdye"/><path fill="url(#iqwFqNS)" class="a124lcdye"/><path fill="url(#iiRMWBW)" class="j9vp7gz0m"/><path fill="url(#iYneMqd)" class="j68h5l-_g"/><g filter="url(#imSSfKE)"><path fill="url(#ixUGKJk)" class="heg5c9gcv"/><path fill="url(#iCph9Ib)" class="heg5c9gcv"/><path fill="url(#iXPsQYd)" class="heg5c9gcv"/><path fill="url(#i5Umrrc)" class="heg5c9gcv"/><path fill="url(#ipuibcc)" class="heg5c9gcv"/></g><path fill="url(#i7QtCxy)" class="heg5c9gcv"/><g filter="url(#iP3bUGX)"><path stroke="url(#iV85h8t)" class="ql-d_bcrc"/></g><g filter="url(#iqxHege)"><path stroke="url(#iKoqh9b)" class="sqxhjlnxl"/></g><g filter="url(#iXmk8Ec)"><path stroke="url(#iQKjYHb)" class="c7dra70nl"/></g><path fill="url(#i0V0Mvc)" class="i-_q9txbo"/><path fill="url(#iyxB2Sb)" class="vwrtm3bab"/><g filter="url(#iu7oVhc)"><path fill="url(#izeTu1x)" class="w7du6pb_e"/></g><path fill="url(#iBDnBjc)" class="w7du6pb_e"/><path fill="url(#i9xFYMe)" class="w7du6pb_e"/><path fill="url(#iqBQxhb)" class="w7du6pb_e"/><path fill="url(#ingtXNc)" class="w7du6pb_e"/><path fill="url(#iGqJ6Sd)" class="w7du6pb_e"/><path fill="url(#iHRRvxd)" class="w7du6pb_e"/><path fill="url(#iEq7Koe)" class="w7du6pb_e"/><g filter="url(#igrnibb)"><path class="qxnrq812s"/></g><g filter="url(#iEtyqCd)"><path class="xynzhkbxy"/><path fill="url(#iApdixu)" class="fz7829bxy"/><path fill="url(#inmCk6k)" class="fz7829bxy"/><path fill="url(#iOYBYzD)" class="fz7829bxy"/><path fill="url(#iL7LsTb)" class="fz7829bxy"/><path fill="url(#iV7Swbb)" class="fz7829bxy"/></g><g filter="url(#iGjJVJc)"><path stroke="url(#ij4kfsc)" class="rvpscutoq"/></g><path fill="url(#ijVklIe)" class="ht7we4nuf"/><g filter="url(#iGMxN5G)"><path fill="url(#iooPrHl)" class="alk6evr_q"/><path fill="url(#iJrd4Gc)" class="alk6evr_q"/><path fill="url(#iWrkBVO)" class="alk6evr_q"/><path fill="url(#i1h7SAE)" class="alk6evr_q"/><path fill="url(#ilebzPe)" class="alk6evr_q"/></g><g filter="url(#ig2iE8c)"><path class="erfl5rbdl"/></g><g filter="url(#imZYUhb)"><path class="q01--1lrv"/></g><g filter="url(#iECqEcc)"><path class="z8ub0xbwd"/><path fill="url(#iVww9ib)" class="ybkft5ymj"/><path fill="url(#iemKnJe)" class="ybkft5ymj"/></g><g filter="url(#iCPLJqd)"><path class="v8w-mebcs"/><path fill="url(#i4jhvyb)" class="pevf4cfll"/><path fill="url(#icqR3Sd)" class="pevf4cfll"/><path fill="url(#iz1TJLe)" class="pevf4cfll"/></g><path class="yae6yabyn"/><path fill="url(#iZE941c)" class="kn3fsib5n"/><path class="zgetey7cf"/><g filter="url(#iwBDKqc)"><path class="isxfb77db"/><path fill="url(#iqTGPrb)" class="ix8mu0bhv"/></g><g filter="url(#iqFTQ6c)"><path fill="url(#iJzTwQd)" class="jr9hdpl0f"/></g><path class="gmjg4ccxy"/><path fill="url(#iIUOmce)" class="o2winac2b"/><path class="b0maullyh"/><g filter="url(#i5jlsSh)"><path fill="url(#iaMsqcb)" class="sb62shdsk"/></g><g filter="url(#iqYnMhb)"><ellipse transform="rotate(-27.914 12.973 10.113)" class="pdbgs6drv"/><ellipse fill="url(#iWsRgQr)" transform="rotate(-27.914 12.973 10.113)" class="b9q8czbkr"/></g><path fill="url(#iZ76jhe)" class="nba0bkbns"/><path fill="url(#iiuSvYd)" class="nba0bkbns"/><path fill="url(#ikYWktb)" class="nba0bkbns"/><path fill="url(#i8f1DHe)" class="nba0bkbns"/><path fill="url(#iEymkTc)" class="geaiemm2w"/><path fill="url(#iCrKoOd)" class="geaiemm2w"/><g filter="url(#iZtBXkB)"><path fill="url(#ipwYZrg)" class="h6b9t3l5c"/></g><g filter="url(#iocY7Il)"><path fill="url(#ikaDmDd)" class="jzblanbdg"/></g><g filter="url(#i8Uwgfc)"><path class="vgq7babse"/></g><g filter="url(#iuarFOb)"><path class="n93nbib0k"/></g><g filter="url(#igAesYn)" class="z4n2hhy8u"><path fill="url(#i699k9c)" class="xo2zgxulc"/></g><g filter="url(#iLMAr9c)"><path clip-rule="evenodd" class="d5_x1jahj"/></g><defs><radialGradient id="iF2xL7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.8125 -3.29991 0 15.446 18.316)" gradientUnits="userSpaceOnUse"><stop class="e2ig5yb1x"/><stop offset="1" class="rsfdnufmx"/></radialGradient><radialGradient id="iJex2Eb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.65625 6.93357 0 15.446 30.316)" gradientUnits="userSpaceOnUse"><stop class="eol9ugodk"/><stop offset="1" class="e080jybbb"/></radialGradient><radialGradient id="i0x9rSc" cx="0" cy="0" r="1" gradientTransform="rotate(161.686 4.493 14.56)scale(4.67425 7.57955)" gradientUnits="userSpaceOnUse"><stop class="hy6proxed"/><stop offset="1" class="bqs6izbmd"/></radialGradient><radialGradient id="iIr2zNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.375 -2.57376 0 9.302 17.41)" gradientUnits="userSpaceOnUse"><stop class="x3hlfcbwc"/><stop offset="1" class="sfpaimhix"/></radialGradient><radialGradient id="idCIDmb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.15073 2.71782 0 21.206 30.285)" gradientUnits="userSpaceOnUse"><stop class="lj5m7ucmi"/><stop offset="1" class="d3a6h5dbs"/></radialGradient><radialGradient id="icbfzYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -3.9375 0 22.77 18.535)" gradientUnits="userSpaceOnUse"><stop class="n8vj2kb3y"/><stop offset="1" class="irjqokbks"/></radialGradient><radialGradient id="iBCBk6c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7279 1.31251 -2.69681 -7.65971 14.999 21.91)" gradientUnits="userSpaceOnUse"><stop class="iezv8nbum"/><stop offset="1" class="ry-6rkb7q"/></radialGradient><radialGradient id="iYFpHob" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74796 3.71877 -3.74799 -3.7774 22.49 17.69)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="t0qf5rbqk"/></radialGradient><radialGradient id="iuMA8qd" cx="0" cy="0" r="1" gradientTransform="rotate(-64.11 29.307 -.255)scale(8.30198 11.1931)" gradientUnits="userSpaceOnUse"><stop class="mvrro-b_u"/><stop offset=".93" class="ocku6nzyd"/></radialGradient><radialGradient id="i9zEBle" cx="0" cy="0" r="1" gradientTransform="matrix(-.73439 2.1875 -3.93465 -1.32095 19.943 15.988)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="xpzhm0iru"/><stop offset="1" class="jqs3afbfy"/></radialGradient><radialGradient id="ikhTrkd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95848 0 0 -8.5991 8.226 26.112)" gradientUnits="userSpaceOnUse"><stop class="xoi7hsb-w"/><stop offset="1" class="hkq9astav"/></radialGradient><radialGradient id="iYC5CUv" cx="0" cy="0" r="1" gradientTransform="matrix(-7.51743 0 0 -10.8202 10.005 28.968)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="c1dciy28n"/><stop offset="1" class="vxd8ts5kx"/></radialGradient><radialGradient id="iKGtVBM" cx="0" cy="0" r="1" gradientTransform="matrix(-1 2.84375 -3.2172 -1.13131 12.552 16.066)" gradientUnits="userSpaceOnUse"><stop offset=".058" class="fbqio7b7r"/><stop offset="1" class="txsyviqti"/></radialGradient><radialGradient id="iTZvVue" cx="0" cy="0" r="1" gradientTransform="matrix(.41584 12.10916 -8.52544 .29277 24.177 17.878)" gradientUnits="userSpaceOnUse"><stop class="v6ge5bcpf"/><stop offset="1" class="z78o0obou"/></radialGradient><radialGradient id="itTjdXb" cx="0" cy="0" r="1" gradientTransform="matrix(.81871 2.22312 -3.53394 1.30145 15.426 17.172)" gradientUnits="userSpaceOnUse"><stop class="zvwlq8j8i"/><stop offset=".566" class="eay1fibfp"/><stop offset="1" class="t-t2odb0m"/></radialGradient><radialGradient id="iK0HGSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.45312 -1.20313 0 13.666 16.765)" gradientUnits="userSpaceOnUse"><stop class="ajg6ar9_l"/><stop offset="1" class="w3-o4ac4j"/><stop offset="1" class="z96dqpbaj"/></radialGradient><radialGradient id="i2hcoXd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.25223 1.07928 -1.05974 -2.21144 28.021 23.934)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="tj2vllbvr"/><stop offset=".956" class="fop80r8ws"/></radialGradient><radialGradient id="ihXXnId" cx="0" cy="0" r="1" gradientTransform="matrix(.80395 -.6129 .46984 .6163 27.206 23.466)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="q7l79-2rh"/><stop offset="1" class="aszpk2bre"/></radialGradient><radialGradient id="ilUA1Ec" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54688 -.39416 0 25.571 19.378)" gradientUnits="userSpaceOnUse"><stop class="hkh0bccgk"/><stop offset="1" class="sfa02aclf"/></radialGradient><radialGradient id="in80oDb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91833 0 0 -.20741 25.177 19.066)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="afeb8bsjy"/><stop offset="1" class="rced3uh7f"/></radialGradient><radialGradient id="iEsINHM" cx="0" cy="0" r="1" gradientTransform="matrix(-.28516 .14844 -.12607 -.24218 27.005 18.918)" gradientUnits="userSpaceOnUse"><stop class="p4k8mjbje"/><stop offset="1" class="e1oaafz6u"/></radialGradient><radialGradient id="imH7Vqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .13281 -.08816 -.11928 23.407 19.277)" gradientUnits="userSpaceOnUse"><stop class="bj_z41bxg"/><stop offset="1" class="boi6rx35q"/></radialGradient><radialGradient id="iqwFqNS" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -.51563 0 26.227 21.222)" gradientUnits="userSpaceOnUse"><stop class="tsloro5fn"/><stop offset="1" class="p9rinuedy"/></radialGradient><radialGradient id="iCph9Ib" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.574 25.292)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iXPsQYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.574 26.587)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="i5Umrrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.574 27.837)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="ipuibcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.574 29.188)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="i7QtCxy" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.01752 -3.72384 0 27.668 24.97)" gradientUnits="userSpaceOnUse"><stop class="b4rjnnb6m"/><stop offset="1" class="bgp-eqwmb"/></radialGradient><radialGradient id="i0V0Mvc" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.609 20.402)scale(2.15387 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="iyxB2Sb" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46403 -1.43156 4.55498 9.37 12.291)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="izeTu1x" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22784 0 0 -9.248 18.233 10.86)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="i9xFYMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 13 -10.7656 0 15.892 4.52)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="wki8rib4u"/><stop offset="1" class="x7jui5iih"/></radialGradient><radialGradient id="iqBQxhb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 17.873 9.547)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="ingtXNc" cx="0" cy="0" r="1" gradientTransform="matrix(.00393 -1.09427 1.19083 .00428 13.126 9.593)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="iGqJ6Sd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49597 .5363 -1.37 -21.7029 18.858 11.848)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="iHRRvxd" cx="0" cy="0" r="1" gradientTransform="matrix(3.0984 -3.27776 1.1999 1.13424 9.958 6.534)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="iEq7Koe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.74316 2.88295 -2.3801 -1.43912 17.853 5.88)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="inmCk6k" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 15.892 12.376)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="iL7LsTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.008 11.806)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="ijVklIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.8997 0 15.426 14.399)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iJrd4Gc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50132 8.85443 0 10.196 7.967)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iWrkBVO" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 14.997 -5.975)scale(2.51513 4.45631)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="i1h7SAE" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 10.215 -1.423)scale(2.82328 2.07243)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="ilebzPe" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09581 14.52 1.409)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iVww9ib" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20112 0 0 -.81692 15.68 3.668)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iemKnJe" cx="0" cy="0" r="1" gradientTransform="matrix(3.21816 -5.09543 5.64521 3.5654 9.995 7.61)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="i4jhvyb" cx="0" cy="0" r="1" gradientTransform="matrix(3.05838 0 0 1.19577 18.84 4.445)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="icqR3Sd" cx="0" cy="0" r="1" gradientTransform="matrix(2.67872 -2.55217 4.67237 4.90405 18.06 7.482)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iz1TJLe" cx="0" cy="0" r="1" gradientTransform="rotate(6.667 -42.97 150.432)scale(3.27032 1.36922)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iZE941c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.608 10.209)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iqTGPrb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.21 .89)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iIUOmce" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.244 10.209)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iWsRgQr" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 12.958 10.428)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iiuSvYd" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24327 -2.14025 .59968 20.044 9.957)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="ikYWktb" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.404 10.502)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="i8f1DHe" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 20.518 10.674)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="iCrKoOd" cx="0" cy="0" r="1" gradientTransform="rotate(-173.034 5.578 4.98)scale(1.62516 1.74453)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="ipwYZrg" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .15731 -.19303 -1.12456 10.511 10.6)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><linearGradient id="ivWcDIe" x1="8.23" x2="22.659" y1="15.296" y2="15.296" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iqijBdb" x1="11.239" x2="11.239" y1="30.41" y2="29.097" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iTXvIeu" x1="15.177" x2="14.208" y1="29.097" y2="29.097" gradientUnits="userSpaceOnUse"><stop offset=".129" class="dx1e6jb0z"/><stop offset="1" class="q4mowll4q"/></linearGradient><linearGradient id="iYuCe2d" x1="19.74" x2="19.74" y1="30.41" y2="29.097" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iDWkYOd" x1="15.802" x2="16.505" y1="27.972" y2="27.972" gradientUnits="userSpaceOnUse"><stop class="bx23o8bkx"/><stop offset="1" class="i4kgizoks"/></linearGradient><linearGradient id="iZ6dTnd" x1="10.677" x2="12.896" y1="17.941" y2="24.628" gradientUnits="userSpaceOnUse"><stop class="v4-zmrbyl"/><stop offset="1" class="r-0tl8b_g"/></linearGradient><linearGradient id="ic5ISlz" x1="20.45" x2="18.099" y1="18.97" y2="23.671" gradientUnits="userSpaceOnUse"><stop class="z4xhuybyb"/><stop offset="1" class="lkjzf4omc"/></linearGradient><linearGradient id="iL0OQae" x1="18.958" x2="17.552" y1="24.097" y2="22.597" gradientUnits="userSpaceOnUse"><stop class="p2mir8bpk"/><stop offset="1" class="ifg4wbcuq"/></linearGradient><linearGradient id="iU0Zedb" x1="17.146" x2="17.974" y1="18.878" y2="19.222" gradientUnits="userSpaceOnUse"><stop offset=".081" class="ea_0ewlyw"/><stop offset="1" class="z_a2ribdx"/></linearGradient><linearGradient id="inx4RRc" x1="6.567" x2="6.567" y1="30.352" y2="29.219" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="isL6aLe" x1="8.38" x2="7.935" y1="29.386" y2="29.384" gradientUnits="userSpaceOnUse"><stop offset=".175" class="w01lnqx9a"/><stop offset="1" class="xx10debny"/></linearGradient><linearGradient id="i5KOZnc" x1="22.753" x2="23.162" y1="27.66" y2="27.644" gradientUnits="userSpaceOnUse"><stop class="ckzhu0bvt"/><stop offset="1" class="dtqi4cbss"/></linearGradient><linearGradient id="ixdtEFe" x1="23.825" x2="26.529" y1="20.847" y2="20.847" gradientUnits="userSpaceOnUse"><stop offset=".253" class="cpykpvzxv"/><stop offset=".773" class="ahix7mbin"/></linearGradient><linearGradient id="iF1k9Ki" x1="26.529" x2="26.18" y1="20.831" y2="20.831" gradientUnits="userSpaceOnUse"><stop class="g1a66we9o"/><stop offset="1" class="c3eiz-bza"/></linearGradient><linearGradient id="itN89Zb" x1="26.529" x2="25.177" y1="23.16" y2="23.16" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ubsir5m6c"/><stop offset="1" class="v0fk_zbwr"/></linearGradient><linearGradient id="iWn83Lb" x1="26.529" x2="26.129" y1="23.308" y2="23.308" gradientUnits="userSpaceOnUse"><stop class="bywelvb6j"/><stop offset="1" class="s44sum5km"/></linearGradient><linearGradient id="i6aufrd" x1="23.696" x2="24.227" y1="23.308" y2="23.308" gradientUnits="userSpaceOnUse"><stop class="jr9zsmblm"/><stop offset="1" class="r1tra0r1f"/></linearGradient><linearGradient id="iiRMWBW" x1="24.782" x2="23.892" y1="21.8" y2="21.8" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iYneMqd" x1="24.782" x2="23.892" y1="23.581" y2="23.581" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="ixUGKJk" x1="27.165" x2="23.137" y1="28.05" y2="28.05" gradientUnits="userSpaceOnUse"><stop offset=".146" class="v5rheyc4i"/><stop offset=".861" class="j1qr75obr"/></linearGradient><linearGradient id="iV85h8t" x1="23.754" x2="25.463" y1="26.068" y2="26.068" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iKoqh9b" x1="23.676" x2="25.385" y1="27.373" y2="27.373" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iQKjYHb" x1="23.754" x2="25.463" y1="28.677" y2="28.677" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iBDnBjc" x1="20.583" x2="16.23" y1="12.545" y2="12.545" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iApdixu" x1="16.264" x2="15.426" y1="11.69" y2="11.725" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="iOYBYzD" x1="15.426" x2="15.426" y1="12.829" y2="12.364" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="iV7Swbb" x1="15.426" x2="15.426" y1="9.995" y2="10.671" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="ij4kfsc" x1="14.224" x2="14.543" y1="14.244" y2="13.41" gradientUnits="userSpaceOnUse"><stop class="c2rd33bbv"/><stop offset="1" class="zcdcyccef"/></linearGradient><linearGradient id="iooPrHl" x1="22.278" x2="10.665" y1="5.197" y2="5.197" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iJzTwQd" x1="18.386" x2="18.072" y1="10.263" y2="10.456" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iaMsqcb" x1="13.988" x2="13.674" y1="10.262" y2="10.456" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZ76jhe" x1="21.862" x2="20.655" y1="10.024" y2="12.2" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="iEymkTc" x1="9.576" x2="11.034" y1="10.728" y2="10.601" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="ikaDmDd" x1="20.905" x2="20.905" y1="9.653" y2="11.556" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><linearGradient id="i699k9c" x1="10.588" x2="22.177" y1="9.727" y2="9.727" gradientUnits="userSpaceOnUse"><stop class="z473rkg5k"/><stop offset=".115" class="f-zxjbc7n"/><stop offset=".257" class="f-zxjbc7n"/><stop offset=".917" class="l7b4ixb5j"/></linearGradient><filter id="iEqIOab" width="7.023" height="11.703" x="8.591" y="15.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2178" stdDeviation=".375"/></filter><filter id="iFM6Nuc" width="5.673" height="10.453" x="9.475" y="15.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.721569 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2178"/></filter><filter id="iqpBnSd" width="6.388" height="10.529" x="15.499" y="16.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2178" stdDeviation=".375"/></filter><filter id="ifPOLWb" width="4.008" height=".781" x="23.173" y="18.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.796078 0 0 0 0 0.94902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2178"/></filter><filter id="imSSfKE" width="4.468" height="5.556" x="23.137" y="24.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2178"/></filter><filter id="iP3bUGX" width="2.097" height=".3" x="23.604" y="25.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2178" stdDeviation=".05"/></filter><filter id="iqxHege" width="2.097" height=".3" x="23.526" y="27.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2178" stdDeviation=".05"/></filter><filter id="iXmk8Ec" width="2.097" height=".3" x="23.604" y="28.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2178" stdDeviation=".05"/></filter><filter id="iu7oVhc" width="11.22" height="12.542" x="10.363" y="4.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2178"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2178" result="effect2_innerShadow_4002_2178"/></filter><filter id="igrnibb" width="3.747" height="4.9" x="13.41" y="9.186" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2178" stdDeviation=".5"/></filter><filter id="iEtyqCd" width="2.277" height="3.3" x="14.287" y="9.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2178" stdDeviation=".1"/></filter><filter id="iGjJVJc" width="3.718" height="1.573" x="13.566" y="13.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2178" stdDeviation=".05"/></filter><filter id="iGMxN5G" width="12.873" height="8.357" x="8.989" y="1.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2178"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2178" result="effect2_innerShadow_4002_2178"/></filter><filter id="ig2iE8c" width="2.339" height="1.19" x="17.015" y="7.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2178"/></filter><filter id="imZYUhb" width="2.339" height="1.176" x="11.758" y="7.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2178"/></filter><filter id="iECqEcc" width="6.734" height="5.992" x="9.345" y="2.601" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2178"/><feGaussianBlur result="effect2_foregroundBlur_4002_2178" stdDeviation=".125"/></filter><filter id="iCPLJqd" width="6.361" height="5.736" x="15.267" y="3.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2178" stdDeviation=".125"/></filter><filter id="iwBDKqc" width=".787" height=".696" x="16.874" y="9.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2178" stdDeviation=".05"/></filter><filter id="iqFTQ6c" width=".891" height=".913" x="17.714" y="9.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2178" stdDeviation=".1"/></filter><filter id="i5jlsSh" width=".986" height="1.04" x="13.271" y="9.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2178" stdDeviation=".1"/></filter><filter id="iqYnMhb" width=".913" height=".705" x="12.516" y="9.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2178" stdDeviation=".05"/></filter><filter id="iZtBXkB" width="1.329" height="2.379" x="9.345" y="9.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2178" stdDeviation=".125"/></filter><filter id="iocY7Il" width="1.947" height="2.903" x="19.931" y="9.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2178" stdDeviation=".25"/></filter><filter id="i8Uwgfc" width="2.105" height=".86" x="11.828" y="7.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2178" stdDeviation=".075"/></filter><filter id="iuarFOb" width="2.105" height=".86" x="17.107" y="7.513" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2178" stdDeviation=".075"/></filter><filter id="igAesYn" width="10.729" height="5.624" x="10.061" y="6.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.239216 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2178"/></filter><filter id="iLMAr9c" width="11.479" height="6.324" x="9.611" y="5.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.494118 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2178"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.752941 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2178" result="effect2_innerShadow_4002_2178"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:scientist-light" /></template>
<style>
.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.a124lcdye {
  d: path("M26.529 21.222v4.172h-2.704v-4.172z");
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.afeb8bsjy {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
}

.ahix7mbin {
  stop-color: var(--svg-color--bff0ff, #BFF0FF);
}

.ainf1jcmz {
  d: path("m9.608 17.112l-.13 1.733a.6.6 0 0 0 .493.636l.48.084a.15.15 0 0 1 .084.249l-.626.691a.5.5 0 0 0 .015.686L14.656 26a.2.2 0 0 0 .343-.14v-3.38a2 2 0 0 0-.176-.82l-2.605-5.803c-.93.299-1.807.723-2.61 1.256");
}

.ajg6ar9_l {
  stop-color: var(--svg-color--de9187, #DE9187);
}

.alk6evr_q {
  d: path("M20.28 4.217c.515.177.976.536 1.268 1.05a2.37 2.37 0 0 1-.106 2.527a1.56 1.56 0 0 0-.27.874v1.188a1.7 1.7 0 0 0-.668-.268l.079-1.606a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379l.031 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.144-2.446a2.34 2.34 0 0 1 1.3-1.126a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.28-.118.588-.188.912-.188c.843 0 1.58.456 1.989 1.132c.308.51.79.88 1.352 1.073");
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b_wzmzbwq {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.675px;
  fill: var(--svg-color--addaff, #ADDAFF);
  rx: 0.391px;
}

.b0maullyh {
  fill: var(--svg-color--000, #000);
  d: path("M13.753 10.624a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .06-.236");
}

.b4rjnnb6m {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.b9q8czbkr {
  cx: 12.973px;
  cy: 10.113px;
  rx: 0.39px;
  ry: 0.197px;
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bew_bibae {
  d: path("m21.37 17.112l.132 1.733a.6.6 0 0 1-.494.636l-.48.084a.15.15 0 0 0-.085.249l.626.691a.5.5 0 0 1-.014.686L16.323 26a.2.2 0 0 1-.343-.14v-3.38a2 2 0 0 1 .175-.82l2.606-5.803c.929.299 1.807.723 2.61 1.256");
}

.bgp-eqwmb {
  stop-color: var(--svg-color--ffe0c3, #FFE0C3);
  stop-opacity: 0;
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

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.bx23o8bkx {
  stop-color: var(--svg-color--b28598, #B28598);
}

.bywelvb6j {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c1dciy28n {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
  stop-opacity: 0;
}

.c2rd33bbv {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
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

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ckzhu0bvt {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
}

.cpykpvzxv {
  stop-color: var(--svg-color--a3d3ff, #A3D3FF);
}

.d3a6h5dbs {
  stop-color: var(--svg-color--ccb8e5, #CCB8E5);
}

.d5_x1jahj {
  fill: var(--svg-color--9f9ba5, #9F9BA5);
  fill-rule: evenodd;
  d: path("M9.761 9.17c.011-1.677 1.389-3.006 3.047-3.006h5.275a3.01 3.01 0 0 1 3.007 3.04v.001c-.022 1.568-1.339 2.918-2.907 2.973h-.002a3.06 3.06 0 0 1-2.63-1.342c-.045-.065-.09-.076-.112-.076s-.067.01-.112.076a3.08 3.08 0 0 1-2.549 1.352a3.02 3.02 0 0 1-3.017-3.017zm.6.002a2.42 2.42 0 0 0 2.417 2.416c.841 0 1.62-.435 2.05-1.085l.002-.003a.74.74 0 0 1 .609-.34c.243 0 .465.128.608.34l.001.001a2.46 2.46 0 0 0 2.114 1.077c1.248-.044 2.31-1.133 2.328-2.381a2.41 2.41 0 0 0-2.407-2.433h-5.275c-1.336 0-2.437 1.07-2.447 2.408");
}

.d7d_80btw {
  stop-color: var(--svg-color--0e7268, #0E7268);
}

.dgtwjnbll {
  d: path("m21.02 18.142l.115 1.533a.53.53 0 0 1-.437.563l-.424.075a.133.133 0 0 0-.076.22l.554.611a.44.44 0 0 1-.012.608l-4.188 4.254a.177.177 0 0 1-.303-.124v-2.991c0-.25.053-.497.155-.725l2.306-5.136c.822.265 1.599.64 2.31 1.111");
}

.dtqi4cbss {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
  stop-opacity: 0;
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dx1e6jb0z {
  stop-color: var(--svg-color--be9bb3, #BE9BB3);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e080jybbb {
  stop-color: var(--svg-color--ed5030, #ED5030);
  stop-opacity: 0;
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.e1oaafz6u {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
  stop-opacity: 0;
}

.e2ig5yb1x {
  stop-color: var(--svg-color--e07221, #E07221);
}

.ea_0ewlyw {
  stop-color: var(--svg-color--c79f97, #C79F97);
}

.eay1fibfp {
  stop-color: var(--svg-color--d0908c, #D0908C);
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.eol9ugodk {
  stop-color: var(--svg-color--ed5030, #ED5030);
}

.erfl5rbdl {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.159 8.024a1.85 1.85 0 0 0-.688-.411c-.304-.096-.685-.122-1.212-.057a.277.277 0 1 0 .067.55c.481-.059.776-.028.979.036c.198.062.332.163.49.3a.277.277 0 1 0 .364-.418");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f-zxjbc7n {
  stop-color: var(--svg-color--8ac5a2, #8AC5A2);
}

.fbqio7b7r {
  stop-color: var(--svg-color--a27d98, #A27D98);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.fop80r8ws {
  stop-color: var(--svg-color--c79175, #C79175);
}

.ft5dv1b6b {
  fill: none;
}

.fz7829bxy {
  d: path("m15.043 10.3l-.531 1.839c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.645-.408-.765 0");
}

.g1a66we9o {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.geaiemm2w {
  d: path("M10.381 9a1.62 1.62 0 0 0-1.392 1.594c0 .86.673 1.56 1.521 1.607a78 78 0 0 1-.129-3.2");
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gip5y3buk {
  d: path("M26.434 22.958c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.gmjg4ccxy {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.035 9.46c-.653 0-1.205.45-1.355 1.059a.273.273 0 0 0 .268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h6b9t3l5c {
  d: path("M10.34 9.661a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.heg5c9gcv {
  d: path("M23.137 25.313c0-.4.325-.732.726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.207a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.406-.658");
}

.hkh0bccgk {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
}

.hkq9astav {
  stop-color: var(--svg-color--d6cbe2, #D6CBE2);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.ht7we4nuf {
  d: path("M15.426 13.756c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.584.846c.664 0 1.248-.339 1.583-.846c.086-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.hy6proxed {
  stop-color: var(--svg-color--e1d2f9, #E1D2F9);
}

.i-_q9txbo {
  d: path("M20.287 12.11c.335-.011.65-.125.905-.31v.932c0 .893-.533 1.689-1.341 2.019q.256-.546.346-1.18z");
}

.i4kgizoks {
  stop-color: var(--svg-color--d1bee7, #D1BEE7);
  stop-opacity: 0;
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.iezv8nbum {
  stop-color: var(--svg-color--fcefff, #FCEFFF);
}

.ifg4wbcuq {
  stop-color: var(--svg-color--e2d2ee, #E2D2EE);
  stop-opacity: 0;
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.irjqokbks {
  stop-color: var(--svg-color--d7ccea, #D7CCEA);
  stop-opacity: 0;
}

.isxfb77db {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.544 9.92c.064.085-.07.19-.22.302c-.151.113-.264.193-.327.107c-.064-.085.007-.245.159-.358c.15-.113.325-.136.388-.05");
}

.ix8mu0bhv {
  d: path("M17.544 9.92c.064.085-.07.19-.22.302c-.151.113-.264.193-.327.107c-.064-.085.007-.245.159-.358c.15-.113.325-.136.388-.05");
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.j68h5l-_g {
  d: path("M23.825 23.816v-.469h.805a.234.234 0 1 1 0 .469z");
}

.j9vp7gz0m {
  d: path("M23.825 22.035v-.47h.805a.234.234 0 0 1 0 .47z");
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jqs3afbfy {
  stop-color: var(--svg-color--ece2e9, #ECE2E9);
  stop-opacity: 0;
}

.jr9hdpl0f {
  d: path("M18.405 10.507a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.jr9zsmblm {
  stop-color: var(--svg-color--a4c098, #A4C098);
}

.jzblanbdg {
  d: path("M20.431 11.556q.059-.95.111-1.903a.956.956 0 0 1-.11 1.903");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kn3fsib5n {
  d: path("M17.61 9.732a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l69inwbok {
  d: path("M15.426 18.617a2.11 2.11 0 0 1-2.11-2.11v-1.39h4.22v1.39c0 1.17-.95 2.11-2.11 2.11");
}

.l7b4ixb5j {
  stop-color: var(--svg-color--b2d5c0, #B2D5C0);
  stop-opacity: 0.63;
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lceri-vrq {
  d: path("M22.753 29.988v-11.79c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj5m7ucmi {
  stop-color: var(--svg-color--bea0dc, #BEA0DC);
}

.lkjzf4omc {
  stop-color: var(--svg-color--c5b2dd, #C5B2DD);
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lzxh7zbhd {
  d: path("M11.114 16.28a10.5 10.5 0 0 0-2.878 1.918v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h10.453v-6.52z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
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

.n93nbib0k {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M18.987 8.149c-.257-.185-.898-.509-1.655-.382");
}

.nba0bkbns {
  d: path("M20.348 12.2q.1-1.595.184-3.191a1.61 1.61 0 0 1-.184 3.191");
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o2winac2b {
  d: path("M13.242 9.732a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.ocku6nzyd {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.ox0t0tbyw {
  d: path("M15.466 15.348c-2.75 0-5.32 1.06-7.23 2.85v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h21.79l.01-2.03c.01-1.76-.25-3.51-.77-5.18c-.57-1.81-1.59-3.38-2.91-4.61a10.62 10.62 0 0 0-7.2-2.82");
}

.p2mir8bpk {
  stop-color: var(--svg-color--d2b4ed, #D2B4ED);
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

.pdbgs6drv {
  cx: 12.973px;
  cy: 10.113px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.pevf4cfll {
  d: path("m20.639 8.51l-.03-.63c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.256-.97.67-1.712 1.655-1.521c.974.189 2.083.517 2.903 1.051c1.744 1.138 1.439 3.189.52 4.155");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.q01--1lrv {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.015 7.915a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.386.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.q4mowll4q {
  stop-color: var(--svg-color--e2d2f8, #E2D2F8);
  stop-opacity: 0;
}

.q7l79-2rh {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.ql-d_bcrc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 25.99h1.797");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxnrq812s {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.024 10.491l-.59 1.839c-.101.378.14.756.484.756h.732c.343 0 .585-.384.484-.756l-.495-1.839c-.105-.407-.504-.407-.615 0");
}

.r-0tl8b_g {
  stop-color: var(--svg-color--bfa7d3, #BFA7D3);
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r1tra0r1f {
  stop-color: var(--svg-color--a4c098, #A4C098);
  stop-opacity: 0;
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.rced3uh7f {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
  stop-opacity: 0;
}

.rsfdnufmx {
  stop-color: var(--svg-color--b64118, #B64118);
}

.rvpscutoq {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.075 13.361a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27c.349.528.955.88 1.646.88a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.044h-.002c-.39.203-.85.32-1.35.32c-.496 0-.961-.117-1.351-.32Z");
}

.ry-6rkb7q {
  stop-color: var(--svg-color--e6d7e3, #E6D7E3);
}

.s44sum5km {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
  stop-opacity: 0;
}

.sb62shdsk {
  d: path("M14.057 10.52c0-.29-.235-.481-.298-.54l-.288.28l.177.36z");
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

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.sqxhjlnxl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.676 27.294h1.797");
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.t-t2odb0m {
  stop-color: var(--svg-color--b4756b, #B4756B);
}

.t0qf5rbqk {
  stop-color: var(--svg-color--e6d2de, #E6D2DE);
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.tj2vllbvr {
  stop-color: var(--svg-color--f3c6af, #F3C6AF);
}

.tkgx_8bnk {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.675px;
  rx: 0.391px;
}

.tsloro5fn {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
}

.txsyviqti {
  stop-color: var(--svg-color--aa9fa6, #AA9FA6);
  stop-opacity: 0;
}

.ubsir5m6c {
  stop-color: var(--svg-color--ccff86, #CCFF86);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v0fk_zbwr {
  stop-color: var(--svg-color--83b651, #83B651);
}

.v4-zmrbyl {
  stop-color: var(--svg-color--b0a6b5, #B0A6B5);
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v6ge5bcpf {
  stop-color: var(--svg-color--faf8fe, #FAF8FE);
}

.v8w-mebcs {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m20.639 8.51l-.03-.63c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.135-.12-.368c-.256-.97.67-1.712 1.655-1.521c.974.189 2.083.517 2.903 1.051c1.744 1.138 1.439 3.189.52 4.155");
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vgq7babse {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.053 8.195c.256-.185.897-.51 1.655-.382");
}

.vmc-iabjh {
  d: path("m9.474 17.72l-.131 1.733a.6.6 0 0 0 .494.636l.479.085a.15.15 0 0 1 .085.248l-.626.691a.5.5 0 0 0 .014.687l4.733 4.808a.2.2 0 0 0 .342-.14v-3.38a2 2 0 0 0-.175-.82l-2.606-5.804a10.6 10.6 0 0 0-2.61 1.256");
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vwrtm3bab {
  d: path("M10.564 12.11a1.64 1.64 0 0 1-.904-.31v.932c0 .893.532 1.689 1.34 2.019a4.1 4.1 0 0 1-.345-1.18z");
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.vxd8ts5kx {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
}

.vzhel1b-t {
  d: path("M19.865 16.28a10.5 10.5 0 0 1 2.878 1.918v.014l.01-.014c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07H15.98v-6.52z");
}

.w01lnqx9a {
  stop-color: var(--svg-color--bfa6da, #BFA6DA);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.w3-o4ac4j {
  stop-color: var(--svg-color--cd8472, #CD8472);
  stop-opacity: 0;
}

.w7du6pb_e {
  d: path("M10.6 13.625a3.916 3.916 0 0 0 3.887 3.405h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.236-3.76.324-5.642a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.21-1.443a.66.66 0 0 0-.616-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379c0 1.86.116 3.691.238 5.557");
}

.wki8rib4u {
  stop-color: var(--svg-color--daa2a2, #DAA2A2);
  stop-opacity: 0;
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wpy995b9j {
  d: path("M23.825 19.456h2.703v5.938h-2.703z");
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x3hlfcbwc {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
}

.x3pdtmzbl {
  stop-color: var(--svg-color--29615d, #29615D);
}

.x7jui5iih {
  stop-color: var(--svg-color--c37d97, #C37D97);
}

.xo2zgxulc {
  d: path("M18.083 6.464h-5.275c-1.497 0-2.737 1.2-2.747 2.707a2.72 2.72 0 0 0 2.717 2.717c.942 0 1.814-.486 2.3-1.22c.189-.277.533-.277.721 0a2.76 2.76 0 0 0 2.373 1.21c1.408-.05 2.598-1.27 2.618-2.677a2.71 2.71 0 0 0-2.707-2.737");
}

.xoi7hsb-w {
  stop-color: var(--svg-color--ddcef1, #DDCEF1);
}

.xpzhm0iru {
  stop-color: var(--svg-color--cec5ca, #CEC5CA);
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.xx10debny {
  stop-color: var(--svg-color--c0a9d9, #C0A9D9);
  stop-opacity: 0;
}

.xynzhkbxy {
  fill: var(--svg-color--f6bfab, #F6BFAB);
  d: path("m15.043 10.3l-.531 1.839c-.109.378.152.756.52.756h.787c.369 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.645-.408-.765 0");
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.yae6yabyn {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.817 9.46c.653 0 1.204.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.ybkft5ymj {
  d: path("m15.658 5.244l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.805-.767-1.688c0-1.072.781-1.614 1.28-1.96c.14-.097.26-.179.33-.252l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.892V5.23z");
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z_a2ribdx {
  stop-color: var(--svg-color--e7d3df, #E7D3DF);
  stop-opacity: 0;
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z473rkg5k {
  stop-color: var(--svg-color--b2d5c0, #B2D5C0);
}

.z4n2hhy8u {
  opacity: var(--svg-opacity--0-6, 0.6);
}

.z4xhuybyb {
  stop-color: var(--svg-color--c8c2cc, #C8C2CC);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.z78o0obou {
  stop-color: var(--svg-color--c6a5e0, #C6A5E0);
}

.z8ub0xbwd {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m15.658 5.244l-.066-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.767-.805-.767-1.688c0-1.072.781-1.614 1.28-1.96c.14-.097.26-.179.33-.252l.1-.105c.35-.37.973-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.892V5.23z");
}

.z96dqpbaj {
  stop-color: var(--svg-color--de9187, #DE9187);
  stop-opacity: 0;
}

.zcdcyccef {
  stop-color: var(--svg-color--e1aca6, #E1ACA6);
  stop-opacity: 0;
}

.zgetey7cf {
  fill: var(--svg-color--000, #000);
  d: path("M17.099 10.624a.51.51 0 0 1 .51-.511a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.235");
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zpmhxsbxd {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
  stop-opacity: 0;
}

.zvwlq8j8i {
  stop-color: var(--svg-color--d38496, #D38496);
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

</style>
