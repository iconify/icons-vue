<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":33};
const content = `<g class="ft5dv1b6b"><path fill="url(#iPaaoii)" class="vh_un0b_u"/><path fill="url(#iVPi7dc)" class="o2f2ovuoo"/><path fill="url(#iUq2R3c)" class="zavprx2nu"/><path fill="url(#iqLOV6d)" class="s4zv63nni"/><g filter="url(#ikxS1AS)"><path fill="url(#id34Ikg)" class="a2zze1bcp"/></g><path fill="url(#iAe2jic)" class="a2zze1bcp"/><path fill="url(#i5g8Lqd)" class="a2zze1bcp"/><path fill="url(#imoWkvc)" class="a2zze1bcp"/><path fill="url(#ic4Wuzc)" class="a2zze1bcp"/><path fill="url(#iAOnbGd)" class="a2zze1bcp"/><path fill="url(#iFSLVkb)" class="a2zze1bcp"/><path fill="url(#iDrMn9c)" class="a2zze1bcp"/><g filter="url(#iX9YvFc)"><path class="t7yh0hf_x"/></g><g filter="url(#iwmI9Gb)"><path class="p0ldlzgkt"/><path fill="url(#ijyBVpb)" class="ltqrzdb7q"/><path fill="url(#i9GREbd)" class="ltqrzdb7q"/><path fill="url(#ikoMMvu)" class="ltqrzdb7q"/><path fill="url(#idwdr6b)" class="ltqrzdb7q"/><path fill="url(#iWe0AKc)" class="ltqrzdb7q"/></g><g filter="url(#i5FSYpe)"><path stroke="url(#iqoBVDb)" class="o92m3lbae"/></g><path fill="url(#i2dVUAc)" class="aaacne_5z"/><g filter="url(#ioXbXuc)"><path fill="url(#iSVMlad)" class="mt97pnhfa"/><path fill="url(#iMfPE1d)" class="mt97pnhfa"/><path fill="url(#iIbfGqH)" class="mt97pnhfa"/><path fill="url(#ihs4yJb)" class="mt97pnhfa"/><path fill="url(#iXCLxte)" class="mt97pnhfa"/></g><g filter="url(#io0osDd)"><path class="bncj6nbye"/><path fill="url(#iM3V6Yc)" class="m85_zobye"/><path fill="url(#i6NIi9d)" class="m85_zobye"/></g><g filter="url(#ipHWFjd)"><path class="bowq5ib2o"/><path fill="url(#icRTiBd)" class="jlllnebdx"/></g><path fill="url(#ie3Jprd)" class="pmmbaet1b"/><path fill="url(#iDMInre)" class="pmmbaet1b"/><path fill="url(#ijeR7qc)" class="pmmbaet1b"/><path fill="url(#i1mlk2D)" class="pmmbaet1b"/><path fill="url(#i3BrvEc)" class="vfpz3nzlh"/><path fill="url(#iibYTyd)" class="vfpz3nzlh"/><g filter="url(#iGkClhd)"><path fill="url(#ieAVCDe)" class="mqatnwb7r"/></g><g filter="url(#iNDLbte)"><path fill="url(#i2M0T0c)" class="j52o6nbeg"/></g><g filter="url(#iTYrG0c)"><path class="ysxrm4uyy"/></g><path fill="url(#ixRQl3b)" class="j8sdcok6a"/><path fill="url(#i8sLyyb)" class="lxxjtjbpr"/><path fill="url(#iP5SDed)" class="lxxjtjbpr"/><path fill="url(#iPVhE2b)" class="lxxjtjbpr"/><path fill="url(#iyJyfOb)" class="lxxjtjbpr"/><path fill="url(#iR8Uple)" class="lxxjtjbpr"/><path fill="url(#iYTyuSE)" class="lxxjtjbpr"/><g filter="url(#i3i60Ic)"><path fill="url(#i6mnT5d)" class="e0wfhpbyy"/><path fill="url(#iOIN71d)" class="e0wfhpbyy"/><path fill="url(#i2HPEoe)" class="e0wfhpbyy"/></g><path fill="url(#iDR3kZD)" class="aefwo3bed"/><path fill="url(#icTp73d)" class="aefwo3bed"/><g filter="url(#iPs8CjL)"><path fill="url(#i1DFwqL)" class="kz3e_kwhy"/><path fill="url(#iSFPiYc)" class="kz3e_kwhy"/></g><g filter="url(#iyUQ0zd)"><path class="x2mvaybuj"/><path fill="url(#iZb1Lgc)" class="d9k92hb3z"/><path fill="url(#ipwGezd)" class="d9k92hb3z"/></g><path fill="url(#ibxTEIb)" class="lnnq9g1hs"/><path fill="url(#ilaPNnd)" class="lnnq9g1hs"/><path fill="url(#idjZzid)" class="xj3lonb_s"/><path fill="url(#ievnUXb)" class="xj3lonb_s"/><path fill="url(#i66omkb)" class="roydk-c2b"/><path fill="url(#iKSUY7c)" class="roydk-c2b"/><path fill="url(#iUVgkrd)" class="roydk-c2b"/><path fill="url(#iuMykle)" class="roydk-c2b"/><path fill="url(#iDuIIFc)" class="ib-e97gvn"/><path fill="url(#iHMXBic)" class="przuo7bga"/><path fill="url(#idqxSZc)" class="u69m9xb2c"/><path fill="url(#iiSxGFy)" class="u69m9xb2c"/><path fill="url(#iYPdkQe)" class="u69m9xb2c"/><g filter="url(#iI4quKd)"><path stroke="url(#iU7vAuc)" class="geget3s5f"/></g><path fill="url(#iWduF6v)" class="cvt9shbtj"/><path fill="url(#i8k3Wqe)" class="cvt9shbtj"/><path fill="url(#i0qroLc)" class="tuyve8bzg"/><g filter="url(#iIt82qc)"><path fill="url(#iVCSyye)" class="cl8z70zew"/><path fill="url(#iCwIi4d)" class="cl8z70zew"/><path fill="url(#iq71JBe)" class="cl8z70zew"/></g><path fill="url(#iAo5VBc)" class="xtufuib5k"/><path fill="url(#ixkd2Cb)" class="xtufuib5k"/><path fill="url(#iaaEahw)" class="xtufuib5k"/><path fill="url(#icxe0wd)" class="xtufuib5k"/><path class="w_w1tbavy"/><path fill="url(#iY91F1p)" class="cfvk8yscg"/><path fill="url(#i65YnOb)" class="cfvk8yscg"/><path class="d5t3hz92z"/><path fill="url(#iJHBi3d)" class="xxns0gg4i"/><path fill="url(#iHqACud)" class="xxns0gg4i"/><path fill="url(#ivLB7Oc)" class="xxns0gg4i"/><path fill="url(#iDqehLe)" class="pfahw7jhf"/><path fill="url(#i8xTvzg)" class="pfahw7jhf"/><path fill="url(#ifAfAec)" class="pfahw7jhf"/><path fill="url(#iyBiJTd)" class="jswkgxfop"/><path fill="url(#iKYBiLe)" class="jswkgxfop"/><path fill="url(#ika6Zbc)" class="jswkgxfop"/><path fill="url(#izhm4Uc)" class="ymw0zacdj"/><path fill="url(#iPvypgc)" class="ymw0zacdj"/><path fill="url(#i2vvPlf)" class="ymw0zacdj"/><path fill="url(#iJ9m1ti)" class="ymw0zacdj"/><g filter="url(#iNpfACc)"><path stroke="url(#iAkvLKb)" class="a81w0ygfz"/></g><g filter="url(#iKPUCUQ)"><path class="zrz4nworg"/></g><g filter="url(#izTtryc)"><path class="lsy8a_brx"/></g><g filter="url(#ie0RlDB)"><circle fill="url(#iOxTq1G)" class="ky0z_lbmb"/></g><g filter="url(#ikIlrBc)"><circle fill="url(#iYKNuLe)" class="jixqgub8x"/></g><g filter="url(#itIdX0d)"><path class="pn8w7jbzs"/></g><g filter="url(#i5H89kp)"><path class="x-qk2z5ts"/></g><path fill="url(#iWPCbxc)" class="d3zgybcsf"/><path fill="url(#ivu8Krd)" class="m19b90bbg"/><g filter="url(#iYLxEAO)" class="i5de26xkm"><path stroke="url(#iwigpTc)" class="c29p3sb0d"/><path stroke="url(#i5OmMBe)" class="c29p3sb0d"/></g><g filter="url(#i5vjhFc)" class="i5de26xkm"><path stroke="url(#iEzbmIH)" class="b2nqurbhe"/><path stroke="url(#ibmysNx)" class="b2nqurbhe"/></g><g filter="url(#iRyTN2b)" class="mc2zb0bvp"><path class="t8_8lcczx"/></g><g filter="url(#i9OLxzb)" class="mc2zb0bvp"><path class="t84wefbqx"/></g><defs><radialGradient id="iUq2R3c" cx="0" cy="0" r="1" gradientTransform="matrix(1.1072 1.88468 -2.23885 1.31526 19.772 11.782)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iqLOV6d" cx="0" cy="0" r="1" gradientTransform="matrix(1.5577 .20113 -.6205 4.80562 9.058 14.194)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="id34Ikg" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22338 .92949 -1.64425 -9.2401 17.66 11.187)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="i5g8Lqd" cx="0" cy="0" r="1" gradientTransform="matrix(1.18748 12.59464 -10.42984 .98338 15.383 5.497)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="imoWkvc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.39336 2.0464 -5.2275 -21.44084 18.46 12.063)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="ic4Wuzc" cx="0" cy="0" r="1" gradientTransform="rotate(-43.122 14.86 -6.742)scale(4.93037 1.80486)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iAOnbGd" cx="0" cy="0" r="1" gradientTransform="matrix(.20958 2.53702 -1.01416 .08378 19.876 7.786)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iFSLVkb" cx="0" cy="0" r="1" gradientTransform="rotate(111.069 6.042 8.766)scale(3.41898 2.82265)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="i9GREbd" cx="0" cy="0" r="1" gradientTransform="matrix(.0434 .2439 -.7665 .1364 15.563 12.963)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="idwdr6b" cx="0" cy="0" r="1" gradientTransform="rotate(145.279 5.855 8.621)scale(1.69824 2.72921)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="i2dVUAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.12814 -.72012 2.89723 -.51555 15.484 15.223)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="iMfPE1d" cx="0" cy="0" r="1" gradientTransform="matrix(-.62252 -3.49833 8.84687 -1.57428 9.115 9.727)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iIbfGqH" cx="0" cy="0" r="1" gradientTransform="matrix(-.33277 -2.53067 4.48385 -.58961 19.43 9.242)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="ihs4yJb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.63265 -1.1307 .82999 -1.9325 17.56 3.105)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iXCLxte" cx="0" cy="0" r="1" gradientTransform="matrix(1.16659 1.3128 -3.03984 2.70127 12.27 2.405)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iM3V6Yc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.19924 .39135 -.14524 -.81622 13.83 4.456)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="i6NIi9d" cx="0" cy="0" r="1" gradientTransform="matrix(2.30948 -5.66326 6.2743 2.55867 8.85 9.406)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="icRTiBd" cx="0" cy="0" r="1" gradientTransform="matrix(3.31294 -.19818 .08297 1.38706 15.738 6.526)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iDMInre" cx="0" cy="0" r="1" gradientTransform="matrix(1.02685 2.1296 -2.0318 .9797 19.308 9.964)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="ijeR7qc" cx="0" cy="0" r="1" gradientTransform="rotate(-64.01 18.238 -10.59)scale(1.35753 1.13788)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="i1mlk2D" cx="0" cy="0" r="1" gradientTransform="rotate(-79.353 16.342 -6.702)scale(1.68242 2.24795)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iibYTyd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0434 2.14765 -2.11134 -.04267 9.465 11.888)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="ieAVCDe" cx="0" cy="0" r="1" gradientTransform="matrix(-.88773 .32011 -.14119 -.39154 9.898 12.302)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="iPVhE2b" cx="0" cy="0" r="1" gradientTransform="matrix(.21875 3.1875 -3.62585 .24883 8.716 21.3)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="bzi-27bxc"/><stop offset="1" class="brh-pzb_h"/></radialGradient><radialGradient id="iyJyfOb" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 3.4375 -2.71722 -.59285 6.466 20.018)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="lwl1xgbup"/><stop offset="1" class="kar3bi73q"/></radialGradient><radialGradient id="iR8Uple" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15508 -.34883 1.8893 -6.25609 8.673 30.674)" gradientUnits="userSpaceOnUse"><stop class="ijdg6fbam"/><stop offset="1" class="sjvismp2t"/></radialGradient><radialGradient id="i6mnT5d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0785 6 -4.46735 -1.54757 17.013 25.455)" gradientUnits="userSpaceOnUse"><stop class="v2wkn2ras"/><stop offset="1" class="yxmxw0ard"/></radialGradient><radialGradient id="iOIN71d" cx="0" cy="0" r="1" gradientTransform="rotate(-132.901 15.046 10.465)scale(4.22338 6.72611)" gradientUnits="userSpaceOnUse"><stop class="bji58ac7a"/><stop offset="1" class="eqapwmsga"/></radialGradient><radialGradient id="i2HPEoe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62501 -3.8277 2.0945 -1.4364 21.185 26.392)" gradientUnits="userSpaceOnUse"><stop offset=".393" class="c8r1g2bnk"/><stop offset="1" class="kyl8adb5j"/></radialGradient><radialGradient id="iDR3kZD" cx="0" cy="0" r="1" gradientTransform="matrix(-5.34372 2.81254 -2.95164 -5.608 26.403 21.737)" gradientUnits="userSpaceOnUse"><stop class="z3zsa5bpu"/><stop offset="1" class="c_p6lvbtv"/></radialGradient><radialGradient id="i1DFwqL" cx="0" cy="0" r="1" gradientTransform="rotate(164.954 9.052 13.064)scale(3.00943 4.47011)" gradientUnits="userSpaceOnUse"><stop class="dyh_p3bsl"/><stop offset="1" class="acgtzjb8q"/></radialGradient><radialGradient id="iSFPiYc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66156 -1.3125 1.73451 -2.1958 22.878 26.174)" gradientUnits="userSpaceOnUse"><stop class="fo4qq4q_b"/><stop offset="1" class="a6ayzxb8w"/></radialGradient><radialGradient id="iZb1Lgc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -5.73004 19.34 29.612)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="bamcey7be"/><stop offset="1" class="a-744r8ne"/></radialGradient><radialGradient id="ipwGezd" cx="0" cy="0" r="1" gradientTransform="rotate(33.14 -38.91 40.897)scale(2.25791 .79383)" gradientUnits="userSpaceOnUse"><stop class="afa21ukyb"/><stop offset="1" class="sozlwmb1o"/></radialGradient><radialGradient id="ievnUXb" cx="0" cy="0" r="1" gradientTransform="rotate(168.154 12.836 15.097)scale(6.54566 1.70736)" gradientUnits="userSpaceOnUse"><stop class="kcxizyr3a"/><stop offset="1" class="uz8nvn0bw"/></radialGradient><radialGradient id="i66omkb" cx="0" cy="0" r="1" gradientTransform="matrix(.84205 2.73 -2.93117 .9041 6.841 20.548)" gradientUnits="userSpaceOnUse"><stop class="phzm4snim"/><stop offset="1" class="czerk-92m"/></radialGradient><radialGradient id="iKSUY7c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .87171 -.46263 -.67998 9.982 21.52)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="wyqcze2zy"/><stop offset="1" class="r6dyzpbfo"/></radialGradient><radialGradient id="iUVgkrd" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 .75 -.43392 .18532 7.24 21.158)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="r1y6vkpka"/><stop offset="1" class="xrzwqzb7j"/></radialGradient><radialGradient id="iuMykle" cx="0" cy="0" r="1" gradientTransform="rotate(153.654 1.833 11.596)scale(2.61542 2.57494)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="tz2l_he6k"/><stop offset="1" class="twkrvc03o"/></radialGradient><radialGradient id="iYPdkQe" cx="0" cy="0" r="1" gradientTransform="matrix(-.3711 1.25391 -.1532 -.04534 16.086 19.15)" gradientUnits="userSpaceOnUse"><stop class="tomvu1bgl"/><stop offset="1" class="sinn-3bvk"/></radialGradient><radialGradient id="iU7vAuc" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.60156 1.71998 -.58078 9.388 23.69)" gradientUnits="userSpaceOnUse"><stop class="gmelrdffb"/><stop offset="1" class="khl528bkl"/></radialGradient><radialGradient id="i8k3Wqe" cx="0" cy="0" r="1" gradientTransform="matrix(-.64063 2 -.16496 -.05284 15.898 18.49)" gradientUnits="userSpaceOnUse"><stop class="njdbcpw8w"/><stop offset="1" class="p6n8nbb9p"/></radialGradient><radialGradient id="iCwIi4d" cx="0" cy="0" r="1" gradientTransform="matrix(1.42187 .6875 -.62811 1.29906 11.53 19.177)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l8v5z5bog"/><stop offset="1" class="ll6ec2bpd"/></radialGradient><radialGradient id="ixkd2Cb" cx="0" cy="0" r="1" gradientTransform="matrix(2.3281 3.09377 -4.49478 3.3824 7.81 18.783)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="zm6geub_u"/><stop offset="1" class="lrce32g5i"/></radialGradient><radialGradient id="iaaEahw" cx="0" cy="0" r="1" gradientTransform="matrix(-1.82813 3.21874 -1.86644 -1.06007 10.2 18.236)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="eg892dbvw"/><stop offset="1" class="lq414ub4c"/></radialGradient><radialGradient id="icxe0wd" cx="0" cy="0" r="1" gradientTransform="matrix(-.1359 3.04807 -.73147 -.03261 7.35 18.79)" gradientUnits="userSpaceOnUse"><stop class="ny_jxsr8o"/><stop offset="1" class="s5w7sgqdm"/></radialGradient><radialGradient id="iY91F1p" cx="0" cy="0" r="1" gradientTransform="matrix(-.97119 .31036 -.1504 -.47062 14.375 17.125)" gradientUnits="userSpaceOnUse"><stop class="kaydztigo"/><stop offset="1" class="ojt9l7bfl"/></radialGradient><radialGradient id="i65YnOb" cx="0" cy="0" r="1" gradientTransform="matrix(.125 -.9375 3.91224 .52166 12.703 18.203)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="i4p54obux"/><stop offset="1" class="z44v3-bta"/></radialGradient><radialGradient id="iJHBi3d" cx="0" cy="0" r="1" gradientTransform="matrix(.18995 -.92273 4.1369 .8516 12.185 19.578)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="bamcey7be"/><stop offset="1" class="a-744r8ne"/></radialGradient><radialGradient id="iHqACud" cx="0" cy="0" r="1" gradientTransform="rotate(-171.743 6.56 8.762)scale(2.12166 2.39641)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="dto0_ubls"/><stop offset=".907" class="t-pst_b0z"/></radialGradient><radialGradient id="ivLB7Oc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 .41406 -.20022 -.51377 13.89 18.195)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="k35cj8b6j"/><stop offset="1" class="kdyinjb2g"/></radialGradient><radialGradient id="iDqehLe" cx="0" cy="0" r="1" gradientTransform="matrix(-.60938 .84374 -2.96419 -2.14083 11.45 19.564)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="fus102bkw"/><stop offset="1" class="d_o4p9bes"/></radialGradient><radialGradient id="i8xTvzg" cx="0" cy="0" r="1" gradientTransform="matrix(2.3789 1.48047 -.66284 1.0651 11.355 19.675)" gradientUnits="userSpaceOnUse"><stop class="q_yfvabjb"/><stop offset="1" class="bxxfcfh8v"/></radialGradient><radialGradient id="ifAfAec" cx="0" cy="0" r="1" gradientTransform="matrix(-.3672 .53142 -1.08325 -.74848 12.138 19.47)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="ikgl8m1ug"/><stop offset="1" class="qj5edhacv"/></radialGradient><radialGradient id="iyBiJTd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33928 1.42858 -2.02518 -1.89858 10.944 20.259)" gradientUnits="userSpaceOnUse"><stop class="gn724k1ul"/><stop offset="1" class="vgekv3bdy"/></radialGradient><radialGradient id="iKYBiLe" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 -.875 1.67102 3.163 8.278 21.783)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="ex769achu"/><stop offset="1" class="e7foweb5i"/></radialGradient><radialGradient id="ika6Zbc" cx="0" cy="0" r="1" gradientTransform="matrix(1.20313 .67188 -.27198 .48704 10.796 20.875)" gradientUnits="userSpaceOnUse"><stop class="cn3fn4-mf"/><stop offset="1" class="dzll2bclm"/></radialGradient><radialGradient id="iPvypgc" cx="0" cy="0" r="1" gradientTransform="rotate(105.675 .814 16.164)scale(1.31451 .34383)" gradientUnits="userSpaceOnUse"><stop class="cn05xwrkd"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="i2vvPlf" cx="0" cy="0" r="1" gradientTransform="rotate(105.036 .694 16.64)scale(.54206 .1592)" gradientUnits="userSpaceOnUse"><stop class="em3lc9y5i"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="iJ9m1ti" cx="0" cy="0" r="1" gradientTransform="rotate(174.906 8.377 10.63)scale(.43997 .38553)" gradientUnits="userSpaceOnUse"><stop class="tzj34xnjq"/><stop offset="1" class="ugbytbngn"/></radialGradient><radialGradient id="iAkvLKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.26365 -2.21465 3.37212 -.40144 7.844 22.49)" gradientUnits="userSpaceOnUse"><stop class="zmq4c2bxg"/><stop offset="1" class="trma59b_r"/></radialGradient><radialGradient id="iOxTq1G" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 15.466 -4.455)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="x6u8q5ddp"/><stop offset=".876" class="mc_gf1bbw"/></radialGradient><radialGradient id="iYKNuLe" cx="0" cy="0" r="1" gradientTransform="matrix(.76782 -1.48268 1.92055 .99457 16.9 10.6)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="namtwab4r"/><stop offset=".535" class="ylo0visum"/></radialGradient><radialGradient id="iWPCbxc" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .35569 2.1855 11.383 11.827)" gradientUnits="userSpaceOnUse"><stop class="fdm2y6x_j"/><stop offset="1" class="h1ie4dmkz"/></radialGradient><radialGradient id="ivu8Krd" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .35569 2.1855 16.013 11.018)" gradientUnits="userSpaceOnUse"><stop class="fdm2y6x_j"/><stop offset="1" class="h1ie4dmkz"/></radialGradient><radialGradient id="i5OmMBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 13.555 11.462)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="g7xtertqj"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="eovkc4nhj"/></radialGradient><radialGradient id="ibmysNx" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 18.185 10.654)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="g7xtertqj"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="eovkc4nhj"/></radialGradient><linearGradient id="iPaaoii" x1="19.3" x2="12.412" y1="19.279" y2="30.955" gradientUnits="userSpaceOnUse"><stop class="iezg62obf"/><stop offset="1" class="w444cbj2i"/></linearGradient><linearGradient id="iVPi7dc" x1="15.761" x2="17.294" y1="17.908" y2="18.893" gradientUnits="userSpaceOnUse"><stop offset=".177" class="os24xccvv"/><stop offset="1" class="jje_xpbkc"/></linearGradient><linearGradient id="iAe2jic" x1="20.307" x2="15.958" y1="12.453" y2="13.227" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="iDrMn9c" x1="16.013" x2="15.899" y1="17.925" y2="17.285" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="ijyBVpb" x1="15.812" x2="14.981" y1="12.211" y2="12.395" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="ikoMMvu" x1="15.177" x2="15.095" y1="13.499" y2="13.034" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iWe0AKc" x1="14.652" x2="14.793" y1="10.547" y2="11.342" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="iqoBVDb" x1="14.256" x2="14.425" y1="15.282" y2="14.392" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iSVMlad" x1="20.694" x2="9.092" y1="4.811" y2="6.875" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="ie3Jprd" x1="21.137" x2="20.318" y1="9.708" y2="12.097" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="i3BrvEc" x1="8.987" x2="10.421" y1="12.595" y2="12.209" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="i2M0T0c" x1="20.05" x2="20.388" y1="9.508" y2="11.409" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="ixRQl3b" x1="23.345" x2="27.19" y1="25.016" y2="29.592" gradientUnits="userSpaceOnUse"><stop class="d0ocakaur"/><stop offset="1" class="u_vqqhk3b"/></linearGradient><linearGradient id="i8sLyyb" x1="9.185" x2="3.716" y1="26.987" y2="25.518" gradientUnits="userSpaceOnUse"><stop class="hbzm4jmfo"/><stop offset="1" class="hzk1ijbie"/></linearGradient><linearGradient id="iP5SDed" x1="3.591" x2="5.403" y1="26.612" y2="27.268" gradientUnits="userSpaceOnUse"><stop class="dm21qhbor"/><stop offset="1" class="xvwmp6tlw"/></linearGradient><linearGradient id="iYTyuSE" x1="9.305" x2="8.912" y1="29.004" y2="28.879" gradientUnits="userSpaceOnUse"><stop class="icorotc4i"/><stop offset="1" class="deg8fdc9j"/></linearGradient><linearGradient id="icTp73d" x1="24.685" x2="24.372" y1="26.018" y2="24.549" gradientUnits="userSpaceOnUse"><stop class="dy155dxdg"/><stop offset="1" class="dypnkmnss"/></linearGradient><linearGradient id="ibxTEIb" x1="19.471" x2="19.471" y1="27.307" y2="30.674" gradientUnits="userSpaceOnUse"><stop class="di46q3nvv"/><stop offset="1" class="bhzzakkbd"/></linearGradient><linearGradient id="ilaPNnd" x1="19.599" x2="19.513" y1="27.236" y2="27.744" gradientUnits="userSpaceOnUse"><stop class="m9orc9b3r"/><stop offset="1" class="zegip2beb"/></linearGradient><linearGradient id="idjZzid" x1="26.622" x2="27.06" y1="27.456" y2="31.174" gradientUnits="userSpaceOnUse"><stop class="xyrntivgr"/><stop offset="1" class="cjhyb2bbj"/></linearGradient><linearGradient id="iDuIIFc" x1="11.22" x2="11.073" y1="22.746" y2="20.103" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="iHMXBic" x1="12.427" x2="12.04" y1="20.937" y2="18.955" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="idqxSZc" x1="16.153" x2="15.372" y1="18.736" y2="21.722" gradientUnits="userSpaceOnUse"><stop class="e6bcurcdv"/><stop offset="1" class="jxwnoqbqn"/></linearGradient><linearGradient id="iiSxGFy" x1="15.281" x2="15.504" y1="21.942" y2="21.052" gradientUnits="userSpaceOnUse"><stop class="w_57dfb5m"/><stop offset="1" class="t78i98bfv"/></linearGradient><linearGradient id="iWduF6v" x1="15.028" x2="13.903" y1="17.971" y2="22.299" gradientUnits="userSpaceOnUse"><stop class="nn3wh7bnm"/><stop offset="1" class="tbs366q3s"/></linearGradient><linearGradient id="i0qroLc" x1="15.341" x2="14.232" y1="18.346" y2="17.986" gradientUnits="userSpaceOnUse"><stop class="h94nvm15h"/><stop offset="1" class="qtvy6rbzh"/></linearGradient><linearGradient id="iVCSyye" x1="14.528" x2="13.299" y1="17.861" y2="22.611" gradientUnits="userSpaceOnUse"><stop class="qic_n_blg"/><stop offset="1" class="qh-ows9fr"/></linearGradient><linearGradient id="iq71JBe" x1="12.625" x2="12.843" y1="21.677" y2="20.599" gradientUnits="userSpaceOnUse"><stop class="e122-lbju"/><stop offset="1" class="grqmao4rm"/></linearGradient><linearGradient id="iAo5VBc" x1="8.497" x2="9.04" y1="17.361" y2="21.861" gradientUnits="userSpaceOnUse"><stop class="gnkeuhb_f"/><stop offset="1" class="vkqqj1b4e"/></linearGradient><linearGradient id="izhm4Uc" x1="16.597" x2="16.013" y1="19.237" y2="21.737" gradientUnits="userSpaceOnUse"><stop class="neym138jd"/><stop offset="1" class="kmp3a3cnr"/></linearGradient><linearGradient id="iwigpTc" x1="11.476" x2="13.758" y1="11.869" y2="12.024" gradientUnits="userSpaceOnUse"><stop class="d3bth9bgz"/><stop offset="1" class="pvzvrjbje"/></linearGradient><linearGradient id="iEzbmIH" x1="16.107" x2="18.388" y1="11.062" y2="11.217" gradientUnits="userSpaceOnUse"><stop class="d3bth9bgz"/><stop offset="1" class="pvzvrjbje"/></linearGradient><filter id="ikxS1AS" width="11.934" height="12.691" x="9.245" y="5.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3532"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3532" result="effect2_innerShadow_4002_3532"/></filter><filter id="iX9YvFc" width="3.766" height="4.982" x="13.095" y="9.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3532" stdDeviation=".5"/></filter><filter id="iwmI9Gb" width="2.295" height="3.382" x="13.938" y="10.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3532" stdDeviation=".1"/></filter><filter id="i5FSYpe" width="3.719" height="1.864" x="13.475" y="13.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3532" stdDeviation=".05"/></filter><filter id="ioXbXuc" width="12.937" height="9.678" x="7.602" y="2.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3532"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3532" result="effect2_innerShadow_4002_3532"/></filter><filter id="io0osDd" width="6.509" height="6.798" x="7.998" y="3.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3532"/><feGaussianBlur result="effect2_foregroundBlur_4002_3532" stdDeviation=".125"/></filter><filter id="ipHWFjd" width="6.797" height="5.093" x="13.541" y="3.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3532"/><feGaussianBlur result="effect2_foregroundBlur_4002_3532" stdDeviation=".125"/></filter><filter id="iGkClhd" width="1.512" height="2.364" x="8.716" y="11.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3532" stdDeviation=".125"/></filter><filter id="iNDLbte" width="2.019" height="2.923" x="19.188" y="9.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3532" stdDeviation=".25"/></filter><filter id="iTYrG0c" width="5.452" height="2.49" x="14.644" y="3.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3532" stdDeviation=".375"/></filter><filter id="i3i60Ic" width="11.192" height="8.359" x="11.542" y="22.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.607843 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3532"/></filter><filter id="iPs8CjL" width="7.407" height="8.444" x="19.124" y="19.394" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3532"/></filter><filter id="iyUQ0zd" width="8.208" height="4.667" x="12.492" y="26.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.129412 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3532"/></filter><filter id="iI4quKd" width="3.456" height="1.701" x="7.457" y="22.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3532" stdDeviation=".1"/></filter><filter id="iIt82qc" width="4.309" height="4.662" x="11.119" y="17.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.552941 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3532"/></filter><filter id="iNpfACc" width="3.647" height="2.753" x="6.339" y="20.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3532" stdDeviation=".05"/></filter><filter id="iKPUCUQ" width="2.414" height=".981" x="15.928" y="7.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0509804 0 0 0 0 0.0470588 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3532"/></filter><filter id="izTtryc" width="2.273" height="1.458" x="10.792" y="8.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0509804 0 0 0 0 0.0470588 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3532"/></filter><filter id="ie0RlDB" width="3.987" height="3.987" x="10.476" y="8.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3532" stdDeviation=".325"/></filter><filter id="ikIlrBc" width="3.987" height="3.987" x="15.065" y="8.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3532" stdDeviation=".325"/></filter><filter id="itIdX0d" width="2.236" height="1.32" x="10.758" y="8.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3532" stdDeviation=".125"/></filter><filter id="i5H89kp" width="2.369" height=".864" x="15.911" y="7.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3532" stdDeviation=".125"/></filter><filter id="iYLxEAO" width="2.323" height=".964" x="11.381" y="11.343" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3532" stdDeviation=".05"/></filter><filter id="i5vjhFc" width="2.323" height=".964" x="16.011" y="10.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3532" stdDeviation=".05"/></filter><filter id="iRyTN2b" width="2.634" height="2.141" x="16.45" y="26.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3532" stdDeviation=".125"/></filter><filter id="i9OLxzb" width="4.536" height="1" x="12.822" y="29.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3532" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-feeding-baby-dark" /></template>
<style>
.a-744r8ne {
  stop-color: var(--svg-color--2d1517, #2D1517);
  stop-opacity: 0;
}

.a2zze1bcp {
  d: path("M10.525 15.307a3.974 3.974 0 0 0 4.488 2.712l1.885-.336a3.974 3.974 0 0 0 3.277-4.094c-.217-1.902-.432-3.798-.68-5.695a1.47 1.47 0 0 0-1.632-1.185l-1.399.248a2.46 2.46 0 0 1-2.466-1.048a.67.67 0 0 0-.69-.308l-1.271.226c-1.844.328-3.07 2.105-2.738 3.97c.331 1.86.773 3.668 1.226 5.51");
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a6ayzxb8w {
  stop-color: var(--svg-color--289d47, #289D47);
  stop-opacity: 0;
}

.a81w0ygfz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.67 20.424c-.207.432-.32 1.448.874 2.055c1.194.606 1.992.148 2.242-.157");
}

.aaacne_5z {
  d: path("M15.37 14.58a3.05 3.05 0 0 1-1.443-.082c-.15-.045-.269.136-.16.245a1.92 1.92 0 0 0 1.732.563a1.92 1.92 0 0 0 1.431-1.126c.064-.145-.11-.268-.235-.174c-.363.28-.813.483-1.325.574");
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.acgtzjb8q {
  stop-color: var(--svg-color--3ba055, #3BA055);
}

.aefwo3bed {
  d: path("M23.52 27.833a4.3 4.3 0 1 0 .001-8.6a4.3 4.3 0 0 0 0 8.6");
}

.afa21ukyb {
  stop-color: var(--svg-color--2f2127, #2F2127);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.b2nqurbhe {
  d: path("M16.161 11.053c.151.14.548.37 1.063.273c.562-.106.888-.458.96-.64");
}

.bamcey7be {
  stop-color: var(--svg-color--2d1517, #2D1517);
}

.bhzzakkbd {
  stop-color: var(--svg-color--d4453a, #D4453A);
}

.bji58ac7a {
  stop-color: var(--svg-color--208d47, #208D47);
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.bncj6nbye {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m14.088 6.034l-.09-.125a.67.67 0 0 0-.69-.308l-1.271.226c-1.844.328-3.07 2.105-2.738 3.97l.05.275c-.387-.198-.91-.667-1.068-1.55c-.19-1.07.494-1.75.931-2.185c.123-.122.227-.225.285-.312l.081-.122c.284-.433.789-1.203 1.824-1.685a5.6 5.6 0 0 1 1.489-.435c.467-.07.867.273.95.739l.266 1.495z");
}

.bowq5ib2o {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m19.645 8.413l-.141-.626c-.147-.76-.889-1.278-1.658-1.174l-1.399.249a2.46 2.46 0 0 1-2.346-.881s-.088-.134-.196-.37c-.416-.913.366-1.805 1.369-1.791c1.012.013 2.19.143 3.112.535c1.945.826 2.005 2.93 1.26 4.058");
}

.brh-pzb_h {
  stop-color: var(--svg-color--f36716, #F36716);
  stop-opacity: 0;
}

.bxxfcfh8v {
  stop-color: var(--svg-color--462e2a, #462E2A);
  stop-opacity: 0;
}

.bzi-27bxc {
  stop-color: var(--svg-color--f36716, #F36716);
}

.c_p6lvbtv {
  stop-color: var(--svg-color--31be7d, #31BE7D);
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c29p3sb0d {
  d: path("M11.531 11.86c.151.141.548.371 1.063.274c.562-.107.888-.459.96-.64");
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c8r1g2bnk {
  stop-color: var(--svg-color--148c3e, #148C3E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cfvk8yscg {
  d: path("M10.175 17.135c.356.125.481.33.515.453l.446.39l2.291.363a.92.92 0 0 0 1.062-.872a.913.913 0 0 0-.922-.95c-1.175.013-2.688.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.cjhyb2bbj {
  stop-color: var(--svg-color--ff5641, #FF5641);
}

.cl8z70zew {
  d: path("m12.243 17.139l2.635.734c.357.104.645.406.521.797l-.779 2.704c-.096.329-.442.504-.851.394l-2.6-.734z");
}

.cn05xwrkd {
  stop-color: var(--svg-color--fed466, #FED466);
}

.cn3fn4-mf {
  stop-color: var(--svg-color--685655, #685655);
}

.cvt9shbtj {
  d: path("m12.015 16.708l3.172.884c.43.125.744.558.627.96l-.9 3.086c-.115.396-.532.606-1.024.473l-3.129-.883z");
}

.czerk-92m {
  stop-color: var(--svg-color--cf482d, #CF482D);
}

.d_o4p9bes {
  stop-color: var(--svg-color--3c2626, #3C2626);
}

.d0ocakaur {
  stop-color: var(--svg-color--ff3200, #FF3200);
}

.d3bth9bgz {
  stop-color: var(--svg-color--2d2d2d, #2D2D2D);
}

.d3zgybcsf {
  d: path("M11.489 11.593c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34c-.19-.14-.11-.43.11-.47");
}

.d5t3hz92z {
  fill: var(--svg-color--47302e, #47302E);
  d: path("M9.745 18.057c.244.25.331.526.344.632l.484.47l2.342.407a.89.89 0 0 0 1.024-.694a.9.9 0 0 0-.774-1.078c-1.09-.133-2.42-.306-2.78-.347c-.612-.07-.944.297-.64.61");
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.d9k92hb3z {
  d: path("M17.256 26.357a.937.937 0 0 0-1.12 1.497l.93.802a.1.1 0 0 1-.062.175l-3.644.072a.886.886 0 0 0 .018 1.771h6.06v-1l1.062-1.226z");
}

.deg8fdc9j {
  stop-color: var(--svg-color--ff451c, #FF451C);
  stop-opacity: 0;
}

.di46q3nvv {
  stop-color: var(--svg-color--ce5621, #CE5621);
}

.dm21qhbor {
  stop-color: var(--svg-color--d46751, #D46751);
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.dto0_ubls {
  stop-color: var(--svg-color--422e2b, #422E2B);
  stop-opacity: 0;
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

.dzll2bclm {
  stop-color: var(--svg-color--685655, #685655);
  stop-opacity: 0;
}

.e0wfhpbyy {
  d: path("M21.911 24.693c-1.17-2.04-3.78-2.73-5.81-1.56l-2.43 1.4c-2.04 1.17-2.73 3.78-1.56 5.81l.21.33h7.73l.3-.18a4.23 4.23 0 0 0 1.56-5.8");
}

.e122-lbju {
  stop-color: var(--svg-color--8b72aa, #8B72AA);
}

.e6bcurcdv {
  stop-color: var(--svg-color--6cd9f5, #6CD9F5);
}

.e7foweb5i {
  stop-color: var(--svg-color--382028, #382028);
  stop-opacity: 0;
}

.eg892dbvw {
  stop-color: var(--svg-color--412c2a, #412C2A);
}

.em3lc9y5i {
  stop-color: var(--svg-color--fed064, #FED064);
}

.eovkc4nhj {
  stop-color: var(--svg-color--303030, #303030);
  stop-opacity: 0;
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.eqapwmsga {
  stop-color: var(--svg-color--208d47, #208D47);
  stop-opacity: 0;
}

.ex769achu {
  stop-color: var(--svg-color--382028, #382028);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fdm2y6x_j {
  stop-color: var(--svg-color--070509, #070509);
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fo4qq4q_b {
  stop-color: var(--svg-color--289d47, #289D47);
}

.ft5dv1b6b {
  fill: none;
}

.fu3c0cblo {
  stop-color: var(--svg-color--f38820, #F38820);
}

.fus102bkw {
  stop-color: var(--svg-color--49302c, #49302C);
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g7xtertqj {
  stop-color: var(--svg-color--303030, #303030);
}

.geget3s5f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.857 23.706c.578.14 1.918.172 2.656-.828");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gmelrdffb {
  stop-color: var(--svg-color--ff8040, #FF8040);
}

.gn724k1ul {
  stop-color: var(--svg-color--543b38, #543B38);
}

.gnkeuhb_f {
  stop-color: var(--svg-color--463836, #463836);
}

.grqmao4rm {
  stop-color: var(--svg-color--b59cc2, #B59CC2);
  stop-opacity: 0;
}

.h1ie4dmkz {
  stop-color: var(--svg-color--131212, #131212);
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.h94nvm15h {
  stop-color: var(--svg-color--43b1db, #43B1DB);
}

.hbzm4jmfo {
  stop-color: var(--svg-color--f54c3c, #F54C3C);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hzk1ijbie {
  stop-color: var(--svg-color--e2492a, #E2492A);
}

.i4p54obux {
  stop-color: var(--svg-color--3b201d, #3B201D);
}

.i5de26xkm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.ib-e97gvn {
  d: path("m11.92 21.274l-.46-.5c-.28-.3-.68-.48-1.09-.49c-.42-.01-.82.16-1.11.46l-.17.18l.53-.95c.22-.39.59-.66 1.02-.74s.88.03 1.23.3l.99.8c.33.27.38.75.12 1.09c-.21.26-.56.35-.85.24a.9.9 0 0 0-.21-.39");
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

.ijdg6fbam {
  stop-color: var(--svg-color--fc4a51, #FC4A51);
}

.ikgl8m1ug {
  stop-color: var(--svg-color--301d1a, #301D1A);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j52o6nbeg {
  d: path("M19.915 11.494q-.111-.962-.227-1.922a.97.97 0 0 1 .227 1.922");
}

.j8sdcok6a {
  d: path("m29.221 26.014l-4.94-6.05l-3.16 8.57z");
}

.jixqgub8x {
  cx: 17.058px;
  cy: 10.196px;
  r: 1.344px;
}

.jje_xpbkc {
  stop-color: var(--svg-color--633428, #633428);
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jlllnebdx {
  d: path("m19.645 8.413l-.141-.626c-.147-.76-.889-1.278-1.658-1.174l-1.399.249a2.46 2.46 0 0 1-2.346-.881s-.088-.134-.196-.37c-.416-.913.366-1.805 1.369-1.791c1.012.013 2.19.143 3.112.535c1.945.826 2.005 2.93 1.26 4.058");
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.jswkgxfop {
  d: path("M8.933 21.603c-.315.22-.723.211-.906-.109c-.392-.948.72-1.58 1.5-1.598c1.168-.027 1.75.63 1.937 1.121c.188.493.227 1.477-.672 1.54c-.804.055-.847-.5-.98-.743c-.133-.242-.594-.41-.88-.21");
}

.jxwnoqbqn {
  stop-color: var(--svg-color--3782ce, #3782CE);
}

.k_pdrlblj {
  stop-color: var(--svg-color--ebb830, #EBB830);
  stop-opacity: 0;
}

.k35cj8b6j {
  stop-color: var(--svg-color--685755, #685755);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.kar3bi73q {
  stop-color: var(--svg-color--d25e22, #D25E22);
  stop-opacity: 0;
}

.kaydztigo {
  stop-color: var(--svg-color--695856, #695856);
}

.kcxizyr3a {
  stop-color: var(--svg-color--ff8a47, #FF8A47);
}

.kdyinjb2g {
  stop-color: var(--svg-color--533a36, #533A36);
  stop-opacity: 0;
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
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

.ky0z_lbmb {
  cx: 12.47px;
  cy: 10.924px;
  r: 1.344px;
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.kyl8adb5j {
  stop-color: var(--svg-color--148c3e, #148C3E);
  stop-opacity: 0;
}

.kz3e_kwhy {
  d: path("M21.65 24.614a4.3 4.3 0 0 1 .711-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l8v5z5bog {
  stop-color: var(--svg-color--6e574e, #6E574E);
}

.ll6ec2bpd {
  stop-color: var(--svg-color--6e574e, #6E574E);
  stop-opacity: 0;
}

.lnnq9g1hs {
  d: path("M19.074 27.457a.15.15 0 0 1 .15-.15h.643v3.367h-.793z");
}

.lq414ub4c {
  stop-color: var(--svg-color--412c2a, #412C2A);
  stop-opacity: 0;
}

.lrce32g5i {
  stop-color: var(--svg-color--441f26, #441F26);
}

.lsy8a_brx {
  fill: var(--svg-color--0e0710, #0E0710);
  d: path("M10.997 9.414a2.8 2.8 0 0 1 1.673-.663a.281.281 0 0 1 .03.562a2.25 2.25 0 0 0-1.335.526a1 1 0 0 0-.082.076l-.002.003a.281.281 0 0 1-.416-.379z");
}

.ltqrzdb7q {
  d: path("m14.346 11.04l-.205 1.932c-.04.397.287.728.655.663l.786-.14c.368-.066.56-.496.385-.848l-.857-1.743c-.187-.386-.718-.292-.764.136");
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.lwl1xgbup {
  stop-color: var(--svg-color--d25e22, #D25E22);
}

.lxxjtjbpr {
  d: path("m2.277 30.674l2.93-9.156c.351-1.414 2.07-2.104 3.65-1.614s2.49 2.333 2.006 3.692l-2.216 7.078z");
}

.m19b90bbg {
  d: path("M16.12 10.783c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34a.263.263 0 0 1 .11-.47");
}

.m85_zobye {
  d: path("m14.088 6.034l-.09-.125a.67.67 0 0 0-.69-.308l-1.271.226c-1.844.328-3.07 2.105-2.738 3.97l.05.275c-.387-.198-.91-.667-1.068-1.55c-.19-1.07.494-1.75.931-2.185c.123-.122.227-.225.285-.312l.081-.122c.284-.433.789-1.203 1.824-1.685a5.6 5.6 0 0 1 1.489-.435c.467-.07.867.273.95.739l.266 1.495z");
}

.m9orc9b3r {
  stop-color: var(--svg-color--ae4614, #AE4614);
}

.mc_gf1bbw {
  stop-color: var(--svg-color--361c1f, #361C1F);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mqatnwb7r {
  d: path("M9.56 11.394a.97.97 0 0 0 .418 1.863q-.22-.93-.418-1.863");
}

.mt97pnhfa {
  d: path("M18.524 4.186c.546.086 1.07.363 1.454.825c.612.737.717 1.73.343 2.543a1.6 1.6 0 0 0-.115.922l.211 1.187a1.8 1.8 0 0 0-.714-.15l-.207-1.618a1.47 1.47 0 0 0-1.633-1.186l-1.399.249a2.46 2.46 0 0 1-2.466-1.049a.67.67 0 0 0-.69-.308l-1.271.226c-1.844.328-3.07 2.105-2.738 3.97l.304 1.531a1.7 1.7 0 0 0-.672.392l-.214-1.2c-.055-.31-.205-.6-.426-.825a2.43 2.43 0 0 1-.577-2.418A2.38 2.38 0 0 1 8.812 5.92a2.72 2.72 0 0 0 1.185-1.355a2.36 2.36 0 0 1 2.726-1.425c.411.098.84.022 1.193-.212c.26-.168.554-.293.878-.35a2.36 2.36 0 0 1 2.188.777c.398.454.946.738 1.542.831");
}

.n8jici3hn {
  stop-color: var(--svg-color--fed466, #FED466);
  stop-opacity: 0;
}

.namtwab4r {
  stop-color: var(--svg-color--50322e, #50322E);
}

.neym138jd {
  stop-color: var(--svg-color--f3c22a, #F3C22A);
}

.njdbcpw8w {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
}

.nn3wh7bnm {
  stop-color: var(--svg-color--58d4f5, #58D4F5);
}

.ny_jxsr8o {
  stop-color: var(--svg-color--574743, #574743);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2f2ovuoo {
  d: path("M15.76 19.204c1.06 0 1.91-.86 1.91-1.91v-2.26a1.91 1.91 0 1 0-3.82 0v2.26c-.01 1.06.85 1.91 1.91 1.91");
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o92m3lbae {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.95 14.427c.425.134.91.168 1.406.08c.501-.09.94-.288 1.294-.56v-.001a.23.23 0 0 1 .277-.003a.216.216 0 0 1 .072.266m-3.05.218l2.981-.247m-2.98.247h-.001a.23.23 0 0 0-.262.094a.214.214 0 0 0 .026.274m.236-.368l-.183.316M17 14.208l-.069-.03m.07.03l-.07-.03m.07.03a2 2 0 0 1-1.488 1.171a2 2 0 0 1-1.8-.585m3.218-.615a1.92 1.92 0 0 1-1.431 1.126a1.92 1.92 0 0 1-1.733-.563m-.053.052l.053-.053m-.053.053h-.001l.054-.053");
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.ojt9l7bfl {
  stop-color: var(--svg-color--695856, #695856);
  stop-opacity: 0;
}

.os24xccvv {
  stop-color: var(--svg-color--3f1817, #3F1817);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p0ldlzgkt {
  fill: var(--svg-color--402929, #402929);
  d: path("m14.346 11.04l-.205 1.932c-.04.397.287.728.655.663l.786-.14c.368-.066.56-.496.385-.848l-.857-1.743c-.187-.386-.718-.292-.764.136");
}

.p6n8nbb9p {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
  stop-opacity: 0;
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pdon63boo {
  stop-color: var(--svg-color--f38820, #F38820);
  stop-opacity: 0;
}

.pfahw7jhf {
  d: path("M8.597 19.154a.28.28 0 0 1 .133-.27c.981-.69 2.005-.304 2.383 0c.304.236 1 .79 1.363 1.082c.446.36.372.961.043 1.317c-.276.298-.751.24-.93.148L9.491 20.12c-.054-.313-.234-.563-.48-.637s-.402-.133-.414-.328");
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.phzm4snim {
  stop-color: var(--svg-color--ce6122, #CE6122);
}

.pmmbaet1b {
  d: path("M20.01 12.152a330 330 0 0 0-.382-3.222a1.634 1.634 0 0 1 .383 3.222");
}

.pn8w7jbzs {
  stroke: var(--svg-color--2f2f30, #2F2F30);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M11.083 9.687c.225-.23.808-.665 1.586-.67");
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.przuo7bga {
  d: path("M10.64 19.244c-.28.05-.54.19-.74.38c.01-.05.02-.1.04-.15l.12-.33c.28-.78 1.09-1.27 1.91-1.15l1.66.23c.42.06.72.45.66.87s-.45.72-.87.66l-1.57-.22c-.34-.26-.78-.37-1.21-.29");
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.pvzvrjbje {
  stop-color: var(--svg-color--2d2d2d, #2D2D2D);
  stop-opacity: 0;
}

.q_yfvabjb {
  stop-color: var(--svg-color--685756, #685756);
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
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

.qj5edhacv {
  stop-color: var(--svg-color--301d1a, #301D1A);
  stop-opacity: 0;
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qtvy6rbzh {
  stop-color: var(--svg-color--42b8e0, #42B8E0);
}

.r1y6vkpka {
  stop-color: var(--svg-color--b42c01, #B42C01);
}

.r6dyzpbfo {
  stop-color: var(--svg-color--a62302, #A62302);
  stop-opacity: 0;
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.roydk-c2b {
  d: path("M10.29 22.36c-.284.88-1.448 1.293-2.6.921s-1.793-1.178-1.573-2.266c.18-.888.883-1.75 2.738-1.24c1.153.372 1.719 1.705 1.435 2.585");
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.s4zv63nni {
  d: path("M10.22 13.8a1.66 1.66 0 0 1-.959-.148l.166.93a2.2 2.2 0 0 0 1.698 1.78a4.2 4.2 0 0 1-.555-1.118z");
}

.s5w7sgqdm {
  stop-color: var(--svg-color--574743, #574743);
  stop-opacity: 0;
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
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

.sozlwmb1o {
  stop-color: var(--svg-color--2f2127, #2F2127);
  stop-opacity: 0;
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t-pst_b0z {
  stop-color: var(--svg-color--422e2b, #422E2B);
}

.t78i98bfv {
  stop-color: var(--svg-color--735caf, #735CAF);
  stop-opacity: 0;
}

.t7yh0hf_x {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m14.361 11.24l-.263 1.942c-.034.396.275.73.618.67l.731-.13c.343-.062.517-.489.35-.843l-.821-1.748c-.178-.389-.576-.318-.615.109");
}

.t8_8lcczx {
  stroke: var(--svg-color--5e4a49, #5E4A49);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m16.95 26.964l1.634 1.14");
}

.t84wefbqx {
  stroke: var(--svg-color--543d3f, #543D3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.322 29.77h3.536");
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

.tuyve8bzg {
  d: path("m14.902 17.772l-2.636-.735l-1.073 3.895l2.6.734c.408.11.755-.064.85-.394l.78-2.703c.123-.391-.165-.694-.521-.797");
}

.twkrvc03o {
  stop-color: var(--svg-color--c24713, #C24713);
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
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

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u69m9xb2c {
  d: path("m15.605 18.54l.555.158a.15.15 0 0 1 .103.186l-.784 2.73a.15.15 0 0 1-.185.102l-.555-.159z");
}

.ugbytbngn {
  stop-color: var(--svg-color--ffd267, #FFD267);
  stop-opacity: 0;
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uz8nvn0bw {
  stop-color: var(--svg-color--ff8a47, #FF8A47);
  stop-opacity: 0;
}

.v2wkn2ras {
  stop-color: var(--svg-color--31ae6a, #31AE6A);
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.vfpz3nzlh {
  d: path("M9.474 10.728a1.633 1.633 0 0 0 .708 3.172a79 79 0 0 1-.708-3.172");
}

.vgekv3bdy {
  stop-color: var(--svg-color--3e2828, #3E2828);
}

.vh_un0b_u {
  d: path("M7.23 30.674c-1.05 0-1.9-.85-1.89-1.9l.01-2.13c0-5.77 4.79-10.46 10.69-10.46c5.91 0 10.69 4.68 10.69 10.46l.17 4.03z");
}

.vkqqj1b4e {
  stop-color: var(--svg-color--3a1a1d, #3A1A1D);
}

.w_57dfb5m {
  stop-color: var(--svg-color--735caf, #735CAF);
}

.w_w1tbavy {
  fill: var(--svg-color--432c2a, #432C2A);
  d: path("M10.175 17.135c.356.125.481.33.515.453l.446.39l2.291.363a.92.92 0 0 0 1.062-.872a.913.913 0 0 0-.922-.95c-1.175.013-2.688.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.w444cbj2i {
  stop-color: var(--svg-color--fa362a, #FA362A);
}

.wyqcze2zy {
  stop-color: var(--svg-color--a62302, #A62302);
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x-qk2z5ts {
  stroke: var(--svg-color--2f2f30, #2F2F30);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.956 8.412c-.29-.139-.985-.35-1.72-.09");
}

.x2mvaybuj {
  fill: var(--svg-color--412526, #412526);
  d: path("M17.256 26.357a.937.937 0 0 0-1.12 1.497l.93.802a.1.1 0 0 1-.062.175l-3.644.072a.886.886 0 0 0 .018 1.771h6.06v-1l1.062-1.226z");
}

.x6u8q5ddp {
  stop-color: var(--svg-color--3e2928, #3E2928);
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xj3lonb_s {
  d: path("M20.691 26.452c1.598-.23 4.567-.809 6.543-1.27c1.522-.263 2.64 1.203 2.64 2.781c0 1.371-1.021 2.236-1.746 2.618a.86.86 0 0 1-.403.093H19.71v-3.086c0-.797.281-1 .98-1.136");
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xrzwqzb7j {
  stop-color: var(--svg-color--b42c01, #B42C01);
  stop-opacity: 0;
}

.xtufuib5k {
  d: path("M8.206 17.916c1.031-1.086 1.92-1.37 2.32-1.375l.797.867l-.93 3.516c-.179.315-.563.996-.695 1.152c-.164.195-.735.63-1.765.238c-.888-.337-1.15-.898-1.176-1.148c.233-1.167.649-2.358 1.45-3.25");
}

.xvwmp6tlw {
  stop-color: var(--svg-color--e6422d, #E6422D);
  stop-opacity: 0;
}

.xxns0gg4i {
  d: path("M9.745 18.057c.244.25.331.526.344.632l.484.47l2.342.407a.89.89 0 0 0 1.024-.694a.9.9 0 0 0-.774-1.078c-1.09-.133-2.42-.306-2.78-.347c-.612-.07-.944.297-.64.61");
}

.xyrntivgr {
  stop-color: var(--svg-color--ff7c1e, #FF7C1E);
}

.ylo0visum {
  stop-color: var(--svg-color--442927, #442927);
}

.ymw0zacdj {
  d: path("m15.53 21.44l.227.068a.5.5 0 0 0 .491-.12l.364-.352a.13.13 0 0 1 .128-.034l.315.084a.485.485 0 0 0 .252-.935l-.303-.083a.13.13 0 0 1-.097-.109l-.07-.44a.5.5 0 0 0-.36-.403l-.26-.072z");
}

.ysxrm4uyy {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("m18.049 5.348l-2.08.37a.49.49 0 1 1-.093-.974c.554-.01 1.292-.018 1.793.016c1.132.076 1.526.55 1.676.912a1.54 1.54 0 0 0-1.296-.324");
}

.yxmxw0ard {
  stop-color: var(--svg-color--32996b, #32996B);
}

.z3zsa5bpu {
  stop-color: var(--svg-color--53f595, #53F595);
}

.z44v3-bta {
  stop-color: var(--svg-color--3b201d, #3B201D);
  stop-opacity: 0;
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zavprx2nu {
  d: path("M19.934 12.07c.333-.07.627-.24.849-.468l.165.93a2.2 2.2 0 0 1-.98 2.255q.159-.59.136-1.24z");
}

.zegip2beb {
  stop-color: var(--svg-color--ae4614, #AE4614);
  stop-opacity: 0;
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zm6geub_u {
  stop-color: var(--svg-color--441f26, #441F26);
  stop-opacity: 0;
}

.zmq4c2bxg {
  stop-color: var(--svg-color--d1623d, #D1623D);
}

.zrz4nworg {
  fill: var(--svg-color--0e0710, #0E0710);
  d: path("M18.107 8.257a2.75 2.75 0 0 0-1.98-.135a.281.281 0 1 0 .164.537c.443-.134.955-.138 1.525.08a.281.281 0 1 0 .29-.482");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
