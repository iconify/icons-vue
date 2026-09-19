<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ikFz25a)" class="hpbf-mbbs"/><path fill="url(#i8g7lKd)" class="emat5kllu"/><path fill="url(#izTIbHb)" class="vkmoa2bgc"/><path fill="url(#ixMXFpE)" class="s599otu9k"/><g filter="url(#ix1mPib)"><path fill="url(#iJdLbAd)" class="rdfu8xqvl"/><path fill="url(#iSSBnob)" class="rdfu8xqvl"/></g><path fill="url(#iDFkokc)" class="rdfu8xqvl"/><path fill="url(#i0EvNPe)" class="rdfu8xqvl"/><path fill="url(#iF8ug4c)" class="rdfu8xqvl"/><path fill="url(#inQYf9c)" class="rdfu8xqvl"/><path fill="url(#iObPlxc)" class="rdfu8xqvl"/><path fill="url(#iZaloSe)" class="rdfu8xqvl"/><path fill="url(#iaHZaIc)" class="rdfu8xqvl"/><g filter="url(#ivsWz4b)"><path class="rqbec9bxg"/></g><g filter="url(#ivfkXPj)"><path class="qm9mii7bp"/><path fill="url(#iC4i2Ic)" class="ms0h6vbdl"/><path fill="url(#i7QU3Yu)" class="ms0h6vbdl"/><path fill="url(#iFlfBzd)" class="ms0h6vbdl"/><path fill="url(#i4TU3Px)" class="ms0h6vbdl"/><path fill="url(#ifubKhZ)" class="ms0h6vbdl"/></g><g filter="url(#i6wIOzc)"><path fill="url(#iXwrxDb)" class="qhztoebdo"/></g><g filter="url(#iHVU0fc)"><path stroke="url(#iZS9pEn)" class="xaev7oldu"/></g><path fill="url(#igKCe0d)" class="a-nb7zbxy"/><g filter="url(#ihEx5cd)"><path fill="url(#iuDx4ie)" class="gk1ryqb5w"/><path fill="url(#ibHB1ac)" class="gk1ryqb5w"/><path fill="url(#ikQwDtc)" class="gk1ryqb5w"/><path fill="url(#iLgyKwc)" class="gk1ryqb5w"/><path fill="url(#i3Yh5ge)" class="gk1ryqb5w"/></g><g filter="url(#iSeRcRc)"><path class="jcvyznbme"/></g><g filter="url(#iamu7hb)"><path class="zonay4blc"/></g><g filter="url(#i5dAFOt)"><path class="bp_0a2x2s"/><path fill="url(#i4DCVrc)" class="yibo1bbtp"/><path fill="url(#ia52Ced)" class="yibo1bbtp"/></g><g filter="url(#i7g03GF)"><path class="z3onfuh1i"/><path fill="url(#itqUatd)" class="ybv5jrznt"/><path fill="url(#iWFsB1c)" class="ybv5jrznt"/></g><path fill="url(#ifKYnye)" class="tx1f5kbzi"/><path fill="url(#iqdjCNr)" class="tx1f5kbzi"/><path fill="url(#iYzT0Vc)" class="tx1f5kbzi"/><path fill="url(#iCFuKAd)" class="tx1f5kbzi"/><path fill="url(#iC0wSuc)" class="el1w3ub2m"/><path fill="url(#iwZlx1c)" class="el1w3ub2m"/><g filter="url(#iTBwP3b)"><path fill="url(#i3g0jLd)" class="nmgehrbde"/></g><g filter="url(#iABgOEe)"><path fill="url(#iqMJacc)" class="dgjbigo9b"/></g><g filter="url(#ie5SaCe)"><path class="p1_arrbav"/></g><g filter="url(#iiu6Xxc)"><path class="kpahiqbxi"/></g><g filter="url(#i5JBM3d)"><path class="z8kn0tyhs"/></g><path fill="url(#iDliJ8b)" class="eis_d-rpv"/><path fill="url(#i1wXmKc)" class="m7g5qjj9l"/><path fill="url(#iaEbiZd)" class="m7g5qjj9l"/><path fill="url(#isgrVne)" class="m7g5qjj9l"/><path fill="url(#ieV1ihd)" class="m7g5qjj9l"/><path fill="url(#iRBrfjj)" class="m7g5qjj9l"/><path fill="url(#iVAuCEc)" class="m7g5qjj9l"/><g filter="url(#ivRq4Ke)"><path fill="url(#iWiEjme)" class="zkllbdcmm"/><path fill="url(#iwUEBWc)" class="zkllbdcmm"/><path fill="url(#i60CXuz)" class="zkllbdcmm"/></g><path fill="url(#ihn1Tbv)" class="urcycevie"/><path fill="url(#iQN5bXb)" class="urcycevie"/><g filter="url(#iymJHQc)"><path fill="url(#i5V9vPN)" class="m00m2sd0g"/><path fill="url(#ieOuQke)" class="m00m2sd0g"/></g><g filter="url(#i6Zz3tc)"><path class="g3aduzb1s"/><path fill="url(#iqGiSIb)" class="vxuagmllm"/><path fill="url(#iU3P2mb)" class="vxuagmllm"/><path fill="url(#isJDIRc)" class="vxuagmllm"/></g><path fill="url(#i7aVVcd)" class="zvp8msbqz"/><path fill="url(#iKop9nJ)" class="zvp8msbqz"/><path fill="url(#iJtTmab)" class="zmi4w8bcg"/><path fill="url(#iyOgKml)" class="zmi4w8bcg"/><path fill="url(#iYmdcct)" class="poexxt13f"/><path fill="url(#ivPLlGe)" class="poexxt13f"/><path fill="url(#iwgUBXU)" class="poexxt13f"/><path fill="url(#iXViCjd)" class="poexxt13f"/><path fill="url(#iFiU0ad)" class="qp1u6qbwv"/><path fill="url(#iknftsc)" class="dgdf5hjmy"/><path fill="url(#imvh43d)" class="z6eb4kblv"/><path fill="url(#i7cUsud)" class="z6eb4kblv"/><path fill="url(#iur0u4d)" class="z6eb4kblv"/><g filter="url(#ij4Fsdc)"><path stroke="url(#iM2G8EG)" class="cj1sl_bqb"/></g><path fill="url(#iueugbc)" class="lkdb1y-jt"/><path fill="url(#iDi1K4C)" class="lkdb1y-jt"/><path fill="url(#i1nGRvc)" class="q_48wdbvi"/><g filter="url(#iXmjNac)"><path fill="url(#ic1buzb)" class="jlg325b9p"/><path fill="url(#ibCEz9E)" class="jlg325b9p"/><path fill="url(#iSq290c)" class="jlg325b9p"/></g><path fill="url(#iyeEiae)" class="hkd847oax"/><path fill="url(#in8ZqWb)" class="hkd847oax"/><path fill="url(#iXSsP1d)" class="hkd847oax"/><path fill="url(#i7YPRxb)" class="hkd847oax"/><path fill="url(#iftB2Ab)" class="hkd847oax"/><path class="nfxh0wuuc"/><path fill="url(#iKthkEe)" class="hl0xq4brp"/><path fill="url(#iyv4KOe)" class="hl0xq4brp"/><path class="w6b4lnbbx"/><path fill="url(#iuLEUDc)" class="liitwlntz"/><path fill="url(#iwOBHMb)" class="liitwlntz"/><path fill="url(#igOp4Nc)" class="dl3hh1b2p"/><path fill="url(#ieAn44b)" class="dl3hh1b2p"/><path fill="url(#iV827Qd)" class="dl3hh1b2p"/><path fill="url(#iZufP5d)" class="dl3hh1b2p"/><path fill="url(#iBmKzse)" class="bu_bl572i"/><path fill="url(#iC1wXhQ)" class="bu_bl572i"/><path fill="url(#ixtiqYU)" class="bu_bl572i"/><path fill="url(#iJtq1wc)" class="hzjcm7beg"/><path fill="url(#icYxDUb)" class="hzjcm7beg"/><path fill="url(#iD3rOWb)" class="hzjcm7beg"/><path fill="url(#iuItPlc)" class="hzjcm7beg"/><g filter="url(#ikWlr1V)"><path stroke="url(#i18aVqb)" class="npcbhubbk"/></g><g filter="url(#iEyW7DG)" class="mc2zb0bvp"><path class="yu0d-vcbn"/></g><g filter="url(#iekZlHc)" class="mc2zb0bvp"><path class="esennwbzv"/></g><g filter="url(#iMHktte)"><circle fill="url(#ixLrf1d)" class="lt00fqber"/></g><g filter="url(#ipW6oge)"><circle fill="url(#iuD4z5j)" class="qfqp0mb_l"/></g><path fill="url(#ilD1yYa)" class="ysy2yub5t"/><path fill="url(#i5b0SJC)" class="w6tfixy4t"/><g filter="url(#i61vjad)" class="i5de26xkm"><path stroke="url(#iJbOMoe)" class="iixz2pbja"/><path stroke="url(#ivN48Dd)" class="iixz2pbja"/></g><g filter="url(#ixWqTcb)" class="i5de26xkm"><path stroke="url(#iOQ9vbd)" class="tnq1kg2hb"/><path stroke="url(#iEOdJuB)" class="tnq1kg2hb"/></g><defs><radialGradient id="izTIbHb" cx="0" cy="0" r="1" gradientTransform="matrix(1.0935 1.90366 -2.2614 1.299 19.87 11.127)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="ixMXFpE" cx="0" cy="0" r="1" gradientTransform="rotate(7.917 -92.595 72.375)scale(1.57748 4.86662)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iJdLbAd" cx="0" cy="0" r="1" gradientTransform="rotate(170.47 8.44 5.994)scale(5.32855 9.42616)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="iSSBnob" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26571 3.1921 -2.63533 -1.04495 16.532 5.568)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="i0EvNPe" cx="0" cy="0" r="1" gradientTransform="matrix(2.63314 -3.38082 4.61549 3.59475 13.848 18.472)" gradientUnits="userSpaceOnUse"><stop class="opc5nbd0u"/><stop offset="1" class="d1h879bbi"/></radialGradient><radialGradient id="iF8ug4c" cx="0" cy="0" r="1" gradientTransform="matrix(-8.4496 1.97297 -5.03995 -21.5845 18.55 11.396)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="inQYf9c" cx="0" cy="0" r="1" gradientTransform="matrix(2.91118 -3.503 1.03473 .85992 7.644 9.381)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="iObPlxc" cx="0" cy="0" r="1" gradientTransform="matrix(.1856 2.55 -1.01934 .07419 20.013 7.114)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iZaloSe" cx="0" cy="0" r="1" gradientTransform="rotate(126.843 6.873 7.142)scale(2.88405 2.55211)" gradientUnits="userSpaceOnUse"><stop class="op-vxebsg"/><stop offset="1" class="ceh8ilb4x"/></radialGradient><radialGradient id="iaHZaIc" cx="0" cy="0" r="1" gradientTransform="matrix(-.18792 -1.61611 8.72698 -1.01476 15.917 17.68)" gradientUnits="userSpaceOnUse"><stop class="p108vxifj"/><stop offset="1" class="bqa94ibrz"/></radialGradient><radialGradient id="i7QU3Yu" cx="0" cy="0" r="1" gradientTransform="rotate(80.47 .564 15.373)scale(.24881 .78194)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="i4TU3Px" cx="0" cy="0" r="1" gradientTransform="rotate(145.838 6.031 8.244)scale(1.70564 2.7411)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="igKCe0d" cx="0" cy="0" r="1" gradientTransform="matrix(2.01227 -1.44655 5.81983 8.09587 15.05 14.707)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ibHB1ac" cx="0" cy="0" r="1" gradientTransform="rotate(-99.53 8.383 .592)scale(3.56877 9.025)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="ikQwDtc" cx="0" cy="0" r="1" gradientTransform="rotate(-96.932 13.572 -4.373)scale(2.56358 4.54215)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iLgyKwc" cx="0" cy="0" r="1" gradientTransform="rotate(-156.197 9.119 -.674)scale(2.87767 2.11236)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="i3Yh5ge" cx="0" cy="0" r="1" gradientTransform="matrix(.87738 1.09109 -2.52645 2.0316 12.428 1.635)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="i4DCVrc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.21257 .37145 -.13786 -.82117 13.973 3.71)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="ia52Ced" cx="0" cy="0" r="1" gradientTransform="matrix(2.37498 -5.66501 6.27625 2.63123 8.925 8.633)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="itqUatd" cx="0" cy="0" r="1" gradientTransform="matrix(2.2619 -3.0175 5.5243 4.14098 17.01 7.142)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iWFsB1c" cx="0" cy="0" r="1" gradientTransform="matrix(3.32916 -.16654 .06973 1.39386 15.87 5.808)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iqdjCNr" cx="0" cy="0" r="1" gradientTransform="rotate(64.817 2.39 19.945)scale(2.37454 2.2655)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iYzT0Vc" cx="0" cy="0" r="1" gradientTransform="matrix(.60943 -1.21967 1.02232 .51082 19.876 9.783)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="iCFuKAd" cx="0" cy="0" r="1" gradientTransform="matrix(.3284 -1.65754 2.2147 .43878 20.02 9.937)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="iwZlx1c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66687 .27984 -.31248 -1.8613 9.947 11.55)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="i3g0jLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.89469 .3128 -.32072 -.91734 9.949 11.552)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="isgrVne" cx="0" cy="0" r="1" gradientTransform="matrix(.21875 3.1875 -3.62585 .24883 8.716 20.6)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="bzi-27bxc"/><stop offset="1" class="brh-pzb_h"/></radialGradient><radialGradient id="ieV1ihd" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 3.4375 -2.71722 -.59285 6.466 19.32)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="lwl1xgbup"/><stop offset="1" class="kar3bi73q"/></radialGradient><radialGradient id="iRBrfjj" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15508 -.34883 1.8893 -6.25609 8.674 29.975)" gradientUnits="userSpaceOnUse"><stop class="ijdg6fbam"/><stop offset="1" class="sjvismp2t"/></radialGradient><radialGradient id="iWiEjme" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0785 6 -4.46735 -1.54757 17.014 24.757)" gradientUnits="userSpaceOnUse"><stop class="v2wkn2ras"/><stop offset="1" class="yxmxw0ard"/></radialGradient><radialGradient id="iwUEBWc" cx="0" cy="0" r="1" gradientTransform="rotate(-132.901 14.894 10.116)scale(4.22338 6.72611)" gradientUnits="userSpaceOnUse"><stop class="bji58ac7a"/><stop offset="1" class="eqapwmsga"/></radialGradient><radialGradient id="i60CXuz" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62501 -3.8277 2.0945 -1.4364 21.185 25.694)" gradientUnits="userSpaceOnUse"><stop offset=".393" class="c8r1g2bnk"/><stop offset="1" class="kyl8adb5j"/></radialGradient><radialGradient id="ihn1Tbv" cx="0" cy="0" r="1" gradientTransform="matrix(-5.34372 2.81254 -2.95164 -5.608 26.404 21.038)" gradientUnits="userSpaceOnUse"><stop class="z3zsa5bpu"/><stop offset="1" class="c_p6lvbtv"/></radialGradient><radialGradient id="i5V9vPN" cx="0" cy="0" r="1" gradientTransform="rotate(164.954 9.098 12.715)scale(3.00943 4.47011)" gradientUnits="userSpaceOnUse"><stop class="dyh_p3bsl"/><stop offset="1" class="acgtzjb8q"/></radialGradient><radialGradient id="ieOuQke" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66156 -1.3125 1.73451 -2.1958 22.878 25.475)" gradientUnits="userSpaceOnUse"><stop class="fo4qq4q_b"/><stop offset="1" class="a6ayzxb8w"/></radialGradient><radialGradient id="iqGiSIb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -5.73004 19.341 28.913)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="jxwdq3van"/><stop offset="1" class="ytapvgb1c"/></radialGradient><radialGradient id="iU3P2mb" cx="0" cy="0" r="1" gradientTransform="rotate(33.14 -37.736 40.548)scale(2.25791 .79383)" gradientUnits="userSpaceOnUse"><stop class="uuwie8bnd"/><stop offset="1" class="nkti4m6tj"/></radialGradient><radialGradient id="isJDIRc" cx="0" cy="0" r="1" gradientTransform="matrix(6.57813 0 0 1.16319 13 29.976)" gradientUnits="userSpaceOnUse"><stop class="nz1ipmv-m"/><stop offset="1" class="uw-cne-zt"/></radialGradient><radialGradient id="iyOgKml" cx="0" cy="0" r="1" gradientTransform="rotate(168.154 12.872 14.747)scale(6.54566 1.70736)" gradientUnits="userSpaceOnUse"><stop class="kcxizyr3a"/><stop offset="1" class="uz8nvn0bw"/></radialGradient><radialGradient id="iYmdcct" cx="0" cy="0" r="1" gradientTransform="matrix(.84205 2.73 -2.93117 .9041 6.842 19.85)" gradientUnits="userSpaceOnUse"><stop class="phzm4snim"/><stop offset="1" class="czerk-92m"/></radialGradient><radialGradient id="ivPLlGe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .87171 -.46263 -.67998 9.982 20.823)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="wyqcze2zy"/><stop offset="1" class="r6dyzpbfo"/></radialGradient><radialGradient id="iwgUBXU" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 .75 -.43392 .18532 7.24 20.46)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="r1y6vkpka"/><stop offset="1" class="xrzwqzb7j"/></radialGradient><radialGradient id="iXViCjd" cx="0" cy="0" r="1" gradientTransform="rotate(153.654 1.915 11.247)scale(2.61542 2.57494)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="tz2l_he6k"/><stop offset="1" class="twkrvc03o"/></radialGradient><radialGradient id="iur0u4d" cx="0" cy="0" r="1" gradientTransform="matrix(-.3711 1.25391 -.1532 -.04534 16.086 18.451)" gradientUnits="userSpaceOnUse"><stop class="tomvu1bgl"/><stop offset="1" class="sinn-3bvk"/></radialGradient><radialGradient id="iM2G8EG" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.60156 1.71998 -.58078 9.388 22.992)" gradientUnits="userSpaceOnUse"><stop class="gmelrdffb"/><stop offset="1" class="khl528bkl"/></radialGradient><radialGradient id="iDi1K4C" cx="0" cy="0" r="1" gradientTransform="matrix(-.64063 2 -.16496 -.05284 15.898 17.79)" gradientUnits="userSpaceOnUse"><stop class="njdbcpw8w"/><stop offset="1" class="p6n8nbb9p"/></radialGradient><radialGradient id="ibCEz9E" cx="0" cy="0" r="1" gradientTransform="rotate(25.805 -34.568 34.409)scale(1.57936 1.44294)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l8v5z5bog"/><stop offset="1" class="ll6ec2bpd"/></radialGradient><radialGradient id="in8ZqWb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0156 3.18752 -2.63101 -1.6637 9.531 18.438)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="d-33bzb2o"/><stop offset=".996" class="g2g0htigy"/></radialGradient><radialGradient id="iXSsP1d" cx="0" cy="0" r="1" gradientTransform="rotate(119.595 -.004 11.738)scale(3.70167 1.33422)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="ha1dqccsi"/><stop offset="1" class="ziy-jybcv"/></radialGradient><radialGradient id="i7YPRxb" cx="0" cy="0" r="1" gradientTransform="matrix(-.1359 3.04807 -.73147 -.03261 7.35 18.093)" gradientUnits="userSpaceOnUse"><stop class="eim87q2nu"/><stop offset="1" class="ndf7m0b2h"/></radialGradient><radialGradient id="iftB2Ab" cx="0" cy="0" r="1" gradientTransform="matrix(.25 1.01562 -.9916 .24409 8.992 20.648)" gradientUnits="userSpaceOnUse"><stop offset=".412" class="v0y0h5pun"/><stop offset="1" class="sx4xd35ql"/></radialGradient><radialGradient id="iKthkEe" cx="0" cy="0" r="1" gradientTransform="matrix(-.97119 .31036 -.1504 -.47062 14.375 16.427)" gradientUnits="userSpaceOnUse"><stop class="y6_vjs3df"/><stop offset="1" class="ui58-1_-x"/></radialGradient><radialGradient id="iyv4KOe" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 -.93275 3.89243 .13041 12.797 17.5)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="w8ej_fbdv"/><stop offset="1" class="ycyum3z7k"/></radialGradient><radialGradient id="iuLEUDc" cx="0" cy="0" r="1" gradientTransform="rotate(-80.715 17.239 2.227)scale(.83681 3.75171)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="qxxa4bmmv"/><stop offset="1" class="j25x9tegw"/></radialGradient><radialGradient id="iwOBHMb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 .41406 -.20022 -.51377 13.89 17.497)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="a3emfp-7e"/><stop offset="1" class="tmyz66fau"/></radialGradient><radialGradient id="igOp4Nc" cx="0" cy="0" r="1" gradientTransform="matrix(-.60938 .84374 -2.96419 -2.14083 11.45 18.866)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="tnkwcrb_w"/><stop offset="1" class="fmfd79b2c"/></radialGradient><radialGradient id="ieAn44b" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 1.28906 -.23264 .31583 11.656 19.211)" gradientUnits="userSpaceOnUse"><stop class="ti3jmkb7y"/><stop offset="1" class="mnw_fc_zm"/></radialGradient><radialGradient id="iV827Qd" cx="0" cy="0" r="1" gradientTransform="matrix(-.3672 .53142 -1.08325 -.74848 12.138 18.773)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="t5sd16bfc"/><stop offset="1" class="v3_lnpb5q"/></radialGradient><radialGradient id="iZufP5d" cx="0" cy="0" r="1" gradientTransform="matrix(1.26608 -.19478 .4132 2.68585 8.78 18.474)" gradientUnits="userSpaceOnUse"><stop class="ye-ecgz9l"/><stop offset="1" class="afcdt12xs"/></radialGradient><radialGradient id="iBmKzse" cx="0" cy="0" r="1" gradientTransform="rotate(-60.743 22.77 3.09)scale(1.93424 2.14966)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="svx6r0gzk"/><stop offset="1" class="tc83oubxb"/></radialGradient><radialGradient id="iC1wXhQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.15624 .72351 -.29288 .46806 10.844 20.126)" gradientUnits="userSpaceOnUse"><stop class="amlvwb9ik"/><stop offset="1" class="hgj37ubhx"/></radialGradient><radialGradient id="ixtiqYU" cx="0" cy="0" r="1" gradientTransform="matrix(-.42969 1.98437 -4.09811 -.8874 10.273 19.953)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="ud0xernhq"/><stop offset="1" class="diy3tbc3u"/></radialGradient><radialGradient id="icYxDUb" cx="0" cy="0" r="1" gradientTransform="rotate(105.675 1.08 15.815)scale(1.31451 .34383)" gradientUnits="userSpaceOnUse"><stop class="cn05xwrkd"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="iD3rOWb" cx="0" cy="0" r="1" gradientTransform="rotate(105.036 .962 16.291)scale(.54206 .1592)" gradientUnits="userSpaceOnUse"><stop class="em3lc9y5i"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="iuItPlc" cx="0" cy="0" r="1" gradientTransform="rotate(174.906 8.393 10.28)scale(.43997 .38553)" gradientUnits="userSpaceOnUse"><stop class="tzj34xnjq"/><stop offset="1" class="ugbytbngn"/></radialGradient><radialGradient id="i18aVqb" cx="0" cy="0" r="1" gradientTransform="matrix(-.26365 -2.21465 3.37212 -.40144 7.844 21.79)" gradientUnits="userSpaceOnUse"><stop class="zmq4c2bxg"/><stop offset="1" class="trma59b_r"/></radialGradient><radialGradient id="ixLrf1d" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 14.893 -4.805)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".053" class="zfr5v_r8t"/><stop offset=".876" class="tpw8-_30q"/></radialGradient><radialGradient id="iuD4z5j" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 16.589 -8.94)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="i89aqmaix"/><stop offset=".535" class="c7hm4yb7u"/></radialGradient><radialGradient id="ilD1yYa" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .3557 2.1855 11.383 11.129)" gradientUnits="userSpaceOnUse"><stop class="fdm2y6x_j"/><stop offset="1" class="h1ie4dmkz"/></radialGradient><radialGradient id="i5b0SJC" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .35569 2.1855 16.013 10.319)" gradientUnits="userSpaceOnUse"><stop class="fdm2y6x_j"/><stop offset="1" class="h1ie4dmkz"/></radialGradient><radialGradient id="ivN48Dd" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 13.555 10.764)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="g7xtertqj"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="eovkc4nhj"/></radialGradient><radialGradient id="iEOdJuB" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 18.185 9.956)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="g7xtertqj"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="eovkc4nhj"/></radialGradient><linearGradient id="ikFz25a" x1="19.3" x2="12.412" y1="18.58" y2="30.257" gradientUnits="userSpaceOnUse"><stop class="iezg62obf"/><stop offset="1" class="w444cbj2i"/></linearGradient><linearGradient id="i8g7lKd" x1="15.761" x2="17.294" y1="17.21" y2="18.194" gradientUnits="userSpaceOnUse"><stop offset=".177" class="m8j63xbdo"/><stop offset="1" class="piesmtbrq"/></linearGradient><linearGradient id="iDFkokc" x1="20.401" x2="17.858" y1="11.806" y2="12.233" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="iC4i2Ic" x1="15.889" x2="15.052" y1="11.519" y2="11.696" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iFlfBzd" x1="15.238" x2="15.16" y1="12.806" y2="12.338" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="ifubKhZ" x1="14.782" x2="14.874" y1="10.086" y2="10.636" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="iXwrxDb" x1="14.716" x2="14.961" y1="9.872" y2="11.138" gradientUnits="userSpaceOnUse"><stop class="i5etcbh5r"/><stop offset="1" class="kyqssj_6u"/></linearGradient><linearGradient id="iZS9pEn" x1="14.296" x2="14.475" y1="14.588" y2="13.695" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iuDx4ie" x1="20.864" x2="9.192" y1="4.134" y2="6.094" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="ifKYnye" x1="21.261" x2="20.415" y1="9.056" y2="11.447" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iC0wSuc" x1="9.03" x2="10.474" y1="11.837" y2="11.463" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iqMJacc" x1="20.171" x2="20.492" y1="8.844" y2="10.758" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="iDliJ8b" x1="23.345" x2="27.191" y1="24.317" y2="28.893" gradientUnits="userSpaceOnUse"><stop class="d0ocakaur"/><stop offset="1" class="u_vqqhk3b"/></linearGradient><linearGradient id="i1wXmKc" x1="9.185" x2="3.716" y1="26.288" y2="24.819" gradientUnits="userSpaceOnUse"><stop class="hbzm4jmfo"/><stop offset="1" class="hzk1ijbie"/></linearGradient><linearGradient id="iaEbiZd" x1="3.591" x2="5.404" y1="25.913" y2="26.569" gradientUnits="userSpaceOnUse"><stop class="dm21qhbor"/><stop offset="1" class="xvwmp6tlw"/></linearGradient><linearGradient id="iVAuCEc" x1="9.306" x2="8.913" y1="28.306" y2="28.181" gradientUnits="userSpaceOnUse"><stop class="icorotc4i"/><stop offset="1" class="deg8fdc9j"/></linearGradient><linearGradient id="iQN5bXb" x1="24.685" x2="24.373" y1="25.319" y2="23.85" gradientUnits="userSpaceOnUse"><stop class="dy155dxdg"/><stop offset="1" class="dypnkmnss"/></linearGradient><linearGradient id="i7aVVcd" x1="19.471" x2="19.471" y1="26.608" y2="29.976" gradientUnits="userSpaceOnUse"><stop class="di46q3nvv"/><stop offset="1" class="bhzzakkbd"/></linearGradient><linearGradient id="iKop9nJ" x1="19.599" x2="19.513" y1="26.538" y2="27.046" gradientUnits="userSpaceOnUse"><stop class="m9orc9b3r"/><stop offset="1" class="zegip2beb"/></linearGradient><linearGradient id="iJtTmab" x1="26.623" x2="27.06" y1="26.757" y2="30.476" gradientUnits="userSpaceOnUse"><stop class="xyrntivgr"/><stop offset="1" class="cjhyb2bbj"/></linearGradient><linearGradient id="iFiU0ad" x1="11.22" x2="11.074" y1="22.048" y2="19.404" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="iknftsc" x1="12.427" x2="12.04" y1="20.238" y2="18.257" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="imvh43d" x1="16.154" x2="15.373" y1="18.038" y2="21.025" gradientUnits="userSpaceOnUse"><stop class="e6bcurcdv"/><stop offset="1" class="jxwnoqbqn"/></linearGradient><linearGradient id="i7cUsud" x1="15.281" x2="15.504" y1="21.244" y2="20.354" gradientUnits="userSpaceOnUse"><stop class="w_57dfb5m"/><stop offset="1" class="t78i98bfv"/></linearGradient><linearGradient id="iueugbc" x1="15.029" x2="13.904" y1="17.272" y2="21.6" gradientUnits="userSpaceOnUse"><stop class="nn3wh7bnm"/><stop offset="1" class="tbs366q3s"/></linearGradient><linearGradient id="i1nGRvc" x1="15.341" x2="14.232" y1="17.648" y2="17.288" gradientUnits="userSpaceOnUse"><stop class="h94nvm15h"/><stop offset="1" class="qtvy6rbzh"/></linearGradient><linearGradient id="ic1buzb" x1="14.529" x2="13.299" y1="17.163" y2="21.913" gradientUnits="userSpaceOnUse"><stop class="qic_n_blg"/><stop offset="1" class="qh-ows9fr"/></linearGradient><linearGradient id="iSq290c" x1="12.625" x2="12.844" y1="20.979" y2="19.901" gradientUnits="userSpaceOnUse"><stop class="e122-lbju"/><stop offset="1" class="grqmao4rm"/></linearGradient><linearGradient id="iyeEiae" x1="8.498" x2="9.041" y1="16.663" y2="21.163" gradientUnits="userSpaceOnUse"><stop class="uptie3ora"/><stop offset="1" class="w5xbz1t2h"/></linearGradient><linearGradient id="iJtq1wc" x1="16.597" x2="16.013" y1="18.538" y2="21.038" gradientUnits="userSpaceOnUse"><stop class="neym138jd"/><stop offset="1" class="kmp3a3cnr"/></linearGradient><linearGradient id="iJbOMoe" x1="11.477" x2="13.758" y1="11.171" y2="11.326" gradientUnits="userSpaceOnUse"><stop class="d3bth9bgz"/><stop offset="1" class="pvzvrjbje"/></linearGradient><linearGradient id="iOQ9vbd" x1="16.107" x2="18.388" y1="10.363" y2="10.519" gradientUnits="userSpaceOnUse"><stop class="d3bth9bgz"/><stop offset="1" class="pvzvrjbje"/></linearGradient><filter id="ix1mPib" width="11.937" height="12.754" x="9.323" y="4.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3535"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3535" result="effect2_innerShadow_4002_3535"/></filter><filter id="ivsWz4b" width="3.774" height="4.995" x="13.154" y="9.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3535" stdDeviation=".5"/></filter><filter id="ivfkXPj" width="2.304" height="3.395" x="13.999" y="9.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3535" stdDeviation=".1"/></filter><filter id="i6wIOzc" width="2.304" height="3.395" x="13.955" y="9.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3535" stdDeviation=".1"/></filter><filter id="iHVU0fc" width="3.738" height="1.853" x="13.518" y="13.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3535" stdDeviation=".05"/></filter><filter id="ihEx5cd" width="13.007" height="9.656" x="7.684" y="1.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3535"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3535" result="effect2_innerShadow_4002_3535"/></filter><filter id="iSeRcRc" width="2.426" height="1.039" x="15.99" y="6.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3535"/></filter><filter id="iamu7hb" width="2.29" height="1.454" x="10.774" y="7.598" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3535"/></filter><filter id="i5dAFOt" width="6.405" height="6.79" x="8.082" y="2.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3535"/><feGaussianBlur result="effect2_foregroundBlur_4002_3535" stdDeviation=".125"/></filter><filter id="i7g03GF" width="6.784" height="5.125" x="13.677" y="2.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3535" stdDeviation=".125"/></filter><filter id="iTBwP3b" width="1.507" height="2.376" x="8.763" y="10.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3535" stdDeviation=".125"/></filter><filter id="iABgOEe" width="2.014" height="2.933" x="19.307" y="8.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3535" stdDeviation=".25"/></filter><filter id="ie5SaCe" width="2.349" height="1.413" x="10.693" y="7.69" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3535" stdDeviation=".125"/></filter><filter id="iiu6Xxc" width="2.478" height=".973" x="15.927" y="6.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3535" stdDeviation=".125"/></filter><filter id="i5JBM3d" width="5.465" height="2.488" x="14.777" y="3.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3535" stdDeviation=".375"/></filter><filter id="ivRq4Ke" width="11.192" height="8.359" x="11.542" y="21.867" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.607843 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3535"/></filter><filter id="iymJHQc" width="7.407" height="8.444" x="19.124" y="18.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3535"/></filter><filter id="i6Zz3tc" width="8.208" height="4.667" x="12.492" y="25.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.309804 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3535"/></filter><filter id="ij4Fsdc" width="3.456" height="1.701" x="7.457" y="21.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3535" stdDeviation=".1"/></filter><filter id="iXmjNac" width="4.309" height="4.662" x="11.119" y="16.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.552941 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3535"/></filter><filter id="ikWlr1V" width="3.647" height="2.753" x="6.339" y="19.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3535" stdDeviation=".05"/></filter><filter id="iEyW7DG" width="2.634" height="2.141" x="16.45" y="25.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3535" stdDeviation=".125"/></filter><filter id="iekZlHc" width="4.536" height="1" x="12.822" y="28.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3535" stdDeviation=".15"/></filter><filter id="iMHktte" width="3.987" height="3.987" x="10.476" y="8.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3535" stdDeviation=".325"/></filter><filter id="ipW6oge" width="3.987" height="3.987" x="15.065" y="7.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3535" stdDeviation=".325"/></filter><filter id="i61vjad" width="2.323" height=".964" x="11.382" y="10.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3535" stdDeviation=".05"/></filter><filter id="ixWqTcb" width="2.323" height=".964" x="16.012" y="9.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3535" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-feeding-baby-medium-dark" /></template>
<style>
.a-nb7zbxy {
  d: path("M15.421 13.894c-.51.085-1.01.046-1.448-.097c-.15-.046-.271.133-.164.244a1.93 1.93 0 0 0 1.735.583a1.93 1.93 0 0 0 1.448-1.117c.065-.145-.108-.27-.234-.177a3.05 3.05 0 0 1-1.337.564");
}

.a3emfp-7e {
  stop-color: var(--svg-color--967970, #967970);
}

.a6ayzxb8w {
  stop-color: var(--svg-color--289d47, #289D47);
  stop-opacity: 0;
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.acgtzjb8q {
  stop-color: var(--svg-color--3ba055, #3BA055);
}

.afcdt12xs {
  stop-color: var(--svg-color--7c5c50, #7C5C50);
  stop-opacity: 0;
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.amlvwb9ik {
  stop-color: var(--svg-color--9b7c73, #9B7C73);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.bhzzakkbd {
  stop-color: var(--svg-color--d4453a, #D4453A);
}

.bji58ac7a {
  stop-color: var(--svg-color--208d47, #208D47);
}

.bp_0a2x2s {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m14.218 5.298l-.09-.126a.68.68 0 0 0-.688-.317l-1.28.215c-1.855.311-3.103 2.084-2.788 3.96l.046.277c-.385-.203-.907-.68-1.056-1.567c-.181-1.078.513-1.754.956-2.186c.125-.122.23-.224.29-.31l.082-.122c.289-.432.803-1.2 1.848-1.675a5.6 5.6 0 0 1 1.503-.422c.468-.066.865.281.943.748l.253 1.508z");
}

.bqa94ibrz {
  stop-color: var(--svg-color--853935, #853935);
  stop-opacity: 0;
}

.brh-pzb_h {
  stop-color: var(--svg-color--f36716, #F36716);
  stop-opacity: 0;
}

.bu_bl572i {
  d: path("M8.933 20.905c-.314.22-.722.211-.906-.11c-.391-.947.721-1.579 1.5-1.597c1.168-.027 1.75.629 1.938 1.121s.226 1.477-.672 1.54c-.804.055-.848-.5-.98-.743c-.134-.242-.595-.41-.88-.21");
}

.bzi-27bxc {
  stop-color: var(--svg-color--f36716, #F36716);
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c_p6lvbtv {
  stop-color: var(--svg-color--31be7d, #31BE7D);
}

.c7hm4yb7u {
  stop-color: var(--svg-color--8a5a50, #8A5A50);
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c8r1g2bnk {
  stop-color: var(--svg-color--148c3e, #148C3E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.ceh8ilb4x {
  stop-color: var(--svg-color--98746b, #98746B);
  stop-opacity: 0;
}

.cj1sl_bqb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.857 23.007c.578.14 1.919.172 2.656-.828");
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.cjhyb2bbj {
  stop-color: var(--svg-color--ff5641, #FF5641);
}

.cn05xwrkd {
  stop-color: var(--svg-color--fed466, #FED466);
}

.czerk-92m {
  stop-color: var(--svg-color--cf482d, #CF482D);
}

.d-33bzb2o {
  stop-color: var(--svg-color--734154, #734154);
  stop-opacity: 0;
}

.d0ocakaur {
  stop-color: var(--svg-color--ff3200, #FF3200);
}

.d1h879bbi {
  stop-color: var(--svg-color--6f3c47, #6F3C47);
  stop-opacity: 0;
}

.d3bth9bgz {
  stop-color: var(--svg-color--2d2d2d, #2D2D2D);
}

.deg8fdc9j {
  stop-color: var(--svg-color--ff451c, #FF451C);
  stop-opacity: 0;
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dgdf5hjmy {
  d: path("M10.641 18.545c-.28.05-.54.19-.74.38c.01-.05.02-.1.04-.15l.12-.33c.28-.78 1.09-1.27 1.91-1.15l1.66.23c.42.06.72.45.66.87s-.45.72-.87.66l-1.57-.22c-.34-.26-.78-.37-1.21-.29");
}

.dgjbigo9b {
  d: path("M20.017 10.838a327 327 0 0 0-.21-1.932a.974.974 0 0 1 .21 1.932");
}

.di46q3nvv {
  stop-color: var(--svg-color--ce5621, #CE5621);
}

.diy3tbc3u {
  stop-color: var(--svg-color--713d53, #713D53);
}

.dl3hh1b2p {
  d: path("M8.597 18.456a.28.28 0 0 1 .133-.27c.981-.69 2.005-.304 2.383 0c.305.236 1 .79 1.363 1.083c.446.36.372.96.043 1.316c-.276.298-.751.241-.93.148l-2.097-1.312c-.055-.312-.235-.562-.48-.637c-.247-.074-.403-.133-.415-.328");
}

.dm21qhbor {
  stop-color: var(--svg-color--d46751, #D46751);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dy155dxdg {
  stop-color: var(--svg-color--33c966, #33C966);
}

.dyh_p3bsl {
  stop-color: var(--svg-color--279f64, #279F64);
}

.dypnkmnss {
  stop-color: var(--svg-color--33c966, #33C966);
  stop-opacity: 0;
}

.e122-lbju {
  stop-color: var(--svg-color--8b72aa, #8B72AA);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e6bcurcdv {
  stop-color: var(--svg-color--6cd9f5, #6CD9F5);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.eim87q2nu {
  stop-color: var(--svg-color--7f635a, #7F635A);
}

.eis_d-rpv {
  d: path("m29.221 25.315l-4.94-6.05l-3.16 8.57z");
}

.el1w3ub2m {
  d: path("M9.547 9.96a1.654 1.654 0 0 0-1.13 1.842a1.64 1.64 0 0 0 1.8 1.358a80 80 0 0 1-.67-3.2");
}

.em3lc9y5i {
  stop-color: var(--svg-color--fed064, #FED064);
}

.emat5kllu {
  d: path("M15.761 18.505c1.06 0 1.91-.86 1.91-1.91v-2.26a1.91 1.91 0 1 0-3.82 0v2.26c-.01 1.06.85 1.91 1.91 1.91");
}

.eovkc4nhj {
  stop-color: var(--svg-color--303030, #303030);
  stop-opacity: 0;
}

.eqapwmsga {
  stop-color: var(--svg-color--208d47, #208D47);
  stop-opacity: 0;
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.esennwbzv {
  stroke: var(--svg-color--8c6565, #8C6565);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.323 29.072h3.535");
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fdm2y6x_j {
  stop-color: var(--svg-color--070509, #070509);
}

.fmfd79b2c {
  stop-color: var(--svg-color--764d50, #764D50);
}

.fo4qq4q_b {
  stop-color: var(--svg-color--289d47, #289D47);
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.ft5dv1b6b {
  fill: none;
}

.fu3c0cblo {
  stop-color: var(--svg-color--f38820, #F38820);
}

.g2g0htigy {
  stop-color: var(--svg-color--612e25, #612E25);
}

.g3aduzb1s {
  fill: var(--svg-color--7d5252, #7D5252);
  d: path("M17.256 25.658a.937.937 0 0 0-1.12 1.497l.931.802a.1.1 0 0 1-.063.176l-3.643.072a.886.886 0 0 0 .017 1.77h6.06v-1L20.5 27.75z");
}

.g7xtertqj {
  stop-color: var(--svg-color--303030, #303030);
}

.gk1ryqb5w {
  d: path("M18.691 3.486a2.37 2.37 0 0 1 1.452.842c.608.747.704 1.745.32 2.558a1.6 1.6 0 0 0-.125.924l.2 1.194a1.8 1.8 0 0 0-.715-.157L19.63 7.22a1.477 1.477 0 0 0-1.628-1.206l-1.408.236a2.47 2.47 0 0 1-2.466-1.077a.68.68 0 0 0-.69-.317l-1.279.215c-1.855.311-3.103 2.084-2.788 3.96l.29 1.54c-.25.081-.501.211-.68.387L8.78 9.751a1.6 1.6 0 0 0-.42-.833a2.44 2.44 0 0 1-.556-2.435A2.4 2.4 0 0 1 8.92 5.132a2.73 2.73 0 0 0 1.204-1.35a2.37 2.37 0 0 1 2.752-1.404c.412.102.844.03 1.2-.202c.262-.166.56-.288.885-.342a2.37 2.37 0 0 1 2.19.802c.395.46.943.75 1.54.85");
}

.gmelrdffb {
  stop-color: var(--svg-color--ff8040, #FF8040);
}

.grqmao4rm {
  stop-color: var(--svg-color--b59cc2, #B59CC2);
  stop-opacity: 0;
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.h1ie4dmkz {
  stop-color: var(--svg-color--131212, #131212);
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h94nvm15h {
  stop-color: var(--svg-color--43b1db, #43B1DB);
}

.ha1dqccsi {
  stop-color: var(--svg-color--7d5d51, #7D5D51);
}

.hbzm4jmfo {
  stop-color: var(--svg-color--f54c3c, #F54C3C);
}

.hgj37ubhx {
  stop-color: var(--svg-color--9b7c73, #9B7C73);
  stop-opacity: 0;
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hkd847oax {
  d: path("M8.207 17.218c1.03-1.086 1.919-1.37 2.32-1.375l.797.867l-.93 3.516c-.18.315-.564.996-.695 1.152c-.164.195-.735.63-1.766.238c-.887-.337-1.15-.898-1.176-1.148c.234-1.168.65-2.358 1.45-3.25");
}

.hl0xq4brp {
  d: path("M10.175 16.437c.356.124.482.33.516.453l.445.39l2.292.362a.92.92 0 0 0 1.061-.871a.913.913 0 0 0-.922-.95c-1.174.013-2.687.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hpbf-mbbs {
  d: path("M7.231 29.975c-1.05 0-1.9-.85-1.89-1.9l.01-2.13c0-5.77 4.79-10.46 10.69-10.46c5.91 0 10.69 4.68 10.69 10.46l.17 4.03z");
}

.hzjcm7beg {
  d: path("m15.53 20.74l.227.069a.5.5 0 0 0 .492-.12l.364-.352a.13.13 0 0 1 .128-.034l.314.084a.484.484 0 0 0 .253-.935l-.303-.083a.13.13 0 0 1-.098-.108l-.069-.44a.5.5 0 0 0-.36-.404l-.26-.072z");
}

.hzk1ijbie {
  stop-color: var(--svg-color--e2492a, #E2492A);
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i5de26xkm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.i5etcbh5r {
  stop-color: var(--svg-color--845b55, #845B55);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.i89aqmaix {
  stop-color: var(--svg-color--936757, #936757);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.icorotc4i {
  stop-color: var(--svg-color--ff451c, #FF451C);
}

.iezg62obf {
  stop-color: var(--svg-color--ff8427, #FF8427);
}

.iixz2pbja {
  d: path("M11.532 11.162c.15.14.547.37 1.062.273c.563-.106.888-.458.96-.64");
}

.ijdg6fbam {
  stop-color: var(--svg-color--fc4a51, #FC4A51);
}

.j25x9tegw {
  stop-color: var(--svg-color--6e413f, #6E413F);
  stop-opacity: 0;
}

.jcvyznbme {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M18.182 7.357a1.9 1.9 0 0 0-.76-.297c-.323-.045-.71-.007-1.23.147a.283.283 0 0 0 .161.542c.474-.14.775-.16.99-.13c.21.03.362.109.543.22a.283.283 0 0 0 .296-.482");
}

.jlg325b9p {
  d: path("m12.243 16.44l2.635.735c.357.104.645.406.522.797l-.78 2.704c-.095.329-.442.504-.851.393l-2.6-.733z");
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.jxwdq3van {
  stop-color: var(--svg-color--6c3d40, #6C3D40);
}

.jxwnoqbqn {
  stop-color: var(--svg-color--3782ce, #3782CE);
}

.k_pdrlblj {
  stop-color: var(--svg-color--ebb830, #EBB830);
  stop-opacity: 0;
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kar3bi73q {
  stop-color: var(--svg-color--d25e22, #D25E22);
  stop-opacity: 0;
}

.kcxizyr3a {
  stop-color: var(--svg-color--ff8a47, #FF8A47);
}

.khl528bkl {
  stop-color: var(--svg-color--ff8040, #FF8040);
  stop-opacity: 0;
}

.kloinabmx {
  stop-color: var(--svg-color--c26f5c, #C26F5C);
  stop-opacity: 0;
}

.kmp3a3cnr {
  stop-color: var(--svg-color--ce953a, #CE953A);
}

.kpahiqbxi {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.03 7.511c-.29-.142-.988-.36-1.728-.104");
}

.kyl8adb5j {
  stop-color: var(--svg-color--148c3e, #148C3E);
  stop-opacity: 0;
}

.kyqssj_6u {
  stop-color: var(--svg-color--845b55, #845B55);
  stop-opacity: 0;
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l8v5z5bog {
  stop-color: var(--svg-color--6e574e, #6E574E);
}

.liitwlntz {
  d: path("M9.746 17.358c.243.25.33.526.343.633l.485.469l2.341.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.775-1.078c-1.09-.133-2.42-.306-2.779-.347c-.613-.07-.945.297-.64.61");
}

.lkdb1y-jt {
  d: path("m12.015 16.01l3.172.883c.43.125.744.559.627.96l-.899 3.086c-.115.396-.533.607-1.025.474l-3.129-.884z");
}

.ll6ec2bpd {
  stop-color: var(--svg-color--6e574e, #6E574E);
  stop-opacity: 0;
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.lt00fqber {
  cx: 12.47px;
  cy: 10.226px;
  r: 1.344px;
}

.lwl1xgbup {
  stop-color: var(--svg-color--d25e22, #D25E22);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m00m2sd0g {
  d: path("M21.651 23.915a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.m7g5qjj9l {
  d: path("m2.277 29.975l2.93-9.156c.352-1.414 2.07-2.104 3.65-1.614s2.49 2.333 2.006 3.692l-2.216 7.078z");
}

.m8j63xbdo {
  stop-color: var(--svg-color--763638, #763638);
}

.m9orc9b3r {
  stop-color: var(--svg-color--ae4614, #AE4614);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mnw_fc_zm {
  stop-color: var(--svg-color--94776f, #94776F);
  stop-opacity: 0;
}

.ms0h6vbdl {
  d: path("m14.427 10.328l-.224 1.938c-.045.398.28.735.651.672l.79-.132c.371-.063.568-.492.397-.848l-.845-1.759c-.183-.39-.717-.3-.769.13");
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n8jici3hn {
  stop-color: var(--svg-color--fed466, #FED466);
  stop-opacity: 0;
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.ndf7m0b2h {
  stop-color: var(--svg-color--7f635a, #7F635A);
  stop-opacity: 0;
}

.neym138jd {
  stop-color: var(--svg-color--f3c22a, #F3C22A);
}

.nfxh0wuuc {
  fill: var(--svg-color--7c5b4d, #7C5B4D);
  d: path("M10.175 16.437c.356.124.482.33.516.453l.445.39l2.292.362a.92.92 0 0 0 1.061-.871a.913.913 0 0 0-.922-.95c-1.174.013-2.687.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.njdbcpw8w {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nkti4m6tj {
  stop-color: var(--svg-color--7d505c, #7D505C);
  stop-opacity: 0;
}

.nmgehrbde {
  d: path("M9.618 10.636a.974.974 0 0 0 .401 1.875a79 79 0 0 1-.4-1.875");
}

.nn3wh7bnm {
  stop-color: var(--svg-color--58d4f5, #58D4F5);
}

.npcbhubbk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.67 19.726c-.206.432-.32 1.448.874 2.054c1.194.607 1.993.149 2.243-.156");
}

.nz1ipmv-m {
  stop-color: var(--svg-color--7c4264, #7C4264);
}

.op-vxebsg {
  stop-color: var(--svg-color--98746b, #98746B);
}

.opc5nbd0u {
  stop-color: var(--svg-color--6f3c47, #6F3C47);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p1_arrbav {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.068 8.728c.227-.229.816-.663 1.6-.663");
}

.p108vxifj {
  stop-color: var(--svg-color--853935, #853935);
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.p6n8nbb9p {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
  stop-opacity: 0;
}

.pdon63boo {
  stop-color: var(--svg-color--f38820, #F38820);
  stop-opacity: 0;
}

.phzm4snim {
  stop-color: var(--svg-color--ce6122, #CE6122);
}

.piesmtbrq {
  stop-color: var(--svg-color--965c49, #965C49);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.poexxt13f {
  d: path("M10.29 21.662c-.283.88-1.448 1.292-2.6.92c-1.152-.37-1.792-1.177-1.572-2.265c.18-.888.883-1.75 2.738-1.24c1.152.372 1.718 1.705 1.434 2.585");
}

.pvzvrjbje {
  stop-color: var(--svg-color--2d2d2d, #2D2D2D);
  stop-opacity: 0;
}

.q_48wdbvi {
  d: path("m14.902 17.073l-2.636-.734l-1.073 3.895l2.6.734c.408.11.755-.065.851-.394l.78-2.703c.122-.391-.165-.694-.522-.798");
}

.qfqp0mb_l {
  cx: 17.059px;
  cy: 9.497px;
  r: 1.344px;
}

.qh-ows9fr {
  stop-color: var(--svg-color--a07cb6, #A07CB6);
}

.qhztoebdo {
  d: path("m14.383 10.243l-.224 1.938c-.045.398.28.735.651.672l.79-.132c.371-.063.568-.492.396-.848l-.844-1.759c-.183-.39-.717-.3-.769.13");
}

.qic_n_blg {
  stop-color: var(--svg-color--d2c9d1, #D2C9D1);
}

.qm9mii7bp {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m14.427 10.328l-.224 1.938c-.045.398.28.735.651.672l.79-.132c.371-.063.568-.492.397-.848l-.845-1.759c-.183-.39-.717-.3-.769.13");
}

.qp1u6qbwv {
  d: path("m11.921 20.575l-.46-.5c-.28-.3-.68-.48-1.09-.49c-.42-.01-.82.16-1.11.46l-.17.18l.53-.95c.22-.39.59-.66 1.02-.74s.88.03 1.23.3l.99.8c.33.27.38.75.12 1.09c-.21.26-.56.35-.85.24a.9.9 0 0 0-.21-.39");
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qtvy6rbzh {
  stop-color: var(--svg-color--42b8e0, #42B8E0);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.qxxa4bmmv {
  stop-color: var(--svg-color--6e413f, #6E413F);
}

.r1y6vkpka {
  stop-color: var(--svg-color--b42c01, #B42C01);
}

.r6dyzpbfo {
  stop-color: var(--svg-color--a62302, #A62302);
  stop-opacity: 0;
}

.rdfu8xqvl {
  d: path("M10.549 14.576a3.99 3.99 0 0 0 4.48 2.768l1.897-.319a3.99 3.99 0 0 0 3.33-4.08a354 354 0 0 0-.625-5.726a1.477 1.477 0 0 0-1.628-1.206l-1.408.236a2.47 2.47 0 0 1-2.466-1.077a.68.68 0 0 0-.69-.317l-1.279.215c-1.855.311-3.103 2.084-2.788 3.96c.314 1.87.74 3.691 1.177 5.546");
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rqbec9bxg {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m14.441 10.529l-.283 1.947c-.038.397.27.737.614.679l.736-.124c.345-.058.523-.485.359-.842l-.807-1.764c-.176-.392-.576-.325-.619.104");
}

.s599otu9k {
  d: path("M10.257 13.059a1.67 1.67 0 0 1-.962-.158l.157.936c.151.898.82 1.608 1.689 1.803a4.2 4.2 0 0 1-.547-1.127z");
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.sinn-3bvk {
  stop-color: var(--svg-color--6cd8f5, #6CD8F5);
  stop-opacity: 0;
}

.sjvismp2t {
  stop-color: var(--svg-color--fc4a51, #FC4A51);
  stop-opacity: 0;
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.svx6r0gzk {
  stop-color: var(--svg-color--713e53, #713E53);
}

.sx4xd35ql {
  stop-color: var(--svg-color--734054, #734054);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t5sd16bfc {
  stop-color: var(--svg-color--6b463c, #6B463C);
}

.t78i98bfv {
  stop-color: var(--svg-color--735caf, #735CAF);
  stop-opacity: 0;
}

.tbs366q3s {
  stop-color: var(--svg-color--4760c0, #4760C0);
}

.tc83oubxb {
  stop-color: var(--svg-color--886658, #886658);
}

.ti3jmkb7y {
  stop-color: var(--svg-color--94776f, #94776F);
}

.tmyz66fau {
  stop-color: var(--svg-color--7d5b50, #7D5B50);
  stop-opacity: 0;
}

.tnkwcrb_w {
  stop-color: var(--svg-color--846256, #846256);
}

.tnq1kg2hb {
  d: path("M16.162 10.355c.15.14.547.37 1.062.273c.563-.106.888-.458.961-.64");
}

.tomvu1bgl {
  stop-color: var(--svg-color--78e0ff, #78E0FF);
}

.tpw8-_30q {
  stop-color: var(--svg-color--6b4041, #6B4041);
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.trma59b_r {
  stop-color: var(--svg-color--d1623d, #D1623D);
  stop-opacity: 0;
}

.twkrvc03o {
  stop-color: var(--svg-color--c24713, #C24713);
}

.tx1f5kbzi {
  d: path("M20.106 11.5q-.168-1.622-.353-3.24a1.64 1.64 0 0 1 .353 3.24");
}

.tz2l_he6k {
  stop-color: var(--svg-color--c24713, #C24713);
  stop-opacity: 0;
}

.tzj34xnjq {
  stop-color: var(--svg-color--ffd267, #FFD267);
}

.u_vqqhk3b {
  stop-color: var(--svg-color--ff9400, #FF9400);
}

.ud0xernhq {
  stop-color: var(--svg-color--713d53, #713D53);
  stop-opacity: 0;
}

.ugbytbngn {
  stop-color: var(--svg-color--ffd267, #FFD267);
  stop-opacity: 0;
}

.ui58-1_-x {
  stop-color: var(--svg-color--856053, #856053);
  stop-opacity: 0;
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uptie3ora {
  stop-color: var(--svg-color--73564c, #73564C);
}

.urcycevie {
  d: path("M23.521 27.135a4.3 4.3 0 1 0 0-8.6a4.3 4.3 0 0 0 0 8.6");
}

.uuwie8bnd {
  stop-color: var(--svg-color--6a3e48, #6A3E48);
}

.uw-cne-zt {
  stop-color: var(--svg-color--7c4264, #7C4264);
  stop-opacity: 0;
}

.uz8nvn0bw {
  stop-color: var(--svg-color--ff8a47, #FF8A47);
  stop-opacity: 0;
}

.v0y0h5pun {
  stop-color: var(--svg-color--734054, #734054);
}

.v2wkn2ras {
  stop-color: var(--svg-color--31ae6a, #31AE6A);
}

.v3_lnpb5q {
  stop-color: var(--svg-color--6b463c, #6B463C);
  stop-opacity: 0;
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vkmoa2bgc {
  d: path("M20.03 11.418a1.67 1.67 0 0 0 .857-.462l.157.935c.15.898-.25 1.788-1.007 2.256q.165-.591.149-1.244z");
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.vxuagmllm {
  d: path("M17.256 25.658a.937.937 0 0 0-1.12 1.497l.931.802a.1.1 0 0 1-.063.176l-3.643.072a.886.886 0 0 0 .017 1.77h6.06v-1L20.5 27.75z");
}

.w_57dfb5m {
  stop-color: var(--svg-color--735caf, #735CAF);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w444cbj2i {
  stop-color: var(--svg-color--fa362a, #FA362A);
}

.w5xbz1t2h {
  stop-color: var(--svg-color--714f47, #714F47);
}

.w6b4lnbbx {
  fill: var(--svg-color--7c5a4f, #7C5A4F);
  d: path("M9.746 17.358c.243.25.33.526.343.633l.485.469l2.341.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.775-1.078c-1.09-.133-2.42-.306-2.779-.347c-.613-.07-.945.297-.64.61");
}

.w6tfixy4t {
  d: path("M16.12 10.085c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34a.263.263 0 0 1 .11-.47");
}

.w8ej_fbdv {
  stop-color: var(--svg-color--7e574e, #7E574E);
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wyqcze2zy {
  stop-color: var(--svg-color--a62302, #A62302);
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xaev7oldu {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.061 13.537a.22.22 0 0 0-.07-.268a.23.23 0 0 0-.277 0v.001c-.359.27-.802.465-1.305.55a3 3 0 0 1-1.413-.094a.23.23 0 0 0-.263.092a.214.214 0 0 0 .022.275m3.306-.556l-.069-.03l.07.03zm0 0a2 2 0 0 1-1.505 1.161a2 2 0 0 1-1.801-.605m0 0l.054-.052m-.054.052l.054-.052m0 0a1.93 1.93 0 0 0 1.735.583a1.93 1.93 0 0 0 1.448-1.117c.065-.145-.108-.27-.234-.177a3.05 3.05 0 0 1-1.337.564c-.51.085-1.01.046-1.448-.097c-.15-.046-.271.133-.164.244Z");
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xrzwqzb7j {
  stop-color: var(--svg-color--b42c01, #B42C01);
  stop-opacity: 0;
}

.xvwmp6tlw {
  stop-color: var(--svg-color--e6422d, #E6422D);
  stop-opacity: 0;
}

.xyrntivgr {
  stop-color: var(--svg-color--ff7c1e, #FF7C1E);
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y6_vjs3df {
  stop-color: var(--svg-color--987a70, #987A70);
}

.ybv5jrznt {
  d: path("m19.776 7.741l-.136-.63c-.14-.765-.88-1.292-1.653-1.195l-1.408.236a2.47 2.47 0 0 1-2.347-.908s-.09-.138-.197-.38c-.406-.917.386-1.796 1.388-1.746c.988.05 2.132.22 3.047.62c1.946.85 2.066 2.878 1.306 4.003");
}

.ycyum3z7k {
  stop-color: var(--svg-color--7e574e, #7E574E);
  stop-opacity: 0;
}

.ye-ecgz9l {
  stop-color: var(--svg-color--7c5c50, #7C5C50);
}

.yibo1bbtp {
  d: path("m14.218 5.298l-.09-.126a.68.68 0 0 0-.688-.317l-1.28.215c-1.855.311-3.103 2.084-2.788 3.96l.046.277c-.385-.203-.907-.68-1.056-1.567c-.181-1.078.513-1.754.956-2.186c.125-.122.23-.224.29-.31l.082-.122c.289-.432.803-1.2 1.848-1.675a5.6 5.6 0 0 1 1.503-.422c.468-.066.865.281.943.748l.253 1.508z");
}

.ysy2yub5t {
  d: path("M11.49 10.894c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34c-.19-.14-.11-.43.11-.47");
}

.ytapvgb1c {
  stop-color: var(--svg-color--6c3d40, #6C3D40);
  stop-opacity: 0;
}

.yu0d-vcbn {
  stroke: var(--svg-color--8f706a, #8F706A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m16.95 26.266l1.635 1.14");
}

.yxmxw0ard {
  stop-color: var(--svg-color--32996b, #32996B);
}

.z3onfuh1i {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m19.776 7.741l-.136-.63c-.14-.765-.88-1.292-1.653-1.195l-1.408.236a2.47 2.47 0 0 1-2.347-.908s-.09-.138-.197-.38c-.406-.917.386-1.796 1.388-1.746c.988.05 2.132.22 3.047.62c1.946.85 2.066 2.878 1.306 4.003");
}

.z3zsa5bpu {
  stop-color: var(--svg-color--53f595, #53F595);
}

.z6eb4kblv {
  d: path("m15.606 17.841l.554.16a.15.15 0 0 1 .103.185l-.783 2.73a.15.15 0 0 1-.186.103l-.555-.16z");
}

.z8kn0tyhs {
  fill: var(--svg-color--49373d, #49373D);
  d: path("m18.192 4.585l-2.092.351a.492.492 0 1 1-.085-.98c.558-.004 1.299-.004 1.801.035c1.137.087 1.527.568 1.675.932a1.54 1.54 0 0 0-1.3-.338");
}

.zegip2beb {
  stop-color: var(--svg-color--ae4614, #AE4614);
  stop-opacity: 0;
}

.zfr5v_r8t {
  stop-color: var(--svg-color--74514c, #74514C);
}

.ziy-jybcv {
  stop-color: var(--svg-color--7d5d51, #7D5D51);
  stop-opacity: 0;
}

.zkllbdcmm {
  d: path("M21.911 23.996c-1.17-2.04-3.78-2.73-5.81-1.56l-2.43 1.4c-2.04 1.17-2.73 3.78-1.56 5.81l.21.33h7.73l.3-.18a4.23 4.23 0 0 0 1.56-5.8");
}

.zmi4w8bcg {
  d: path("M20.692 25.753c1.597-.23 4.566-.809 6.543-1.27c1.522-.263 2.64 1.203 2.64 2.781c0 1.372-1.022 2.237-1.746 2.619a.86.86 0 0 1-.404.093h-8.014V26.89c0-.797.281-1 .98-1.137");
}

.zmq4c2bxg {
  stop-color: var(--svg-color--d1623d, #D1623D);
}

.zonay4blc {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M10.982 8.453a2.83 2.83 0 0 1 1.687-.655a.283.283 0 1 1 .026.565a2.26 2.26 0 0 0-1.346.52a1 1 0 0 0-.082.076l-.003.003a.283.283 0 0 1-.415-.384z");
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zvp8msbqz {
  d: path("M19.075 26.758a.15.15 0 0 1 .15-.15h.642v3.368h-.793z");
}

</style>
