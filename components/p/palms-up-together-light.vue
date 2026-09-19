<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iIj429G)"><path class="bxm85ac_d"/></g><path fill="url(#ic1WCIe)" class="bmpatcbho"/><path fill="url(#i5rRxae)" class="bsvlz-bbs"/><path fill="url(#iobtZDy)" class="bsvlz-bbs"/><path fill="url(#iqDwvsd)" class="bsvlz-bbs"/><path fill="url(#iR4ZBlz)" class="bsvlz-bbs"/><path fill="url(#iP4XfUb)" class="bsvlz-bbs"/><path fill="url(#iuPPpFe)" class="lgbd-k7ej"/><path fill="url(#iX8QiDA)" class="lgbd-k7ej"/><path fill="url(#ihrrgvN)" class="lgbd-k7ej"/><path fill="url(#iIBy8Gd)" class="lgbd-k7ej"/><path fill="url(#ijXrK1c)" class="jw00e5bpm"/><path fill="url(#iZi1XEi)" class="jw00e5bpm"/><path fill="url(#iSzWwLe)" class="jw00e5bpm"/><path fill="url(#i9SVXsb)" class="jw00e5bpm"/><path fill="url(#iSDhxBe)" class="kwe384bnh"/><path fill="url(#iMdbBbS)" class="kwe384bnh"/><path fill="url(#in42yGc)" class="kwe384bnh"/><path fill="url(#i1yBwHb)" class="kwe384bnh"/><path fill="url(#i8ygYac)" class="ujhqir03i"/><path fill="url(#iFosxpc)" class="ujhqir03i"/><g filter="url(#iDXlmad)"><path fill="url(#iTSGu5d)" class="g16yvvb2b"/></g><g filter="url(#imNhpwL)"><rect fill="url(#iRsdTne)" class="wp3fp9bsg"/></g><g filter="url(#itNFaGc)"><path stroke="url(#iPjDabb)" class="xm0z3ccpp"/></g><g filter="url(#isdVBub)"><path stroke="url(#ii0w8Md)" class="awp5c0tzb"/></g><g filter="url(#iocHkWd)"><path class="u721w4k2u"/></g><g filter="url(#ixSjjxd)"><path stroke="url(#iMEnU9R)" class="w4t3qsb6h"/></g><g filter="url(#i8ZYg1c)"><path stroke="url(#ijeOfRd)" class="v51fq4b0y"/></g><g filter="url(#iqJPJFe)"><path stroke="url(#iSim7Fb)" class="yglbmkbbv"/></g><g filter="url(#itG5X6b)"><path class="kokdz6b9t"/></g><path fill="url(#ifQOwpd)" class="mhrcfzpac"/><path fill="url(#i8ouEIb)" class="mhrcfzpac"/><path fill="url(#irjlmDS)" class="mhrcfzpac"/><path fill="url(#iOBgxvd)" class="soqxlnoxv"/><path fill="url(#idO0yxe)" class="soqxlnoxv"/><path fill="url(#ijKhske)" class="soqxlnoxv"/><path fill="url(#imvIBJb)" class="soqxlnoxv"/><path fill="url(#iXddbka)" class="soqxlnoxv"/><path fill="url(#iNtncHd)" class="nqfo7ub1d"/><path fill="url(#i8vDMDb)" class="nqfo7ub1d"/><path fill="url(#ihCAJnE)" class="nqfo7ub1d"/><path fill="url(#isv3vmb)" class="nqfo7ub1d"/><path fill="url(#ia4llPm)" class="o14407o9p"/><path fill="url(#iQP1zSb)" class="o14407o9p"/><path fill="url(#iaPEflu)" class="o14407o9p"/><path fill="url(#i1IGVYc)" class="o14407o9p"/><path fill="url(#ifHFmLc)" class="qhs9-n4dm"/><path fill="url(#iNxUENd)" class="qhs9-n4dm"/><path fill="url(#iq1yENb)" class="dbs6_713q"/><g filter="url(#iiGQuSd)"><path class="v5xbr1b9p"/></g><g filter="url(#iymdoBd)"><path fill="url(#iKdiaZd)" class="cv8923b0m"/></g><g filter="url(#iwD3lEc)"><path fill="url(#iOFQOxd)" class="gm52xgkng"/></g><g filter="url(#i12FDKb)"><path stroke="url(#iZSP6SL)" class="ab6ade43t"/></g><defs><linearGradient id="i5rRxae" x1="3.245" x2="5.55" y1="16.706" y2="16.706" gradientUnits="userSpaceOnUse"><stop class="kz8uvyblk"/><stop offset="1" class="rlw3im_cx"/></linearGradient><linearGradient id="iobtZDy" x1="7.499" x2="6.058" y1="16.188" y2="16.299" gradientUnits="userSpaceOnUse"><stop class="huvvslb_d"/><stop offset="1" class="puwb9bb0g"/></linearGradient><linearGradient id="iP4XfUb" x1="7.106" x2="5.65" y1="19.599" y2="18.866" gradientUnits="userSpaceOnUse"><stop class="uw0wzsn6p"/><stop offset="1" class="fmyqnxbcv"/></linearGradient><linearGradient id="iuPPpFe" x1="6.193" x2="8.219" y1="14.519" y2="14.519" gradientUnits="userSpaceOnUse"><stop class="v1fjeyb4x"/><stop offset="1" class="v-a616b0d"/></linearGradient><linearGradient id="iX8QiDA" x1="10.254" x2="8.922" y1="14.479" y2="14.479" gradientUnits="userSpaceOnUse"><stop class="nl4perboj"/><stop offset="1" class="gcjk9ubpr"/></linearGradient><linearGradient id="ihrrgvN" x1="8.146" x2="8.146" y1="18.528" y2="16.512" gradientUnits="userSpaceOnUse"><stop class="uw0wzsn6p"/><stop offset="1" class="fmyqnxbcv"/></linearGradient><linearGradient id="ijXrK1c" x1="9.604" x2="11.048" y1="16.065" y2="16.068" gradientUnits="userSpaceOnUse"><stop class="dvvsmvbfi"/><stop offset="1" class="yw7xz_mkt"/></linearGradient><linearGradient id="iZi1XEi" x1="13.245" x2="12.069" y1="16.093" y2="16.093" gradientUnits="userSpaceOnUse"><stop class="hy6esgc9r"/><stop offset="1" class="buxzypfoj"/></linearGradient><linearGradient id="iSzWwLe" x1="10.947" x2="10.889" y1="20.114" y2="16.481" gradientUnits="userSpaceOnUse"><stop offset=".46" class="uw0wzsn6p"/><stop offset="1" class="fmyqnxbcv"/></linearGradient><linearGradient id="iSDhxBe" x1="12.474" x2="14.51" y1="18.172" y2="18.176" gradientUnits="userSpaceOnUse"><stop class="agqr1fqnl"/><stop offset="1" class="yvp5_ebmi"/></linearGradient><linearGradient id="iMdbBbS" x1="16.608" x2="15.216" y1="18.172" y2="18.172" gradientUnits="userSpaceOnUse"><stop class="fvgs_cbqi"/><stop offset="1" class="z3wmenbgy"/></linearGradient><linearGradient id="iTSGu5d" x1="5.266" x2="5.875" y1="10.094" y2="18.903" gradientUnits="userSpaceOnUse"><stop class="z2ocpzy1c"/><stop offset="1" class="ez54n3brs"/></linearGradient><linearGradient id="iRsdTne" x1="8.695" x2="10.775" y1="6.625" y2="17.847" gradientUnits="userSpaceOnUse"><stop class="y28tgx-in"/><stop offset="1" class="h0vjas8xq"/></linearGradient><linearGradient id="iPjDabb" x1="15.875" x2="12.598" y1="15.534" y2="27.346" gradientUnits="userSpaceOnUse"><stop class="wl3r7lcsl"/><stop offset="1" class="i6vv_mv8s"/></linearGradient><linearGradient id="ii0w8Md" x1="13.883" x2="5.886" y1="20.148" y2="19.743" gradientUnits="userSpaceOnUse"><stop class="obzsb4qok"/><stop offset="1" class="d6j0fibkm"/></linearGradient><linearGradient id="iMEnU9R" x1="7.129" x2="6.894" y1="18.562" y2="20.983" gradientUnits="userSpaceOnUse"><stop class="q5u40b7rv"/><stop offset="1" class="pfdmmcc2p"/></linearGradient><linearGradient id="ijeOfRd" x1="12.725" x2="12.579" y1="19.331" y2="19.754" gradientUnits="userSpaceOnUse"><stop class="wvl4ponzh"/><stop offset="1" class="sa15ql7ok"/></linearGradient><linearGradient id="iSim7Fb" x1="9.766" x2="9.785" y1="18.381" y2="18.828" gradientUnits="userSpaceOnUse"><stop class="bo9hvcbia"/><stop offset="1" class="c8p91v_5g"/></linearGradient><linearGradient id="iOBgxvd" x1="24.703" x2="27.089" y1="16.221" y2="16.706" gradientUnits="userSpaceOnUse"><stop class="jp0lmqb1t"/><stop offset="1" class="j3vw9xa3w"/></linearGradient><linearGradient id="idO0yxe" x1="26.047" x2="26.672" y1="19.252" y2="17.221" gradientUnits="userSpaceOnUse"><stop class="o9l3lj37o"/><stop offset="1" class="ma75l4tpe"/></linearGradient><linearGradient id="imvIBJb" x1="28.672" x2="27.266" y1="17.08" y2="17.002" gradientUnits="userSpaceOnUse"><stop class="qz4ot1b2f"/><stop offset="1" class="v7sxv_yvc"/></linearGradient><linearGradient id="iNtncHd" x1="22.26" x2="24.742" y1="14.015" y2="14.015" gradientUnits="userSpaceOnUse"><stop class="zy1yztg1o"/><stop offset="1" class="oyp2giuib"/></linearGradient><linearGradient id="i8vDMDb" x1="26.234" x2="24.655" y1="14.284" y2="14.015" gradientUnits="userSpaceOnUse"><stop class="x-ji0sdhw"/><stop offset="1" class="ml1gn4b3a"/><stop offset="1" class="xfnnc1brw"/></linearGradient><linearGradient id="ihCAJnE" x1="23.293" x2="23.293" y1="18.397" y2="16.015" gradientUnits="userSpaceOnUse"><stop class="o9l3lj37o"/><stop offset="1" class="ma75l4tpe"/></linearGradient><linearGradient id="ia4llPm" x1="18.46" x2="21.026" y1="15.603" y2="15.603" gradientUnits="userSpaceOnUse"><stop class="j-or5tb5f"/><stop offset="1" class="vkh3wmi4u"/></linearGradient><linearGradient id="iQP1zSb" x1="19.984" x2="19.984" y1="19.971" y2="17.596" gradientUnits="userSpaceOnUse"><stop class="o9l3lj37o"/><stop offset="1" class="ma75l4tpe"/></linearGradient><linearGradient id="iKdiaZd" x1="17.859" x2="19.1" y1="13.745" y2="22.988" gradientUnits="userSpaceOnUse"><stop class="obzsb4qok"/><stop offset="1" class="d6j0fibkm"/></linearGradient><linearGradient id="iOFQOxd" x1="21.3" x2="22.088" y1="12.075" y2="20.948" gradientUnits="userSpaceOnUse"><stop class="xvj33islx"/><stop offset="1" class="rvif-wb4h"/></linearGradient><linearGradient id="iZSP6SL" x1="25.984" x2="17.334" y1="21.076" y2="20.829" gradientUnits="userSpaceOnUse"><stop class="hsmomw9sm"/><stop offset="1" class="h4g8pqbcl"/></linearGradient><radialGradient id="ic1WCIe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4055 17.94428 -12.74747 -1.70885 10.962 12.941)" gradientUnits="userSpaceOnUse"><stop offset=".774" class="i9ewiqmwr"/><stop offset="1" class="z-fxlcvzk"/></radialGradient><radialGradient id="iqDwvsd" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 -.125 .49576 4.58576 4.5 19.594)" gradientUnits="userSpaceOnUse"><stop class="r_1b8mb8n"/><stop offset="1" class="e3idfjmse"/></radialGradient><radialGradient id="iR4ZBlz" cx="0" cy="0" r="1" gradientTransform="matrix(-.28574 2.59375 -2.48411 -.27366 4.91 10.156)" gradientUnits="userSpaceOnUse"><stop class="jcfgc9tou"/><stop offset="1" class="rn0ypyb5q"/></radialGradient><radialGradient id="iIBy8Gd" cx="0" cy="0" r="1" gradientTransform="rotate(122.261 2.176 7.163)scale(2.67608 4.1835)" gradientUnits="userSpaceOnUse"><stop class="jy-zo_4wh"/><stop offset="1" class="ilvrzubdr"/></radialGradient><radialGradient id="i9SVXsb" cx="0" cy="0" r="1" gradientTransform="rotate(108.681 2.332 9.593)scale(2.69033 2.49995)" gradientUnits="userSpaceOnUse"><stop class="a3um2ccdr"/><stop offset="1" class="v_ba5s4yq"/></radialGradient><radialGradient id="in42yGc" cx="0" cy="0" r="1" gradientTransform="rotate(-49.148 29.119 -3.34)scale(4.04834 6.33482)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="vhxzwb5vo"/><stop offset="1" class="w9v04g5wl"/></radialGradient><radialGradient id="i1yBwHb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.58526 2.25577 -1.30627 -.918 15.884 12.855)" gradientUnits="userSpaceOnUse"><stop class="hlym_db8t"/><stop offset="1" class="j0jxcob9z"/></radialGradient><radialGradient id="i8ygYac" cx="0" cy="0" r="1" gradientTransform="rotate(161.655 .935 9.547)scale(2.33228 4.21779)" gradientUnits="userSpaceOnUse"><stop offset=".007" class="tieq01byj"/><stop offset="1" class="bfpghqq5m"/></radialGradient><radialGradient id="iFosxpc" cx="0" cy="0" r="1" gradientTransform="matrix(2.89136 -2.98366 4.84233 4.69254 1.505 20.06)" gradientUnits="userSpaceOnUse"><stop offset=".696" class="j8u8__bkt"/><stop offset="1" class="j9f2d0frw"/></radialGradient><radialGradient id="ifQOwpd" cx="0" cy="0" r="1" gradientTransform="rotate(143.135 12.436 14.17)scale(2.49507 3.08863)" gradientUnits="userSpaceOnUse"><stop class="tieq01byj"/><stop offset=".745" class="bfpghqq5m"/></radialGradient><radialGradient id="i8ouEIb" cx="0" cy="0" r="1" gradientTransform="matrix(11.59374 4.0625 -5.91453 16.87915 18.797 19.252)" gradientUnits="userSpaceOnUse"><stop offset=".823" class="ha_0wczly"/><stop offset="1" class="b9toukgmw"/></radialGradient><radialGradient id="irjlmDS" cx="0" cy="0" r="1" gradientTransform="rotate(109.306 6.974 16.68)scale(16.5476 14.7892)" gradientUnits="userSpaceOnUse"><stop offset=".721" class="th9h17ssd"/><stop offset="1" class="iqn3z23ip"/></radialGradient><radialGradient id="ijKhske" cx="0" cy="0" r="1" gradientTransform="rotate(156.949 13.217 8.928)scale(1.5962 1.15685)" gradientUnits="userSpaceOnUse"><stop class="o71v97e3v"/><stop offset="1" class="k7v6fkbxr"/></radialGradient><radialGradient id="iXddbka" cx="0" cy="0" r="1" gradientTransform="rotate(103.404 6.122 20.633)scale(3.57368 1.76064)" gradientUnits="userSpaceOnUse"><stop offset=".398" class="ldqtq5bej"/><stop offset="1" class="ux_j4hben"/></radialGradient><radialGradient id="isv3vmb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9104 1.45892 -.92719 -1.21411 25.807 9.614)" gradientUnits="userSpaceOnUse"><stop class="xb01m179x"/><stop offset="1" class="x_q9zom5s"/></radialGradient><radialGradient id="iaPEflu" cx="0" cy="0" r="1" gradientTransform="matrix(-.00003 -9.76499 4.0055 -.00001 20.695 19.934)" gradientUnits="userSpaceOnUse"><stop offset=".763" class="j5ckc1lmw"/><stop offset="1" class="nr3eeqb1a"/></radialGradient><radialGradient id="i1IGVYc" cx="0" cy="0" r="1" gradientTransform="rotate(132.113 8.486 10.565)scale(1.96669 1.26799)" gradientUnits="userSpaceOnUse"><stop class="xvj33islx"/><stop offset="1" class="rvif-wb4h"/></radialGradient><radialGradient id="ifHFmLc" cx="0" cy="0" r="1" gradientTransform="matrix(.44 3.2784 -4.5721 .61364 17.7 12.254)" gradientUnits="userSpaceOnUse"><stop class="j7hojbbkk"/><stop offset="1" class="i54-0ggyc"/></radialGradient><radialGradient id="iNxUENd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.27068 1.29423 -.92672 -.90986 19.143 13.473)" gradientUnits="userSpaceOnUse"><stop class="ufuwm4b_g"/><stop offset="1" class="btg3hq-4h"/></radialGradient><radialGradient id="iq1yENb" cx="0" cy="0" r="1" gradientTransform="rotate(20.056 -42.317 84.917)scale(1.57817 4.28098)" gradientUnits="userSpaceOnUse"><stop class="q_-x1erdq"/><stop offset="1" class="c-h_76z_f"/></radialGradient><filter id="iIj429G" width="15.887" height="21.793" x="1.113" y="8.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.654902 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3962"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.682353 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3962" result="effect2_innerShadow_20020_3962"/></filter><filter id="iDXlmad" width="2.833" height="10.003" x="4.201" y="11.249" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3962" stdDeviation=".25"/></filter><filter id="imNhpwL" width="2.063" height="9.793" x="7.663" y="9.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3962" stdDeviation=".25"/></filter><filter id="itNFaGc" width="6.045" height="16.977" x="10.723" y="12.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3962" stdDeviation=".625"/></filter><filter id="isdVBub" width="11.477" height="5.166" x="4.28" y="17.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3962" stdDeviation=".625"/></filter><filter id="iocHkWd" width="7.738" height="10.182" x=".766" y="16.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3962" stdDeviation="1"/></filter><filter id="ixSjjxd" width="2.012" height="2.673" x="5.305" y="18.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3962" stdDeviation=".125"/></filter><filter id="i8ZYg1c" width="3.141" height="1.381" x="9.958" y="18.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3962" stdDeviation=".125"/></filter><filter id="iqJPJFe" width="3.129" height="1.447" x="6.973" y="17.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3962" stdDeviation=".125"/></filter><filter id="itG5X6b" width="15.887" height="21.293" x="16" y="8.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.603922 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3962"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.541176 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_3962" result="effect2_innerShadow_20020_3962"/></filter><filter id="iiGQuSd" width="5.961" height="9.438" x="24.297" y="16.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3962" stdDeviation=".75"/></filter><filter id="iymdoBd" width="2.219" height="8.57" x="17.359" y="13.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3962" stdDeviation=".25"/></filter><filter id="iwD3lEc" width="2.219" height="9.236" x="20.351" y="10.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3962" stdDeviation=".25"/></filter><filter id="i12FDKb" width="12.094" height="6.468" x="15.766" y="17.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3962" stdDeviation=".625"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:palms-up-together-light" /></template>
<style>
.a3um2ccdr {
  stop-color: var(--svg-color--f5c0a1, #F5C0A1);
}

.ab6ade43t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M17.64 21.659c1.115-1.167 4.344-3.313 8.344-2.563");
}

.agqr1fqnl {
  stop-color: var(--svg-color--e8a992, #E8A992);
}

.awp5c0tzb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M6.156 19.372c1.406-.416 4.92-.783 7.727 1.08");
}

.b9toukgmw {
  stop-color: var(--svg-color--f4c6b1, #F4C6B1);
}

.bfpghqq5m {
  stop-color: var(--svg-color--ffdfc6, #FFDFC6);
  stop-opacity: 0;
}

.bmpatcbho {
  d: path("M6.193 10.919a1.773 1.773 0 1 1 3.547 0v.739c.259-.566.862-.91 1.565-.91c.94 0 1.7.762 1.7 1.702v.915c.313-.324.776-.51 1.294-.51A1.7 1.7 0 0 1 16 14.556v8.196c0 2.118-.656 3.498-1.021 3.98a6.32 6.32 0 0 1-6.14 3.175c-2.468-.161-3.883-1.396-4.823-2.577c-.86-1.14-1.594-3.011-1.82-3.664l.002-.011c-.276-.782-1.01-3.072-1.084-4.79v-.055a1.853 1.853 0 0 1 2.097-1.837l-.306-4.145a1.743 1.743 0 0 1 3.288-.925z");
}

.bo9hvcbia {
  stop-color: var(--svg-color--ffd6bb, #FFD6BB);
}

.bsvlz-bbs {
  d: path("M4.515 10.961c-.96.071-1.68.907-1.61 1.867l.306 4.145c.8.105 1.439.72 1.58 1.508h.002l.785 3.974c.406-.171 1.672-.875 1.263-3.647l-.46-6.237a1.743 1.743 0 0 0-1.866-1.61");
}

.btg3hq-4h {
  stop-color: var(--svg-color--ffceb9, #FFCEB9);
  stop-opacity: 0;
}

.buxzypfoj {
  stop-color: var(--svg-color--fabf9f, #FABF9F);
  stop-opacity: 0;
}

.bxm85ac_d {
  fill: var(--svg-color--ffc8b5, #FFC8B5);
  d: path("M6.193 10.919a1.773 1.773 0 1 1 3.547 0v.739c.259-.566.862-.91 1.565-.91c.94 0 1.7.762 1.7 1.702v.915c.313-.324.776-.51 1.294-.51A1.7 1.7 0 0 1 16 14.556v8.196c0 2.118-.656 3.498-1.021 3.98a6.32 6.32 0 0 1-6.14 3.175c-2.468-.161-3.883-1.396-4.823-2.577c-.86-1.14-1.594-3.011-1.82-3.664l.002-.011c-.276-.782-1.01-3.072-1.084-4.79v-.055a1.853 1.853 0 0 1 2.097-1.837l-.306-4.145a1.743 1.743 0 0 1 3.288-.925z");
}

.c-h_76z_f {
  stop-color: var(--svg-color--d99c86, #D99C86);
  stop-opacity: 0;
}

.c8p91v_5g {
  stop-color: var(--svg-color--ffd6bb, #FFD6BB);
  stop-opacity: 0;
}

.cv8923b0m {
  d: path("M17.86 21.315v-7.569c.867-.037 1.218.596 1.218 1.176v5.247z");
}

.d6j0fibkm {
  stop-color: var(--svg-color--ffd2bd, #FFD2BD);
  stop-opacity: 0;
}

.dbs6_713q {
  d: path("M30.886 18.866v-.056a1.853 1.853 0 0 0-3.677-.33h-.002l-.793 4.03l3.367 1.203c.258-.719 1.03-3.085 1.105-4.847");
}

.dvvsmvbfi {
  stop-color: var(--svg-color--edad94, #EDAD94);
}

.e3idfjmse {
  stop-color: var(--svg-color--eca885, #ECA885);
  stop-opacity: 0;
}

.ez54n3brs {
  stop-color: var(--svg-color--ffd3bd, #FFD3BD);
  stop-opacity: 0;
}

.fmyqnxbcv {
  stop-color: var(--svg-color--ffc8b5, #FFC8B5);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvgs_cbqi {
  stop-color: var(--svg-color--e2a590, #E2A590);
}

.g16yvvb2b {
  d: path("m5.541 20.752l-.837-8.4a.548.548 0 1 1 1.09-.108l.74 7.607z");
}

.gcjk9ubpr {
  stop-color: var(--svg-color--f9bd9d, #F9BD9D);
  stop-opacity: 0;
}

.gm52xgkng {
  d: path("M20.851 19.565V11.33c.867-.039 1.22.618 1.22 1.22v7.015z");
}

.h0vjas8xq {
  stop-color: var(--svg-color--ffe1c6, #FFE1C6);
  stop-opacity: 0;
}

.h4g8pqbcl {
  stop-color: var(--svg-color--fbc8b3, #FBC8B3);
  stop-opacity: 0;
}

.ha_0wczly {
  stop-color: var(--svg-color--f4c6b1, #F4C6B1);
  stop-opacity: 0;
}

.hlym_db8t {
  stop-color: var(--svg-color--fbceb4, #FBCEB4);
}

.hsmomw9sm {
  stop-color: var(--svg-color--fbc8b3, #FBC8B3);
}

.huvvslb_d {
  stop-color: var(--svg-color--ebad8f, #EBAD8F);
}

.hy6esgc9r {
  stop-color: var(--svg-color--fabf9f, #FABF9F);
}

.i54-0ggyc {
  stop-color: var(--svg-color--e9b99e, #E9B99E);
  stop-opacity: 0;
}

.i6vv_mv8s {
  stop-color: var(--svg-color--ffd6c1, #FFD6C1);
  stop-opacity: 0;
}

.i9ewiqmwr {
  stop-color: var(--svg-color--c88b98, #C88B98);
  stop-opacity: 0;
}

.ilvrzubdr {
  stop-color: var(--svg-color--fdceb1, #FDCEB1);
  stop-opacity: 0;
}

.iqn3z23ip {
  stop-color: var(--svg-color--bf8094, #BF8094);
}

.j-or5tb5f {
  stop-color: var(--svg-color--e6a98e, #E6A98E);
}

.j0jxcob9z {
  stop-color: var(--svg-color--fbceb4, #FBCEB4);
  stop-opacity: 0;
}

.j3vw9xa3w {
  stop-color: var(--svg-color--e5a68e, #E5A68E);
  stop-opacity: 0;
}

.j5ckc1lmw {
  stop-color: var(--svg-color--e2b196, #E2B196);
  stop-opacity: 0;
}

.j7hojbbkk {
  stop-color: var(--svg-color--e9b99e, #E9B99E);
}

.j8u8__bkt {
  stop-color: var(--svg-color--ffccae, #FFCCAE);
  stop-opacity: 0;
}

.j9f2d0frw {
  stop-color: var(--svg-color--ffccae, #FFCCAE);
}

.jcfgc9tou {
  stop-color: var(--svg-color--e6b89c, #E6B89C);
}

.jp0lmqb1t {
  stop-color: var(--svg-color--e5a68e, #E5A68E);
}

.jw00e5bpm {
  d: path("M11.305 10.749c-.94 0-1.7.612-1.7 1.551v6.456a1.7 1.7 0 0 0 2.993 1.105v-5.454c0-.422.154-.778.408-1.042v-.915a1.7 1.7 0 0 0-1.701-1.701");
}

.jy-zo_4wh {
  stop-color: var(--svg-color--fdceb1, #FDCEB1);
}

.k7v6fkbxr {
  stop-color: var(--svg-color--ffe0c5, #FFE0C5);
  stop-opacity: 0;
}

.kokdz6b9t {
  fill: var(--svg-color--f4bfaf, #F4BFAF);
  d: path("M25.807 10.919a1.773 1.773 0 1 0-3.547 0v.739c-.259-.566-.862-.91-1.565-.91a1.7 1.7 0 0 0-1.7 1.702v.915c-.313-.324-.776-.51-1.294-.51A1.7 1.7 0 0 0 16 14.556v8.196c0 2.118.656 3.498 1.021 3.98a6.32 6.32 0 0 0 6.14 3.175c2.468-.161 3.883-1.396 4.823-2.577c.86-1.14 1.594-3.011 1.82-3.664l-.002-.011c.276-.782 1.01-3.072 1.084-4.79v-.055a1.853 1.853 0 0 0-2.097-1.837l.306-4.145a1.743 1.743 0 0 0-3.288-.925z");
}

.kwe384bnh {
  d: path("M12.598 14.407c0-.94.762-1.552 1.701-1.552S16 13.617 16 14.556v4.613a1.7 1.7 0 1 1-3.402 0z");
}

.kz8uvyblk {
  stop-color: var(--svg-color--e3a993, #E3A993);
}

.ldqtq5bej {
  stop-color: var(--svg-color--d28f74, #D28F74);
}

.lgbd-k7ej {
  d: path("M6.193 10.919a1.773 1.773 0 1 1 3.547 0v.739q-.134.286-.136.643v5.492a1.774 1.774 0 0 1-2.789.668l-.434-5.89a1.7 1.7 0 0 0-.188-.668z");
}

.ma75l4tpe {
  stop-color: var(--svg-color--f4bfaf, #F4BFAF);
  stop-opacity: 0;
}

.mhrcfzpac {
  d: path("M25.807 10.919a1.773 1.773 0 1 0-3.547 0v.739c-.259-.566-.862-.91-1.565-.91a1.7 1.7 0 0 0-1.7 1.702v.915c-.313-.324-.776-.51-1.294-.51A1.7 1.7 0 0 0 16 14.556v8.196c0 2.118.656 3.498 1.021 3.98a6.32 6.32 0 0 0 6.14 3.175c2.468-.161 3.883-1.396 4.823-2.577c.86-1.14 1.594-3.011 1.82-3.664l-.002-.011c.276-.782 1.01-3.072 1.084-4.79v-.055a1.853 1.853 0 0 0-2.097-1.837l.306-4.145a1.743 1.743 0 0 0-3.288-.925z");
}

.ml1gn4b3a {
  stop-color: var(--svg-color--dba28c, #DBA28C);
  stop-opacity: 0;
}

.nl4perboj {
  stop-color: var(--svg-color--f9bd9d, #F9BD9D);
}

.nqfo7ub1d {
  d: path("M25.807 10.919a1.773 1.773 0 1 0-3.547 0v.739q.134.286.136.643v5.492a1.774 1.774 0 0 0 2.789.668l.434-5.89c.018-.24.084-.466.188-.668z");
}

.nr3eeqb1a {
  stop-color: var(--svg-color--e2b196, #E2B196);
}

.o14407o9p {
  d: path("M20.695 10.749c.94 0 1.7.612 1.7 1.551v6.456a1.7 1.7 0 0 1-2.993 1.105v-5.454c0-.422-.154-.778-.408-1.042v-.915a1.7 1.7 0 0 1 1.701-1.701");
}

.o71v97e3v {
  stop-color: var(--svg-color--ffe0c5, #FFE0C5);
}

.o9l3lj37o {
  stop-color: var(--svg-color--f4bfaf, #F4BFAF);
}

.obzsb4qok {
  stop-color: var(--svg-color--ffd2bd, #FFD2BD);
}

.oyp2giuib {
  stop-color: var(--svg-color--e5a98f, #E5A98F);
  stop-opacity: 0;
}

.pfdmmcc2p {
  stop-color: var(--svg-color--ffd4be, #FFD4BE);
  stop-opacity: 0;
}

.puwb9bb0g {
  stop-color: var(--svg-color--ebad8f, #EBAD8F);
  stop-opacity: 0;
}

.q_-x1erdq {
  stop-color: var(--svg-color--d99c86, #D99C86);
}

.q5u40b7rv {
  stop-color: var(--svg-color--ffd4be, #FFD4BE);
}

.qhs9-n4dm {
  d: path("M19.402 14.407c0-.94-.762-1.552-1.701-1.552A1.7 1.7 0 0 0 16 14.556v4.613a1.7 1.7 0 1 0 3.402 0z");
}

.qz4ot1b2f {
  stop-color: var(--svg-color--ffd3b8, #FFD3B8);
}

.r_1b8mb8n {
  stop-color: var(--svg-color--eca885, #ECA885);
}

.rlw3im_cx {
  stop-color: var(--svg-color--e3a993, #E3A993);
  stop-opacity: 0;
}

.rn0ypyb5q {
  stop-color: var(--svg-color--e6b89c, #E6B89C);
  stop-opacity: 0;
}

.rvif-wb4h {
  stop-color: var(--svg-color--fecfbb, #FECFBB);
  stop-opacity: 0;
}

.sa15ql7ok {
  stop-color: var(--svg-color--ffd0bc, #FFD0BC);
  stop-opacity: 0;
}

.soqxlnoxv {
  d: path("M27.485 10.961c.96.071 1.68.907 1.61 1.867l-.306 4.145c-.8.105-1.439.72-1.58 1.508h-.002l-.785 3.974c-.406-.171-1.672-.875-1.263-3.647l.46-6.237c.071-.96.907-1.68 1.866-1.61");
}

.th9h17ssd {
  stop-color: var(--svg-color--bf8094, #BF8094);
  stop-opacity: 0;
}

.tieq01byj {
  stop-color: var(--svg-color--ffdfc6, #FFDFC6);
}

.u721w4k2u {
  stroke: var(--svg-color--ffdbc5, #FFDBC5);
  stroke-linecap: round;
  d: path("m3.266 18.531l.944 3.996c.145.593.668 1.441 1.793 1.113");
}

.ufuwm4b_g {
  stop-color: var(--svg-color--ffceb9, #FFCEB9);
}

.ujhqir03i {
  d: path("M1.114 18.866v-.056a1.853 1.853 0 0 1 3.677-.33h.002l.772 4.012l-3.346 1.221c-.258-.719-1.03-3.085-1.105-4.847");
}

.uw0wzsn6p {
  stop-color: var(--svg-color--ffc8b5, #FFC8B5);
}

.ux_j4hben {
  stop-color: var(--svg-color--d28f74, #D28F74);
  stop-opacity: 0;
}

.v_ba5s4yq {
  stop-color: var(--svg-color--f5c0a1, #F5C0A1);
  stop-opacity: 0;
}

.v-a616b0d {
  stop-color: var(--svg-color--e3a281, #E3A281);
  stop-opacity: 0;
}

.v1fjeyb4x {
  stop-color: var(--svg-color--e3a281, #E3A281);
}

.v51fq4b0y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M10.458 18.83c.27.146 1.078.425 2.14.375");
}

.v5xbr1b9p {
  stroke: var(--svg-color--dda495, #DDA495);
  stroke-linecap: round;
  d: path("M28.258 18.565c-.188.958-1.367 4.312-1.961 5.437");
}

.v7sxv_yvc {
  stop-color: var(--svg-color--ffd3b8, #FFD3B8);
  stop-opacity: 0;
}

.vhxzwb5vo {
  stop-color: var(--svg-color--ffc9b6, #FFC9B6);
}

.vkh3wmi4u {
  stop-color: var(--svg-color--e6a98e, #E6A98E);
  stop-opacity: 0;
}

.w4t3qsb6h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M6.817 18.835c-.065.266-.358.973-1.012 1.673");
}

.w9v04g5wl {
  stop-color: var(--svg-color--ffc9b6, #FFC9B6);
  stop-opacity: 0;
}

.wl3r7lcsl {
  stop-color: var(--svg-color--ffd6c1, #FFD6C1);
}

.wp3fp9bsg {
  width: 1.063px;
  height: 8.793px;
  x: 8.163px;
  y: 10.093px;
  rx: 0.531px;
}

.wvl4ponzh {
  stop-color: var(--svg-color--ffd0bc, #FFD0BC);
}

.x_q9zom5s {
  stop-color: var(--svg-color--ffdec5, #FFDEC5);
  stop-opacity: 0;
}

.x-ji0sdhw {
  stop-color: var(--svg-color--edaf8f, #EDAF8F);
}

.xb01m179x {
  stop-color: var(--svg-color--ffdec5, #FFDEC5);
}

.xfnnc1brw {
  stop-color: var(--svg-color--edaf8f, #EDAF8F);
  stop-opacity: 0;
}

.xm0z3ccpp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M14.893 14.489v7.862c.011 1.226-.432 4.015-2.295 5.365");
}

.xvj33islx {
  stop-color: var(--svg-color--fecfbb, #FECFBB);
}

.y28tgx-in {
  stop-color: var(--svg-color--ffe1c6, #FFE1C6);
}

.yglbmkbbv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M7.473 18.746c.305.037 1.159 0 2.129-.436");
}

.yvp5_ebmi {
  stop-color: var(--svg-color--e8a992, #E8A992);
  stop-opacity: 0;
}

.yw7xz_mkt {
  stop-color: var(--svg-color--edad94, #EDAD94);
  stop-opacity: 0;
}

.z-fxlcvzk {
  stop-color: var(--svg-color--c88b98, #C88B98);
}

.z2ocpzy1c {
  stop-color: var(--svg-color--ffd3bd, #FFD3BD);
}

.z3wmenbgy {
  stop-color: var(--svg-color--e2a590, #E2A590);
  stop-opacity: 0;
}

.zy1yztg1o {
  stop-color: var(--svg-color--e5a98f, #E5A98F);
}

</style>
