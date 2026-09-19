<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iEqcAze)"><path fill="url(#it4ti6b)" class="aemo1cb1q"/><path fill="url(#icfoy8d)" class="aemo1cb1q"/></g><g filter="url(#ihoBhlb)"><path fill="url(#i6M7y8c)" class="k9wtqmbef"/></g><path fill="url(#inVhzSd)" class="k9wtqmbef"/><g filter="url(#i9v6Zod)"><path class="uciguo95i"/><path fill="url(#il9wKGe)" class="p823fnbia"/></g><g filter="url(#irVL8Ec)"><path fill="url(#i5oiOlX)" clip-rule="evenodd" class="ftl41uazn"/></g><g filter="url(#iA8YEtc)"><circle stroke="url(#iFDDVqX)" class="z2ogs_vck"/></g><path fill="url(#iqcxYCd)" class="rtqrfdb3t"/><path class="rmo1iwb_p"/><path fill="url(#ib6qBDb)" class="wo7enbs3l"/><path fill="url(#iNgKCll)" class="wo7enbs3l"/><path fill="url(#inLgqpd)" clip-rule="evenodd" class="ra689e2fy"/><path fill="url(#i4ErWdb)" clip-rule="evenodd" class="ra689e2fy"/><path fill="url(#iAzoYod)" clip-rule="evenodd" class="defuztb0z"/><path fill="url(#i81NlEf)" clip-rule="evenodd" class="frl5-vc4s"/><path fill="url(#ioVnG4d)" clip-rule="evenodd" class="frl5-vc4s"/><g filter="url(#iVJLfzd)"><path fill="url(#i4Z9sud)" clip-rule="evenodd" class="fhxrfacsu"/><path fill="url(#i74ryGd)" clip-rule="evenodd" class="fhxrfacsu"/></g><path fill="url(#ixcAGVL)" clip-rule="evenodd" class="ng_8ekg9m"/><path fill="url(#iDmVz3c)" clip-rule="evenodd" class="x0la_kp1k"/><path fill="url(#i6cTuqc)" clip-rule="evenodd" class="x0la_kp1k"/><path fill="url(#izVRZWc)" clip-rule="evenodd" class="x0la_kp1k"/><path fill="url(#iddVvyd)" class="m3fnulbuf"/><path fill="url(#iC41ekd)" class="m3fnulbuf"/><path fill="url(#iSGll2c)" class="m3fnulbuf"/><path fill="url(#iO2HNIb)" class="qh--u2bfq"/><path fill="url(#iOFPFEc)" class="qh--u2bfq"/><g filter="url(#ilp4Bdd)"><path fill="url(#iaWOFFd)" class="do77voeuo"/><path fill="url(#ixcYfQd)" class="do77voeuo"/></g><circle fill="url(#ikrUZIb)" class="yw84gcbaz"/><circle fill="url(#iCKS5td)" class="yw84gcbaz"/><g filter="url(#ieDEBub)"><path class="yzd4i4kse"/><path fill="url(#iJEtVHd)" class="ovgl0qgnr"/><path fill="url(#iWecI1d)" class="ovgl0qgnr"/></g><path fill="url(#iiO9Ucc)" transform="rotate(-55.397 13.546 8.51)" class="kl_lwk9ux"/><path fill="url(#isjNzXh)" transform="rotate(-55.397 13.546 8.51)" class="kl_lwk9ux"/><g filter="url(#iM4apRy)"><path fill="url(#ib3S52d)" class="n1wukybpj"/><path fill="url(#ibAf6Nb)" class="n1wukybpj"/></g><g filter="url(#idM9Dve)"><path fill="url(#iHL5fEd)" class="t0umacb5g"/><path fill="url(#i3QeoVn)" class="t0umacb5g"/></g><g filter="url(#itWcxJz)"><path fill="url(#iH8N9lN)" class="r5h7b-urd"/></g><g filter="url(#imLKpMC)"><path class="yjmpw-u6e"/><path fill="url(#irytaAd)" class="oxt4ifqva"/></g><g filter="url(#ikUAh0F)"><path clip-rule="evenodd" class="sxz_wf09g"/></g><g filter="url(#iI7hEWd)"><path clip-rule="evenodd" class="lmxfxo9xh"/><path fill="url(#ickWjtb)" clip-rule="evenodd" class="x--0qpb9w"/></g><path fill="url(#iz6Cc8d)" clip-rule="evenodd" class="ypkdur5_u"/><path fill="url(#imvWp0c)" clip-rule="evenodd" class="ypkdur5_u"/><g filter="url(#im6QrId)"><path fill="url(#iaARYfe)" class="zro955b4q"/></g><path fill="url(#iMNgVke)" clip-rule="evenodd" class="pm1b-8inu"/><path fill="url(#inMUTsc)" clip-rule="evenodd" class="pm1b-8inu"/><path fill="url(#iIDvl6H)" clip-rule="evenodd" class="o0z3_q1mf"/><path fill="url(#iRXs3Dt)" clip-rule="evenodd" class="o0z3_q1mf"/><g filter="url(#i84Sn5b)"><circle class="o786ujbwq"/></g><path fill="url(#iurjzfd)" class="nme23stjs"/><g filter="url(#iG1DF1d)"><path fill="url(#iHVY1Qc)" class="vy5gs0bfe"/><path fill="url(#iqRW4mb)" class="vy5gs0bfe"/><path fill="url(#iNNnhPd)" class="vy5gs0bfe"/><path fill="url(#iQemYEe)" class="vy5gs0bfe"/></g><path clip-rule="evenodd" class="m22mabb0k"/><path class="mb6yhmklz"/><path fill="url(#iUzJire)" class="fusk07b7u"/><path class="bvfvx5b_v"/><circle transform="rotate(-66.134 11.044 7.609)" class="wcwf26bex"/><g filter="url(#iUaBdOb)"><path fill="url(#i9A12El)" class="b_qw4kb0w"/></g><circle fill="url(#iFPtWxd)" transform="rotate(-66.134 13.448 6.428)" class="inxrwd09n"/><path clip-rule="evenodd" class="p4kao-i7q"/><path fill="url(#iwFnOGd)" clip-rule="evenodd" class="gg4t9o52q"/><path fill="url(#iDqyPfe)" clip-rule="evenodd" class="gg4t9o52q"/><path fill="url(#iLfER1d)" clip-rule="evenodd" class="gg4t9o52q"/><g filter="url(#iJZ78ee)"><path fill="url(#iIhweFm)" class="n7m9lcrvd"/></g><g filter="url(#iGtDMed)"><path fill="url(#ipGUPWb)" class="yfsgwoocz"/></g><defs><radialGradient id="inVhzSd" cx="0" cy="0" r="1" gradientTransform="rotate(150.331 11.723 6.343)scale(3.70975 8.36641)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="l4_q8ccja"/><stop offset="1" class="fy0gg3b4w"/></radialGradient><radialGradient id="il9wKGe" cx="0" cy="0" r="1" gradientTransform="matrix(4.42529 4.18325 -2.33905 2.47438 19.74 27.4)" gradientUnits="userSpaceOnUse"><stop class="qfj7itbso"/><stop offset="1" class="p1dkvx0ja"/></radialGradient><radialGradient id="i5oiOlX" cx="0" cy="0" r="1" gradientTransform="rotate(126.943 -.254 13.402)scale(9.77501 9.43553)" gradientUnits="userSpaceOnUse"><stop class="y16t4y92n"/><stop offset="1" class="hqorccbwh"/></radialGradient><radialGradient id="iNgKCll" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53127 2.45312 -.44454 -.27749 20.337 21.55)" gradientUnits="userSpaceOnUse"><stop class="m3q9izqvj"/><stop offset="1" class="gxtng2bih"/></radialGradient><radialGradient id="i4ErWdb" cx="0" cy="0" r="1" gradientTransform="rotate(-68.026 18.047 .728)scale(2.88119 .32513)" gradientUnits="userSpaceOnUse"><stop class="f-r3ld20z"/><stop offset="1" class="qnv5cwbcc"/></radialGradient><radialGradient id="i81NlEf" cx="0" cy="0" r="1" gradientTransform="matrix(6.71875 4.82813 -1.31599 1.83131 10.212 19.113)" gradientUnits="userSpaceOnUse"><stop class="zo6cprbov"/><stop offset="1" class="cc9670aeb"/></radialGradient><radialGradient id="i4Z9sud" cx="0" cy="0" r="1" gradientTransform="rotate(134.451 9.904 17.375)scale(9.80603 9.46548)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="msqk4cb8o"/><stop offset="1" class="wc0bxtmli"/></radialGradient><radialGradient id="i6cTuqc" cx="0" cy="0" r="1" gradientTransform="rotate(103.707 2.998 16.923)scale(4.61583 .44083)" gradientUnits="userSpaceOnUse"><stop class="rgol9fpyb"/><stop offset="1" class="jk5eocp2v"/></radialGradient><radialGradient id="izVRZWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -1.0625 1.65481 -.04867 18.493 24.348)" gradientUnits="userSpaceOnUse"><stop class="d-6jagb2y"/><stop offset="1" class="zd8v8x_xx"/></radialGradient><radialGradient id="iddVvyd" cx="0" cy="0" r="1" gradientTransform="matrix(-.28125 3.99268 -5.05379 -.356 15.407 15.785)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="hwlgdac9v"/><stop offset=".868" class="o83duvb6p"/></radialGradient><radialGradient id="iC41ekd" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 .45313 -.35 .94138 15.774 17.754)" gradientUnits="userSpaceOnUse"><stop offset=".346" class="t0xl0mbii"/><stop offset="1" class="d9lnsac_l"/></radialGradient><radialGradient id="iSGll2c" cx="0" cy="0" r="1" gradientTransform="rotate(-167.255 8.862 8.03)scale(2.69131 3.58612)" gradientUnits="userSpaceOnUse"><stop offset=".738" class="brfhj2bpt"/><stop offset="1" class="p0n-v6bwi"/><stop offset="1" class="yt4h0-bzj"/></radialGradient><radialGradient id="iO2HNIb" cx="0" cy="0" r="1" gradientTransform="rotate(143.881 6.892 10.236)scale(2.86275 1.23215)" gradientUnits="userSpaceOnUse"><stop offset=".255" class="o5ujuoler"/><stop offset="1" class="cvi6_hb_e"/></radialGradient><radialGradient id="ixcYfQd" cx="0" cy="0" r="1" gradientTransform="matrix(-.86719 0 0 -.96875 25.61 25.41)" gradientUnits="userSpaceOnUse"><stop class="nus19y6ts"/><stop offset="1" class="aiqsdtepb"/></radialGradient><radialGradient id="ikrUZIb" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 -.65625 .66797 1.5904 17.712 25.77)" gradientUnits="userSpaceOnUse"><stop offset=".47" class="v5ts0ibjo"/><stop offset="1" class="huz3s4d_a"/></radialGradient><radialGradient id="iCKS5td" cx="0" cy="0" r="1" gradientTransform="rotate(151.189 6.208 15.08)scale(1.78324)" gradientUnits="userSpaceOnUse"><stop offset=".632" class="da9xf6l5p"/><stop offset="1" class="cbgow0bwo"/></radialGradient><radialGradient id="iWecI1d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1094 -2 6.41983 -3.56106 16.29 26.113)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="egxex7b7c"/><stop offset=".943" class="hs-_dnasa"/></radialGradient><radialGradient id="isjNzXh" cx="0" cy="0" r="1" gradientTransform="matrix(.03133 1.4211 -.52543 .01158 14.971 9.495)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="gcjq1zqgn"/><stop offset="1" class="aflx5ac8k"/></radialGradient><radialGradient id="ib3S52d" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 -8.78125 2.52881 -.21598 17.93 24.504)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="iqlq1pbje"/><stop offset="1" class="o2gu83zjq"/></radialGradient><radialGradient id="ibAf6Nb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6875 .0625 -.11168 -3.01554 18.837 18.223)" gradientUnits="userSpaceOnUse"><stop offset=".284" class="slryrmbbo"/><stop offset="1" class="dpi-7sbrv"/></radialGradient><radialGradient id="iHL5fEd" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 -4.9297 2.6132 2.71672 16.806 16.129)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="zwrak1b2j"/><stop offset="1" class="zvme7yb8w"/></radialGradient><radialGradient id="i3QeoVn" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 -.09375 .01804 .49916 18.228 14.41)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="aw4amab0f"/><stop offset="1" class="jqhw67baa"/></radialGradient><radialGradient id="iH8N9lN" cx="0" cy="0" r="1" gradientTransform="matrix(-3.49999 -4.06251 1.70908 -1.47243 21.118 12.098)" gradientUnits="userSpaceOnUse"><stop class="ff0nxwb2o"/><stop offset="1" class="uakehioxk"/></radialGradient><radialGradient id="irytaAd" cx="0" cy="0" r="1" gradientTransform="matrix(3.25232 0 0 1.29925 10.07 13.535)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="qktpib9mi"/><stop offset="1" class="ms8ncfh9g"/></radialGradient><radialGradient id="ickWjtb" cx="0" cy="0" r="1" gradientTransform="rotate(158.559 7.91 6.339)scale(1.11134 1.23837)" gradientUnits="userSpaceOnUse"><stop class="fze29cbbv"/><stop offset="1" class="mp1bj4bkr"/><stop offset="1" class="af2e8qwjk"/></radialGradient><radialGradient id="iz6Cc8d" cx="0" cy="0" r="1" gradientTransform="matrix(1.70877 .92892 -1.02417 1.884 7.02 13.365)" gradientUnits="userSpaceOnUse"><stop offset=".686" class="fqxr12j4i"/><stop offset="1" class="j9bmo4yzb"/></radialGradient><radialGradient id="imvWp0c" cx="0" cy="0" r="1" gradientTransform="rotate(-169.577 4.876 6.853)scale(1.33255 2.06198)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="xal9k3bum"/><stop offset="1" class="p_o38mbkb"/></radialGradient><radialGradient id="iaARYfe" cx="0" cy="0" r="1" gradientTransform="matrix(5.5 -1.4375 2.00475 7.67032 17.368 15.285)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="f6rwhfb_k"/><stop offset=".905" class="aw8cj7bar"/></radialGradient><radialGradient id="iMNgVke" cx="0" cy="0" r="1" gradientTransform="matrix(1.04759 .75841 -1.02541 1.4164 7.395 14.048)" gradientUnits="userSpaceOnUse"><stop offset=".686" class="fqxr12j4i"/><stop offset="1" class="j9bmo4yzb"/></radialGradient><radialGradient id="inMUTsc" cx="0" cy="0" r="1" gradientTransform="rotate(-167.973 4.915 7.051)scale(.83427 1.78585)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="xal9k3bum"/><stop offset="1" class="p_o38mbkb"/></radialGradient><radialGradient id="iIDvl6H" cx="0" cy="0" r="1" gradientTransform="matrix(1.01589 .59884 -.82449 1.39869 7.728 14.356)" gradientUnits="userSpaceOnUse"><stop offset=".686" class="fqxr12j4i"/><stop offset="1" class="j9bmo4yzb"/></radialGradient><radialGradient id="iRXs3Dt" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 -.07813 .17332 -1.6638 8.59 15.128)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="xal9k3bum"/><stop offset="1" class="p_o38mbkb"/></radialGradient><radialGradient id="iurjzfd" cx="0" cy="0" r="1" gradientTransform="matrix(.7033 .45388 -.35617 .55188 10.738 8.515)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="jxqufcbzg"/><stop offset="1" class="cuptu7i6i"/></radialGradient><radialGradient id="iHVY1Qc" cx="0" cy="0" r="1" gradientTransform="rotate(-22.029 27.898 -25.28)scale(3.44598 3.57404)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="tnn6d9lnt"/><stop offset="1" class="w0i7s3bkp"/></radialGradient><radialGradient id="iqRW4mb" cx="0" cy="0" r="1" gradientTransform="matrix(1.19125 1.58855 -1.28185 .96125 13 5.694)" gradientUnits="userSpaceOnUse"><stop class="ur7lpnbek"/><stop offset="1" class="ja_424b_z"/></radialGradient><radialGradient id="iNNnhPd" cx="0" cy="0" r="1" gradientTransform="matrix(.90159 3.3233 -3.95241 1.07226 12.4 7.157)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="byihu8b7s"/><stop offset="1" class="x91_06blc"/></radialGradient><radialGradient id="iQemYEe" cx="0" cy="0" r="1" gradientTransform="matrix(-.8274 2.00842 -2.0948 -.86298 14.637 6.534)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="hihpobcpj"/><stop offset="1" class="vn5o04bza"/></radialGradient><radialGradient id="i9A12El" cx="0" cy="0" r="1" gradientTransform="matrix(.92075 1.6354 -1.07153 .60329 14.702 5.187)" gradientUnits="userSpaceOnUse"><stop class="ac50icc3e"/><stop offset="1" class="cztd2jqtm"/></radialGradient><radialGradient id="iFPtWxd" cx="0" cy="0" r="1" gradientTransform="rotate(83.69 3.243 10.626)scale(.99581)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="dhib36bjr"/><stop offset="1" class="uucs6l1bh"/></radialGradient><radialGradient id="iLfER1d" cx="0" cy="0" r="1" gradientTransform="matrix(.19358 -.09647 .56549 1.1347 13.41 7.072)" gradientUnits="userSpaceOnUse"><stop class="pav55masc"/><stop offset="1" class="egqy8jbwr"/></radialGradient><radialGradient id="iIhweFm" cx="0" cy="0" r="1" gradientTransform="matrix(1.10146 2.21488 -2.60328 1.29461 11.745 3.827)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="w9h_a4buy"/><stop offset=".919" class="jvvv5bmeo"/></radialGradient><radialGradient id="ipGUPWb" cx="0" cy="0" r="1" gradientTransform="rotate(-117.114 7.882 -.945)scale(.71048 1.82194)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="chmofghwi"/><stop offset="1" class="tn7myqe_j"/></radialGradient><filter id="iEqcAze" width="28.938" height="27.87" x="2.022" y="3.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.658824 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23495"/></filter><filter id="ihoBhlb" width="8.378" height="5.198" x="17.762" y="3.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.705882 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23495"/></filter><filter id="i9v6Zod" width="27.922" height="3.388" x="2.038" y="27.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.258824 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23495"/></filter><filter id="irVL8Ec" width="9.938" height="9.938" x="2.095" y="20.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.156863 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23495"/></filter><filter id="iA8YEtc" width="10.409" height="10.409" x="1.859" y="20.37" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23495" stdDeviation=".25"/></filter><filter id="iVJLfzd" width="10.037" height="10.037" x="20.04" y="20.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.0862745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23495"/></filter><filter id="ilp4Bdd" width="9.188" height="4.077" x="16.673" y="23.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.341176 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23495"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.490196 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23495" result="effect2_innerShadow_3987_23495"/></filter><filter id="ieDEBub" width="4.034" height="2.181" x="13.536" y="23.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.188235 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23495"/></filter><filter id="iM4apRy" width="3.572" height="8.62" x="15.209" y="16.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.709804 0 0 0 0 0.623529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23495"/></filter><filter id="idM9Dve" width="6.668" height="7.67" x="16.587" y="10.949" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.360784 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23495"/></filter><filter id="itWcxJz" width="7.971" height="5.869" x="15.046" y="7.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.411765 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23495"/></filter><filter id="imLKpMC" width="6.005" height="4.259" x="6.942" y="11.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.505882 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23495"/></filter><filter id="ikUAh0F" width="3.137" height="2.915" x="6.942" y="13.227" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.117647 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23495"/></filter><filter id="iI7hEWd" width="10.272" height="6.937" x="7.819" y="8.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.545098 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23495"/></filter><filter id="im6QrId" width="5.496" height="6.372" x="17.733" y="11.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23495" stdDeviation=".3"/></filter><filter id="i84Sn5b" width="2.969" height="2.969" x="7.747" y="12.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23495" stdDeviation=".3"/></filter><filter id="iG1DF1d" width="5.746" height="5.269" x="10.207" y="5.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.745098 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23495"/></filter><filter id="iUaBdOb" width="3.248" height="2.905" x="13.076" y="4.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0745098 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23495"/></filter><filter id="iJZ78ee" width="6.138" height="5.314" x="9.076" y="2.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23495"/></filter><filter id="iGtDMed" width="2.064" height="1.459" x="11.117" y="4.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.482353 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23495"/></filter><linearGradient id="it4ti6b" x1="9.642" x2="27.946" y1="21.646" y2="9.457" gradientUnits="userSpaceOnUse"><stop class="jk9sxjbtz"/><stop offset="1" class="bsmaek8tk"/></linearGradient><linearGradient id="icfoy8d" x1="29.354" x2="25.894" y1="12.635" y2="15.049" gradientUnits="userSpaceOnUse"><stop offset=".164" class="lc4-hmwkn"/><stop offset="1" class="jvv3w_k0n"/></linearGradient><linearGradient id="i6M7y8c" x1="21.147" x2="24.889" y1="7.646" y2="5.554" gradientUnits="userSpaceOnUse"><stop class="tw0q1w8vf"/><stop offset="1" class="icj8g3w8l"/></linearGradient><linearGradient id="iFDDVqX" x1="9.275" x2="3.243" y1="21.91" y2="28.942" gradientUnits="userSpaceOnUse"><stop class="aqhis8bfy"/><stop offset="1" class="dicaxrbsa"/></linearGradient><linearGradient id="iqcxYCd" x1="17.743" x2="18.712" y1="21.113" y2="20.108" gradientUnits="userSpaceOnUse"><stop offset=".573" class="js-d6kbwq"/><stop offset="1" class="ujlly7xsd"/></linearGradient><linearGradient id="ib6qBDb" x1="22.259" x2="17.665" y1="22.682" y2="22.223" gradientUnits="userSpaceOnUse"><stop offset=".891" class="eper2rg6p"/><stop offset="1" class="btv0f_swr"/></linearGradient><linearGradient id="inLgqpd" x1="11.54" x2="10.665" y1="15.504" y2="15.223" gradientUnits="userSpaceOnUse"><stop class="b32taybyq"/><stop offset="1" class="cq_k1jhvn"/></linearGradient><linearGradient id="iAzoYod" x1="9.775" x2="8.493" y1="20.457" y2="19.973" gradientUnits="userSpaceOnUse"><stop offset=".146" class="l2qa6pp5f"/><stop offset="1" class="j4w4r7dqg"/></linearGradient><linearGradient id="ioVnG4d" x1="12.993" x2="13.384" y1="22.504" y2="22.004" gradientUnits="userSpaceOnUse"><stop class="xlcjgwbhs"/><stop offset="1" class="xdbcf5brc"/><stop offset="1" class="dkvvw7m1c"/></linearGradient><linearGradient id="i74ryGd" x1="20.04" x2="27.795" y1="28.015" y2="25.574" gradientUnits="userSpaceOnUse"><stop class="qkrvzzbyd"/><stop offset="1" class="zaq2lsbln"/></linearGradient><linearGradient id="ixcAGVL" x1="23.821" x2="22.759" y1="22.442" y2="23.192" gradientUnits="userSpaceOnUse"><stop class="ikszdii2u"/><stop offset="1" class="li38i4ecv"/></linearGradient><linearGradient id="iDmVz3c" x1="19.618" x2="18.603" y1="21.215" y2="21.067" gradientUnits="userSpaceOnUse"><stop class="wjlh8kb9f"/><stop offset="1" class="pf-dzrbda"/></linearGradient><linearGradient id="iOFPFEc" x1="16.626" x2="16.993" y1="14.34" y2="14.871" gradientUnits="userSpaceOnUse"><stop class="oqmso-c_s"/><stop offset="1" class="s2g06frqj"/></linearGradient><linearGradient id="iaWOFFd" x1="25.337" x2="16.673" y1="25.574" y2="25.574" gradientUnits="userSpaceOnUse"><stop class="jk12cqb2p"/><stop offset="1" class="bjfaebcql"/></linearGradient><linearGradient id="iJEtVHd" x1="17.47" x2="16.712" y1="25.442" y2="25.442" gradientUnits="userSpaceOnUse"><stop class="z_jgx_kqm"/><stop offset="1" class="ktkvjmbcj"/></linearGradient><linearGradient id="iiO9Ucc" x1="15.556" x2="13.511" y1="9.973" y2="10.056" gradientUnits="userSpaceOnUse"><stop class="xqbtjumcc"/><stop offset="1" class="odf7_hbpj"/></linearGradient><linearGradient id="iUzJire" x1="11.388" x2="11.023" y1="7.9" y2="7.411" gradientUnits="userSpaceOnUse"><stop class="bie0h0-8q"/><stop offset="1" class="fwnzc4ctw"/></linearGradient><linearGradient id="iwFnOGd" x1="13.8" x2="13.37" y1="7.255" y2="7.491" gradientUnits="userSpaceOnUse"><stop class="zcigs7bii"/><stop offset="1" class="nr87if9lw"/></linearGradient><linearGradient id="iDqyPfe" x1="13.7" x2="14.237" y1="9.146" y2="8.801" gradientUnits="userSpaceOnUse"><stop offset=".324" class="x0zx5qyer"/><stop offset="1" class="k6zficbhz"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-mountain-biking-light" /></template>
<style>
.ac50icc3e {
  stop-color: var(--svg-color--231820, #231820);
}

.aemo1cb1q {
  d: path("m3.89 17.353l-1.868 1.938v11.281H29.96V14.041l-6.14-9.305a2.3 2.3 0 0 0-3.841.002l-8.916 13.549a.5.5 0 0 1-.715.127L8.3 16.896c-1.32-.98-3.2-.8-4.41.457");
}

.af2e8qwjk {
  stop-color: var(--svg-color--fcceb9, #FCCEB9);
  stop-opacity: 0;
}

.aflx5ac8k {
  stop-color: var(--svg-color--f0b8a2, #F0B8A2);
  stop-opacity: 0;
}

.aiqsdtepb {
  stop-color: var(--svg-color--ffd359, #FFD359);
  stop-opacity: 0;
}

.aqhis8bfy {
  stop-color: var(--svg-color--302a5b, #302A5B);
}

.aw4amab0f {
  stop-color: var(--svg-color--736e75, #736E75);
}

.aw8cj7bar {
  stop-color: var(--svg-color--afa6a9, #AFA6A9);
}

.b_qw4kb0w {
  d: path("m14.358 7.214l-1.282-1.218L15.2 4.72c.217.34.745 1.389.723 1.686c-.03.41-.174.97-.641 1.096c-.374.1-.797-.154-.924-.288");
}

.b32taybyq {
  stop-color: var(--svg-color--bfa8c7, #BFA8C7);
}

.bie0h0-8q {
  stop-color: var(--svg-color--6f443d, #6F443D);
}

.bjfaebcql {
  stop-color: var(--svg-color--e8774d, #E8774D);
}

.brfhj2bpt {
  stop-color: var(--svg-color--ecb19f, #ECB19F);
  stop-opacity: 0;
}

.bsmaek8tk {
  stop-color: var(--svg-color--36c571, #36C571);
}

.btv0f_swr {
  stop-color: var(--svg-color--615f76, #615F76);
}

.bvfvx5b_v {
  fill: var(--svg-color--414141, #414141);
  d: path("M11.4 7.888a1 1 0 0 0-.054-.094c-.098-.14-.236-.213-.31-.162c-.074.052-.054.207.043.347q.03.042.062.075z");
}

.byihu8b7s {
  stop-color: var(--svg-color--dba096, #DBA096);
  stop-opacity: 0;
}

.cbgow0bwo {
  stop-color: var(--svg-color--e2dfe5, #E2DFE5);
}

.cc9670aeb {
  stop-color: var(--svg-color--932145, #932145);
}

.chmofghwi {
  stop-color: var(--svg-color--4b89d0, #4B89D0);
}

.cq_k1jhvn {
  stop-color: var(--svg-color--908590, #908590);
}

.cuptu7i6i {
  stop-color: var(--svg-color--e8ac93, #E8AC93);
}

.cvi6_hb_e {
  stop-color: var(--svg-color--564a5a, #564A5A);
}

.cztd2jqtm {
  stop-color: var(--svg-color--151a31, #151A31);
}

.d-6jagb2y {
  stop-color: var(--svg-color--ac2735, #AC2735);
}

.d9lnsac_l {
  stop-color: var(--svg-color--c88d7e, #C88D7E);
  stop-opacity: 0;
}

.da9xf6l5p {
  stop-color: var(--svg-color--e2dfe5, #E2DFE5);
  stop-opacity: 0;
}

.defuztb0z {
  fill-rule: evenodd;
  d: path("M10.562 16.933a.55.55 0 0 1 .3.718l-3.29 8a.55.55 0 0 1-1.017-.418l3.29-8a.55.55 0 0 1 .717-.3");
}

.dhib36bjr {
  stop-color: var(--svg-color--cf9f9d, #CF9F9D);
}

.dicaxrbsa {
  stop-color: var(--svg-color--302a5b, #302A5B);
  stop-opacity: 0;
}

.dkvvw7m1c {
  stop-color: var(--svg-color--9c2649, #9C2649);
  stop-opacity: 0;
}

.do77voeuo {
  d: path("M18.92 27.398q-.186.04-.384.04a1.863 1.863 0 1 1 .403-3.683l5.898.905a.927.927 0 0 1-.086 1.838z");
}

.dpi-7sbrv {
  stop-color: var(--svg-color--c78490, #C78490);
  stop-opacity: 0;
}

.egqy8jbwr {
  stop-color: var(--svg-color--4d3a6e, #4D3A6E);
  stop-opacity: 0;
}

.egxex7b7c {
  stop-color: var(--svg-color--5c4f86, #5C4F86);
  stop-opacity: 0;
}

.eper2rg6p {
  stop-color: var(--svg-color--615f76, #615F76);
  stop-opacity: 0;
}

.f-r3ld20z {
  stop-color: var(--svg-color--baa3b9, #BAA3B9);
}

.f6rwhfb_k {
  stop-color: var(--svg-color--afa6a9, #AFA6A9);
  stop-opacity: 0;
}

.ff0nxwb2o {
  stop-color: var(--svg-color--54a7f5, #54A7F5);
}

.fhxrfacsu {
  fill-rule: evenodd;
  d: path("M25.009 21.606a3.969 3.969 0 1 0 0 7.937a3.969 3.969 0 0 0 0-7.937m-4.969 3.968a4.969 4.969 0 1 1 9.938 0a4.969 4.969 0 0 1-9.938 0");
}

.fqxr12j4i {
  stop-color: var(--svg-color--d29b92, #D29B92);
}

.frl5-vc4s {
  fill-rule: evenodd;
  d: path("M9.638 19.16c.102-.222.43-.465.672-.281l6.25 4.75a.55.55 0 0 1-.665.875l-6.081-4.61c-.242-.183-.305-.452-.176-.734");
}

.ft5dv1b6b {
  fill: none;
}

.ftl41uazn {
  fill-rule: evenodd;
  d: path("M7.064 21.606a3.969 3.969 0 1 0 0 7.937a3.969 3.969 0 0 0 0-7.937m-4.97 3.968a4.969 4.969 0 1 1 9.938 0a4.969 4.969 0 0 1-9.937 0");
}

.fusk07b7u {
  d: path("m11.593 7.764l-.033-.05c-.175-.252-.428-.38-.564-.285c-.136.094-.104.376.072.628l.022.03z");
}

.fwnzc4ctw {
  stop-color: var(--svg-color--5a332d, #5A332D);
}

.fy0gg3b4w {
  stop-color: var(--svg-color--d9d1df, #D9D1DF);
  stop-opacity: 0;
}

.fze29cbbv {
  stop-color: var(--svg-color--fcceb9, #FCCEB9);
}

.gcjq1zqgn {
  stop-color: var(--svg-color--f0b8a2, #F0B8A2);
}

.gg4t9o52q {
  fill-rule: evenodd;
  d: path("M12.631 5.713a.304.304 0 0 1 .408.138l1.686 3.4a.305.305 0 0 1-.546.27l-1.685-3.4a.305.305 0 0 1 .137-.408");
}

.gxtng2bih {
  stop-color: var(--svg-color--5d5c7e, #5D5C7E);
  stop-opacity: 0;
}

.hihpobcpj {
  stop-color: var(--svg-color--ecbaaa, #ECBAAA);
}

.hqorccbwh {
  stop-color: var(--svg-color--3c2150, #3C2150);
}

.hs-_dnasa {
  stop-color: var(--svg-color--493b63, #493B63);
}

.huz3s4d_a {
  stop-color: var(--svg-color--c5bfcb, #C5BFCB);
}

.hwlgdac9v {
  stop-color: var(--svg-color--c68c7c, #C68C7C);
}

.icj8g3w8l {
  stop-color: var(--svg-color--e2dce7, #E2DCE7);
}

.ikszdii2u {
  stop-color: var(--svg-color--fd5a60, #FD5A60);
}

.inxrwd09n {
  cx: 13.448px;
  cy: 6.428px;
  r: 0.68px;
}

.iqlq1pbje {
  stop-color: var(--svg-color--f3c0b0, #F3C0B0);
}

.j4w4r7dqg {
  stop-color: var(--svg-color--973c50, #973C50);
}

.j9bmo4yzb {
  stop-color: var(--svg-color--c7898c, #C7898C);
}

.ja_424b_z {
  stop-color: var(--svg-color--b27d80, #B27D80);
  stop-opacity: 0;
}

.jk12cqb2p {
  stop-color: var(--svg-color--f7b14e, #F7B14E);
}

.jk5eocp2v {
  stop-color: var(--svg-color--e44354, #E44354);
  stop-opacity: 0;
}

.jk9sxjbtz {
  stop-color: var(--svg-color--37c173, #37C173);
}

.jqhw67baa {
  stop-color: var(--svg-color--736e75, #736E75);
  stop-opacity: 0;
}

.js-d6kbwq {
  stop-color: var(--svg-color--cb8983, #CB8983);
}

.jvv3w_k0n {
  stop-color: var(--svg-color--36c871, #36C871);
  stop-opacity: 0;
}

.jvvv5bmeo {
  stop-color: var(--svg-color--52abe4, #52ABE4);
}

.jxqufcbzg {
  stop-color: var(--svg-color--dfaf96, #DFAF96);
}

.k6zficbhz {
  stop-color: var(--svg-color--72687c, #72687C);
  stop-opacity: 0;
}

.k9wtqmbef {
  d: path("M17.762 8.106L20.01 6.79a.4.4 0 0 1 .511.091l1.07 1.3a.6.6 0 0 0 .927 0l1.067-1.297a.4.4 0 0 1 .515-.088l1.791 1.076l-2.07-3.137a2.3 2.3 0 0 0-3.841.002z");
}

.kl_lwk9ux {
  d: path("M13.546 8.511H15.7v2.668h-2.154z");
}

.ktkvjmbcj {
  stop-color: var(--svg-color--605c92, #605C92);
  stop-opacity: 0;
}

.l2qa6pp5f {
  stop-color: var(--svg-color--d4385b, #D4385B);
}

.l4_q8ccja {
  stop-color: var(--svg-color--ebeaed, #EBEAED);
}

.lc4-hmwkn {
  stop-color: var(--svg-color--4cdd80, #4CDD80);
}

.li38i4ecv {
  stop-color: var(--svg-color--af253c, #AF253C);
}

.lmxfxo9xh {
  fill: var(--svg-color--e7b6a2, #E7B6A2);
  fill-rule: evenodd;
  d: path("M17.133 8.872c.479.327.602.98.274 1.46c-.783 1.144-3.151 4.302-7.932 4.787c-.577.059-1.595-.32-1.654-.896s.865-1.135 1.442-1.193c3.844-.39 5.74-2.904 6.41-3.884a1.05 1.05 0 0 1 1.46-.274");
}

.m22mabb0k {
  fill: var(--svg-color--86004d, #86004D);
  fill-rule: evenodd;
  d: path("M11.915 9.44a.12.12 0 0 1 .036-.168c.103-.067.237-.228.301-.559a.122.122 0 0 1 .24.046c-.074.378-.236.606-.41.718a.12.12 0 0 1-.168-.036");
}

.m3fnulbuf {
  d: path("m14.006 16.043l1.34-.836l1.038 1.04l-.765 3.53a200 200 0 0 0-1.688-1.242c-.148-.101-.66-.543-.653-1.238c.008-.711.477-1.072.727-1.254");
}

.m3q9izqvj {
  stop-color: var(--svg-color--5d5c7e, #5D5C7E);
}

.mb6yhmklz {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.92 7.5c-.063.24.087.472.166.589l.901-.579c-.568-.595-.98-.335-1.067-.01");
}

.mp1bj4bkr {
  stop-color: var(--svg-color--ebbca0, #EBBCA0);
  stop-opacity: 0;
}

.ms8ncfh9g {
  stop-color: var(--svg-color--8c5ea8, #8C5EA8);
  stop-opacity: 0;
}

.msqk4cb8o {
  stop-color: var(--svg-color--373c67, #373C67);
}

.n1wukybpj {
  d: path("m16.087 16.598l.554-.514L18.68 18c-.274.154-.887.463-1.031.582c-.11.09-.11.235-.11.328l-.046 5.594l-1.407-.672c-.138-.794-.42-2.708-.769-4.3c-.395-1.801.376-2.593.77-2.934");
}

.n7m9lcrvd {
  d: path("m15.064 4.93l-4.792 2.713a.27.27 0 0 1-.355-.067a5.8 5.8 0 0 1-.642-1.156c-.62-1.48.393-2.368.525-2.504c.191-.197.72-.686 1.88-1.167c1.36-.564 2.263.013 2.715.567c.284.348.6.875.787 1.232a.286.286 0 0 1-.119.381");
}

.ng_8ekg9m {
  fill-rule: evenodd;
  d: path("M19.747 17.219a.55.55 0 0 0-.172.758l4.719 7.477a.55.55 0 0 0 .93-.587l-4.719-7.477a.55.55 0 0 0-.758-.171");
}

.nme23stjs {
  d: path("M10.794 9.245c-.215-.137-.225-.303-.17-.674a.85.85 0 0 0-.086-.554l.882 1c-.104.235-.41.365-.626.228");
}

.nr87if9lw {
  stop-color: var(--svg-color--37234c, #37234C);
  stop-opacity: 0;
}

.nus19y6ts {
  stop-color: var(--svg-color--ffd359, #FFD359);
}

.o0z3_q1mf {
  fill-rule: evenodd;
  d: path("M8.965 14.114a.33.33 0 0 1 0 .402c-.151.126-.342.39-.372.594a.35.35 0 0 1-.693-.101c.019-.129.077-.285.155-.43c.08-.147.196-.312.354-.442c.148-.123.433-.172.556-.023");
}

.o2gu83zjq {
  stop-color: var(--svg-color--e4af9f, #E4AF9F);
}

.o5ujuoler {
  stop-color: var(--svg-color--4f414e, #4F414E);
}

.o786ujbwq {
  cx: 9.231px;
  cy: 14.022px;
  r: 0.885px;
  fill: var(--svg-color--e3b3a0, #E3B3A0);
}

.o83duvb6p {
  stop-color: var(--svg-color--cd8b8b, #CD8B8B);
}

.odf7_hbpj {
  stop-color: var(--svg-color--c6817c, #C6817C);
}

.oqmso-c_s {
  stop-color: var(--svg-color--72696b, #72696B);
}

.ovgl0qgnr {
  d: path("m16.106 23.824l-1.809.86c-.43.213-.756.465-.761.957c-.002.123.107.214.23.214h3.504a.2.2 0 0 0 .2-.2v-1.15z");
}

.oxt4ifqva {
  d: path("M12.946 12.207a.575.575 0 0 0-.575-.575h-3.05a2.13 2.13 0 0 0 0 4.26h.183a.575.575 0 0 0 0-1.15h-.183a.98.98 0 1 1 0-1.96h3.05a.575.575 0 0 0 .575-.575");
}

.p_o38mbkb {
  stop-color: var(--svg-color--dba398, #DBA398);
}

.p0n-v6bwi {
  stop-color: var(--svg-color--dca28a, #DCA28A);
}

.p1dkvx0ja {
  stop-color: var(--svg-color--8a4c56, #8A4C56);
  stop-opacity: 0;
}

.p4kao-i7q {
  fill: var(--svg-color--4d3771, #4D3771);
  fill-rule: evenodd;
  d: path("M12.631 5.713a.304.304 0 0 1 .408.138l1.686 3.4a.305.305 0 0 1-.546.27l-1.685-3.4a.305.305 0 0 1 .137-.408");
}

.p823fnbia {
  d: path("m5.654 27.758l-3.616 2.158v.672H29.96v-.672l-3.532-2.15a2.4 2.4 0 0 0-2.429-.04l-.817.462a2 2 0 0 1-1.838.067l-1.318-.622a2.25 2.25 0 0 0-1.965.02l-1.177.587a2 2 0 0 1-1.823-.02l-1.126-.59a2 2 0 0 0-1.782-.04l-1.42.67a2 2 0 0 1-1.826-.062l-.855-.476a2.4 2.4 0 0 0-2.398.036");
}

.pav55masc {
  stop-color: var(--svg-color--564975, #564975);
}

.pf-dzrbda {
  stop-color: var(--svg-color--a62f2f, #A62F2F);
}

.pm1b-8inu {
  fill-rule: evenodd;
  d: path("M8.818 14.055a.35.35 0 0 1-.227.44a.6.6 0 0 0-.406.457a.35.35 0 0 1-.683-.152c.05-.223.235-.767.876-.972a.35.35 0 0 1 .44.227");
}

.qfj7itbso {
  stop-color: var(--svg-color--8a4c56, #8A4C56);
}

.qh--u2bfq {
  d: path("m15.286 15.242l2.64-1.61l1.208.63l-2.727 2.476c-.268-.23-.84-1.05-1.12-1.496");
}

.qkrvzzbyd {
  stop-color: var(--svg-color--352542, #352542);
}

.qktpib9mi {
  stop-color: var(--svg-color--8c5ea8, #8C5EA8);
}

.qnv5cwbcc {
  stop-color: var(--svg-color--baa3b9, #BAA3B9);
  stop-opacity: 0;
}

.r5h7b-urd {
  d: path("M16.103 11.754c.664.625 1.363 1.586 1.671 1.969l4.243-2.18c-.586-.976-2.07-2.531-3.54-3.36c-1.718-.812-2.672 0-3.304 1.071c-.414.852.258 1.781.93 2.5");
}

.ra689e2fy {
  fill-rule: evenodd;
  d: path("M12.496 12.198a.5.5 0 0 1 .271.653l-2.54 6.247a.5.5 0 0 1-.924-.381l2.54-6.247a.5.5 0 0 1 .653-.272");
}

.rgol9fpyb {
  stop-color: var(--svg-color--e44354, #E44354);
}

.rmo1iwb_p {
  fill: var(--svg-color--413354, #413354);
  d: path("m17.89 21.464l-.301 1.98c-.066.476-.04.887.364 1.167c.102.07.238.031.307-.071l1.964-2.902a.2.2 0 0 0-.054-.277l-.952-.645z");
}

.rtqrfdb3t {
  d: path("m19.195 20.73l-1.827-1.988l-.423 2.059l1 .706z");
}

.s2g06frqj {
  stop-color: var(--svg-color--72696b, #72696B);
  stop-opacity: 0;
}

.slryrmbbo {
  stop-color: var(--svg-color--c78490, #C78490);
}

.sxz_wf09g {
  fill: var(--svg-color--2b174f, #2B174F);
  fill-rule: evenodd;
  d: path("M8.34 13.82v-.02a.572.572 0 1 0-1.144 0v.021h-.003a2.13 2.13 0 0 0 2.128 2.072h.183a.575.575 0 1 0 0-1.15h-.183a.98.98 0 0 1-.978-.922z");
}

.t0umacb5g {
  d: path("m18.371 14.375l-.636-.7l4.032-2.476c1.422 1.867 1.5 3.211.836 4.274c-.664 1.062-1.582 2.05-2.618 2.945c-.27.235-.802.362-1.359-.18c-.707-.687-1.578-1.578-2.039-2.113l1.777-1.608a.1.1 0 0 0 .007-.142");
}

.t0xl0mbii {
  stop-color: var(--svg-color--c08175, #C08175);
}

.tn7myqe_j {
  stop-color: var(--svg-color--337bcd, #337BCD);
}

.tnn6d9lnt {
  stop-color: var(--svg-color--ddac9a, #DDAC9A);
}

.tw0q1w8vf {
  stop-color: var(--svg-color--d7cfdf, #D7CFDF);
}

.uakehioxk {
  stop-color: var(--svg-color--3b79d4, #3B79D4);
}

.uciguo95i {
  fill: var(--svg-color--97595f, #97595F);
  d: path("m5.654 27.758l-3.616 2.158v.672H29.96v-.672l-3.532-2.15a2.4 2.4 0 0 0-2.429-.04l-.817.462a2 2 0 0 1-1.838.067l-1.318-.622a2.25 2.25 0 0 0-1.965.02l-1.177.587a2 2 0 0 1-1.823-.02l-1.126-.59a2 2 0 0 0-1.782-.04l-1.42.67a2 2 0 0 1-1.826-.062l-.855-.476a2.4 2.4 0 0 0-2.398.036");
}

.ujlly7xsd {
  stop-color: var(--svg-color--d5a595, #D5A595);
}

.ur7lpnbek {
  stop-color: var(--svg-color--b27d80, #B27D80);
}

.uucs6l1bh {
  stop-color: var(--svg-color--c58284, #C58284);
}

.v5ts0ibjo {
  stop-color: var(--svg-color--d8cfe2, #D8CFE2);
}

.vn5o04bza {
  stop-color: var(--svg-color--ecbaaa, #ECBAAA);
  stop-opacity: 0;
}

.vy5gs0bfe {
  d: path("M12.048 9.986c-.838-.74-1.554-1.953-1.84-2.427l3.508-2.308l1.988 1.67a5.4 5.4 0 0 1-.894 2.02c-.7.948-1.663 2.017-2.762 1.045");
}

.w0i7s3bkp {
  stop-color: var(--svg-color--d79f9b, #D79F9B);
}

.w9h_a4buy {
  stop-color: var(--svg-color--4fbdff, #4FBDFF);
}

.wc0bxtmli {
  stop-color: var(--svg-color--38144f, #38144F);
}

.wcwf26bex {
  cx: 11.044px;
  cy: 7.609px;
  r: 0.088px;
  fill: var(--svg-color--dfdfdf, #DFDFDF);
}

.wjlh8kb9f {
  stop-color: var(--svg-color--e5435f, #E5435F);
}

.wo7enbs3l {
  d: path("m17.89 21.464l-.301 1.98c-.066.476-.04.887.364 1.167c.102.07.238.031.307-.071l1.964-2.902a.2.2 0 0 0-.054-.277l-.952-.645z");
}

.x--0qpb9w {
  fill-rule: evenodd;
  d: path("M17.133 8.872c.479.327.602.98.274 1.46c-.783 1.144-3.151 4.302-7.932 4.787c-.577.059-1.595-.32-1.654-.896s.865-1.135 1.442-1.193c3.844-.39 5.74-2.904 6.41-3.884a1.05 1.05 0 0 1 1.46-.274");
}

.x0la_kp1k {
  fill-rule: evenodd;
  d: path("M20.05 17.14a.55.55 0 0 1 .418.656l-1.578 7.078a.55.55 0 1 1-1.074-.24l1.578-7.078a.55.55 0 0 1 .657-.417");
}

.x0zx5qyer {
  stop-color: var(--svg-color--72687c, #72687C);
}

.x91_06blc {
  stop-color: var(--svg-color--cb8583, #CB8583);
}

.xal9k3bum {
  stop-color: var(--svg-color--dba398, #DBA398);
  stop-opacity: 0;
}

.xdbcf5brc {
  stop-color: var(--svg-color--96275e, #96275E);
  stop-opacity: 0;
}

.xlcjgwbhs {
  stop-color: var(--svg-color--96275e, #96275E);
}

.xqbtjumcc {
  stop-color: var(--svg-color--ebbda6, #EBBDA6);
}

.y16t4y92n {
  stop-color: var(--svg-color--32295b, #32295B);
}

.yfsgwoocz {
  d: path("M11.162 5.866a.37.37 0 0 1 .147-.499l1.329-.723a.368.368 0 0 1 .351.646l-1.328.723a.37.37 0 0 1-.5-.147");
}

.yjmpw-u6e {
  fill: var(--svg-color--c0b9bc, #C0B9BC);
  d: path("M12.946 12.207a.575.575 0 0 0-.575-.575h-3.05a2.13 2.13 0 0 0 0 4.26h.183a.575.575 0 0 0 0-1.15h-.183a.98.98 0 1 1 0-1.96h3.05a.575.575 0 0 0 .575-.575");
}

.ypkdur5_u {
  fill-rule: evenodd;
  d: path("M9.328 13.52a.35.35 0 0 1-.35.35c-.173 0-.436.042-.663.15c-.226.106-.37.252-.415.438a.35.35 0 1 1-.68-.166c.114-.466.462-.748.796-.906c.334-.157.701-.216.962-.216a.35.35 0 0 1 .35.35");
}

.yt4h0-bzj {
  stop-color: var(--svg-color--ecb19f, #ECB19F);
}

.yw84gcbaz {
  cx: 18.38px;
  cy: 25.574px;
  r: 1.027px;
}

.yzd4i4kse {
  fill: var(--svg-color--5b4e85, #5B4E85);
  d: path("m16.106 23.824l-1.809.86c-.43.213-.756.465-.761.957c-.002.123.107.214.23.214h3.504a.2.2 0 0 0 .2-.2v-1.15z");
}

.z_jgx_kqm {
  stop-color: var(--svg-color--605c92, #605C92);
}

.z2ogs_vck {
  cx: 7.064px;
  cy: 25.574px;
  r: 4.555px;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
}

.zaq2lsbln {
  stop-color: var(--svg-color--352542, #352542);
  stop-opacity: 0;
}

.zcigs7bii {
  stop-color: var(--svg-color--37234c, #37234C);
}

.zd8v8x_xx {
  stop-color: var(--svg-color--ac2735, #AC2735);
  stop-opacity: 0;
}

.zo6cprbov {
  stop-color: var(--svg-color--ce3d5e, #CE3D5E);
}

.zro955b4q {
  d: path("m20.997 13.493l-.523-.864l1.125-.656c.968 1.313 1.343 2.297.734 2.875c-.487.463-2.87 1.724-4 2.297l2.503-2.414a1 1 0 0 0 .161-1.238");
}

.zvme7yb8w {
  stop-color: var(--svg-color--a3a1a2, #A3A1A2);
}

.zwrak1b2j {
  stop-color: var(--svg-color--726b71, #726B71);
}

</style>
