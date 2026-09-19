<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iIGonRc)" transform="rotate(-4.337 12.169 6.865)" class="a1da5kbqi"/><path class="nabtn9l8m"/><path fill="url(#i8VM4ei)" class="zpa7mldrv"/><path fill="url(#iD33dve)" class="zpa7mldrv"/><path fill="url(#ioBMhOb)" class="zpa7mldrv"/><path fill="url(#iweMHeb)" class="zpa7mldrv"/><path fill="url(#ihCjGwc)" class="zpa7mldrv"/><path fill="url(#idzSiGd)" class="sk73usb5s"/><path fill="url(#iCdv1Vc)" class="sk73usb5s"/><path fill="url(#ik9fgId)" class="sk73usb5s"/><path fill="url(#iQfh0Dc)" class="sk73usb5s"/><path fill="url(#iJgDMAe)" class="sk73usb5s"/><path fill="url(#iGacved)" class="sk73usb5s"/><circle fill="url(#i8s2vQd)" class="brmc4x8xa"/><g filter="url(#inIf05b)"><path clip-rule="evenodd" class="ts9tb8bsq"/></g><path class="l5zs6lb1l"/><path fill="url(#iSuuKzJ)" class="ty4qpzlbs"/><path fill="url(#il4Zpzc)" class="ty4qpzlbs"/><path fill="url(#izNPYBu)" class="ty4qpzlbs"/><rect class="qroywyb5a"/><path fill="url(#iYOVuOc)" class="jtdoe8b1j"/><path fill="url(#i9maRyd)" class="jtdoe8b1j"/><path fill="url(#ijs2chl)" class="jtdoe8b1j"/><path fill="url(#iRwazib)" class="jtdoe8b1j"/><g filter="url(#iOdIRzh)"><path class="ptpobzbvy"/><path fill="url(#iyZ0Pcb)" class="pu7pehbfx"/><path fill="url(#im7kWwk)" class="pu7pehbfx"/></g><path fill="url(#iIaqbRN)" class="pu7pehbfx"/><g filter="url(#i7HbV6d)"><path class="r-srsfz3r"/><path fill="url(#iMBUKpe)" class="y8kmnrbzv"/><path fill="url(#iksBMib)" class="y8kmnrbzv"/></g><g filter="url(#iYwEnMd)"><path stroke="url(#ibNqehb)" class="u1lot21qq"/></g><path class="a1xiwtecu"/><path fill="url(#ia9dURd)" class="t8c7sz24v"/><path fill="url(#imaaVNe)" class="t8c7sz24v"/><path fill="url(#i4rOk9d)" class="t8c7sz24v"/><g filter="url(#iX3qRVc)"><path class="rkrjr6ybk"/><path fill="url(#iFBsqAb)" class="fi4qb9b3i"/></g><path class="konn74byh"/><path fill="url(#iZ8oR2c)" class="m36k8qebf"/><path fill="url(#iApzCtc)" class="m36k8qebf"/><path fill="url(#iCx8Iqb)" class="m36k8qebf"/><path fill="url(#iFJC63b)" class="m36k8qebf"/><path fill="url(#ia46NVc)" class="m36k8qebf"/><path fill="url(#iQSf98M)" class="cn95gzbsf"/><g filter="url(#i8RKzHc)"><path fill="url(#ip7sdxe)" class="j550m1axq"/><path fill="url(#it1FDvc)" class="j550m1axq"/></g><g filter="url(#i6khInc)"><path fill="url(#iTXvNDe)" class="wikbxxztg"/></g><path fill="url(#ig7yDzb)" class="wikbxxztg"/><path fill="url(#iBArgyd)" class="vjum1m-hr"/><path clip-rule="evenodd" class="ve1of5bvm"/><path class="tb442ccsw"/><path fill="url(#im3SzmX)" class="pcs07tw9d"/><path fill="url(#i9eXbqd)" class="ka4upqomb"/><ellipse fill="url(#i8yE0Ic)" transform="rotate(24.61 10.87 5.414)" class="ebzh3x3ih"/><g filter="url(#iZ3gTzd)"><path class="yf-deubpt"/></g><defs><radialGradient id="i8VM4ei" cx="0" cy="0" r="1" gradientTransform="rotate(27.371 -18.212 13.78)scale(7.9528 2.89243)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="m8pmc0btt"/><stop offset="1" class="m72ygetof"/></radialGradient><radialGradient id="iD33dve" cx="0" cy="0" r="1" gradientTransform="matrix(7 5.09375 -5.69907 7.83185 4.984 9.04)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="z26-wfbav"/><stop offset=".956" class="iou487baj"/></radialGradient><radialGradient id="ioBMhOb" cx="0" cy="0" r="1" gradientTransform="matrix(-.85938 1.24999 -.4913 -.33777 5.078 10.93)" gradientUnits="userSpaceOnUse"><stop offset=".418" class="yeyqi9phi"/><stop offset="1" class="j9k09pb-s"/></radialGradient><radialGradient id="iweMHeb" cx="0" cy="0" r="1" gradientTransform="matrix(.59003 .20313 -.9568 2.77923 3.535 11.087)" gradientUnits="userSpaceOnUse"><stop class="mcvrg0kam"/><stop offset="1" class="q-30hhb4p"/></radialGradient><radialGradient id="ihCjGwc" cx="0" cy="0" r="1" gradientTransform="rotate(143.499 1.013 5.805)scale(.97189 1.16056)" gradientUnits="userSpaceOnUse"><stop class="bjjn4ob6s"/><stop offset="1" class="snqm-cbpd"/></radialGradient><radialGradient id="iCdv1Vc" cx="0" cy="0" r="1" gradientTransform="rotate(-103.261 13.906 2.775)scale(5.32961 3.05083)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="s6seicc8w"/><stop offset="1" class="yjn3q9srk"/></radialGradient><radialGradient id="ik9fgId" cx="0" cy="0" r="1" gradientTransform="rotate(84.038 -1.247 12.61)scale(5.68701 2.16045)" gradientUnits="userSpaceOnUse"><stop class="kve1gec_d"/><stop offset="1" class="r0_3lybww"/></radialGradient><radialGradient id="iQfh0Dc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40625 .71875 -1.45293 -4.86416 17.109 13.353)" gradientUnits="userSpaceOnUse"><stop class="wpy2jtqib"/><stop offset="1" class="u6kcyml4j"/></radialGradient><radialGradient id="iJgDMAe" cx="0" cy="0" r="1" gradientTransform="matrix(1.60634 -.72509 .88198 1.95392 14.394 10.94)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="p5n-ewbqx"/><stop offset="1" class="q11m-vutr"/></radialGradient><radialGradient id="iGacved" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03125 .60937 -.64188 -1.08628 13.677 10.634)" gradientUnits="userSpaceOnUse"><stop class="gjadyfboc"/><stop offset="1" class="asuvzebmi"/></radialGradient><radialGradient id="i8s2vQd" cx="0" cy="0" r="1" gradientTransform="rotate(24.692 -16.933 55.351)scale(1.12213 1.1783)" gradientUnits="userSpaceOnUse"><stop class="bmfdee-fc"/><stop offset=".906" class="y5luhbaev"/></radialGradient><radialGradient id="il4Zpzc" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 .1875 -.31662 2.16356 12.671 9.947)" gradientUnits="userSpaceOnUse"><stop class="wtj81mbzy"/><stop offset="1" class="k870jjb1v"/></radialGradient><radialGradient id="izNPYBu" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 .42188 -.65918 -1.36717 17.359 8.432)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="gz3om4b5e"/><stop offset="1" class="s9nkndynh"/></radialGradient><radialGradient id="ijs2chl" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65317 9.34098 -2.71885 -1.35439 14.084 21.12)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="y_4ptxbzf"/><stop offset="1" class="ado7u1b7k"/></radialGradient><radialGradient id="iRwazib" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8268 4.82559 -1.33887 -.50685 13.911 21.086)" gradientUnits="userSpaceOnUse"><stop class="hpbocun_g"/><stop offset="1" class="umrurxb6b"/></radialGradient><radialGradient id="iIaqbRN" cx="0" cy="0" r="1" gradientTransform="matrix(.89465 -.29687 .493 1.48575 3.933 27.946)" gradientUnits="userSpaceOnUse"><stop class="rmzq06bzd"/><stop offset="1" class="n1b4mhj1w"/></radialGradient><radialGradient id="iksBMib" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 1.96875 -.89768 .49871 17.828 21.228)" gradientUnits="userSpaceOnUse"><stop class="nkql81bxe"/><stop offset="1" class="bi5pn_1vn"/></radialGradient><radialGradient id="iFBsqAb" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 17.015 18.76)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="iZ8oR2c" cx="0" cy="0" r="1" gradientTransform="matrix(2.87501 3.59374 -13.67711 10.94177 13.922 16.978)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="iApzCtc" cx="0" cy="0" r="1" gradientTransform="matrix(1.01138 -2.18079 7.25457 3.36445 14.536 22.458)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iCx8Iqb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.05436 1.3596 -1.29326 -1.95412 18.044 16.8)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="ia46NVc" cx="0" cy="0" r="1" gradientTransform="matrix(1.90625 -.90625 .11383 .23944 13.515 17.087)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="iQSf98M" cx="0" cy="0" r="1" gradientTransform="matrix(.3125 .60583 -.77155 .39799 9.797 6.083)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="it1FDvc" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 -.04688 .05715 -1.0287 13.336 5.67)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="iTXvNDe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43749 3.12502 -3.54357 -3.89789 15.211 3.008)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="jve2rcqoj"/><stop offset="1" class="kpbiulbbs"/></radialGradient><radialGradient id="ig7yDzb" cx="0" cy="0" r="1" gradientTransform="matrix(-.1172 -1.30469 2.76646 -.2485 14.578 7.204)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="jfv70ccah"/><stop offset="1" class="b30rr0b3q"/></radialGradient><radialGradient id="iBArgyd" cx="0" cy="0" r="1" gradientTransform="rotate(115.703 5.095 7.032)scale(1.04478 1.69772)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="im3SzmX" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 0 0 .53125 10.973 5.744)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="i9eXbqd" cx="0" cy="0" r="1" gradientTransform="matrix(.25 0 0 .54102 10.805 5.765)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="iIGonRc" x1="12.284" x2="14.253" y1="8.962" y2="8.484" gradientUnits="userSpaceOnUse"><stop class="rvkj67bhb"/><stop offset="1" class="yvc-8db_y"/></linearGradient><linearGradient id="idzSiGd" x1="14.394" x2="14.394" y1="8.384" y2="17.504" gradientUnits="userSpaceOnUse"><stop class="s-mmaacyl"/><stop offset="1" class="b108nwbbf"/></linearGradient><linearGradient id="iSuuKzJ" x1="16.515" x2="15.109" y1="10.978" y2="8.541" gradientUnits="userSpaceOnUse"><stop class="cx6lx2x4e"/><stop offset="1" class="sbq6vwbkt"/></linearGradient><linearGradient id="iYOVuOc" x1="12.453" x2="9.078" y1="20.041" y2="28.166" gradientUnits="userSpaceOnUse"><stop class="rshq-s3st"/><stop offset="1" class="rvpou-b_v"/></linearGradient><linearGradient id="i9maRyd" x1="7.845" x2="9.12" y1="24.705" y2="25.188" gradientUnits="userSpaceOnUse"><stop class="q2m7j_fif"/><stop offset="1" class="mt6f54ber"/></linearGradient><linearGradient id="iyZ0Pcb" x1="5.898" x2="6.054" y1="29.002" y2="28.689" gradientUnits="userSpaceOnUse"><stop class="vrnt79u8g"/><stop offset="1" class="z-p3-w_an"/></linearGradient><linearGradient id="im7kWwk" x1="8.14" x2="7.484" y1="29.4" y2="28.962" gradientUnits="userSpaceOnUse"><stop class="sted03b1z"/><stop offset="1" class="ubkqlww9x"/></linearGradient><linearGradient id="iMBUKpe" x1="18.172" x2="19.64" y1="22.728" y2="22.072" gradientUnits="userSpaceOnUse"><stop class="rz90b38rn"/><stop offset="1" class="lngpjjb0b"/></linearGradient><linearGradient id="ibNqehb" x1="19.437" x2="24.375" y1="21.259" y2="21.072" gradientUnits="userSpaceOnUse"><stop class="f7j3ni3bi"/><stop offset="1" class="i_d2dkbya"/></linearGradient><linearGradient id="ia9dURd" x1="26.14" x2="26.64" y1="19.595" y2="20.759" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="imaaVNe" x1="26.14" x2="26.904" y1="22.556" y2="21.751" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="i4rOk9d" x1="27.922" x2="27.515" y1="21.837" y2="21.978" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="iFJC63b" x1="13.171" x2="13.859" y1="17.228" y2="18.16" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="ip7sdxe" x1="13.024" x2="10.162" y1="6.412" y2="6.584" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="i8yE0Ic" x1="10.798" x2="10.985" y1="5.376" y2="5.436" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><filter id="inIf05b" width="10.118" height="5.774" x="14.278" y="7.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.929412 0 0 0 0 0.552941 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_534"/></filter><filter id="iOdIRzh" width="4.813" height="3.178" x="3.933" y="27.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.286275 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_534"/></filter><filter id="i7HbV6d" width="8.943" height="4.095" x="17.135" y="19.447" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_534"/></filter><filter id="iYwEnMd" width="6.408" height="2.475" x="18.707" y="19.716" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_534" stdDeviation=".2"/></filter><filter id="iX3qRVc" width="3.978" height="6.092" x="16.312" y="15.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_534"/></filter><filter id="i8RKzHc" width="4.443" height="5.249" x="9.962" y="3.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.576471 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_534"/></filter><filter id="i6khInc" width="6.391" height="5.479" x="9.528" y="1.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.835294 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_534"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.592157 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_534" result="effect2_innerShadow_4002_534"/></filter><filter id="iZ3gTzd" width="1.117" height=".648" x="10.765" y="4.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.2 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_534"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-running" /></template>
<style>
.a1da5kbqi {
  d: path("M12.169 6.865h1.946v3.44h-1.946z");
}

.a1xiwtecu {
  fill: var(--svg-color--473f82, #473F82);
  d: path("m26.737 19.612l-1.234.473l-.16 1.749c.305.315 1.058 1.04 1.715 1.633c.428.387.844.467 1.146.433c.23-.026.312-.276.23-.492l-1.374-3.65a.25.25 0 0 0-.323-.146");
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.ado7u1b7k {
  stop-color: var(--svg-color--ec8b4b, #EC8B4B);
  stop-opacity: 0;
}

.asuvzebmi {
  stop-color: var(--svg-color--529cea, #529CEA);
  stop-opacity: 0;
}

.b108nwbbf {
  stop-color: var(--svg-color--337fe1, #337FE1);
}

.b30rr0b3q {
  stop-color: var(--svg-color--ef9926, #EF9926);
  stop-opacity: 0;
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.bi5pn_1vn {
  stop-color: var(--svg-color--f3953d, #F3953D);
  stop-opacity: 0;
}

.bjjn4ob6s {
  stop-color: var(--svg-color--e9b636, #E9B636);
}

.bmfdee-fc {
  stop-color: var(--svg-color--fc9d34, #FC9D34);
}

.brmc4x8xa {
  cx: 22.204px;
  cy: 12.051px;
  r: 0.63px;
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.c6vpnsb1w {
  stop-color: var(--svg-color--9c959a, #9C959A);
}

.clpaphbux {
  stop-color: var(--svg-color--5a418f, #5A418F);
}

.cn95gzbsf {
  d: path("M9.965 5.935a1 1 0 0 0 .258-.457h.18v1.125c-.215.137-.522.116-.613-.09c-.079-.175-.02-.394.175-.578");
}

.cx6lx2x4e {
  stop-color: var(--svg-color--2c6bd5, #2C6BD5);
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.e2g34f-cy {
  stop-color: var(--svg-color--5e5d8f, #5E5D8F);
}

.ebzh3x3ih {
  cx: 10.87px;
  cy: 5.414px;
  rx: 0.064px;
  ry: 0.088px;
}

.egm-dub4f {
  stop-color: var(--svg-color--ffc33e, #FFC33E);
}

.f7j3ni3bi {
  stop-color: var(--svg-color--ffcc43, #FFCC43);
}

.fi4qb9b3i {
  d: path("m17.226 21.595l-.914-2.148l1.793-3.844c1.258 1.754 1.738 2.664 1.98 3.055c.269.432.298.922-.062 1.281c-.637.569-2.13 1.341-2.797 1.656");
}

.ft5dv1b6b {
  fill: none;
}

.fvok_qxen {
  stop-color: var(--svg-color--ffbf42, #FFBF42);
}

.gei07kbgq {
  stop-color: var(--svg-color--5a418f, #5A418F);
  stop-opacity: 0;
}

.gewgt1jbg {
  stop-color: var(--svg-color--afa8b2, #AFA8B2);
}

.gjadyfboc {
  stop-color: var(--svg-color--529cea, #529CEA);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gz3om4b5e {
  stop-color: var(--svg-color--4db0fb, #4DB0FB);
}

.hpbocun_g {
  stop-color: var(--svg-color--d77364, #D77364);
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.i_d2dkbya {
  stop-color: var(--svg-color--ffcc43, #FFCC43);
  stop-opacity: 0;
}

.iou487baj {
  stop-color: var(--svg-color--b7733e, #B7733E);
}

.j23k_cb2p {
  stop-color: var(--svg-color--9c959a, #9C959A);
  stop-opacity: 0;
}

.j2u_3dtev {
  stop-color: var(--svg-color--908582, #908582);
  stop-opacity: 0;
}

.j550m1axq {
  d: path("M10.19 4.972c.038-.802.297-1.188.42-1.3h3.732l.062 3.163c-.866 2.122-3.511 2.213-3.906 1.445c-.395-.767-.353-2.38-.309-3.308");
}

.j96xv6b5h {
  stop-color: var(--svg-color--917ea3, #917EA3);
  stop-opacity: 0;
}

.j9k09pb-s {
  stop-color: var(--svg-color--fea724, #FEA724);
  stop-opacity: 0;
}

.jfv70ccah {
  stop-color: var(--svg-color--b28146, #B28146);
}

.jtdoe8b1j {
  d: path("M9.015 21.947a855 855 0 0 1-1.546 5.219l1.074 1.39c.86-1.614 2.641-4.986 2.93-5.66c.242-.566.566-.71.808-.855l1.34-.805l-1.973-2.473c-.12.094-.594.445-1.32 1.074c-.734.637-1.169 1.618-1.313 2.11");
}

.jve2rcqoj {
  stop-color: var(--svg-color--ffbc2b, #FFBC2B);
}

.k870jjb1v {
  stop-color: var(--svg-color--5aa7ea, #5AA7EA);
  stop-opacity: 0;
}

.ka4upqomb {
  d: path("m11.106 5.765l.004-.072c0-.185-.079-.336-.176-.336s-.176.15-.176.336q0 .038.004.072z");
}

.kg-rnkb9f {
  stop-color: var(--svg-color--827483, #827483);
  stop-opacity: 0;
}

.konn74byh {
  fill: var(--svg-color--918996, #918996);
  d: path("M17.351 14.267s-4.125 3.031-6.023 4.703a17.7 17.7 0 0 0 2.544 2.854a.92.92 0 0 0 1.23-.013c.92-.81 1.78-1.6 2.616-2.552c1.375-1.562 1.047-2.663.766-3.312c-.244-.563-.857-1.354-1.133-1.68");
}

.kpbiulbbs {
  stop-color: var(--svg-color--ffa629, #FFA629);
}

.kve1gec_d {
  stop-color: var(--svg-color--63a0db, #63A0DB);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l5zs6lb1l {
  fill: var(--svg-color--379ffb, #379FFB);
  d: path("M17.849 10.038L16.525 7.32l-2.764 1.323a1.483 1.483 0 0 0 1.255 2.686z");
}

.lngpjjb0b {
  stop-color: var(--svg-color--ffb657, #FFB657);
  stop-opacity: 0;
}

.m36k8qebf {
  d: path("M17.351 14.267s-4.125 3.031-6.023 4.703a17.7 17.7 0 0 0 2.544 2.854a.92.92 0 0 0 1.23-.013c.92-.81 1.78-1.6 2.616-2.552c1.375-1.562 1.047-2.663.766-3.312c-.244-.563-.857-1.354-1.133-1.68");
}

.m72ygetof {
  stop-color: var(--svg-color--d38d2e, #D38D2E);
}

.m8pmc0btt {
  stop-color: var(--svg-color--d38d2e, #D38D2E);
  stop-opacity: 0;
}

.mcvrg0kam {
  stop-color: var(--svg-color--ffd05b, #FFD05B);
}

.mt6f54ber {
  stop-color: var(--svg-color--ffd558, #FFD558);
  stop-opacity: 0;
}

.n1b4mhj1w {
  stop-color: var(--svg-color--64628c, #64628C);
  stop-opacity: 0;
}

.n8gqlhnrc {
  stop-color: var(--svg-color--9583a6, #9583A6);
  stop-opacity: 0;
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nabtn9l8m {
  fill: var(--svg-color--ffb93c, #FFB93C);
  d: path("M3.761 11.837c-.285-.363-.293-.87-.07-1.293c.223-.421.547-.832 1.016-.812c.328.014.598.276.711.62q.105.027.206.075l3 1.448a1.6 1.6 0 0 0 1.639-.149l2.223-1.622a1.15 1.15 0 0 1 1.356 1.858l-2.224 1.622a3.9 3.9 0 0 1-3.993.362l-2.918-1.421c-.246-.121-.72-.4-.946-.688");
}

.nkql81bxe {
  stop-color: var(--svg-color--f3953d, #F3953D);
}

.osaguabiz {
  stop-color: var(--svg-color--917ea3, #917EA3);
}

.p5n-ewbqx {
  stop-color: var(--svg-color--2b71e5, #2B71E5);
}

.pcs07tw9d {
  d: path("M11.301 5.765v-.003c0-.32-.137-.58-.306-.58c-.17 0-.307.26-.307.58v.003z");
}

.ptpobzbvy {
  fill: var(--svg-color--534e8c, #534E8C);
  d: path("m5.039 27.095l2.46.07l1.048 1.391l-.624 1.184a.25.25 0 0 1-.335.106l-3.41-1.75c-.197-.1-.317-.328-.197-.513c.247-.38.74-.488 1.058-.488");
}

.pu7pehbfx {
  d: path("m5.039 27.095l2.46.07l1.048 1.391l-.624 1.184a.25.25 0 0 1-.335.106l-3.41-1.75c-.197-.1-.317-.328-.197-.513c.247-.38.74-.488 1.058-.488");
}

.q-30hhb4p {
  stop-color: var(--svg-color--ffd05b, #FFD05B);
  stop-opacity: 0;
}

.q11m-vutr {
  stop-color: var(--svg-color--2b71e5, #2B71E5);
  stop-opacity: 0;
}

.q2m7j_fif {
  stop-color: var(--svg-color--ffd558, #FFD558);
}

.qroywyb5a {
  width: 1.484px;
  height: 1.324px;
  x: 4.738px;
  y: 10.005px;
  fill: var(--svg-color--ffc039, #FFC039);
  rx: 0.662px;
}

.r-srsfz3r {
  fill: var(--svg-color--ffc439, #FFC439);
  d: path("m17.937 22.658l-.652-1.278l2.613-1.683l.344 1.015l5.836-.687l-.625 1.773c-1.422.446-4.465 1.408-5.504 1.68c-1.074.281-1.848-.434-2.012-.82");
}

.r0_3lybww {
  stop-color: var(--svg-color--347cdb, #347CDB);
  stop-opacity: 0;
}

.rkrjr6ybk {
  fill: var(--svg-color--97919e, #97919E);
  d: path("m17.226 21.595l-.914-2.148l1.793-3.844c1.258 1.754 1.738 2.664 1.98 3.055c.269.432.298.922-.062 1.281c-.637.569-2.13 1.341-2.797 1.656");
}

.rmzq06bzd {
  stop-color: var(--svg-color--64628c, #64628C);
}

.roa1y3bvy {
  stop-color: var(--svg-color--9b92a1, #9B92A1);
  stop-opacity: 0;
}

.rshq-s3st {
  stop-color: var(--svg-color--ffc235, #FFC235);
}

.ruyfycb4r {
  stop-color: var(--svg-color--444367, #444367);
}

.rvkj67bhb {
  stop-color: var(--svg-color--dfa741, #DFA741);
}

.rvpou-b_v {
  stop-color: var(--svg-color--ffc443, #FFC443);
}

.rz90b38rn {
  stop-color: var(--svg-color--ffb657, #FFB657);
}

.s-mmaacyl {
  stop-color: var(--svg-color--4091ec, #4091EC);
}

.s6seicc8w {
  stop-color: var(--svg-color--346ece, #346ECE);
}

.s9nkndynh {
  stop-color: var(--svg-color--4db0fb, #4DB0FB);
  stop-opacity: 0;
}

.sbq6vwbkt {
  stop-color: var(--svg-color--2f89f4, #2F89F4);
  stop-opacity: 0;
}

.sk73usb5s {
  d: path("m13.136 8.92l.74-.39a1 1 0 0 1 .584-.107l2.003 1.774c-.229 1.789.13 3.008.9 4.077l-4.253 3.23c-1.517-2.635-1.93-5.073-1.556-6.354c.318-1.228 1.05-1.898 1.582-2.23");
}

.snqm-cbpd {
  stop-color: var(--svg-color--e9b636, #E9B636);
  stop-opacity: 0;
}

.sq7_rccwx {
  stop-color: var(--svg-color--885fa7, #885FA7);
}

.sted03b1z {
  stop-color: var(--svg-color--4c438d, #4C438D);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.suyap8bzv {
  stop-color: var(--svg-color--eba544, #EBA544);
}

.t8c7sz24v {
  d: path("m26.737 19.612l-1.234.473l-.16 1.749c.305.315 1.058 1.04 1.715 1.633c.428.387.844.467 1.146.433c.23-.026.312-.276.23-.492l-1.374-3.65a.25.25 0 0 0-.323-.146");
}

.tb442ccsw {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.696 5.765h.988c0-.391-.221-.709-.494-.709s-.494.318-.494.71");
}

.ts9tb8bsq {
  fill: var(--svg-color--ffc538, #FFC538);
  fill-rule: evenodd;
  d: path("M19.704 10.182a1.85 1.85 0 0 0-1.873-.286l-2.687 1.093l-.866-2.13l2.687-1.093a4.15 4.15 0 0 1 4.2.64l2.997 2.508a.65.65 0 0 1 .085.911l-.636.772a.65.65 0 0 1-.919.086z");
}

.ty4qpzlbs {
  d: path("M17.849 10.038L16.525 7.32l-2.764 1.323a1.483 1.483 0 0 0 1.255 2.686z");
}

.u1lot21qq {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m19.297 20.181l.392 1.14a.4.4 0 0 0 .435.266l4.563-.656");
}

.u6kcyml4j {
  stop-color: var(--svg-color--598fc9, #598FC9);
  stop-opacity: 0;
}

.ubkqlww9x {
  stop-color: var(--svg-color--4c438d, #4C438D);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.umrurxb6b {
  stop-color: var(--svg-color--d77364, #D77364);
  stop-opacity: 0;
}

.v1sha93vg {
  stop-color: var(--svg-color--746484, #746484);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.ve1of5bvm {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M11.441 6.88a.125.125 0 0 1-.001.176c-.239.233-.583.293-.692.304a.125.125 0 0 1-.026-.248c.094-.01.367-.062.543-.235a.125.125 0 0 1 .176.002");
}

.vjum1m-hr {
  d: path("m12.96 6.426l.2-1.44a.727.727 0 0 1-.2 1.44");
}

.vrnt79u8g {
  stop-color: var(--svg-color--443088, #443088);
}

.vuvc8_ujh {
  stop-color: var(--svg-color--444367, #444367);
  stop-opacity: 0;
}

.vx88q5bse {
  stop-color: var(--svg-color--484083, #484083);
  stop-opacity: 0;
}

.wikbxxztg {
  d: path("M10.828 4.219c-.656 0-.968-.372-1-.836c0-.657.502-.796.696-.817c.218-.023.304-.047.61-.261a.9.9 0 0 1 .91-.098c.148.07.476.105.71.035c.39-.117.696-.113.996.117c.21.16.363.16.614.16c.343 0 .635.154.855.32c.657.498.582 2.208.258 3.169c-.31.919-.777 1.027-1.168.992c-.47-.042-.59-.399-.66-.695a62 62 0 0 0-.266-1.04a1.07 1.07 0 0 1-.531-.671c-.1-.388-.493-.432-.758-.407c-.162.016-.61.032-1.266.032");
}

.wpy2jtqib {
  stop-color: var(--svg-color--598fc9, #598FC9);
}

.wtj81mbzy {
  stop-color: var(--svg-color--5aa7ea, #5AA7EA);
}

.y_4ptxbzf {
  stop-color: var(--svg-color--ec8b4b, #EC8B4B);
}

.y5luhbaev {
  stop-color: var(--svg-color--e17e4b, #E17E4B);
}

.y8kmnrbzv {
  d: path("m17.937 22.658l-.652-1.278l2.613-1.683l.344 1.015l5.836-.687l-.625 1.773c-1.422.446-4.465 1.408-5.504 1.68c-1.074.281-1.848-.434-2.012-.82");
}

.yeyqi9phi {
  stop-color: var(--svg-color--fea724, #FEA724);
}

.yf-deubpt {
  stroke: var(--svg-color--bc5f4e, #BC5F4E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M10.965 4.597c.129 0 .41 0 .617.149");
}

.yjn3q9srk {
  stop-color: var(--svg-color--346ece, #346ECE);
  stop-opacity: 0;
}

.yvc-8db_y {
  stop-color: var(--svg-color--efc441, #EFC441);
}

.z-p3-w_an {
  stop-color: var(--svg-color--534f8c, #534F8C);
  stop-opacity: 0;
}

.z26-wfbav {
  stop-color: var(--svg-color--b7733e, #B7733E);
  stop-opacity: 0;
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

.zpa7mldrv {
  d: path("M3.761 11.837c-.285-.363-.293-.87-.07-1.293c.223-.421.547-.832 1.016-.812c.328.014.598.276.711.62q.105.027.206.075l3 1.448a1.6 1.6 0 0 0 1.639-.149l2.223-1.622a1.15 1.15 0 0 1 1.356 1.858l-2.224 1.622a3.9 3.9 0 0 1-3.993.362l-2.918-1.421c-.246-.121-.72-.4-.946-.688");
}

</style>
