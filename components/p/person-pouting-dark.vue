<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i9O4QKb)" class="odq2frbdh"/><path fill="url(#iik7kQo)" class="odq2frbdh"/><path fill="url(#iO2aVKU)" class="odq2frbdh"/><rect fill="url(#i3uWHRb)" class="o9uu_2vuf"/><rect fill="url(#ixUEihd)" class="o9uu_2vuf"/><path fill="url(#iFHmW8d)" class="lpley2bsg"/><path fill="url(#ifbmyGd)" class="pz8_28qcs"/><path fill="url(#iNp5okb)" class="pz8_28qcs"/><g filter="url(#ibFHjMc)"><path fill="url(#i2Vq3ob)" class="ixbfuabjj"/></g><path fill="url(#irFMW3c)" class="ixbfuabjj"/><path fill="url(#iAHKKUo)" class="ixbfuabjj"/><g filter="url(#isCn1oB)"><path fill="url(#i9aEPPc)" class="h2xwtmsbp"/></g><path fill="url(#icwFiKb)" class="hr__6pb8m"/><path fill="url(#iORVcdd)" class="ac1xhuktd"/><g filter="url(#iqHZULc)"><path fill="url(#iJuMvrQ)" class="fr4u2db8i"/></g><path fill="url(#itsXHId)" class="fr4u2db8i"/><path fill="url(#iUnMHyb)" class="fr4u2db8i"/><path fill="url(#iPzBpNc)" class="fr4u2db8i"/><path fill="url(#iqeJIVb)" class="fr4u2db8i"/><path fill="url(#iXt3Nrc)" class="fr4u2db8i"/><path fill="url(#it5EPye)" class="fr4u2db8i"/><path fill="url(#iZY1dbc)" class="fr4u2db8i"/><path fill="url(#irCQL3f)" class="fr4u2db8i"/><path fill="url(#iM87OAb)" class="fr4u2db8i"/><g filter="url(#iX1K1Cc)"><path fill="url(#insmB4c)" class="i42u1jcxk"/><path fill="url(#iBEIvtb)" class="i42u1jcxk"/></g><g filter="url(#i0aBGjc)"><path class="lzppzvbjq"/></g><g filter="url(#izYgqSd)"><path class="b5xdtvbpr"/><path fill="url(#izGhMfc)" class="l0hv0bczl"/><path fill="url(#iI7qKde)" class="l0hv0bczl"/><path fill="url(#i6nmh1D)" class="l0hv0bczl"/><path fill="url(#iwc6m0d)" class="l0hv0bczl"/><path fill="url(#ibVkaeb)" class="l0hv0bczl"/></g><g filter="url(#iNVYozd)"><path fill="url(#iRLjx7O)" class="w7c30fbkj"/><path fill="url(#iMlZPNd)" class="w7c30fbkj"/><path fill="url(#iZ189ae)" class="w7c30fbkj"/><path fill="url(#ievFTfd)" class="w7c30fbkj"/><path fill="url(#ijnvJFk)" class="w7c30fbkj"/></g><g filter="url(#i32YkYe)"><path class="vrl65yioc"/><path fill="url(#i2Pfcsb)" class="yep1jvbcp"/><path fill="url(#iES9mOd)" class="yep1jvbcp"/></g><g filter="url(#iZekzzJ)"><path class="kt3r-ccwj"/><path fill="url(#iDEHbbe)" class="fbwpm7b3c"/><path fill="url(#i3o6h4d)" class="fbwpm7b3c"/><path fill="url(#iUbtAxe)" class="fbwpm7b3c"/></g><path class="c4ffaubfw"/><path fill="url(#i5qzoSd)" class="zsbbq-hya"/><path class="f-rzflb7f"/><g filter="url(#iJyKm9d)"><path class="bjfup_hfs"/><path fill="url(#i2dydue)" class="wkxl05xjv"/></g><g filter="url(#iqw8Z0d)"><path fill="url(#iM8f5ze)" class="frhrvxb1w"/></g><path class="gb_tpr34z"/><path fill="url(#iI3peEe)" class="uiu1jnbrd"/><path class="w19z1qc3s"/><g filter="url(#ifFd8qd)"><path fill="url(#iRHt1jb)" class="bh_tehlut"/></g><g filter="url(#iUJc8zb)"><ellipse transform="rotate(-27.914 13.55 9.86)" class="x-to_kbtn"/><ellipse fill="url(#ifB0Uzi)" transform="rotate(-27.914 13.55 9.86)" class="lb5uh1r5u"/></g><path fill="url(#iLtNLdc)" class="lrpdblbcr"/><path fill="url(#ic7nbxc)" class="lrpdblbcr"/><path fill="url(#i7AVkAb)" class="lrpdblbcr"/><path fill="url(#itJ9DIe)" class="lrpdblbcr"/><path fill="url(#iDFTdhc)" class="in3qy-btl"/><path fill="url(#io5LRcY)" class="in3qy-btl"/><g filter="url(#iec0sue)"><path fill="url(#iHCdfub)" class="qqqksli-v"/></g><g filter="url(#iMEpFNq)"><path fill="url(#iMOKr7d)" class="n_lbefwpq"/></g><path class="h79xt_fpx"/><path stroke="url(#imjQrfc)" class="wt6bm4iox"/><path stroke="url(#iF0DHnc)" class="wt6bm4iox"/><g filter="url(#iAAczXd)"><rect class="h5sux3b6d"/></g><g filter="url(#iqR0xBd)"><rect class="jkuyqrt8m"/></g><g filter="url(#iIuAqzb)"><path stroke="url(#iYjraZx)" class="d4aj1-biz"/></g><g filter="url(#iFnMDye)"><path stroke="url(#iAUp5cc)" class="hl6ngdbuc"/></g><defs><radialGradient id="i9O4QKb" cx="0" cy="0" r="1" gradientTransform="matrix(2.02197 9.09668 -14.16842 3.14929 14.022 14.59)" gradientUnits="userSpaceOnUse"><stop class="hf1ph1b7l"/><stop offset=".674" class="v5rpejz7p"/></radialGradient><radialGradient id="iik7kQo" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.71875 9.5625 0 21.73 24.313)" gradientUnits="userSpaceOnUse"><stop class="osixu2bon"/><stop offset="1" class="bh4gs6bci"/></radialGradient><radialGradient id="i3uWHRb" cx="0" cy="0" r="1" gradientTransform="rotate(52.035 -8.964 24.325)scale(2.78619 3.42691)" gradientUnits="userSpaceOnUse"><stop offset=".538" class="xl00x07lc"/><stop offset=".962" class="k7jsibb9h"/></radialGradient><radialGradient id="ixUEihd" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 1 -1.28354 1.60442 13.918 16.625)" gradientUnits="userSpaceOnUse"><stop class="czxc369no"/><stop offset="1" class="tpd0s6btx"/></radialGradient><radialGradient id="iNp5okb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 0 0 -9.0144 10.168 23.313)" gradientUnits="userSpaceOnUse"><stop offset=".723" class="pyz9maawt"/><stop offset="1" class="j5lcx07ey"/></radialGradient><radialGradient id="i2Vq3ob" cx="0" cy="0" r="1" gradientTransform="matrix(14.39624 1.34674 -.46749 4.99726 16.71 24.842)" gradientUnits="userSpaceOnUse"><stop class="byra0jsyn"/><stop offset="1" class="lq4btpg7k"/></radialGradient><radialGradient id="irFMW3c" cx="0" cy="0" r="1" gradientTransform="matrix(.70684 1.42914 -5.7496 2.8437 17.536 26.617)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="xl4blsbsc"/><stop offset="1" class="y5-hmbbhn"/></radialGradient><radialGradient id="iAHKKUo" cx="0" cy="0" r="1" gradientTransform="rotate(166.054 12.159 14.007)scale(5.39674 1.22772)" gradientUnits="userSpaceOnUse"><stop class="emfffdbba"/><stop offset="1" class="hrbrn5bar"/></radialGradient><radialGradient id="i9aEPPc" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 2.875 -15.79355 3.09004 16.293 25)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="x7zpsiwqt"/><stop offset=".834" class="cfjku2bno"/></radialGradient><radialGradient id="icwFiKb" cx="0" cy="0" r="1" gradientTransform="matrix(.74603 2.01215 -2.39029 .88623 20.736 11.753)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iORVcdd" cx="0" cy="0" r="1" gradientTransform="rotate(17.447 -34.906 38.595)scale(1.54201 4.75719)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="iJuMvrQ" cx="0" cy="0" r="1" gradientTransform="matrix(-5.20874 0 0 -9.21421 18.798 10.815)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="iUnMHyb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01849 12.37807 -10.25056 -.84343 17.576 4.923)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="iPzBpNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14415 1.41589 0 18.439 9.507)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="iqeJIVb" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.648 -2.102)scale(1.09028 1.18649)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="iXt3Nrc" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.524 6.206)scale(8.48177 21.6667)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="it5EPye" cx="0" cy="0" r="1" gradientTransform="matrix(4.05811 -2.63861 .96592 1.48556 10.553 6.505)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iZY1dbc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23381 2.4883 -.99468 -.09346 21.525 7.909)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="irCQL3f" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7368 2.87242 -2.37141 -1.43386 18.419 5.854)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="iM87OAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.92347 6.89968 0 16.047 16.963)" gradientUnits="userSpaceOnUse"><stop class="xc3cwzl8h"/><stop offset=".264" class="e1s_iwb5s"/><stop offset=".647" class="zr40zg26a"/></radialGradient><radialGradient id="iI7qKde" cx="0" cy="0" r="1" gradientTransform="matrix(0 .24321 -.76438 0 16.465 12.17)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="iwc6m0d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51558 .69488 -1.11673 -2.43567 16.58 11.603)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="iMlZPNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.48852 8.82207 0 10.79 7.933)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iZ189ae" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.255 -6.286)scale(2.50594 4.44002)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="ievFTfd" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 10.493 -1.515)scale(2.81297 2.06486)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="ijnvJFk" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 6.3 14.189)scale(1.72423 3.99252)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="i2Pfcsb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.19308 0 0 -.81394 16.253 3.65)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iES9mOd" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.169 -5.817)scale(6.00459 6.65246)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iDEHbbe" cx="0" cy="0" r="1" gradientTransform="matrix(3.04721 0 0 1.19141 19.401 4.424)" gradientUnits="userSpaceOnUse"><stop class="nszf4yi9c"/><stop offset="1" class="a061yvbds"/></radialGradient><radialGradient id="i3o6h4d" cx="0" cy="0" r="1" gradientTransform="matrix(2.66893 -2.54284 4.6553 4.88613 18.624 7.45)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iUbtAxe" cx="0" cy="0" r="1" gradientTransform="matrix(3.23634 .37827 -.15838 1.355 17.741 5.979)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="i5qzoSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .86238 -1.37171 0 18.16 9.952)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i2dydue" cx="0" cy="0" r="1" gradientTransform="matrix(-.24651 -.31766 .43735 -.33939 17.918 10.041)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iI3peEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87521 -1.39213 0 13.843 9.964)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ifB0Uzi" cx="0" cy="0" r="1" gradientTransform="matrix(-.00834 -.53297 .64065 -.01003 13.534 10.2)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ic7nbxc" cx="0" cy="0" r="1" gradientTransform="matrix(.62625 2.23507 -2.13243 .5975 20.601 9.916)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="i7AVkAb" cx="0" cy="0" r="1" gradientTransform="matrix(.7849 -1.07715 .90287 .6579 20.96 10.459)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="itJ9DIe" cx="0" cy="0" r="1" gradientTransform="matrix(.58485 -1.54475 2.064 .78144 21.074 10.63)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="io5LRcY" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.24 9.455)scale(2.10894 2.07328)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="iHCdfub" cx="0" cy="0" r="1" gradientTransform="matrix(-.91313 .15674 -.06913 -.40274 11.104 10.557)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><radialGradient id="imjQrfc" cx="0" cy="0" r="1" gradientTransform="rotate(-67.758 18.87 -5.425)scale(.40861 .97456)" gradientUnits="userSpaceOnUse"><stop class="a20oreb3g"/><stop offset="1" class="die6v9bjs"/></radialGradient><radialGradient id="iF0DHnc" cx="0" cy="0" r="1" gradientTransform="matrix(.2201 -.23857 .1633 .15066 14.79 14.095)" gradientUnits="userSpaceOnUse"><stop class="a20oreb3g"/><stop offset="1" class="die6v9bjs"/></radialGradient><filter id="ibFHjMc" width="19.161" height="7.244" x="8.205" y="22.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.0941176 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4626"/></filter><filter id="isCn1oB" width="19.009" height="7.177" x="5.218" y="22.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.121569 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4626"/></filter><filter id="iqHZULc" width="11.183" height="12.497" x="10.956" y="4.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4626"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13036_4626" result="effect2_innerShadow_13036_4626"/></filter><filter id="iX1K1Cc" width="1.224" height=".712" x="15.435" y="14.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4626" stdDeviation=".05"/></filter><filter id="i0aBGjc" width="3.74" height="4.889" x="13.989" y="8.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4626" stdDeviation=".5"/></filter><filter id="izYgqSd" width="2.27" height="3.289" x="14.865" y="9.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4626" stdDeviation=".1"/></filter><filter id="iNVYozd" width="12.826" height="8.328" x="9.587" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4626"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13036_4626" result="effect2_innerShadow_13036_4626"/></filter><filter id="i32YkYe" width="7.062" height="6.472" x="9.691" y="2.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4626"/><feGaussianBlur result="effect2_foregroundBlur_13036_4626" stdDeviation=".25"/></filter><filter id="iZekzzJ" width="6.839" height="6.216" x="15.592" y="2.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4626" stdDeviation=".25"/></filter><filter id="iJyKm9d" width=".824" height=".728" x="17.387" y="9.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4626" stdDeviation=".05"/></filter><filter id="iqw8Z0d" width=".922" height=".946" x="18.286" y="9.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4626" stdDeviation=".1"/></filter><filter id="ifFd8qd" width="1.033" height="1.091" x="13.888" y="9.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4626" stdDeviation=".1"/></filter><filter id="iUJc8zb" width=".969" height=".744" x="13.066" y="9.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4626" stdDeviation=".05"/></filter><filter id="iec0sue" width="1.326" height="2.373" x="9.941" y="9.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4626" stdDeviation=".125"/></filter><filter id="iMEpFNq" width="1.943" height="2.896" x="20.425" y="9.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4626" stdDeviation=".25"/></filter><filter id="iAAczXd" width="2.748" height=".641" x="12.463" y="8.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4626"/></filter><filter id="iqR0xBd" width="2.748" height=".641" x="16.982" y="8.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4626"/></filter><filter id="iIuAqzb" width="2.77" height=".7" x="16.98" y="8.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4626" stdDeviation=".125"/></filter><filter id="iFnMDye" width="2.77" height=".7" x="12.485" y="8.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4626" stdDeviation=".125"/></filter><linearGradient id="iO2aVKU" x1="17.426" x2="17.426" y1="30.357" y2="26.753" gradientUnits="userSpaceOnUse"><stop class="s9luuo8wr"/><stop offset="1" class="mw-dyzb9n"/></linearGradient><linearGradient id="iFHmW8d" x1="22.967" x2="24.881" y1="22.469" y2="22.469" gradientUnits="userSpaceOnUse"><stop offset=".17" class="h-4-uqb4q"/><stop offset="1" class="k-xmaur5i"/></linearGradient><linearGradient id="ifbmyGd" x1="8.98" x2="6.915" y1="23.313" y2="22.849" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ev32s2_gl"/><stop offset="1" class="p1zhkctql"/></linearGradient><linearGradient id="itsXHId" x1="21.139" x2="16.802" y1="12.494" y2="12.494" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="insmB4c" x1="16.118" x2="15.391" y1="14.252" y2="14.518" gradientUnits="userSpaceOnUse"><stop class="s7mkmnyxt"/><stop offset="1" class="q4yl2z--c"/></linearGradient><linearGradient id="iBEIvtb" x1="16.094" x2="16.094" y1="14.822" y2="14.47" gradientUnits="userSpaceOnUse"><stop offset=".207" class="cwarzoo8t"/><stop offset="1" class="yzog7ybub"/></linearGradient><linearGradient id="izGhMfc" x1="16.835" x2="16" y1="11.487" y2="11.522" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="i6nmh1D" x1="16" x2="16" y1="12.622" y2="12.159" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="ibVkaeb" x1="16" x2="16" y1="9.678" y2="10.472" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="iRLjx7O" x1="22.827" x2="11.257" y1="5.173" y2="5.173" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iM8f5ze" x1="18.988" x2="18.654" y1="10.009" y2="10.215" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRHt1jb" x1="14.645" x2="14.307" y1="10.022" y2="10.23" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLtNLdc" x1="22.413" x2="21.21" y1="9.983" y2="12.151" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="iDFTdhc" x1="10.172" x2="11.625" y1="10.684" y2="10.557" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iMOKr7d" x1="21.397" x2="21.397" y1="9.602" y2="11.499" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="iYjraZx" x1="19.471" x2="16.653" y1="8.698" y2="8.698" gradientUnits="userSpaceOnUse"><stop offset=".333" class="dwxodwo3m"/><stop offset="1" class="ns3cxsbdp"/></linearGradient><linearGradient id="iAUp5cc" x1="14.976" x2="12.158" y1="8.698" y2="8.698" gradientUnits="userSpaceOnUse"><stop offset=".333" class="dwxodwo3m"/><stop offset="1" class="ns3cxsbdp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-pouting-dark" /></template>
<style>
.a061yvbds {
  stop-color: var(--svg-color--4e494b, #4E494B);
  stop-opacity: 0;
}

.a20oreb3g {
  stop-color: var(--svg-color--635453, #635453);
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ac1xhuktd {
  d: path("M11.157 12.06a1.63 1.63 0 0 1-.902-.307v.927c0 .89.53 1.683 1.336 2.012a4 4 0 0 1-.344-1.176z");
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

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.b5xdtvbpr {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.62 10.103l-.53 1.832c-.108.376.151.753.518.753h.784c.367 0 .627-.383.519-.754l-.53-1.831c-.113-.406-.643-.406-.762 0");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bh_tehlut {
  d: path("M14.72 10.299c0-.311-.253-.519-.321-.581l-.311.3l.191.39z");
}

.bh4gs6bci {
  stop-color: var(--svg-color--ff6646, #FF6646);
  stop-opacity: 0;
}

.bjfup_hfs {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.093 9.645c.068.09-.073.201-.234.321c-.16.12-.28.205-.348.114s.008-.26.169-.38c.16-.12.346-.145.413-.055");
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.byra0jsyn {
  stop-color: var(--svg-color--4a3839, #4A3839);
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c4ffaubfw {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.383 9.156c.694 0 1.28.479 1.44 1.125a.29.29 0 0 1-.285.363h-2.371a.245.245 0 0 1-.242-.29a1.486 1.486 0 0 1 1.458-1.198");
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

.cfjku2bno {
  stop-color: var(--svg-color--4d3330, #4D3330);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cwarzoo8t {
  stop-color: var(--svg-color--442d32, #442D32);
}

.czxc369no {
  stop-color: var(--svg-color--2f1513, #2F1513);
}

.d4aj1-biz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.33 8.698h2.07");
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.die6v9bjs {
  stop-color: var(--svg-color--635453, #635453);
  stop-opacity: 0;
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dwxodwo3m {
  stop-color: var(--svg-color--343434, #343434);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1s_iwb5s {
  stop-color: var(--svg-color--4a1c1c, #4A1C1C);
}

.emfffdbba {
  stop-color: var(--svg-color--5f4844, #5F4844);
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.ev32s2_gl {
  stop-color: var(--svg-color--ff5437, #FF5437);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f-rzflb7f {
  fill: var(--svg-color--000, #000);
  d: path("M17.62 10.394c0-.302.241-.544.543-.544a.54.54 0 0 1 .483.794h-.962a.5.5 0 0 1-.064-.25");
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.fbwpm7b3c {
  d: path("m21.194 8.475l-.03-.63c-.01-.76-.639-1.388-1.4-1.42H18.37a2.41 2.41 0 0 1-2.116-1.255s-.057-.132-.118-.36c-.258-.97.67-1.712 1.654-1.52c.969.187 2.07.514 2.886 1.046c1.738 1.133 1.433 3.176.519 4.139");
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fr4u2db8i {
  d: path("M11.193 13.57a3.9 3.9 0 0 0 3.872 3.393h1.88a3.9 3.9 0 0 0 3.87-3.393c.118-1.877.236-3.746.324-5.622a1.444 1.444 0 0 0-1.374-1.427H18.37a2.41 2.41 0 0 1-2.204-1.438a.66.66 0 0 0-.613-.416h-1.268c-1.84 0-3.33 1.507-3.33 3.366c0 1.854.116 3.678.238 5.537");
}

.frhrvxb1w {
  d: path("M19.008 10.269a.9.9 0 0 0-.246-.492l-.276.303l.124.242z");
}

.ft5dv1b6b {
  fill: none;
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.gb_tpr34z {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.617 9.156c-.704 0-1.3.486-1.461 1.142a.296.296 0 0 0 .289.368h2.406c.154 0 .276-.14.245-.293a1.51 1.51 0 0 0-1.479-1.217");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.h-4-uqb4q {
  stop-color: var(--svg-color--ff491d, #FF491D);
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.h2xwtmsbp {
  d: path("M5.668 28.531c-.6-1.05-.453-2.812-.375-3.597l3.937-.168c.413.212 1.527.088 2.032 0l9.672-1.563c.617-.117 1.448-.177 2.125.188c.728.392.7.965.642 1.352a.1.1 0 0 1-.064.077c-4.285 1.54-12.404 4.814-13.524 5.063c-1.82.312-3.695-.04-4.445-1.352");
}

.h5sux3b6d {
  width: 2.648px;
  height: 0.541px;
  x: 12.463px;
  y: 8.475px;
  fill: var(--svg-color--0b090a, #0B090A);
  rx: 0.271px;
}

.h79xt_fpx {
  fill: var(--svg-color--280017, #280017);
  d: path("M15.145 14.096c.486-.334 1.208-.335 1.7 0a.279.279 0 0 0 .313-.46c-.68-.464-1.652-.464-2.329 0a.278.278 0 1 0 .316.46");
}

.hf1ph1b7l {
  stop-color: var(--svg-color--9d2707, #9D2707);
}

.hl6ngdbuc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.835 8.698h2.07");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hr__6pb8m {
  d: path("M20.844 12.06c.334-.01.646-.124.9-.307v.927c0 .89-.53 1.683-1.335 2.012q.256-.543.345-1.176z");
}

.hrbrn5bar {
  stop-color: var(--svg-color--5f4844, #5F4844);
  stop-opacity: 0;
}

.i42u1jcxk {
  d: path("M16.559 14.692a.512.512 0 0 0-1.024 0z");
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.in3qy-btl {
  d: path("M10.965 8.963a1.604 1.604 0 0 0 .137 3.188a78 78 0 0 1-.138-3.188");
}

.ixbfuabjj {
  d: path("M26.417 28.531c.6-1.05.453-2.812.375-3.597l-3.938-.168c-.412.212-1.526.088-2.03 0l-8.898-1.407c-.617-.117-2.097-.231-2.774.133c-.765.412-1 1.193-.937 1.578c4.27 1.532 12.632 4.563 13.757 4.813c1.82.312 3.695-.04 4.445-1.352");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j5lcx07ey {
  stop-color: var(--svg-color--e45b4e, #E45B4E);
}

.jkuyqrt8m {
  width: 2.648px;
  height: 0.541px;
  x: 16.982px;
  y: 8.475px;
  fill: var(--svg-color--0b090a, #0B090A);
  rx: 0.271px;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.k-xmaur5i {
  stop-color: var(--svg-color--ff6747, #FF6747);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.k7jsibb9h {
  stop-color: var(--svg-color--582b26, #582B26);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.kt3r-ccwj {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m21.194 8.475l-.03-.63c-.01-.76-.639-1.388-1.4-1.42H18.37a2.41 2.41 0 0 1-2.116-1.255s-.057-.132-.118-.36c-.258-.97.67-1.712 1.654-1.52c.969.187 2.07.514 2.886 1.046c1.738 1.133 1.433 3.176.519 4.139");
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l0hv0bczl {
  d: path("m15.62 10.103l-.53 1.832c-.108.376.151.753.518.753h.784c.367 0 .627-.383.519-.754l-.53-1.831c-.113-.406-.643-.406-.762 0");
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.lb5uh1r5u {
  cx: 13.55px;
  cy: 9.86px;
  rx: 0.42px;
  ry: 0.213px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lpley2bsg {
  d: path("M22.967 17.937a10.48 10.48 0 0 1 3.827 7.019l-3.827-.18z");
}

.lq4btpg7k {
  stop-color: var(--svg-color--452831, #452831);
}

.lrpdblbcr {
  d: path("M20.904 12.15q.1-1.589.184-3.179a1.604 1.604 0 0 1-.184 3.18");
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.lzppzvbjq {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.6 10.298l-.588 1.832c-.101.376.14.753.482.753h.73c.341 0 .582-.382.482-.753l-.493-1.832c-.105-.406-.502-.406-.613 0");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mw-dyzb9n {
  stop-color: var(--svg-color--d73726, #D73726);
  stop-opacity: 0;
}

.n_lbefwpq {
  d: path("M20.925 11.499q.058-.948.11-1.897a.952.952 0 0 1-.11 1.897");
}

.ns3cxsbdp {
  stop-color: var(--svg-color--343434, #343434);
  stop-opacity: 0;
}

.nszf4yi9c {
  stop-color: var(--svg-color--4e494b, #4E494B);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o9uu_2vuf {
  width: 4.223px;
  height: 6.028px;
  x: 13.918px;
  y: 12.688px;
  rx: 2.111px;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odq2frbdh {
  d: path("m9.2 24.75l-3.906.183c.577-5.253 5.03-9.34 10.436-9.34h.625c5.415 0 9.872 4.099 10.44 9.363l-4.378-.206v5.188H9.2z");
}

.osixu2bon {
  stop-color: var(--svg-color--ff6547, #FF6547);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p1zhkctql {
  stop-color: var(--svg-color--ff3a19, #FF3A19);
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
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

.pyz9maawt {
  stop-color: var(--svg-color--e45b4e, #E45B4E);
  stop-opacity: 0;
}

.pz8_28qcs {
  d: path("m5.294 24.934l3.847-.16l.058.182h.031v-7.109a10.5 10.5 0 0 0-3.936 7.086");
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q4yl2z--c {
  stop-color: var(--svg-color--554948, #554948);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qqqksli-v {
  d: path("M10.933 9.62a.952.952 0 0 0 .084 1.873a78 78 0 0 1-.084-1.872");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.s7mkmnyxt {
  stop-color: var(--svg-color--331c1f, #331C1F);
}

.s9luuo8wr {
  stop-color: var(--svg-color--d73726, #D73726);
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.tpd0s6btx {
  stop-color: var(--svg-color--2f1513, #2F1513);
  stop-opacity: 0;
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.uiu1jnbrd {
  d: path("M13.84 9.45a.963.963 0 0 0-.927 1.216h1.86a1 1 0 0 0 .035-.254a.97.97 0 0 0-.967-.963");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.v5rpejz7p {
  stop-color: var(--svg-color--ed4628, #ED4628);
}

.vrl65yioc {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m16.232 5.22l-.066-.137a.66.66 0 0 0-.613-.416h-1.268c-1.84 0-3.33 1.507-3.33 3.366v.275c-.338-.258-.764-.802-.764-1.682c0-1.068.779-1.608 1.275-1.952a2.5 2.5 0 0 0 .33-.253l.1-.104c.347-.37.968-1.027 2.051-1.315a5.5 5.5 0 0 1 1.5-.164c.473.01.806.419.806.892v1.476z");
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w19z1qc3s {
  fill: var(--svg-color--000, #000);
  d: path("M14.392 10.412a.55.55 0 0 0-.552-.552a.55.55 0 0 0-.49.806h.976a.55.55 0 0 0 .066-.254");
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.w7c30fbkj {
  d: path("M20.837 4.196c.513.177.972.535 1.263 1.048a2.36 2.36 0 0 1-.106 2.517c-.174.256-.27.561-.27.87v1.185a1.7 1.7 0 0 0-.664-.268l.078-1.6a1.444 1.444 0 0 0-1.374-1.427H18.37a2.41 2.41 0 0 1-2.203-1.437a.66.66 0 0 0-.613-.417h-1.269c-1.839 0-3.329 1.507-3.329 3.366l.03 1.532a1.7 1.7 0 0 0-.717.263V8.632c0-.31-.095-.615-.27-.871c-.475-.7-.56-1.64-.142-2.437c.29-.55.761-.935 1.295-1.122a2.67 2.67 0 0 0 1.379-1.106a2.32 2.32 0 0 1 2.88-.909c.38.166.808.166 1.189 0c.28-.118.587-.187.909-.187c.84 0 1.575.454 1.982 1.128a2.5 2.5 0 0 0 1.347 1.068");
}

.wkxl05xjv {
  d: path("M18.093 9.645c.068.09-.073.201-.234.321c-.16.12-.28.205-.348.114s.008-.26.169-.38c.16-.12.346-.145.413-.055");
}

.wt6bm4iox {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.145 14.096c.486-.334 1.208-.335 1.7 0a.279.279 0 0 0 .313-.46c-.68-.464-1.652-.464-2.329 0a.278.278 0 1 0 .316.46");
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x-to_kbtn {
  cx: 13.55px;
  cy: 9.86px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.42px;
  ry: 0.213px;
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.x7zpsiwqt {
  stop-color: var(--svg-color--5c4543, #5C4543);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xc3cwzl8h {
  stop-color: var(--svg-color--35161b, #35161B);
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xl00x07lc {
  stop-color: var(--svg-color--341617, #341617);
}

.xl4blsbsc {
  stop-color: var(--svg-color--331e2a, #331E2A);
}

.y5-hmbbhn {
  stop-color: var(--svg-color--331e2a, #331E2A);
  stop-opacity: 0;
}

.yep1jvbcp {
  d: path("m16.232 5.22l-.066-.137a.66.66 0 0 0-.613-.416h-1.268c-1.84 0-3.33 1.507-3.33 3.366v.275c-.338-.258-.764-.802-.764-1.682c0-1.068.779-1.608 1.275-1.952a2.5 2.5 0 0 0 .33-.253l.1-.104c.347-.37.968-1.027 2.051-1.315a5.5 5.5 0 0 1 1.5-.164c.473.01.806.419.806.892v1.476z");
}

.yzog7ybub {
  stop-color: var(--svg-color--442d32, #442D32);
  stop-opacity: 0;
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zr40zg26a {
  stop-color: var(--svg-color--4a1c1c, #4A1C1C);
  stop-opacity: 0;
}

.zsbbq-hya {
  d: path("M18.163 9.445a.95.95 0 0 1 .914 1.199h-1.833a.952.952 0 0 1 .918-1.199");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
