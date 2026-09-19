<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#idrjHBQ)" class="xzsnre4ka"/><path fill="url(#iuscchl)" class="x_o33sb8c"/><path fill="url(#ipbsh7d)" class="olt1cqbej"/><path fill="url(#iOh3VSd)" class="dzrf69sqf"/><g filter="url(#igZXrQb)"><path fill="url(#ijRva2H)" class="ht0yexaec"/></g><path fill="url(#iun0Yhd)" class="ht0yexaec"/><path fill="url(#iVfS9ec)" class="ht0yexaec"/><path fill="url(#igXRVAe)" class="ht0yexaec"/><path fill="url(#ixLo4Fc)" class="ht0yexaec"/><path fill="url(#iFmPttd)" class="ht0yexaec"/><g filter="url(#izaJSze)"><path class="p6g1y959n"/></g><g filter="url(#iVSufUc)"><path class="o5s768wpb"/><path fill="url(#i9qVrnw)" class="yyz6uvb9t"/><path fill="url(#i9JbR4c)" class="yyz6uvb9t"/><path fill="url(#imi5cQO)" class="yyz6uvb9t"/><path fill="url(#i8y36pe)" class="yyz6uvb9t"/></g><g filter="url(#iVxwrLV)"><path fill="url(#imyyH5c)" class="q1j_wqbdw"/></g><g filter="url(#iXyDZId)"><path stroke="url(#iTaIvDb)" class="f03q2oq4r"/></g><path fill="url(#iSazaqd)" class="ru8e28bju"/><g filter="url(#i6E0h8d)"><path fill="url(#iIMZ58d)" class="lwayml7-v"/><path fill="url(#iVuDgTd)" class="lwayml7-v"/><path fill="url(#inzvM1d)" class="lwayml7-v"/><path fill="url(#iwypoic)" class="lwayml7-v"/><path fill="url(#i5qYeEe)" class="lwayml7-v"/></g><g filter="url(#iU2jtjd)"><path class="hwhva5kss"/></g><g filter="url(#i5Xcslb)"><path class="g3hnripfm"/></g><g filter="url(#iNMFApe)"><path class="ma300385g"/><path fill="url(#imiVyMG)" class="wbjdhzrgj"/><path fill="url(#inIe72b)" class="wbjdhzrgj"/></g><g filter="url(#ihyUIdc)"><path class="rfh9ucc-q"/><path fill="url(#i1W3XHe)" class="fvf9v11lh"/><path fill="url(#i8uR8Vc)" class="fvf9v11lh"/><path fill="url(#iw9Ojgd)" class="fvf9v11lh"/></g><path fill="url(#iIYqkwe)" class="b14f1uw5k"/><path fill="url(#ixjarqb)" class="b14f1uw5k"/><path fill="url(#icMiDme)" class="b14f1uw5k"/><path fill="url(#iRxQ8ib)" class="b14f1uw5k"/><path fill="url(#iV7oT9h)" class="ur81h3fis"/><path fill="url(#iYlpHKe)" class="ur81h3fis"/><g filter="url(#iyxI70p)"><path fill="url(#ildJoLd)" class="yt2biebrs"/></g><g filter="url(#i8aEZSh)"><path fill="url(#ihgRnHD)" class="r-plr9ycy"/></g><g filter="url(#ivSdWWd)"><path class="bavmm9g-k"/></g><g filter="url(#iujukfb)"><path class="k02zgtbsb"/></g><path fill="url(#iviYLGb)" class="zh5j4o24i"/><path fill="url(#iFOnhJe)" class="r8zbsj1bq"/><path fill="url(#iNkuCJe)" class="r8zbsj1bq"/><path fill="url(#iz9B6tc)" class="r8zbsj1bq"/><path fill="url(#itnSJGu)" class="r8zbsj1bq"/><path fill="url(#ipvUEwu)" class="r8zbsj1bq"/><path fill="url(#is2KT4b)" class="r8zbsj1bq"/><g filter="url(#i1NOhke)"><path fill="url(#iurIuZc)" class="xldtbyboa"/><path fill="url(#i4Q1Jee)" class="xldtbyboa"/><path fill="url(#iukm2Bc)" class="xldtbyboa"/></g><path fill="url(#iAZ10Od)" class="xt0e5dbpd"/><g filter="url(#iqnI3Id)"><path fill="url(#iGdMDqc)" class="ijbc0g1go"/><path fill="url(#i1ibMrd)" class="ijbc0g1go"/></g><g filter="url(#i54J4Sc)"><path class="iqt-sufrb"/><path fill="url(#iRPlFpI)" class="jbfk2nbof"/><path fill="url(#iZifDxb)" class="jbfk2nbof"/><path fill="url(#i3eqHce)" class="jbfk2nbof"/><path fill="url(#i8HDnIb)" class="jbfk2nbof"/></g><path fill="url(#iTPEMfa)" class="nf5zrsbwk"/><path fill="url(#ixuNSNu)" class="nf5zrsbwk"/><path fill="url(#ilRQVue)" class="j903jcckb"/><path fill="url(#iUBBJLe)" class="j903jcckb"/><path fill="url(#iHIShle)" class="h0yn0repu"/><path fill="url(#i4vDA3d)" class="h0yn0repu"/><path fill="url(#itFmAEd)" class="h0yn0repu"/><path fill="url(#iJXeSRb)" class="h0yn0repu"/><path fill="url(#iNLI2pd)" class="bhrasga7j"/><path fill="url(#ikHopNu)" class="yqjzu1_0l"/><path fill="url(#iLcsIIe)" class="q6_clrwlc"/><path fill="url(#iukmJNe)" class="q6_clrwlc"/><path fill="url(#iGRt6Xc)" class="q6_clrwlc"/><g filter="url(#i5W02Bc)"><path stroke="url(#ihDHUBb)" class="o-xm8fsgg"/></g><path fill="url(#iBmDtVH)" class="lwjfgzbrh"/><path fill="url(#iz3yh2b)" class="lwjfgzbrh"/><path fill="url(#ijgnmbd)" class="wopza1bkm"/><g filter="url(#iFCYzqb)"><path fill="url(#i9aCR5c)" class="gwqqnwbju"/><path fill="url(#iXoG2ub)" class="gwqqnwbju"/><path fill="url(#iBIMvkV)" class="gwqqnwbju"/></g><path fill="url(#iF4xuQc)" class="y1n-51biq"/><path fill="url(#ifO0YLe)" class="y1n-51biq"/><path fill="url(#inaAJJe)" class="y1n-51biq"/><path fill="url(#iaqKJnc)" class="y1n-51biq"/><path fill="url(#iqf0OIb)" class="y1n-51biq"/><path class="gljb9qb7i"/><path fill="url(#iESFN0t)" class="wr0a1jdsz"/><path fill="url(#ikcwnkE)" class="wr0a1jdsz"/><path class="n4s665bvu"/><path fill="url(#iYdpsFe)" class="hv19zn7up"/><path fill="url(#ihyL7fb)" class="hv19zn7up"/><path fill="url(#iT91tHc)" class="vrhur_iwf"/><path fill="url(#ikaILRc)" class="vrhur_iwf"/><path fill="url(#i855Odd)" class="vrhur_iwf"/><path fill="url(#iVPt4hb)" class="vrhur_iwf"/><path fill="url(#iCcnuDb)" class="a6lmhgb8v"/><path fill="url(#iMgn06c)" class="a6lmhgb8v"/><path fill="url(#i5GIyJc)" class="a6lmhgb8v"/><path fill="url(#iyMcgYb)" class="a6lmhgb8v"/><path fill="url(#iL6riRc)" class="ukk2wlbxt"/><path fill="url(#iqgRGae)" class="ukk2wlbxt"/><path fill="url(#iL2rbKc)" class="ukk2wlbxt"/><path fill="url(#iAJt6dc)" class="ukk2wlbxt"/><g filter="url(#iKcVnem)"><path stroke="url(#i1VYQOc)" class="c9vqjpi7e"/></g><g filter="url(#ivA33kd)" class="mc2zb0bvp"><path class="habp5x92o"/></g><g filter="url(#i4aL2ld)" class="mc2zb0bvp"><path class="oz48wlb0n"/></g><g filter="url(#iV8XhSL)"><circle fill="url(#iX9Soce)" class="hkdvptb3z"/></g><g filter="url(#iEQECEb)"><circle fill="url(#iba35He)" class="fx1nlcbbg"/></g><path fill="url(#itgCrbd)" class="lgestwbng"/><path fill="url(#iocwaZd)" class="vcmkf2bkc"/><g filter="url(#i8As3zb)" class="i5de26xkm"><path stroke="url(#ilIle3b)" class="u5rcmp2fi"/><path stroke="url(#ieBBEMe)" class="u5rcmp2fi"/></g><g filter="url(#ipUdzEe)" class="i5de26xkm"><path stroke="url(#ivaSove)" class="adv7vqbml"/><path stroke="url(#ijfZTmd)" class="adv7vqbml"/></g><defs><radialGradient id="ipbsh7d" cx="0" cy="0" r="1" gradientTransform="rotate(60.95 .163 22.691)scale(2.20923 2.6244)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="xsgkrbcbf"/><stop offset="1" class="ek_f7q3hx"/></radialGradient><radialGradient id="iOh3VSd" cx="0" cy="0" r="1" gradientTransform="matrix(1.569 .24123 -.74422 4.84048 9.037 13.706)" gradientUnits="userSpaceOnUse"><stop class="oaig2cbln"/><stop offset=".746" class="gfuj0ibqm"/></radialGradient><radialGradient id="ijRva2H" cx="0" cy="0" r="1" gradientTransform="matrix(-5.30043 .81165 -1.01391 -6.6213 17.802 10.878)" gradientUnits="userSpaceOnUse"><stop class="x0n4s-bkb"/><stop offset=".861" class="rqsfe0bvs"/></radialGradient><radialGradient id="iVfS9ec" cx="0" cy="0" r="1" gradientTransform="matrix(1.72808 -4.02764 1.4744 .6326 8.74 7.778)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="igXRVAe" cx="0" cy="0" r="1" gradientTransform="rotate(112.453 6.352 8.51)scale(3.45557 2.85285)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="ixLo4Fc" cx="0" cy="0" r="1" gradientTransform="matrix(1.90625 -3.09375 11.2345 6.92227 14 17.313)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="c0o-9dcgb"/><stop offset="1" class="o7lrx416s"/></radialGradient><radialGradient id="iFmPttd" cx="0" cy="0" r="1" gradientTransform="matrix(-.10938 -1.09375 6.92628 -.69268 15.921 17.906)" gradientUnits="userSpaceOnUse"><stop offset=".049" class="fvv81lbxu"/><stop offset="1" class="xj42tacwz"/></radialGradient><radialGradient id="i9JbR4c" cx="0" cy="0" r="1" gradientTransform="matrix(.0379 .2475 -.77782 .1191 15.641 12.621)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="i8y36pe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.43397 .9433 -1.51596 -2.3045 15.669 12.026)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="iSazaqd" cx="0" cy="0" r="1" gradientTransform="rotate(-98.706 14.15 .796)scale(.73926 2.97423)" gradientUnits="userSpaceOnUse"><stop class="jase_0f7h"/><stop offset="1" class="zn-qjxbde"/></radialGradient><radialGradient id="iVuDgTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.54363 -3.54993 8.97736 -1.37477 9.204 9.194)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="inzvM1d" cx="0" cy="0" r="1" gradientTransform="rotate(-96.108 13.843 -4.347)scale(2.57977 4.57085)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iwypoic" cx="0" cy="0" r="1" gradientTransform="rotate(-155.373 9.245 -.599)scale(2.89585 2.1257)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="i5qYeEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.14669 1.35494 -3.1374 2.65519 12.57 1.873)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="imiVyMG" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23169 .34174 -.12683 -.82827 14.096 3.984)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="inIe72b" cx="0" cy="0" r="1" gradientTransform="rotate(-66.431 11.242 -2.4)scale(6.18151 6.84848)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="i1W3XHe" cx="0" cy="0" r="1" gradientTransform="matrix(3.10084 -.47485 .18566 1.21238 17.42 4.28)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="i8uR8Vc" cx="0" cy="0" r="1" gradientTransform="matrix(2.31965 -3.0035 5.49865 4.2467 17.101 7.481)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iw9Ojgd" cx="0" cy="0" r="1" gradientTransform="matrix(3.35225 -.1194 .04999 1.40353 15.974 6.122)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="ixjarqb" cx="0" cy="0" r="1" gradientTransform="matrix(.98557 2.17682 -2.07686 .94031 19.497 9.682)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="icMiDme" cx="0" cy="0" r="1" gradientTransform="matrix(.63087 -1.21842 1.02128 .5288 19.947 10.179)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="iRxQ8ib" cx="0" cy="0" r="1" gradientTransform="matrix(.35444 -1.66308 2.2221 .47358 20.09 10.336)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="iYlpHKe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66616 .05064 -.05436 -1.78854 9.932 11.815)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="ildJoLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.90477 .3018 -.37033 -1.1102 9.933 11.815)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><radialGradient id="iz9B6tc" cx="0" cy="0" r="1" gradientTransform="matrix(.21875 3.1875 -3.62585 .24883 8.716 20.994)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="bzi-27bxc"/><stop offset="1" class="brh-pzb_h"/></radialGradient><radialGradient id="itnSJGu" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 3.4375 -2.71722 -.59285 6.466 19.713)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="lwl1xgbup"/><stop offset="1" class="kar3bi73q"/></radialGradient><radialGradient id="ipvUEwu" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15508 -.34883 1.8893 -6.25609 8.674 30.369)" gradientUnits="userSpaceOnUse"><stop class="ijdg6fbam"/><stop offset="1" class="sjvismp2t"/></radialGradient><radialGradient id="iurIuZc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0785 6 -4.46735 -1.54757 17.014 25.15)" gradientUnits="userSpaceOnUse"><stop class="v2wkn2ras"/><stop offset="1" class="yxmxw0ard"/></radialGradient><radialGradient id="i4Q1Jee" cx="0" cy="0" r="1" gradientTransform="rotate(-132.901 14.98 10.313)scale(4.22338 6.72611)" gradientUnits="userSpaceOnUse"><stop class="bji58ac7a"/><stop offset="1" class="eqapwmsga"/></radialGradient><radialGradient id="iukm2Bc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62501 -3.8277 2.0945 -1.4364 21.185 26.087)" gradientUnits="userSpaceOnUse"><stop offset=".393" class="c8r1g2bnk"/><stop offset="1" class="kyl8adb5j"/></radialGradient><radialGradient id="iAZ10Od" cx="0" cy="0" r="1" gradientTransform="matrix(-6.038 1.01561 -1.51165 -8.987 27.348 23.199)" gradientUnits="userSpaceOnUse"><stop class="z3zsa5bpu"/><stop offset="1" class="c_p6lvbtv"/></radialGradient><radialGradient id="iGdMDqc" cx="0" cy="0" r="1" gradientTransform="rotate(164.954 9.072 12.911)scale(3.00943 4.47011)" gradientUnits="userSpaceOnUse"><stop class="dyh_p3bsl"/><stop offset="1" class="acgtzjb8q"/></radialGradient><radialGradient id="i1ibMrd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66156 -1.3125 1.73451 -2.1958 22.878 25.869)" gradientUnits="userSpaceOnUse"><stop class="fo4qq4q_b"/><stop offset="1" class="a6ayzxb8w"/></radialGradient><radialGradient id="iRPlFpI" cx="0" cy="0" r="1" gradientTransform="rotate(33.14 -38.397 40.745)scale(2.25791 .79383)" gradientUnits="userSpaceOnUse"><stop class="xohjverxe"/><stop offset="1" class="sghoc4brb"/></radialGradient><radialGradient id="iZifDxb" cx="0" cy="0" r="1" gradientTransform="matrix(6.57813 0 0 1.16319 13 30.37)" gradientUnits="userSpaceOnUse"><stop class="hmgh32r7m"/><stop offset="1" class="ib26drc1k"/></radialGradient><radialGradient id="i8HDnIb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02913 0 0 -3.40472 19.341 29.307)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="at1_k3rsw"/><stop offset="1" class="frn5ss_le"/></radialGradient><radialGradient id="iUBBJLe" cx="0" cy="0" r="1" gradientTransform="rotate(168.154 12.852 14.944)scale(6.54566 1.70736)" gradientUnits="userSpaceOnUse"><stop class="kcxizyr3a"/><stop offset="1" class="uz8nvn0bw"/></radialGradient><radialGradient id="iHIShle" cx="0" cy="0" r="1" gradientTransform="matrix(.84205 2.73 -2.93117 .9041 6.842 20.244)" gradientUnits="userSpaceOnUse"><stop class="phzm4snim"/><stop offset="1" class="czerk-92m"/></radialGradient><radialGradient id="i4vDA3d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .87171 -.46263 -.67998 9.982 21.216)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="wyqcze2zy"/><stop offset="1" class="r6dyzpbfo"/></radialGradient><radialGradient id="itFmAEd" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 .75 -.43392 .18532 7.24 20.853)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="r1y6vkpka"/><stop offset="1" class="xrzwqzb7j"/></radialGradient><radialGradient id="iJXeSRb" cx="0" cy="0" r="1" gradientTransform="rotate(153.654 1.87 11.444)scale(2.61542 2.57494)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="tz2l_he6k"/><stop offset="1" class="twkrvc03o"/></radialGradient><radialGradient id="iGRt6Xc" cx="0" cy="0" r="1" gradientTransform="matrix(-.3711 1.25391 -.1532 -.04534 16.086 18.844)" gradientUnits="userSpaceOnUse"><stop class="tomvu1bgl"/><stop offset="1" class="sinn-3bvk"/></radialGradient><radialGradient id="ihDHUBb" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.60156 1.71998 -.58078 9.388 23.385)" gradientUnits="userSpaceOnUse"><stop class="gmelrdffb"/><stop offset="1" class="khl528bkl"/></radialGradient><radialGradient id="iz3yh2b" cx="0" cy="0" r="1" gradientTransform="matrix(-.64063 2 -.16496 -.05284 15.898 18.184)" gradientUnits="userSpaceOnUse"><stop class="njdbcpw8w"/><stop offset="1" class="p6n8nbb9p"/></radialGradient><radialGradient id="iXoG2ub" cx="0" cy="0" r="1" gradientTransform="rotate(25.805 -35.426 34.606)scale(1.57936 1.44294)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l8v5z5bog"/><stop offset="1" class="ll6ec2bpd"/></radialGradient><radialGradient id="ifO0YLe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0156 3.18752 -2.63101 -1.6637 9.531 18.83)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="u2k5px3jq"/><stop offset="1" class="dmm5ewwwm"/></radialGradient><radialGradient id="inaAJJe" cx="0" cy="0" r="1" gradientTransform="rotate(117.711 .016 11.763)scale(4.44066 1.93651)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="oh8on9brk"/><stop offset="1" class="f1r2vnb5a"/></radialGradient><radialGradient id="iaqKJnc" cx="0" cy="0" r="1" gradientTransform="matrix(-.1359 3.04807 -.73147 -.03261 7.35 18.486)" gradientUnits="userSpaceOnUse"><stop class="n0p5sxbec"/><stop offset="1" class="q4weiw-ee"/></radialGradient><radialGradient id="iqf0OIb" cx="0" cy="0" r="1" gradientTransform="matrix(.15625 1.04772 -1.07633 .16051 9.085 21.01)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="z6zfulbza"/><stop offset="1" class="v3ok2mbfm"/></radialGradient><radialGradient id="iESFN0t" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 -.93275 3.89243 .13041 12.797 17.893)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="tv0y_es3w"/><stop offset="1" class="b84ow2m2e"/></radialGradient><radialGradient id="ikcwnkE" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 5.262 10.01)scale(.78612 .35637)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="jj_i0ybwk"/></radialGradient><radialGradient id="iYdpsFe" cx="0" cy="0" r="1" gradientTransform="rotate(-80.715 17.47 2.424)scale(.83681 3.75171)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="y-w2tsblc"/><stop offset="1" class="xdt63zb6q"/></radialGradient><radialGradient id="ihyL7fb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 .41406 -.20022 -.51377 13.89 17.89)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="c6e6dvbgn"/><stop offset="1" class="ph2kohtod"/></radialGradient><radialGradient id="iT91tHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 1.51562 -5.32458 -2.85442 11.219 19.142)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="b-w3yacim"/><stop offset="1" class="f9l-1bcqi"/></radialGradient><radialGradient id="ikaILRc" cx="0" cy="0" r="1" gradientTransform="matrix(2.29688 1.78687 -.45885 .58982 11.594 19.414)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="u9db7sbld"/><stop offset="1" class="cbv0v1bug"/></radialGradient><radialGradient id="i855Odd" cx="0" cy="0" r="1" gradientTransform="rotate(136.002 2.392 12.03)scale(.96996 1.97716)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="e9ied_q8k"/><stop offset="1" class="r3idh6bhh"/></radialGradient><radialGradient id="iVPt4hb" cx="0" cy="0" r="1" gradientTransform="matrix(.48047 -.3496 .60677 .83392 9.016 19.22)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="urjmhobql"/><stop offset="1" class="lrbywkbvr"/></radialGradient><radialGradient id="iCcnuDb" cx="0" cy="0" r="1" gradientTransform="matrix(1.09945 -1.69165 1.88005 1.2219 8.945 21.839)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="i6m3xbfso"/><stop offset="1" class="ulc1d0bsf"/></radialGradient><radialGradient id="iMgn06c" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 .84935 -.34383 .46806 10.844 20.393)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="mql7c3hze"/><stop offset="1" class="m1_omrdxn"/></radialGradient><radialGradient id="i5GIyJc" cx="0" cy="0" r="1" gradientTransform="rotate(97.522 -3.782 14.676)scale(2.32995 4.84987)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="t5ovicbrp"/><stop offset=".962" class="i2e83jb8g"/></radialGradient><radialGradient id="iyMcgYb" cx="0" cy="0" r="1" gradientTransform="matrix(.54646 -.48802 1.62742 1.82231 7.946 21.155)" gradientUnits="userSpaceOnUse"><stop class="wdwsowbvt"/><stop offset="1" class="iy8y9zu4h"/></radialGradient><radialGradient id="iqgRGae" cx="0" cy="0" r="1" gradientTransform="rotate(105.675 .93 16.012)scale(1.31451 .34383)" gradientUnits="userSpaceOnUse"><stop class="cn05xwrkd"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="iL2rbKc" cx="0" cy="0" r="1" gradientTransform="rotate(105.036 .812 16.488)scale(.54206 .1592)" gradientUnits="userSpaceOnUse"><stop class="em3lc9y5i"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="iAJt6dc" cx="0" cy="0" r="1" gradientTransform="rotate(174.906 8.384 10.477)scale(.43997 .38553)" gradientUnits="userSpaceOnUse"><stop class="tzj34xnjq"/><stop offset="1" class="ugbytbngn"/></radialGradient><radialGradient id="i1VYQOc" cx="0" cy="0" r="1" gradientTransform="matrix(-.26365 -2.21465 3.37212 -.40144 7.844 22.184)" gradientUnits="userSpaceOnUse"><stop class="zmq4c2bxg"/><stop offset="1" class="trma59b_r"/></radialGradient><radialGradient id="iX9Soce" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 15.216 -4.608)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".053" class="dkw76cbyw"/><stop offset=".876" class="wvohhnbma"/></radialGradient><radialGradient id="iba35He" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 16.912 -8.744)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="nsooqoy6p"/><stop offset=".535" class="v_jz0vies"/></radialGradient><radialGradient id="itgCrbd" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .35569 2.1855 11.383 11.522)" gradientUnits="userSpaceOnUse"><stop class="fdm2y6x_j"/><stop offset="1" class="h1ie4dmkz"/></radialGradient><radialGradient id="iocwaZd" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .35569 2.1855 16.013 10.713)" gradientUnits="userSpaceOnUse"><stop class="fdm2y6x_j"/><stop offset="1" class="h1ie4dmkz"/></radialGradient><radialGradient id="ieBBEMe" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 13.555 11.157)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="g7xtertqj"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="eovkc4nhj"/></radialGradient><radialGradient id="ijfZTmd" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 18.185 10.35)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="g7xtertqj"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="eovkc4nhj"/></radialGradient><linearGradient id="idrjHBQ" x1="19.3" x2="12.412" y1="18.973" y2="30.65" gradientUnits="userSpaceOnUse"><stop class="iezg62obf"/><stop offset="1" class="w444cbj2i"/></linearGradient><linearGradient id="iuscchl" x1="15.761" x2="17.294" y1="17.603" y2="18.588" gradientUnits="userSpaceOnUse"><stop offset=".177" class="w_l5294rq"/><stop offset="1" class="zif37mbje"/></linearGradient><linearGradient id="iun0Yhd" x1="20.446" x2="16.033" y1="12.222" y2="12.898" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="i9qVrnw" x1="16.199" x2="15.066" y1="11.75" y2="12.034" gradientUnits="userSpaceOnUse"><stop offset=".217" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="imi5cQO" x1="15.237" x2="15.165" y1="13.153" y2="12.682" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="imyyH5c" x1="14.749" x2="14.974" y1="10.115" y2="11.46" gradientUnits="userSpaceOnUse"><stop class="qbdqkd6lm"/><stop offset="1" class="q7izrcbfn"/></linearGradient><linearGradient id="iTaIvDb" x1="14.262" x2="14.456" y1="14.933" y2="14.037" gradientUnits="userSpaceOnUse"><stop class="i6rf6-mpl"/><stop offset="1" class="a_hi-iy3h"/></linearGradient><linearGradient id="iIMZ58d" x1="21.023" x2="9.25" y1="4.509" y2="6.312" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iIYqkwe" x1="21.352" x2="20.466" y1="9.468" y2="11.862" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="iV7oT9h" x1="9.004" x2="10.463" y1="12.089" y2="11.733" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="ihgRnHD" x1="20.323" x2="20.619" y1="9.24" y2="11.17" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><linearGradient id="iviYLGb" x1="23.345" x2="27.191" y1="24.711" y2="29.287" gradientUnits="userSpaceOnUse"><stop class="d0ocakaur"/><stop offset="1" class="u_vqqhk3b"/></linearGradient><linearGradient id="iFOnhJe" x1="9.185" x2="3.716" y1="26.681" y2="25.213" gradientUnits="userSpaceOnUse"><stop class="hbzm4jmfo"/><stop offset="1" class="hzk1ijbie"/></linearGradient><linearGradient id="iNkuCJe" x1="3.591" x2="5.404" y1="26.306" y2="26.963" gradientUnits="userSpaceOnUse"><stop class="dm21qhbor"/><stop offset="1" class="xvwmp6tlw"/></linearGradient><linearGradient id="is2KT4b" x1="9.306" x2="8.913" y1="28.699" y2="28.574" gradientUnits="userSpaceOnUse"><stop class="icorotc4i"/><stop offset="1" class="deg8fdc9j"/></linearGradient><linearGradient id="i3eqHce" x1="18.303" x2="17.643" y1="26.644" y2="27.539" gradientUnits="userSpaceOnUse"><stop offset=".175" class="pbsapybex"/><stop offset="1" class="vvwmaab9t"/></linearGradient><linearGradient id="iTPEMfa" x1="19.471" x2="19.471" y1="27.002" y2="30.369" gradientUnits="userSpaceOnUse"><stop class="di46q3nvv"/><stop offset="1" class="bhzzakkbd"/></linearGradient><linearGradient id="ixuNSNu" x1="19.599" x2="19.513" y1="26.931" y2="27.439" gradientUnits="userSpaceOnUse"><stop class="m9orc9b3r"/><stop offset="1" class="zegip2beb"/></linearGradient><linearGradient id="ilRQVue" x1="26.623" x2="27.06" y1="27.15" y2="30.869" gradientUnits="userSpaceOnUse"><stop class="xyrntivgr"/><stop offset="1" class="cjhyb2bbj"/></linearGradient><linearGradient id="iNLI2pd" x1="11.22" x2="11.074" y1="22.441" y2="19.798" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="ikHopNu" x1="12.427" x2="12.04" y1="20.632" y2="18.65" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="iLcsIIe" x1="16.154" x2="15.373" y1="18.431" y2="21.418" gradientUnits="userSpaceOnUse"><stop class="e6bcurcdv"/><stop offset="1" class="jxwnoqbqn"/></linearGradient><linearGradient id="iukmJNe" x1="15.281" x2="15.504" y1="21.637" y2="20.747" gradientUnits="userSpaceOnUse"><stop class="w_57dfb5m"/><stop offset="1" class="t78i98bfv"/></linearGradient><linearGradient id="iBmDtVH" x1="15.029" x2="13.904" y1="17.666" y2="21.994" gradientUnits="userSpaceOnUse"><stop class="nn3wh7bnm"/><stop offset="1" class="tbs366q3s"/></linearGradient><linearGradient id="ijgnmbd" x1="15.341" x2="14.232" y1="18.041" y2="17.681" gradientUnits="userSpaceOnUse"><stop class="h94nvm15h"/><stop offset="1" class="qtvy6rbzh"/></linearGradient><linearGradient id="i9aCR5c" x1="14.529" x2="13.299" y1="17.556" y2="22.306" gradientUnits="userSpaceOnUse"><stop class="qic_n_blg"/><stop offset="1" class="qh-ows9fr"/></linearGradient><linearGradient id="iBIMvkV" x1="12.625" x2="12.844" y1="21.372" y2="20.294" gradientUnits="userSpaceOnUse"><stop class="e122-lbju"/><stop offset="1" class="grqmao4rm"/></linearGradient><linearGradient id="iF4xuQc" x1="8.498" x2="9.041" y1="17.056" y2="21.556" gradientUnits="userSpaceOnUse"><stop class="fa6dpirps"/><stop offset="1" class="jplxqgtye"/></linearGradient><linearGradient id="iL6riRc" x1="16.597" x2="16.013" y1="18.931" y2="21.431" gradientUnits="userSpaceOnUse"><stop class="neym138jd"/><stop offset="1" class="kmp3a3cnr"/></linearGradient><linearGradient id="ilIle3b" x1="11.477" x2="13.758" y1="11.564" y2="11.719" gradientUnits="userSpaceOnUse"><stop class="d3bth9bgz"/><stop offset="1" class="pvzvrjbje"/></linearGradient><linearGradient id="ivaSove" x1="16.107" x2="18.388" y1="10.756" y2="10.912" gradientUnits="userSpaceOnUse"><stop class="d3bth9bgz"/><stop offset="1" class="pvzvrjbje"/></linearGradient><filter id="igZXrQb" width="11.938" height="12.844" x="9.348" y="5.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3544"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3544" result="effect2_innerShadow_4002_3544"/></filter><filter id="izaJSze" width="3.786" height="5.013" x="13.149" y="9.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3544" stdDeviation=".5"/></filter><filter id="iVSufUc" width="2.318" height="3.412" x="13.998" y="10.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3544" stdDeviation=".1"/></filter><filter id="iVxwrLV" width="2.318" height="3.412" x="13.95" y="9.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3544" stdDeviation=".1"/></filter><filter id="iXyDZId" width="3.666" height="1.739" x="13.541" y="13.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3544" stdDeviation=".05"/></filter><filter id="i6E0h8d" width="13.108" height="9.621" x="7.716" y="1.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3544"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3544" result="effect2_innerShadow_4002_3544"/></filter><filter id="iU2jtjd" width="2.439" height="1.057" x="16.071" y="7.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3544"/></filter><filter id="i5Xcslb" width="2.314" height="1.438" x="10.804" y="7.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3544"/></filter><filter id="iNMFApe" width="6.622" height="6.775" x="8.117" y="3.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3544"/><feGaussianBlur result="effect2_foregroundBlur_4002_3544" stdDeviation=".125"/></filter><filter id="ihyUIdc" width="6.825" height="5.25" x="13.786" y="3.124" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3544" stdDeviation=".125"/></filter><filter id="iyxI70p" width="1.499" height="2.393" x="8.741" y="10.639" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3544" stdDeviation=".125"/></filter><filter id="i8aEZSh" width="2.006" height="2.947" x="19.455" y="8.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3544" stdDeviation=".25"/></filter><filter id="ivSdWWd" width="2.369" height="1.394" x="10.724" y="7.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3544" stdDeviation=".125"/></filter><filter id="iujukfb" width="2.487" height=".989" x="16.01" y="7.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3544" stdDeviation=".125"/></filter><filter id="i1NOhke" width="11.192" height="8.359" x="11.542" y="22.26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.607843 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3544"/></filter><filter id="iqnI3Id" width="7.407" height="8.444" x="19.124" y="19.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3544"/></filter><filter id="i54J4Sc" width="8.208" height="4.667" x="12.492" y="25.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.678431 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3544"/></filter><filter id="i5W02Bc" width="3.456" height="1.701" x="7.457" y="22.173" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3544" stdDeviation=".1"/></filter><filter id="iFCYzqb" width="4.309" height="4.662" x="11.119" y="16.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.552941 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3544"/></filter><filter id="iKcVnem" width="3.647" height="2.753" x="6.339" y="19.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3544" stdDeviation=".05"/></filter><filter id="ivA33kd" width="2.634" height="2.141" x="16.45" y="26.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3544" stdDeviation=".125"/></filter><filter id="i4aL2ld" width="4.536" height="1" x="12.822" y="28.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3544" stdDeviation=".15"/></filter><filter id="iV8XhSL" width="3.987" height="3.987" x="10.476" y="8.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3544" stdDeviation=".325"/></filter><filter id="iEQECEb" width="3.987" height="3.987" x="15.065" y="7.897" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3544" stdDeviation=".325"/></filter><filter id="i8As3zb" width="2.323" height=".964" x="11.382" y="11.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3544" stdDeviation=".05"/></filter><filter id="ipUdzEe" width="2.323" height=".964" x="16.012" y="10.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3544" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-feeding-baby-light" /></template>
<style>
.a_hi-iy3h {
  stop-color: var(--svg-color--eab6a0, #EAB6A0);
  stop-opacity: 0;
}

.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.a6ayzxb8w {
  stop-color: var(--svg-color--289d47, #289D47);
  stop-opacity: 0;
}

.a6lmhgb8v {
  d: path("M8.933 21.299c-.314.22-.722.21-.906-.11c-.391-.948.721-1.58 1.5-1.597c1.168-.028 1.75.629 1.938 1.12c.187.493.226 1.477-.672 1.54c-.804.056-.848-.5-.98-.742c-.134-.243-.595-.411-.88-.211");
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.acgtzjb8q {
  stop-color: var(--svg-color--3ba055, #3BA055);
}

.adv7vqbml {
  d: path("M16.162 10.748c.15.14.547.37 1.062.273c.563-.106.888-.458.961-.64");
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.at1_k3rsw {
  stop-color: var(--svg-color--cf9085, #CF9085);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b-w3yacim {
  stop-color: var(--svg-color--f1c0a9, #F1C0A9);
}

.b14f1uw5k {
  d: path("M20.154 11.91q-.147-1.634-.308-3.265a1.65 1.65 0 0 1 .308 3.264");
}

.b84ow2m2e {
  stop-color: var(--svg-color--d8ab96, #D8AB96);
  stop-opacity: 0;
}

.bavmm9g-k {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.1 8.99c.231-.227.83-.655 1.618-.644");
}

.bhrasga7j {
  d: path("m11.921 20.968l-.46-.5c-.28-.3-.68-.48-1.09-.49c-.42-.01-.82.16-1.11.46l-.17.18l.53-.95c.22-.39.59-.66 1.02-.74s.88.03 1.23.3l.99.8c.33.27.38.75.12 1.09c-.21.26-.56.35-.85.24a.9.9 0 0 0-.21-.39");
}

.bhzzakkbd {
  stop-color: var(--svg-color--d4453a, #D4453A);
}

.bji58ac7a {
  stop-color: var(--svg-color--208d47, #208D47);
}

.brh-pzb_h {
  stop-color: var(--svg-color--f36716, #F36716);
  stop-opacity: 0;
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.bzi-27bxc {
  stop-color: var(--svg-color--f36716, #F36716);
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c_p6lvbtv {
  stop-color: var(--svg-color--31be7d, #31BE7D);
}

.c0o-9dcgb {
  stop-color: var(--svg-color--c78279, #C78279);
}

.c6e6dvbgn {
  stop-color: var(--svg-color--fdd3be, #FDD3BE);
}

.c8r1g2bnk {
  stop-color: var(--svg-color--148c3e, #148C3E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.c9vqjpi7e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.67 20.119c-.206.432-.32 1.448.874 2.054c1.194.607 1.993.149 2.243-.156");
}

.cbv0v1bug {
  stop-color: var(--svg-color--eab8a3, #EAB8A3);
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

.d0ocakaur {
  stop-color: var(--svg-color--ff3200, #FF3200);
}

.d3bth9bgz {
  stop-color: var(--svg-color--2d2d2d, #2D2D2D);
}

.deg8fdc9j {
  stop-color: var(--svg-color--ff451c, #FF451C);
  stop-opacity: 0;
}

.di46q3nvv {
  stop-color: var(--svg-color--ce5621, #CE5621);
}

.dkw76cbyw {
  stop-color: var(--svg-color--e1ae99, #E1AE99);
}

.dm21qhbor {
  stop-color: var(--svg-color--d46751, #D46751);
}

.dmm5ewwwm {
  stop-color: var(--svg-color--bf7875, #BF7875);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dyh_p3bsl {
  stop-color: var(--svg-color--279f64, #279F64);
}

.dzrf69sqf {
  d: path("M10.22 13.336a1.7 1.7 0 0 1-.964-.172l.144.944c.139.905.802 1.63 1.673 1.838a4.2 4.2 0 0 1-.534-1.142z");
}

.e122-lbju {
  stop-color: var(--svg-color--8b72aa, #8B72AA);
}

.e6bcurcdv {
  stop-color: var(--svg-color--6cd9f5, #6CD9F5);
}

.e9ied_q8k {
  stop-color: var(--svg-color--d9a38b, #D9A38B);
}

.ek_f7q3hx {
  stop-color: var(--svg-color--1a161e, #1A161E);
}

.em3lc9y5i {
  stop-color: var(--svg-color--fed064, #FED064);
}

.eovkc4nhj {
  stop-color: var(--svg-color--303030, #303030);
  stop-opacity: 0;
}

.eqapwmsga {
  stop-color: var(--svg-color--208d47, #208D47);
  stop-opacity: 0;
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f03q2oq4r {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.405 14.251a3.1 3.1 0 0 1-1.455-.118c-.15-.05-.275.13-.169.243a1.94 1.94 0 0 0 1.737.612a1.94 1.94 0 0 0 1.474-1.104c.067-.144-.105-.273-.233-.181a3.1 3.1 0 0 1-1.354.548Z");
}

.f1r2vnb5a {
  stop-color: var(--svg-color--dead92, #DEAD92);
  stop-opacity: 0;
}

.f9l-1bcqi {
  stop-color: var(--svg-color--daa695, #DAA695);
}

.fa6dpirps {
  stop-color: var(--svg-color--dbaa8f, #DBAA8F);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fdm2y6x_j {
  stop-color: var(--svg-color--070509, #070509);
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.fo4qq4q_b {
  stop-color: var(--svg-color--289d47, #289D47);
}

.frn5ss_le {
  stop-color: var(--svg-color--cf9085, #CF9085);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fu3c0cblo {
  stop-color: var(--svg-color--f38820, #F38820);
}

.fvf9v11lh {
  d: path("m19.876 8.123l-.128-.635c-.13-.772-.867-1.313-1.646-1.227l-1.42.217a2.48 2.48 0 0 1-2.348-.947s-.09-.144-.197-.396c-.39-.924.413-1.796 1.415-1.76c1.027.037 2.223.196 3.15.617c1.946.883 1.955 3.01 1.174 4.131");
}

.fvv81lbxu {
  stop-color: var(--svg-color--cf6e63, #CF6E63);
}

.fx1nlcbbg {
  cx: 17.059px;
  cy: 9.891px;
  r: 1.344px;
}

.g3hnripfm {
  fill: var(--svg-color--202020, #202020);
  d: path("M11.018 8.712a2.85 2.85 0 0 1 1.707-.634a.284.284 0 0 1 .017.568a2.28 2.28 0 0 0-1.362.504a1 1 0 0 0-.083.075l-.003.003a.284.284 0 0 1-.412-.392z");
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.g7xtertqj {
  stop-color: var(--svg-color--303030, #303030);
}

.gfuj0ibqm {
  stop-color: var(--svg-color--1e191c, #1E191C);
}

.gljb9qb7i {
  fill: var(--svg-color--eabba1, #EABBA1);
  d: path("M10.175 16.83c.356.125.482.33.516.453l.445.39l2.292.362a.92.92 0 0 0 1.061-.871a.913.913 0 0 0-.922-.95c-1.174.013-2.687.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.gmelrdffb {
  stop-color: var(--svg-color--ff8040, #FF8040);
}

.grqmao4rm {
  stop-color: var(--svg-color--b59cc2, #B59CC2);
  stop-opacity: 0;
}

.gwqqnwbju {
  d: path("m12.243 16.834l2.635.734c.357.104.645.406.522.797l-.78 2.704c-.095.329-.442.504-.851.393l-2.6-.733z");
}

.h0yn0repu {
  d: path("M10.29 22.056c-.283.88-1.448 1.292-2.6.92c-1.152-.371-1.792-1.177-1.572-2.266c.18-.888.883-1.75 2.738-1.24c1.152.372 1.718 1.706 1.434 2.586");
}

.h1ie4dmkz {
  stop-color: var(--svg-color--131212, #131212);
}

.h94nvm15h {
  stop-color: var(--svg-color--43b1db, #43B1DB);
}

.habp5x92o {
  stroke: var(--svg-color--efc6b6, #EFC6B6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m16.95 26.66l1.635 1.14");
}

.hbzm4jmfo {
  stop-color: var(--svg-color--f54c3c, #F54C3C);
}

.hkdvptb3z {
  cx: 12.47px;
  cy: 10.619px;
  r: 1.344px;
}

.hmgh32r7m {
  stop-color: var(--svg-color--cc9098, #CC9098);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.ht0yexaec {
  d: path("M10.493 14.867a4.02 4.02 0 0 0 4.468 2.85l1.913-.293a4.016 4.016 0 0 0 3.411-4.057c-.173-1.928-.344-3.849-.547-5.771a1.487 1.487 0 0 0-1.62-1.238l-1.42.217a2.49 2.49 0 0 1-2.467-1.119a.68.68 0 0 0-.689-.329l-1.29.198c-1.872.287-3.153 2.052-2.863 3.945c.289 1.886.69 3.724 1.104 5.597");
}

.hv19zn7up {
  d: path("M9.746 17.751c.243.25.33.526.343.633l.485.469l2.341.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.775-1.078c-1.09-.133-2.42-.306-2.779-.347c-.613-.07-.945.297-.64.61");
}

.hwhva5kss {
  fill: var(--svg-color--202020, #202020);
  d: path("M18.278 7.713c-.202-.127-.433-.26-.761-.31c-.324-.05-.714-.017-1.238.13a.284.284 0 1 0 .153.548c.479-.134.783-.149.998-.116c.21.033.362.114.543.229a.284.284 0 0 0 .305-.48");
}

.hzk1ijbie {
  stop-color: var(--svg-color--e2492a, #E2492A);
}

.i2e83jb8g {
  stop-color: var(--svg-color--c28485, #C28485);
}

.i5de26xkm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.i6m3xbfso {
  stop-color: var(--svg-color--c58788, #C58788);
}

.i6rf6-mpl {
  stop-color: var(--svg-color--eab6a0, #EAB6A0);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.ib26drc1k {
  stop-color: var(--svg-color--cc9098, #CC9098);
  stop-opacity: 0;
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

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.ijbc0g1go {
  d: path("M21.651 24.308a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.ijdg6fbam {
  stop-color: var(--svg-color--fc4a51, #FC4A51);
}

.iqt-sufrb {
  fill: var(--svg-color--e1b0a4, #E1B0A4);
  d: path("M17.256 26.051a.937.937 0 0 0-1.12 1.498l.931.802a.1.1 0 0 1-.063.175l-3.643.072a.886.886 0 0 0 .017 1.771h6.06v-1l1.062-1.227z");
}

.iy8y9zu4h {
  stop-color: var(--svg-color--c68882, #C68882);
  stop-opacity: 0;
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.j903jcckb {
  d: path("M20.692 26.146c1.597-.23 4.566-.809 6.543-1.27c1.522-.263 2.64 1.204 2.64 2.781c0 1.372-1.022 2.237-1.746 2.619a.86.86 0 0 1-.404.093h-8.014v-3.086c0-.797.281-1 .98-1.137");
}

.jase_0f7h {
  stop-color: var(--svg-color--88014e, #88014E);
}

.jbfk2nbof {
  d: path("M17.256 26.051a.937.937 0 0 0-1.12 1.498l.931.802a.1.1 0 0 1-.063.175l-3.643.072a.886.886 0 0 0 .017 1.771h6.06v-1l1.062-1.227z");
}

.jj_i0ybwk {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
  stop-opacity: 0;
}

.jplxqgtye {
  stop-color: var(--svg-color--c98e84, #C98E84);
}

.jxwnoqbqn {
  stop-color: var(--svg-color--3782ce, #3782CE);
}

.k_pdrlblj {
  stop-color: var(--svg-color--ebb830, #EBB830);
  stop-opacity: 0;
}

.k02zgtbsb {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.123 7.867c-.29-.147-.99-.377-1.738-.13");
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

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.kyl8adb5j {
  stop-color: var(--svg-color--148c3e, #148C3E);
  stop-opacity: 0;
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.l8v5z5bog {
  stop-color: var(--svg-color--6e574e, #6E574E);
}

.lgestwbng {
  d: path("M11.49 11.288c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34c-.19-.14-.11-.43.11-.47");
}

.ll6ec2bpd {
  stop-color: var(--svg-color--6e574e, #6E574E);
  stop-opacity: 0;
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lrbywkbvr {
  stop-color: var(--svg-color--e0ae97, #E0AE97);
  stop-opacity: 0;
}

.lwayml7-v {
  d: path("M18.846 3.825c.55.1 1.073.393 1.449.87c.6.759.683 1.765.284 2.577a1.6 1.6 0 0 0-.138.928l.184 1.205a1.8 1.8 0 0 0-.718-.168l-.17-1.641a1.487 1.487 0 0 0-1.62-1.238l-1.42.217a2.49 2.49 0 0 1-2.466-1.12a.68.68 0 0 0-.689-.328l-1.29.198C10.38 5.61 9.099 7.377 9.389 9.27l.27 1.554a1.76 1.76 0 0 0-.69.379l-.186-1.217a1.6 1.6 0 0 0-.41-.845a2.45 2.45 0 0 1-.525-2.457c.21-.606.628-1.07 1.142-1.344A2.75 2.75 0 0 0 10.222 4a2.385 2.385 0 0 1 2.789-1.374c.413.11.848.043 1.21-.185c.266-.163.567-.282.895-.332a2.38 2.38 0 0 1 2.193.839c.39.468.937.769 1.537.877");
}

.lwjfgzbrh {
  d: path("m12.015 16.403l3.172.884c.43.125.744.558.627.96l-.899 3.085c-.115.397-.533.607-1.025.474l-3.129-.883z");
}

.lwl1xgbup {
  stop-color: var(--svg-color--d25e22, #D25E22);
}

.m1_omrdxn {
  stop-color: var(--svg-color--fccfbe, #FCCFBE);
  stop-opacity: 0;
}

.m9orc9b3r {
  stop-color: var(--svg-color--ae4614, #AE4614);
}

.ma300385g {
  fill: var(--svg-color--23181c, #23181C);
  d: path("M14.32 5.585a3 3 0 0 1-.088-.128a.68.68 0 0 0-.69-.329l-1.29.198C10.381 5.612 9.1 7.378 9.39 9.27l.043.28c-.385-.21-.903-.697-1.04-1.593c-.167-1.086.541-1.757.993-2.185c.128-.12.235-.222.296-.308l.085-.122c.297-.43.826-1.196 1.884-1.658a5.6 5.6 0 0 1 1.523-.404c.47-.058.86.295.932.762l.234 1.526z");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mql7c3hze {
  stop-color: var(--svg-color--fccfbe, #FCCFBE);
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.n0p5sxbec {
  stop-color: var(--svg-color--dda891, #DDA891);
}

.n4s665bvu {
  fill: var(--svg-color--eabaa2, #EABAA2);
  d: path("M9.746 17.751c.243.25.33.526.343.633l.485.469l2.341.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.775-1.078c-1.09-.133-2.42-.306-2.779-.347c-.613-.07-.945.297-.64.61");
}

.n8jici3hn {
  stop-color: var(--svg-color--fed466, #FED466);
  stop-opacity: 0;
}

.neym138jd {
  stop-color: var(--svg-color--f3c22a, #F3C22A);
}

.nf5zrsbwk {
  d: path("M19.075 27.152a.15.15 0 0 1 .15-.15h.642v3.367h-.793z");
}

.njdbcpw8w {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
}

.nn3wh7bnm {
  stop-color: var(--svg-color--58d4f5, #58D4F5);
}

.nsooqoy6p {
  stop-color: var(--svg-color--ffd8ba, #FFD8BA);
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.o-xm8fsgg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.857 23.4c.578.142 1.919.173 2.656-.827");
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o5s768wpb {
  fill: var(--svg-color--dda894, #DDA894);
  d: path("m14.457 10.65l-.254 1.945c-.05.4.272.744.646.686l.797-.122c.374-.057.578-.487.41-.847l-.824-1.782c-.178-.395-.717-.312-.775.12");
}

.o7lrx416s {
  stop-color: var(--svg-color--e5b19d, #E5B19D);
  stop-opacity: 0;
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oaig2cbln {
  stop-color: var(--svg-color--564943, #564943);
}

.oh8on9brk {
  stop-color: var(--svg-color--eebfa5, #EEBFA5);
}

.olt1cqbej {
  d: path("M20.078 11.826c.338-.063.64-.227.87-.453l.144.944a2.23 2.23 0 0 1-1.046 2.255q.175-.593.168-1.25z");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz48wlb0n {
  stroke: var(--svg-color--eebdb1, #EEBDB1);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.323 29.465h3.535");
}

.p6g1y959n {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m14.467 10.845l-.313 1.956c-.044.399.26.745.608.691l.742-.113c.348-.053.534-.48.374-.842l-.787-1.787c-.17-.397-.574-.335-.624.095");
}

.p6n8nbb9p {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
  stop-opacity: 0;
}

.pbsapybex {
  stop-color: var(--svg-color--e4c0a9, #E4C0A9);
}

.pdon63boo {
  stop-color: var(--svg-color--f38820, #F38820);
  stop-opacity: 0;
}

.ph2kohtod {
  stop-color: var(--svg-color--ebbba3, #EBBBA3);
  stop-opacity: 0;
}

.phzm4snim {
  stop-color: var(--svg-color--ce6122, #CE6122);
}

.pvzvrjbje {
  stop-color: var(--svg-color--2d2d2d, #2D2D2D);
  stop-opacity: 0;
}

.q1j_wqbdw {
  d: path("m14.409 10.484l-.254 1.946c-.05.4.272.744.646.686l.797-.122c.374-.057.578-.487.41-.847l-.824-1.782c-.179-.395-.717-.312-.775.119");
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.q4weiw-ee {
  stop-color: var(--svg-color--dda891, #DDA891);
  stop-opacity: 0;
}

.q6_clrwlc {
  d: path("m15.606 18.234l.554.16a.15.15 0 0 1 .103.185l-.783 2.73a.15.15 0 0 1-.186.103l-.555-.16z");
}

.q7izrcbfn {
  stop-color: var(--svg-color--e5b69d, #E5B69D);
  stop-opacity: 0;
}

.qbdqkd6lm {
  stop-color: var(--svg-color--e5b69d, #E5B69D);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qh-ows9fr {
  stop-color: var(--svg-color--a07cb6, #A07CB6);
}

.qic_n_blg {
  stop-color: var(--svg-color--d2c9d1, #D2C9D1);
}

.qtvy6rbzh {
  stop-color: var(--svg-color--42b8e0, #42B8E0);
}

.r-plr9ycy {
  d: path("M20.139 11.243q-.089-.974-.184-1.947a.98.98 0 0 1 .184 1.947");
}

.r1y6vkpka {
  stop-color: var(--svg-color--b42c01, #B42C01);
}

.r3idh6bhh {
  stop-color: var(--svg-color--d9a38b, #D9A38B);
  stop-opacity: 0;
}

.r6dyzpbfo {
  stop-color: var(--svg-color--a62302, #A62302);
  stop-opacity: 0;
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.r8zbsj1bq {
  d: path("m2.277 30.369l2.93-9.156c.352-1.414 2.07-2.104 3.65-1.614s2.49 2.332 2.006 3.692l-2.216 7.078z");
}

.rfh9ucc-q {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m19.876 8.123l-.128-.635c-.13-.772-.867-1.313-1.646-1.227l-1.42.217a2.48 2.48 0 0 1-2.348-.947s-.09-.144-.197-.396c-.39-.924.413-1.796 1.415-1.76c1.027.037 2.223.196 3.15.617c1.946.883 1.955 3.01 1.174 4.131");
}

.rqsfe0bvs {
  stop-color: var(--svg-color--d9a48d, #D9A48D);
}

.ru8e28bju {
  d: path("M15.405 14.251a3.1 3.1 0 0 1-1.455-.118c-.15-.05-.275.13-.169.243a1.94 1.94 0 0 0 1.737.612a1.94 1.94 0 0 0 1.474-1.104c.067-.144-.105-.273-.233-.181a3.1 3.1 0 0 1-1.354.548");
}

.sghoc4brb {
  stop-color: var(--svg-color--ce9989, #CE9989);
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

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.t5ovicbrp {
  stop-color: var(--svg-color--c28485, #C28485);
  stop-opacity: 0;
}

.t78i98bfv {
  stop-color: var(--svg-color--735caf, #735CAF);
  stop-opacity: 0;
}

.tbs366q3s {
  stop-color: var(--svg-color--4760c0, #4760C0);
}

.tomvu1bgl {
  stop-color: var(--svg-color--78e0ff, #78E0FF);
}

.trma59b_r {
  stop-color: var(--svg-color--d1623d, #D1623D);
  stop-opacity: 0;
}

.tv0y_es3w {
  stop-color: var(--svg-color--d8ab96, #D8AB96);
}

.twkrvc03o {
  stop-color: var(--svg-color--c24713, #C24713);
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

.u2k5px3jq {
  stop-color: var(--svg-color--c38486, #C38486);
  stop-opacity: 0;
}

.u5rcmp2fi {
  d: path("M11.532 11.555c.15.14.547.37 1.062.274c.563-.107.888-.459.96-.641");
}

.u9db7sbld {
  stop-color: var(--svg-color--f5c8b4, #F5C8B4);
}

.ugbytbngn {
  stop-color: var(--svg-color--ffd267, #FFD267);
  stop-opacity: 0;
}

.ukk2wlbxt {
  d: path("m15.53 21.134l.227.069a.5.5 0 0 0 .492-.12l.364-.353a.13.13 0 0 1 .128-.033l.314.084a.484.484 0 0 0 .253-.935l-.303-.083a.13.13 0 0 1-.098-.109l-.069-.44a.5.5 0 0 0-.36-.403l-.26-.072z");
}

.ulc1d0bsf {
  stop-color: var(--svg-color--e9b8a1, #E9B8A1);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.ur81h3fis {
  d: path("M9.553 10.212a1.66 1.66 0 0 0-1.164 1.832a1.65 1.65 0 0 0 1.791 1.393a80 80 0 0 1-.627-3.225");
}

.urjmhobql {
  stop-color: var(--svg-color--e0ae97, #E0AE97);
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uz8nvn0bw {
  stop-color: var(--svg-color--ff8a47, #FF8A47);
  stop-opacity: 0;
}

.v_jz0vies {
  stop-color: var(--svg-color--ffc8ac, #FFC8AC);
}

.v2wkn2ras {
  stop-color: var(--svg-color--31ae6a, #31AE6A);
}

.v3ok2mbfm {
  stop-color: var(--svg-color--c07e7e, #C07E7E);
  stop-opacity: 0;
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vcmkf2bkc {
  d: path("M16.12 10.478c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34a.263.263 0 0 1 .11-.47");
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.vrhur_iwf {
  d: path("M8.597 18.85a.28.28 0 0 1 .133-.27c.981-.69 2.005-.305 2.383 0c.305.235 1 .789 1.363 1.082c.446.36.372.96.043 1.316c-.276.298-.751.241-.93.149l-2.097-1.313c-.055-.312-.235-.562-.48-.637c-.247-.074-.403-.132-.415-.328");
}

.vvwmaab9t {
  stop-color: var(--svg-color--e4c0a9, #E4C0A9);
  stop-opacity: 0;
}

.w_57dfb5m {
  stop-color: var(--svg-color--735caf, #735CAF);
}

.w_l5294rq {
  stop-color: var(--svg-color--d97b6e, #D97B6E);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.w444cbj2i {
  stop-color: var(--svg-color--fa362a, #FA362A);
}

.wbjdhzrgj {
  d: path("M14.32 5.585a3 3 0 0 1-.088-.128a.68.68 0 0 0-.69-.329l-1.29.198C10.381 5.612 9.1 7.378 9.39 9.27l.043.28c-.385-.21-.903-.697-1.04-1.593c-.167-1.086.541-1.757.993-2.185c.128-.12.235-.222.296-.308l.085-.122c.297-.43.826-1.196 1.884-1.658a5.6 5.6 0 0 1 1.523-.404c.47-.058.86.295.932.762l.234 1.526z");
}

.wdwsowbvt {
  stop-color: var(--svg-color--c68882, #C68882);
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wopza1bkm {
  d: path("m14.902 17.466l-2.636-.734l-1.073 3.895l2.6.734c.408.11.755-.065.851-.394l.78-2.703c.122-.391-.165-.694-.522-.798");
}

.wr0a1jdsz {
  d: path("M10.175 16.83c.356.125.482.33.516.453l.445.39l2.292.362a.92.92 0 0 0 1.061-.871a.913.913 0 0 0-.922-.95c-1.174.013-2.687.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.wvohhnbma {
  stop-color: var(--svg-color--d69c87, #D69C87);
}

.wyqcze2zy {
  stop-color: var(--svg-color--a62302, #A62302);
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x_o33sb8c {
  d: path("M15.761 18.899c1.06 0 1.91-.86 1.91-1.91v-2.26a1.91 1.91 0 1 0-3.82 0v2.26c-.01 1.06.85 1.91 1.91 1.91");
}

.x0n4s-bkb {
  stop-color: var(--svg-color--ffdfbf, #FFDFBF);
}

.xdt63zb6q {
  stop-color: var(--svg-color--dba48c, #DBA48C);
  stop-opacity: 0;
}

.xj42tacwz {
  stop-color: var(--svg-color--cf6e63, #CF6E63);
  stop-opacity: 0;
}

.xldtbyboa {
  d: path("M21.911 24.389c-1.17-2.04-3.78-2.73-5.81-1.56l-2.43 1.4c-2.04 1.17-2.73 3.78-1.56 5.81l.21.33h7.73l.3-.18a4.23 4.23 0 0 0 1.56-5.8");
}

.xohjverxe {
  stop-color: var(--svg-color--ce9989, #CE9989);
}

.xrzwqzb7j {
  stop-color: var(--svg-color--b42c01, #B42C01);
  stop-opacity: 0;
}

.xsgkrbcbf {
  stop-color: var(--svg-color--313131, #313131);
}

.xt0e5dbpd {
  d: path("M23.77 27.499a4.3 4.3 0 1 0 .001-8.6a4.3 4.3 0 0 0 0 8.6");
}

.xvwmp6tlw {
  stop-color: var(--svg-color--e6422d, #E6422D);
  stop-opacity: 0;
}

.xyrntivgr {
  stop-color: var(--svg-color--ff7c1e, #FF7C1E);
}

.xzsnre4ka {
  d: path("M7.231 30.368c-1.05 0-1.9-.85-1.89-1.9l.01-2.13c0-5.77 4.79-10.46 10.69-10.46c5.91 0 10.69 4.68 10.69 10.46l.17 4.03z");
}

.y-w2tsblc {
  stop-color: var(--svg-color--dba48c, #DBA48C);
}

.y1n-51biq {
  d: path("M8.207 17.61c1.03-1.085 1.919-1.369 2.32-1.374l.797.867l-.93 3.516c-.18.315-.564.996-.695 1.152c-.164.195-.735.63-1.766.238c-.887-.337-1.15-.898-1.176-1.148c.234-1.168.65-2.358 1.45-3.25");
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yqjzu1_0l {
  d: path("M10.641 18.938c-.28.05-.54.19-.74.38c.01-.05.02-.1.04-.15l.12-.33c.28-.78 1.09-1.27 1.91-1.15l1.66.23c.42.06.72.45.66.87s-.45.72-.87.66l-1.57-.22c-.34-.26-.78-.37-1.21-.29");
}

.yt2biebrs {
  d: path("M9.613 10.889a.98.98 0 0 0 .377 1.892q-.2-.945-.377-1.892");
}

.yxmxw0ard {
  stop-color: var(--svg-color--32996b, #32996B);
}

.yyz6uvb9t {
  d: path("m14.457 10.65l-.254 1.945c-.05.4.272.744.646.686l.797-.122c.374-.057.578-.487.41-.847l-.824-1.782c-.178-.395-.717-.312-.775.12");
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z3zsa5bpu {
  stop-color: var(--svg-color--53f595, #53F595);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.z6zfulbza {
  stop-color: var(--svg-color--c07e7e, #C07E7E);
}

.zegip2beb {
  stop-color: var(--svg-color--ae4614, #AE4614);
  stop-opacity: 0;
}

.zh5j4o24i {
  d: path("m29.221 25.709l-4.94-6.05l-3.16 8.57z");
}

.zif37mbje {
  stop-color: var(--svg-color--ffb597, #FFB597);
}

.zmq4c2bxg {
  stop-color: var(--svg-color--d1623d, #D1623D);
}

.zn-qjxbde {
  stop-color: var(--svg-color--86004d, #86004D);
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

</style>
