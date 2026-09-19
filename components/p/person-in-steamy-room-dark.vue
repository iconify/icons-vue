<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iOokUYv)" class="r_bcr-ntk"/><circle fill="url(#ig6gRjd)" class="r_bcr-ntk"/><circle fill="url(#ifqCFkS)" class="iksuiqrgf"/><circle fill="url(#igczLIe)" transform="matrix(-1 0 0 1 21.326 16.165)" class="qnar36wle"/><circle fill="url(#iE9wJUA)" transform="matrix(-1 0 0 1 21.326 16.165)" class="qnar36wle"/><circle fill="url(#iiFjNse)" transform="matrix(-1 0 0 1 23.725 23.368)" class="n5l_opbqq"/><path fill="url(#i4UUWGe)" class="w8e9izb-y"/><path fill="url(#iFqMHgd)" class="w8e9izb-y"/><path fill="url(#iS6d3Rd)" class="w8e9izb-y"/><path fill="url(#i7GTaad)" class="rgs-6fbpw"/><path fill="url(#iU0xveW)" class="rgs-6fbpw"/><path class="lr6p412xr"/><path fill="url(#iJvbFZb)" class="gt-y46nru"/><path fill="url(#iMrfvye)" class="gt-y46nru"/><path fill="url(#ip742Bh)" class="gt-y46nru"/><path fill="url(#izyBClb)" class="gt-y46nru"/><path fill="url(#irX7roe)" class="gt-y46nru"/><path fill="url(#iB984Kc)" class="gt-y46nru"/><path class="dk0gm-byq"/><path fill="url(#i1Dor5L)" class="s6ufut5ul"/><path fill="url(#iv6Yn7W)" class="s6ufut5ul"/><path fill="url(#i4wIgAd)" class="s6ufut5ul"/><g filter="url(#ihhkzjc)"><path fill="url(#iMxg50h)" class="r_ngogb8h"/><path fill="url(#iS1zIlb)" class="r_ngogb8h"/><path fill="url(#iKISTQd)" class="r_ngogb8h"/></g><path class="wkmk90b2p"/><path fill="url(#iPGMG9c)" class="z0t4qbbcm"/><path fill="url(#i7Jd2Db)" class="t5myppnsc"/><g filter="url(#iPkp7ec)"><path fill="url(#ihLUKtb)" class="fmoxrnbbh"/></g><path fill="url(#idniLce)" class="fmoxrnbbh"/><path fill="url(#iVA9TDw)" class="fmoxrnbbh"/><path fill="url(#iZ15y7d)" class="fmoxrnbbh"/><path fill="url(#iWgP2rd)" class="fmoxrnbbh"/><path fill="url(#iO1ZvRb)" class="fmoxrnbbh"/><path fill="url(#iB3sTKd)" class="fmoxrnbbh"/><path fill="url(#iSek39F)" class="fmoxrnbbh"/><path fill="url(#iU7mCnd)" class="fmoxrnbbh"/><path fill="url(#icMvwze)" class="fmoxrnbbh"/><g filter="url(#igrXmbc)"><path class="wus1lvu3r"/></g><g filter="url(#ihSM1Qd)"><path class="fng99fqeo"/><path fill="url(#iCuDRze)" class="l3290_omc"/><path fill="url(#iLKv0nc)" class="l3290_omc"/><path fill="url(#i3L0PxJ)" class="l3290_omc"/><path fill="url(#iJXU5Qx)" class="l3290_omc"/><path fill="url(#iAcGNZb)" class="l3290_omc"/></g><g filter="url(#ipPdYpb)"><path stroke="url(#iHQeGNd)" class="n9_9y0bde"/></g><path fill="url(#iRtRwoc)" class="hbwaqmrec"/><g filter="url(#icn41jc)"><path fill="url(#iRBdCub)" class="k8crpo2qf"/><path fill="url(#ipTcUsb)" class="k8crpo2qf"/><path fill="url(#iOKCx5x)" class="k8crpo2qf"/><path fill="url(#i2gQFFc)" class="k8crpo2qf"/><path fill="url(#iQ0xzhy)" class="k8crpo2qf"/></g><g filter="url(#igUFyze)"><path class="khe1f0wmc"/></g><g filter="url(#iryVANb)"><path class="k_9-5705g"/></g><g filter="url(#iYG6gTC)"><path class="bxqa03bla"/><path fill="url(#iO2xNnd)" class="weeq6_bsp"/><path fill="url(#iCViIhd)" class="weeq6_bsp"/></g><g filter="url(#i2p0bzd)"><path class="eqs32abud"/><path fill="url(#ilpDOWB)" class="ioy4g-b-v"/></g><path class="f_o1x5bna"/><path fill="url(#i0r4fgb)" class="bn-zyfi_h"/><path class="q68kjqb7h"/><g filter="url(#iZZQxdc)"><path class="nwldfrb3p"/><path fill="url(#iR0lLbq)" class="g5wyki2wj"/></g><g filter="url(#ibvogGd)"><path fill="url(#ij00jXb)" class="r29v8vboh"/></g><path class="st6whsb7d"/><path fill="url(#i4hyl0d)" class="woq4pjb0f"/><path class="lcip4nb-l"/><g filter="url(#ieNoNtb)"><path fill="url(#imlYCrd)" class="z-90kcitb"/></g><g filter="url(#i6upZte)"><ellipse transform="rotate(-27.914 13.408 9.954)" class="dofztio7y"/><ellipse fill="url(#i0AAlkd)" transform="rotate(-27.914 13.408 9.954)" class="xycinvbud"/></g><path fill="url(#i3ccNMN)" class="lmxr-1n9l"/><path fill="url(#iqe0O8c)" class="lmxr-1n9l"/><path fill="url(#iAn7Lfe)" class="lmxr-1n9l"/><path fill="url(#iyARIse)" class="lmxr-1n9l"/><path fill="url(#i9VPOzc)" class="iwk7h9zbo"/><path fill="url(#iGT6Syd)" class="iwk7h9zbo"/><g filter="url(#ijBLsFb)"><path fill="url(#ictKFHI)" class="ipgpnwb8w"/></g><g filter="url(#iItPted)"><path fill="url(#iNjtrRb)" class="fh9srbb-t"/></g><g filter="url(#ilnXOed)"><path class="nx6lzwbee"/></g><g filter="url(#iSe3sEd)"><path class="zp2x7ygcj"/></g><g filter="url(#it8Ek5d)"><path class="l2gkvacph"/></g><g filter="url(#iKl8iYc)"><path class="w3k1mgbbp"/></g><defs><radialGradient id="iOokUYv" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 -2.4375 2.72822 4.02238 6.877 17.33)" gradientUnits="userSpaceOnUse"><stop class="dgu6o60tg"/><stop offset="1" class="n_p-4bbbu"/></radialGradient><radialGradient id="ig6gRjd" cx="0" cy="0" r="1" gradientTransform="matrix(-.01562 -1.76562 2.48224 -.02197 8.596 17.83)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="v6wds2dtn"/><stop offset="1" class="nz8ufunsm"/></radialGradient><radialGradient id="ifqCFkS" cx="0" cy="0" r="1" gradientTransform="matrix(-5.47138 9.4622 -7.02133 -4.05998 10.46 19.268)" gradientUnits="userSpaceOnUse"><stop class="qc0o5_36v"/><stop offset="1" class="snymmbrnj"/></radialGradient><radialGradient id="igczLIe" cx="0" cy="0" r="1" gradientTransform="rotate(44.444 -1.585 1.225)scale(4.68833)" gradientUnits="userSpaceOnUse"><stop class="qc07hnbjk"/><stop offset=".836" class="b_5radckw"/></radialGradient><radialGradient id="iE9wJUA" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -1.59375 5.11385 -.10027 2.316 5.313)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vze8wny8i"/><stop offset="1" class="o4sg_vbnc"/></radialGradient><radialGradient id="iiFjNse" cx="0" cy="0" r="1" gradientTransform="matrix(4.95236 7.33803 -10.65664 7.19205 1.352 1.24)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="r8td-ob5s"/><stop offset=".819" class="eegxz98yy"/></radialGradient><radialGradient id="i4UUWGe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35939 5.78125 -6.81223 -1.6018 23.096 22.58)" gradientUnits="userSpaceOnUse"><stop class="yf3t3eb5f"/><stop offset="1" class="a66gbwbzh"/></radialGradient><radialGradient id="i7GTaad" cx="0" cy="0" r="1" gradientTransform="matrix(6.87457 8.07189 -11.19707 9.5362 6.418 22.32)" gradientUnits="userSpaceOnUse"><stop class="pbkzvtx_w"/><stop offset="1" class="ykdcls_lk"/></radialGradient><radialGradient id="iJvbFZb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18749 3.03127 -6.31539 -6.64086 13.752 16.392)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="k3qin7bzy"/><stop offset="1" class="x3axlob0n"/></radialGradient><radialGradient id="ip742Bh" cx="0" cy="0" r="1" gradientTransform="matrix(-4.82764 -11.66358 1.58185 -.65474 15.958 28.962)" gradientUnits="userSpaceOnUse"><stop class="z2ddyab4m"/><stop offset="1" class="cqgvl433q"/></radialGradient><radialGradient id="irX7roe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37282 -3.155 .92095 -.40073 16.346 27.58)" gradientUnits="userSpaceOnUse"><stop class="h3e5alaje"/><stop offset="1" class="u4bo2-o9a"/></radialGradient><radialGradient id="iB984Kc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15863 -1.17796 1.62432 -1.59766 14.336 18.515)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="gyulks50m"/><stop offset="1" class="atms-xm-n"/></radialGradient><radialGradient id="iv6Yn7W" cx="0" cy="0" r="1" gradientTransform="matrix(2.01563 -.67188 .83418 2.50254 17.502 18.33)" gradientUnits="userSpaceOnUse"><stop offset=".374" class="k-y64ibbx"/><stop offset="1" class="pjzr3aclu"/></radialGradient><radialGradient id="i4wIgAd" cx="0" cy="0" r="1" gradientTransform="rotate(110.875 2.49 18.294)scale(11.8396 2.00952)" gradientUnits="userSpaceOnUse"><stop class="bc2qs9bhj"/><stop offset="1" class="ktoycacxm"/></radialGradient><radialGradient id="iS1zIlb" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 1.75 -2.19025 2.26847 13.158 17.204)" gradientUnits="userSpaceOnUse"><stop offset=".275" class="p2wvms-7r"/><stop offset="1" class="a0_4-ebgl"/></radialGradient><radialGradient id="iKISTQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.01211 -.76307 0 16.64 16.221)" gradientUnits="userSpaceOnUse"><stop class="vjc5s1b0i"/><stop offset="1" class="htop0jbiy"/></radialGradient><radialGradient id="iPGMG9c" cx="0" cy="0" r="1" gradientTransform="matrix(.75578 2.03842 -2.42149 .8978 20.682 11.926)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="i7Jd2Db" cx="0" cy="0" r="1" gradientTransform="matrix(1.49027 .46837 -1.44496 4.5976 9.771 12.42)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="ihLUKtb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.27675 0 0 -9.33451 18.718 10.976)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="iVA9TDw" cx="0" cy="0" r="1" gradientTransform="rotate(94.704 6.435 10.554)scale(12.5821 10.4195)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="iZ15y7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15909 1.43438 0 18.355 9.65)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="iWgP2rd" cx="0" cy="0" r="1" gradientTransform="matrix(.00397 -1.10451 1.20197 .00432 13.563 9.697)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="iO1ZvRb" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.486 6.292)scale(8.59252 21.9496)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="iB3sTKd" cx="0" cy="0" r="1" gradientTransform="matrix(4.1111 -2.67306 .97853 1.50495 10.366 6.61)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iSek39F" cx="0" cy="0" r="1" gradientTransform="matrix(-.23685 2.5208 -1.00767 -.09468 21.481 8.031)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iU7mCnd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75946 2.90992 -2.40237 -1.45258 18.334 5.95)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="iLKv0nc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .24639 -.77436 0 16.355 12.349)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="iJXU5Qx" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 6.95 7.685)scale(1.68906 2.71445)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="iRtRwoc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72748 2.92683 0 15.884 14.548)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="ipTcUsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.53407 8.93726 0 10.606 8.056)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iOKCx5x" cx="0" cy="0" r="1" gradientTransform="matrix(.1151 -2.53604 4.49336 .20395 20.79 9.379)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="i2gQFFc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.38089 -1.56592 1.14946 -1.7477 20.03 3.044)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iQ0xzhy" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 6.202 14.094)scale(1.74675 4.04464)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iO2xNnd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.22171 0 0 -.82456 16.14 3.717)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iCViIhd" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.183 -5.59)scale(6.08299 6.73932)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="ilpDOWB" cx="0" cy="0" r="1" gradientTransform="matrix(3.2786 .38323 -.16045 1.37268 17.65 6.077)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="i0r4fgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8189 -1.30256 0 18.087 10.05)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iR0lLbq" cx="0" cy="0" r="1" gradientTransform="matrix(-.23409 -.30165 .4153 -.32228 17.856 10.136)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4hyl0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81895 -1.30263 0 13.682 10.05)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i0AAlkd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.753 -1.456)scale(.49877 .59953)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iqe0O8c" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 3.636 18.579)scale(2.35146 2.24347)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="iAn7Lfe" cx="0" cy="0" r="1" gradientTransform="matrix(.79515 -1.09121 .91466 .6665 20.909 10.615)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iyARIse" cx="0" cy="0" r="1" gradientTransform="matrix(.5925 -1.56492 2.09095 .79165 21.024 10.788)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iGT6Syd" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.086 9.455)scale(2.13648 2.10035)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="ictKFHI" cx="0" cy="0" r="1" gradientTransform="matrix(-.92505 .15879 -.07003 -.408 10.924 10.714)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><filter id="ihhkzjc" width="6.879" height="10.938" x="12.32" y="16.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0509804 0 0 0 0 0.0392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_779"/></filter><filter id="iPkp7ec" width="11.316" height="12.657" x="10.774" y="4.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_779"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_779" result="effect2_innerShadow_4002_779"/></filter><filter id="igrXmbc" width="3.763" height="4.927" x="13.86" y="9.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_779" stdDeviation=".5"/></filter><filter id="ihSM1Qd" width="2.295" height="3.327" x="14.737" y="9.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_779" stdDeviation=".1"/></filter><filter id="ipPdYpb" width="3.749" height="1.583" x="14.01" y="13.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_779" stdDeviation=".05"/></filter><filter id="icn41jc" width="12.993" height="8.43" x="9.388" y="1.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_779"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_779" result="effect2_innerShadow_4002_779"/></filter><filter id="igUFyze" width="2.36" height="1.2" x="17.488" y="7.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_779"/></filter><filter id="iryVANb" width="2.36" height="1.185" x="12.183" y="7.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_779"/></filter><filter id="iYG6gTC" width="6.791" height="6.043" x="9.749" y="2.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_779"/><feGaussianBlur result="effect2_foregroundBlur_4002_779" stdDeviation=".125"/></filter><filter id="i2p0bzd" width="6.419" height="5.787" x="15.724" y="3.067" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_779"/><feGaussianBlur result="effect2_foregroundBlur_4002_779" stdDeviation=".125"/></filter><filter id="iZZQxdc" width=".792" height=".701" x="17.347" y="9.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_779" stdDeviation=".05"/></filter><filter id="ibvogGd" width=".896" height=".918" x="18.195" y="9.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_779" stdDeviation=".1"/></filter><filter id="ieNoNtb" width=".992" height="1.046" x="13.711" y="9.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_779" stdDeviation=".1"/></filter><filter id="i6upZte" width=".92" height=".709" x="12.948" y="9.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_779" stdDeviation=".05"/></filter><filter id="ijBLsFb" width="1.337" height="2.397" x="9.749" y="9.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_779" stdDeviation=".125"/></filter><filter id="iItPted" width="1.955" height="2.921" x="20.373" y="9.247" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_779" stdDeviation=".25"/></filter><filter id="ilnXOed" width="2.421" height="1.164" x="12.105" y="7.351" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_779" stdDeviation=".125"/></filter><filter id="iSe3sEd" width="2.421" height="1.164" x="17.433" y="7.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_779" stdDeviation=".125"/></filter><filter id="it8Ek5d" width="5.301" height="3.02" x="16.779" y="3.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_779" stdDeviation=".375"/></filter><filter id="iKl8iYc" width="3.076" height="1.977" x="15.252" y="17.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_779" stdDeviation=".3"/></filter><linearGradient id="iFqMHgd" x1="24.158" x2="24.189" y1="30.329" y2="26.673" gradientUnits="userSpaceOnUse"><stop offset=".078" class="npfrbd3jd"/><stop offset="1" class="w_5-rbc1a"/></linearGradient><linearGradient id="iS6d3Rd" x1="18.12" x2="19.472" y1="27.765" y2="28.151" gradientUnits="userSpaceOnUse"><stop class="p5jt_ib0l"/><stop offset="1" class="hw19_ybat"/></linearGradient><linearGradient id="iU0xveW" x1="13.658" x2="12.158" y1="28.736" y2="29.267" gradientUnits="userSpaceOnUse"><stop class="h65uoi6pi"/><stop offset="1" class="g04ogacjt"/></linearGradient><linearGradient id="iMrfvye" x1="12.315" x2="13.69" y1="27.392" y2="26.829" gradientUnits="userSpaceOnUse"><stop offset=".223" class="d05zivoho"/><stop offset="1" class="ue2ywxbfs"/></linearGradient><linearGradient id="izyBClb" x1="15.627" x2="14.221" y1="30.173" y2="29.486" gradientUnits="userSpaceOnUse"><stop offset=".208" class="cu8bl7b6w"/><stop offset="1" class="bkwavzmor"/></linearGradient><linearGradient id="i1Dor5L" x1="16.002" x2="18.033" y1="24.829" y2="25.736" gradientUnits="userSpaceOnUse"><stop class="ego3-fbwo"/><stop offset="1" class="up5p4s41k"/></linearGradient><linearGradient id="iMxg50h" x1="16.367" x2="16.367" y1="25.145" y2="15.619" gradientUnits="userSpaceOnUse"><stop class="rh4-2jbhq"/><stop offset="1" class="au_bk3bwb"/></linearGradient><linearGradient id="idniLce" x1="21.09" x2="16.697" y1="12.677" y2="12.677" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="icMvwze" x1="15.932" x2="15.932" y1="17.286" y2="16.64" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="iCuDRze" x1="16.73" x2="15.884" y1="11.657" y2="11.692" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="i3L0PxJ" x1="15.884" x2="15.884" y1="12.807" y2="12.337" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iAcGNZb" x1="15.884" x2="15.884" y1="9.824" y2="10.628" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="iHQeGNd" x1="14.671" x2="14.993" y1="14.392" y2="13.55" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iRBdCub" x1="22.8" x2="11.079" y1="5.26" y2="5.26" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="ij00jXb" x1="18.872" x2="18.555" y1="10.105" y2="10.3" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="imlYCrd" x1="14.433" x2="14.116" y1="10.105" y2="10.3" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3ccNMN" x1="22.381" x2="21.163" y1="10.133" y2="12.329" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="i9VPOzc" x1="9.98" x2="11.452" y1="10.843" y2="10.714" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iNjtrRb" x1="21.351" x2="21.351" y1="9.747" y2="11.668" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-steamy-room-dark" /></template>
<style>
.a0_4-ebgl {
  stop-color: var(--svg-color--381e1a, #381E1A);
  stop-opacity: 0;
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a66gbwbzh {
  stop-color: var(--svg-color--f65c3e, #F65C3E);
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.atms-xm-n {
  stop-color: var(--svg-color--9e2625, #9E2625);
  stop-opacity: 0;
}

.au_bk3bwb {
  stop-color: var(--svg-color--462a27, #462A27);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.b_5radckw {
  stop-color: var(--svg-color--f2e8f1, #F2E8F1);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bc2qs9bhj {
  stop-color: var(--svg-color--ff7347, #FF7347);
}

.bkwavzmor {
  stop-color: var(--svg-color--dd5022, #DD5022);
  stop-opacity: 0;
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.bn-zyfi_h {
  d: path("M18.089 9.57a.9.9 0 0 1 .868 1.138h-1.74a.904.904 0 0 1 .872-1.138");
}

.bxqa03bla {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.119 5.307l-.067-.138a.67.67 0 0 0-.62-.422h-1.286c-1.863 0-3.372 1.527-3.372 3.41v.279c-.343-.262-.775-.813-.775-1.704c0-1.082.79-1.629 1.292-1.978a2.5 2.5 0 0 0 .334-.255l.1-.106c.354-.374.982-1.04 2.08-1.332a5.5 5.5 0 0 1 1.53-.167c.472.012.805.42.805.893v1.507z");
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cqgvl433q {
  stop-color: var(--svg-color--f47246, #F47246);
  stop-opacity: 0;
}

.cu8bl7b6w {
  stop-color: var(--svg-color--dd5022, #DD5022);
}

.d05zivoho {
  stop-color: var(--svg-color--e45c36, #E45C36);
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.dgu6o60tg {
  stop-color: var(--svg-color--e1dae6, #E1DAE6);
}

.dk0gm-byq {
  fill: var(--svg-color--ec551b, #EC551B);
  d: path("M21.82 17.353c-.641-1.313-1.82-1.75-2.594-1.75h-2.61v2.875h2.47c.168.303.002.85-.102 1.086l-3.939 10.39h3.176c1.068-2.583 2.995-7.817 3.383-8.742c.42-1.004.81-2.476.216-3.86");
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.dofztio7y {
  cx: 13.408px;
  cy: 9.954px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.393px;
  ry: 0.199px;
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eegxz98yy {
  stop-color: var(--svg-color--dac9f0, #DAC9F0);
}

.ego3-fbwo {
  stop-color: var(--svg-color--ce3b1b, #CE3B1B);
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.eqs32abud {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m21.146 8.605l-.03-.637c-.01-.771-.647-1.407-1.418-1.44h-1.413c-.897 0-1.716-.49-2.144-1.27c0 0-.062-.144-.125-.388c-.252-.97.674-1.713 1.659-1.523c.986.19 2.113.522 2.945 1.065c1.761 1.148 1.453 3.218.526 4.193");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f_o1x5bna {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.298 9.295c.659 0 1.216.454 1.367 1.069a.277.277 0 0 1-.27.343h-2.252a.232.232 0 0 1-.23-.274a1.41 1.41 0 0 1 1.385-1.138");
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fh9srbb-t {
  d: path("M20.874 11.668q.058-.96.111-1.92a.965.965 0 0 1-.111 1.92");
}

.fmoxrnbbh {
  d: path("M11.014 13.766a3.95 3.95 0 0 0 3.923 3.438h1.904a3.95 3.95 0 0 0 3.922-3.438c.119-1.9.239-3.795.327-5.695a1.463 1.463 0 0 0-1.392-1.445h-1.413a2.44 2.44 0 0 1-2.233-1.457a.67.67 0 0 0-.62-.422h-1.285c-1.863 0-3.373 1.527-3.373 3.41c0 1.879.117 3.727.24 5.61");
}

.fng99fqeo {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.499 10.254l-.537 1.856c-.11.382.153.763.526.763h.793c.373 0 .635-.387.526-.763l-.537-1.856c-.115-.41-.651-.41-.771 0");
}

.ft5dv1b6b {
  fill: none;
}

.g04ogacjt {
  stop-color: var(--svg-color--d63c26, #D63C26);
  stop-opacity: 0;
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.g5wyki2wj {
  d: path("M18.023 9.76c.064.086-.07.19-.223.304c-.152.114-.266.195-.33.109s.008-.248.16-.362c.153-.114.328-.137.393-.051");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gt-y46nru {
  d: path("M9.9 17.353c.641-1.313 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.583-3.292-7.817-3.68-8.742c-.42-1.004-.89-2.476-.297-3.86");
}

.gyulks50m {
  stop-color: var(--svg-color--9e2625, #9E2625);
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.h3e5alaje {
  stop-color: var(--svg-color--c03005, #C03005);
}

.h65uoi6pi {
  stop-color: var(--svg-color--d63c26, #D63C26);
}

.hbwaqmrec {
  d: path("M15.884 13.9c-.512 0-.993-.121-1.398-.332c-.138-.07-.287.085-.2.21c.338.513.927.855 1.598.855s1.26-.342 1.599-.854c.087-.13-.062-.282-.2-.211a3 3 0 0 1-1.399.331");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.htop0jbiy {
  stop-color: var(--svg-color--513f3e, #513F3E);
  stop-opacity: 0;
}

.hw19_ybat {
  stop-color: var(--svg-color--e04438, #E04438);
  stop-opacity: 0;
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.iksuiqrgf {
  cx: 8.275px;
  cy: 23.368px;
  r: 6.305px;
}

.ioy4g-b-v {
  d: path("m21.146 8.605l-.03-.637c-.01-.771-.647-1.407-1.418-1.44h-1.413c-.897 0-1.716-.49-2.144-1.27c0 0-.062-.144-.125-.388c-.252-.97.674-1.713 1.659-1.523c.986.19 2.113.522 2.945 1.065c1.761 1.148 1.453 3.218.526 4.193");
}

.ipgpnwb8w {
  d: path("M10.752 9.766a.965.965 0 0 0 .084 1.897a79 79 0 0 1-.085-1.897");
}

.iwk7h9zbo {
  d: path("M10.783 9.1a1.624 1.624 0 0 0 .14 3.23a79 79 0 0 1-.14-3.23");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.k_9-5705g {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.442 7.858a2.8 2.8 0 0 1 1.755-.363a.28.28 0 1 1-.068.556a2.24 2.24 0 0 0-1.4.287a1 1 0 0 0-.092.06l-.003.003a.28.28 0 0 1-.343-.443z");
}

.k-y64ibbx {
  stop-color: var(--svg-color--99201f, #99201F);
}

.k3qin7bzy {
  stop-color: var(--svg-color--b22307, #B22307);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.k8crpo2qf {
  d: path("M20.785 4.27c.519.18.985.542 1.279 1.062a2.39 2.39 0 0 1-.107 2.55a1.57 1.57 0 0 0-.273.882v1.2a1.8 1.8 0 0 0-.674-.271l.08-1.622a1.463 1.463 0 0 0-1.392-1.445h-1.413a2.44 2.44 0 0 1-2.233-1.457a.67.67 0 0 0-.62-.422h-1.286c-1.863 0-3.372 1.527-3.372 3.41l.03 1.553a1.7 1.7 0 0 0-.726.266V8.764c0-.314-.097-.622-.273-.882a2.41 2.41 0 0 1-.145-2.469a2.37 2.37 0 0 1 1.312-1.137a2.7 2.7 0 0 0 1.397-1.12a2.35 2.35 0 0 1 2.918-.92a1.5 1.5 0 0 0 1.204 0c.284-.12.594-.19.92-.19c.852 0 1.596.46 2.008 1.142c.31.514.798.888 1.366 1.083");
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.khe1f0wmc {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.652 7.968a1.9 1.9 0 0 0-.694-.415c-.307-.097-.691-.123-1.223-.058a.28.28 0 1 0 .067.556c.486-.06.784-.028.988.036c.2.063.336.165.495.303a.28.28 0 0 0 .367-.422");
}

.ktoycacxm {
  stop-color: var(--svg-color--f6682e, #F6682E);
  stop-opacity: 0;
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.l2gkvacph {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M20.116 5.325h-2.1a.487.487 0 1 1 .078-.97c.545.087 1.268.208 1.753.328c1.096.271 1.398.805 1.483 1.185a1.53 1.53 0 0 0-1.214-.543");
}

.l3290_omc {
  d: path("m15.499 10.254l-.537 1.856c-.11.382.153.763.526.763h.793c.373 0 .635-.387.526-.763l-.537-1.856c-.115-.41-.651-.41-.771 0");
}

.lcip4nb-l {
  fill: var(--svg-color--000, #000);
  d: path("M14.196 10.47a.514.514 0 0 0-.516-.516a.514.514 0 0 0-.459.753h.913a.5.5 0 0 0 .062-.237");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmxr-1n9l {
  d: path("M20.852 12.329q.101-1.61.187-3.221a1.625 1.625 0 0 1-.187 3.221");
}

.lr6p412xr {
  fill: var(--svg-color--ed561d, #ED561D);
  d: path("M9.9 17.353c.641-1.313 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.583-3.292-7.817-3.68-8.742c-.42-1.004-.89-2.476-.297-3.86");
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.n_p-4bbbu {
  stop-color: var(--svg-color--e6dee6, #E6DEE6);
}

.n5l_opbqq {
  r: 6.305px;
}

.n9_9y0bde {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.52 13.501c.394.205.864.323 1.364.323c.506 0 .97-.118 1.364-.323a.23.23 0 0 1 .273.045c.065.067.09.176.024.274m-3.024-.319l2.962.278M14.52 13.5h-.001a.23.23 0 0 0-.273.047a.21.21 0 0 0-.023.273m.297-.32l-.235.278m3.26.041h-.001l-.062-.041m.062.041l-.062-.041m.062.041a1.99 1.99 0 0 1-1.66.888a1.99 1.99 0 0 1-1.66-.887m3.258-.042a1.91 1.91 0 0 1-1.599.854c-.67 0-1.26-.342-1.598-.854m-.062.042l.062-.042m-.062.042v-.001l.062-.041");
}

.npfrbd3jd {
  stop-color: var(--svg-color--dd3537, #DD3537);
}

.nwldfrb3p {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.023 9.76c.064.086-.07.19-.223.304c-.152.114-.266.195-.33.109s.008-.248.16-.362c.153-.114.328-.137.393-.051");
}

.nx6lzwbee {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.48 8.14c.26-.186.906-.513 1.67-.385");
}

.nz8ufunsm {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
  stop-opacity: 0;
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o4sg_vbnc {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
  stop-opacity: 0;
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p2wvms-7r {
  stop-color: var(--svg-color--340f0b, #340F0B);
}

.p5jt_ib0l {
  stop-color: var(--svg-color--e04438, #E04438);
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pbkzvtx_w {
  stop-color: var(--svg-color--e06d3d, #E06D3D);
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pjzr3aclu {
  stop-color: var(--svg-color--d03d1c, #D03D1C);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.q68kjqb7h {
  fill: var(--svg-color--000, #000);
  d: path("M17.573 10.47c0-.286.23-.516.516-.516a.514.514 0 0 1 .459.754h-.914a.47.47 0 0 1-.061-.238");
}

.qc07hnbjk {
  stop-color: var(--svg-color--fbf7ff, #FBF7FF);
}

.qc0o5_36v {
  stop-color: var(--svg-color--e0d6e3, #E0D6E3);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qnar36wle {
  r: 4.086px;
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_bcr-ntk {
  cx: 10.674px;
  cy: 16.165px;
  r: 4.086px;
}

.r_ngogb8h {
  d: path("M14.01 16.517h4v.887c.01.175.045.374.152.53a.8.8 0 0 0 .446.333l.464.164c.076.068.22.478.04.984c-.181.505-2.043 5.51-3.094 8.02v.02l-.004-.01l-.005.01v-.02c-1.052-2.51-3.139-7.515-3.32-8.02c-.18-.506-.122-.87-.046-.937l.68-.192c.218-.062.373-.14.515-.347c.113-.166.158-.39.172-.572z");
}

.r29v8vboh {
  d: path("M18.891 10.352a.85.85 0 0 0-.233-.467l-.263.287l.119.23z");
}

.r8td-ob5s {
  stop-color: var(--svg-color--f3ebfe, #F3EBFE);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rgs-6fbpw {
  d: path("M5.096 29.939c0-7.961 4.617-9.875 5.375-10.383l5.047 10.383z");
}

.rh4-2jbhq {
  stop-color: var(--svg-color--4b3030, #4B3030);
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.s6ufut5ul {
  d: path("M21.82 17.353c-.641-1.313-1.82-1.75-2.594-1.75h-2.61v2.875h2.47c.168.303.002.85-.102 1.086l-3.939 10.39h3.176c1.068-2.583 2.995-7.817 3.383-8.742c.42-1.004.81-2.476.216-3.86");
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.snymmbrnj {
  stop-color: var(--svg-color--d5c4df, #D5C4DF);
}

.st6whsb7d {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.471 9.295a1.41 1.41 0 0 0-1.367 1.069a.277.277 0 0 0 .27.344h2.252a.232.232 0 0 0 .23-.275a1.414 1.414 0 0 0-1.385-1.138");
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t5myppnsc {
  d: path("M10.978 12.237a1.66 1.66 0 0 1-.913-.311v.94c0 .901.537 1.704 1.353 2.037a4.1 4.1 0 0 1-.349-1.19z");
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u4bo2-o9a {
  stop-color: var(--svg-color--d84f1a, #D84F1A);
  stop-opacity: 0;
}

.ue2ywxbfs {
  stop-color: var(--svg-color--e45c36, #E45C36);
  stop-opacity: 0;
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.up5p4s41k {
  stop-color: var(--svg-color--e64812, #E64812);
  stop-opacity: 0;
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.v6wds2dtn {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
}

.vjc5s1b0i {
  stop-color: var(--svg-color--513f3e, #513F3E);
}

.vze8wny8i {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
}

.w_5-rbc1a {
  stop-color: var(--svg-color--dd3537, #DD3537);
  stop-opacity: 0;
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

.w3k1mgbbp {
  stroke: var(--svg-color--655554, #655554);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M16.152 18.338c.19.027.71.032 1.275-.163");
}

.w8e9izb-y {
  d: path("M26.947 29.939c0-7.961-4.617-9.875-5.375-10.383l-5.047 10.383z");
}

.weeq6_bsp {
  d: path("m16.119 5.307l-.067-.138a.67.67 0 0 0-.62-.422h-1.286c-1.863 0-3.372 1.527-3.372 3.41v.279c-.343-.262-.775-.813-.775-1.704c0-1.082.79-1.629 1.292-1.978a2.5 2.5 0 0 0 .334-.255l.1-.106c.354-.374.982-1.04 2.08-1.332a5.5 5.5 0 0 1 1.53-.167c.472.012.805.42.805.893v1.507z");
}

.wkmk90b2p {
  fill: var(--svg-color--e8d6ff, #E8D6FF);
  d: path("M1.97 24.017h3.298a5.94 5.94 0 0 1 5.937 5.937H1.971zm28.06 0h-3.298a5.94 5.94 0 0 0-5.937 5.937h9.234z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.woq4pjb0f {
  d: path("M13.68 9.57a.9.9 0 0 0-.868 1.138h1.74a1 1 0 0 0 .033-.238a.907.907 0 0 0-.905-.9");
}

.wus1lvu3r {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.48 10.452l-.597 1.855c-.102.382.143.764.489.764h.738c.347 0 .591-.388.49-.764l-.5-1.855c-.107-.411-.509-.411-.62 0");
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x3axlob0n {
  stop-color: var(--svg-color--e24c14, #E24C14);
  stop-opacity: 0;
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xycinvbud {
  cx: 13.408px;
  cy: 9.954px;
  rx: 0.393px;
  ry: 0.199px;
}

.yf3t3eb5f {
  stop-color: var(--svg-color--ff8244, #FF8244);
}

.ykdcls_lk {
  stop-color: var(--svg-color--dd3d3d, #DD3D3D);
}

.z-90kcitb {
  d: path("M14.503 10.364c0-.29-.237-.485-.3-.543l-.292.281l.18.365z");
}

.z0t4qbbcm {
  d: path("M20.791 12.237c.338-.01.655-.126.913-.311v.94c0 .901-.537 1.704-1.353 2.037q.26-.55.349-1.19z");
}

.z2ddyab4m {
  stop-color: var(--svg-color--f47246, #F47246);
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zp2x7ygcj {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.479 8.094c-.26-.186-.906-.514-1.67-.385");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
