<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i7tFKzd)"><path class="xds4qmbsk"/><path fill="url(#iOzt8we)" class="sis9jbb6v"/><path fill="url(#it89dac)" class="sis9jbb6v"/></g><g filter="url(#ibeoNle)"><path class="jprx-8bud"/><path fill="url(#i0G5Qhc)" class="tim7irbbf"/><path fill="url(#ifxC6Kc)" class="tim7irbbf"/></g><g filter="url(#islonce)"><path class="asyb52bvp"/></g><g filter="url(#iTG42ze)"><path class="t3-co33ny"/></g><g filter="url(#ipuXcYd)"><path class="wi_oohbxi"/><path fill="url(#iDDkNOc)" class="zah51ibqd"/><path fill="url(#iRTv0ie)" class="zah51ibqd"/><path fill="url(#ib4rGUc)" class="zah51ibqd"/><path fill="url(#ivPPOFe)" class="zah51ibqd"/><path fill="url(#i1XHE2q)" class="zah51ibqd"/><path fill="url(#inprlKv)" class="zah51ibqd"/></g><path fill="url(#iHX7kJe)" class="kjv0robsl"/><path fill="url(#iSrbIWI)" class="kjv0robsl"/><path fill="url(#ic5uNgd)" class="kjv0robsl"/><path fill="url(#ivmdrVb)" class="kjv0robsl"/><path stroke="url(#iGjfPtb)" class="bnhrxq-yk"/><path fill="url(#iYcAmxe)" class="w412h4czk"/><path fill="url(#itRu50b)" class="w412h4czk"/><path fill="url(#itRu50b)" class="w412h4czk"/><path fill="url(#ijoTo9c)" class="w412h4czk"/><path fill="url(#inI3oPe)" class="w412h4czk"/><path fill="url(#iIga9Bb)" class="w412h4czk"/><path fill="url(#i11r8Hz)" class="w412h4czk"/><path fill="url(#ijWHGEe)" class="w412h4czk"/><path stroke="url(#ipDil1m)" class="tshs32bvi"/><path fill="url(#iGSHnCs)" class="adkfkefpa"/><path fill="url(#ihtJySR)" class="adkfkefpa"/><path fill="url(#ioZgC6c)" class="adkfkefpa"/><path fill="url(#iHYvf4c)" class="adkfkefpa"/><path fill="url(#iK5EeLe)" class="adkfkefpa"/><path stroke="url(#iB8Wuvc)" class="q54hwb-5v"/><path fill="url(#irWaxeg)" class="xtlwt_l6a"/><path fill="url(#iRJTmBc)" class="xtlwt_l6a"/><path fill="url(#izN1XUb)" class="xtlwt_l6a"/><path fill="url(#ijWC1Tb)" class="xtlwt_l6a"/><path fill="url(#io4UUHb)" class="xtlwt_l6a"/><g filter="url(#iGcdc0c)"><path stroke="url(#ipybS8c)" class="e9qvw8bxk"/></g><g filter="url(#iyW3u4D)"><path stroke="url(#iPBYabe)" class="pmbhggp9y"/></g><g filter="url(#izbNk2d)"><path stroke="url(#ivUGI1b)" class="m1cwp94tq"/></g><g filter="url(#iDGgoje)"><path stroke="url(#imFnvrb)" class="ruakdvgvi"/></g><defs><radialGradient id="iOzt8we" cx="0" cy="0" r="1" gradientTransform="rotate(97.546 -.738 8.028)scale(5.52382)" gradientUnits="userSpaceOnUse"><stop class="bvu_bhb4w"/><stop offset="1" class="nghdesb4o"/></radialGradient><radialGradient id="it89dac" cx="0" cy="0" r="1" gradientTransform="rotate(-101.931 13.387 8.24)scale(5.9909)" gradientUnits="userSpaceOnUse"><stop class="bvu_bhb4w"/><stop offset="1" class="nghdesb4o"/></radialGradient><radialGradient id="i0G5Qhc" cx="0" cy="0" r="1" gradientTransform="matrix(2.02133 4.82383 -10.29003 4.31182 23.15 26.11)" gradientUnits="userSpaceOnUse"><stop class="z7j86yzbx"/><stop offset="1" class="jm-2apa8s"/></radialGradient><radialGradient id="ifxC6Kc" cx="0" cy="0" r="1" gradientTransform="rotate(45.971 -22.445 25.219)scale(5.43989)" gradientUnits="userSpaceOnUse"><stop class="z7j86yzbx"/><stop offset="1" class="jm-2apa8s"/></radialGradient><radialGradient id="iDDkNOc" cx="0" cy="0" r="1" gradientTransform="rotate(91.137 .573 16.23)scale(11.9266)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="fl1rvwb6v"/><stop offset=".661" class="t5fpw5byt"/><stop offset=".733" class="t5fpw5byt"/><stop offset=".938" class="fl1rvwb6v"/></radialGradient><radialGradient id="iRTv0ie" cx="0" cy="0" r="1" gradientTransform="rotate(62.278 -5.704 23.417)scale(17.4619)" gradientUnits="userSpaceOnUse"><stop offset=".499" class="uxfsibbqv"/><stop offset="1" class="t_so4ubms"/></radialGradient><radialGradient id="ib4rGUc" cx="0" cy="0" r="1" gradientTransform="matrix(-.49694 7.44647 -15.83168 -1.05654 16.495 26.98)" gradientUnits="userSpaceOnUse"><stop class="oylljwb0j"/><stop offset="1" class="q_a7w_s2l"/></radialGradient><radialGradient id="ivPPOFe" cx="0" cy="0" r="1" gradientTransform="rotate(90 .01 15.989)scale(11)" gradientUnits="userSpaceOnUse"><stop offset=".938" class="noj8anvgb"/><stop offset="1" class="v2hgllb4v"/></radialGradient><radialGradient id="i1XHE2q" cx="0" cy="0" r="1" gradientTransform="matrix(10.09473 6.7824 -2.88546 4.29463 7.19 8.03)" gradientUnits="userSpaceOnUse"><stop class="n2nnz__ot"/><stop offset="1" class="vb83fkbth"/></radialGradient><radialGradient id="inprlKv" cx="0" cy="0" r="1" gradientTransform="rotate(94.857 2.019 16.02)scale(12.1098)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="c-ywsq7-x"/><stop offset=".79" class="js25pzkks"/></radialGradient><radialGradient id="ic5uNgd" cx="0" cy="0" r="1" gradientTransform="rotate(130.77 -1.93 14.268)scale(6.41066 16.4376)" gradientUnits="userSpaceOnUse"><stop class="d7r7pgzyr"/><stop offset="1" class="x835q6b8k"/></radialGradient><radialGradient id="i11r8Hz" cx="0" cy="0" r="1" gradientTransform="matrix(-1.08994 1.03417 -2.05489 -2.1657 24.304 20.902)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="f_a7_0lul"/><stop offset="1" class="wi53wablq"/></radialGradient><radialGradient id="ijWHGEe" cx="0" cy="0" r="1" gradientTransform="matrix(-.157 -2.05678 2.11826 -.1617 23.295 26.848)" gradientUnits="userSpaceOnUse"><stop class="ztadmtjet"/><stop offset=".75" class="zes7fnb3k"/></radialGradient><radialGradient id="ihtJySR" cx="0" cy="0" r="1" gradientTransform="matrix(-3.01935 3.29493 -8.44855 -7.74194 19.485 11.721)" gradientUnits="userSpaceOnUse"><stop class="pn42_1m-y"/><stop offset="1" class="x835q6b8k"/></radialGradient><radialGradient id="ioZgC6c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.01935 3.29493 -8.44855 -7.74194 19.485 11.721)" gradientUnits="userSpaceOnUse"><stop class="e911bccay"/><stop offset="1" class="x835q6b8k"/></radialGradient><radialGradient id="ijWC1Tb" cx="0" cy="0" r="1" gradientTransform="rotate(134.341 4.623 6.406)scale(1.81909 3.38606)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="f_a7_0lul"/><stop offset="1" class="wi53wablq"/></radialGradient><radialGradient id="io4UUHb" cx="0" cy="0" r="1" gradientTransform="matrix(-.75736 -.9954 2.17456 -1.65453 12.505 11.706)" gradientUnits="userSpaceOnUse"><stop class="zzc0_kbpz"/><stop offset="1" class="gctjexfnm"/></radialGradient><radialGradient id="ipybS8c" cx="0" cy="0" r="1" gradientTransform="rotate(112.479 8.976 7.41)scale(8.47375)" gradientUnits="userSpaceOnUse"><stop class="z_4m6ybwr"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="iPBYabe" cx="0" cy="0" r="1" gradientTransform="rotate(-8.669 185.184 -79.044)scale(7.66401)" gradientUnits="userSpaceOnUse"><stop class="z_4m6ybwr"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="ivUGI1b" cx="0" cy="0" r="1" gradientTransform="rotate(38.257 -16.239 14.361)scale(9.68226)" gradientUnits="userSpaceOnUse"><stop class="z_4m6ybwr"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="imFnvrb" cx="0" cy="0" r="1" gradientTransform="rotate(119.788 10.236 13.212)scale(7.95826 7.95827)" gradientUnits="userSpaceOnUse"><stop class="z_4m6ybwr"/><stop offset="1" class="stui2mbih"/></radialGradient><linearGradient id="iHX7kJe" x1="11.888" x2="7.896" y1="20.757" y2="24.822" gradientUnits="userSpaceOnUse"><stop offset=".042" class="vc--wpv5i"/><stop offset="1" class="zd7ccyysq"/></linearGradient><linearGradient id="iSrbIWI" x1="8.628" x2="9.18" y1="21.151" y2="21.627" gradientUnits="userSpaceOnUse"><stop class="dybzzobbg"/><stop offset="1" class="vghy80bbr"/></linearGradient><linearGradient id="ivmdrVb" x1="11.761" x2="11.007" y1="24.808" y2="23.861" gradientUnits="userSpaceOnUse"><stop class="b1spx5pcq"/><stop offset="1" class="kvnky8b7c"/></linearGradient><linearGradient id="iGjfPtb" x1="12.954" x2="10.905" y1="19.211" y2="21.61" gradientUnits="userSpaceOnUse"><stop class="ykmmubc9n"/><stop offset="1" class="mh358hkmc"/></linearGradient><linearGradient id="iYcAmxe" x1="21.606" x2="24.46" y1="22.352" y2="25.201" gradientUnits="userSpaceOnUse"><stop offset=".042" class="wljkhdb6h"/><stop offset="1" class="r81brwbxu"/></linearGradient><linearGradient id="itRu50b" x1="19.742" x2="21.244" y1="20.178" y2="21.679" gradientUnits="userSpaceOnUse"><stop class="j3lekwgja"/><stop offset="1" class="w4beyha1d"/></linearGradient><linearGradient id="ijoTo9c" x1="19.842" x2="20.806" y1="23.974" y2="23.023" gradientUnits="userSpaceOnUse"><stop class="i-0stgbdj"/><stop offset=".91" class="qo3ym3_6w"/></linearGradient><linearGradient id="inI3oPe" x1="25.03" x2="24.091" y1="26.07" y2="24.857" gradientUnits="userSpaceOnUse"><stop class="i-0stgbdj"/><stop offset=".91" class="qo3ym3_6w"/></linearGradient><linearGradient id="iIga9Bb" x1="23.868" x2="22.575" y1="20.325" y2="21.619" gradientUnits="userSpaceOnUse"><stop offset=".419" class="ay4ver8lx"/><stop offset="1" class="wi53wablq"/></linearGradient><linearGradient id="ipDil1m" x1="20.539" x2="21.454" y1="19.211" y2="20.274" gradientUnits="userSpaceOnUse"><stop class="v5v8qubzb"/><stop offset="1" class="kw0nftvqr"/></linearGradient><linearGradient id="iGSHnCs" x1="23.327" x2="19.764" y1="8.033" y2="11.496" gradientUnits="userSpaceOnUse"><stop class="kgh1k9blv"/><stop offset="1" class="en8bykbfx"/></linearGradient><linearGradient id="iHYvf4c" x1="20.496" x2="21.048" y1="7.826" y2="8.301" gradientUnits="userSpaceOnUse"><stop class="dybzzobbg"/><stop offset="1" class="vghy80bbr"/></linearGradient><linearGradient id="iK5EeLe" x1="23.629" x2="22.874" y1="11.483" y2="10.536" gradientUnits="userSpaceOnUse"><stop class="b1spx5pcq"/><stop offset="1" class="kvnky8b7c"/></linearGradient><linearGradient id="iB8Wuvc" x1="24.822" x2="22.773" y1="5.886" y2="8.285" gradientUnits="userSpaceOnUse"><stop class="iab0nwb4s"/><stop offset="1" class="mh358hkmc"/></linearGradient><linearGradient id="irWaxeg" x1="7.678" x2="11.739" y1="6.678" y2="10.739" gradientUnits="userSpaceOnUse"><stop class="fjvlpbcfk"/><stop offset=".573" class="u5phg13rl"/></linearGradient><linearGradient id="iRJTmBc" x1="8.811" x2="8.05" y1="10.14" y2="10.916" gradientUnits="userSpaceOnUse"><stop class="qfg7ahp1m"/><stop offset="1" class="wn-p7cfol"/></linearGradient><linearGradient id="izN1XUb" x1="12" x2="10.707" y1="7" y2="8.293" gradientUnits="userSpaceOnUse"><stop offset=".419" class="ay4ver8lx"/><stop offset="1" class="wi53wablq"/></linearGradient><filter id="i7tFKzd" width="4.686" height="14.717" x="3" y="8.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.388235 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4791_644"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.482353 0 0 0 0 0.498039 0 0 0 0.4 0"/><feBlend in2="effect1_innerShadow_4791_644" result="effect2_innerShadow_4791_644"/></filter><filter id="ibeoNle" width="14.303" height="5.757" x="8.847" y="24.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.388235 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4791_644"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.482353 0 0 0 0 0.498039 0 0 0 0.4 0"/><feBlend in2="effect1_innerShadow_4791_644" result="effect2_innerShadow_4791_644"/></filter><filter id="islonce" width="4.717" height="14.719" x="24.315" y="8.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.388235 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4791_644"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.482353 0 0 0 0 0.498039 0 0 0 0.4 0"/><feBlend in2="effect1_innerShadow_4791_644" result="effect2_innerShadow_4791_644"/></filter><filter id="iTG42ze" width="14.298" height="5.75" x="8.849" y="1.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.388235 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4791_644"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.482353 0 0 0 0 0.498039 0 0 0 0.4 0"/><feBlend in2="effect1_innerShadow_4791_644" result="effect2_innerShadow_4791_644"/></filter><filter id="ipuXcYd" width="23" height="23" x="4.998" y="4.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.148056 0 0 0 0 0.339175 0 0 0 0.9 0"/><feBlend in2="shape" result="effect1_innerShadow_4791_644"/></filter><filter id="iGcdc0c" width="12.998" height="4.672" x="9.516" y="1.968" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4791_644" stdDeviation=".125"/></filter><filter id="iyW3u4D" width="12.998" height="4.672" x="9.516" y="25.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4791_644" stdDeviation=".125"/></filter><filter id="izbNk2d" width="3.509" height="11.098" x="3.182" y="9.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4791_644" stdDeviation=".125"/></filter><filter id="iDGgoje" width="3.509" height="11.098" x="25.556" y="9.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4791_644" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ring-buoy" /></template>
<style>
.adkfkefpa {
  d: path("M25.13 7.578a.95.95 0 0 1 0 1.343l-3.742 3.743a6.36 6.36 0 0 0-2.904-2.51l3.94-3.94a.95.95 0 0 1 1.343 0z");
}

.asyb52bvp {
  fill: var(--svg-color--b1abb1, #B1ABB1);
  d: path("M26.284 20.029c.902-1 1.747-2.113 1.747-4.029s-.844-3.028-1.747-4.029a16 16 0 0 1-1.207-1.57a16 16 0 0 1-.473-.728a3 3 0 0 1-.276-.537l.95-.313q0 .006.046.096q.05.094.136.237c.115.19.267.426.442.68c.35.513.773 1.076 1.124 1.466c.96 1.064 2.005 2.41 2.005 4.698s-1.044 3.634-2.005 4.699a20 20 0 0 0-1.586 2.044a4 4 0 0 0-.135.22l-.04.077q0 .004 0 0l-.95-.312c.05-.153.171-.353.287-.53c.129-.198.295-.434.479-.683a21 21 0 0 1 1.203-1.486");
}

.ay4ver8lx {
  stop-color: var(--svg-color--f3edf1, #F3EDF1);
  stop-opacity: 0.6;
}

.b1spx5pcq {
  stop-color: var(--svg-color--7d6c84, #7D6C84);
}

.bnhrxq-yk {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M6.856 24.378a.95.95 0 0 1 0-1.344l3.742-3.742a6.36 6.36 0 0 0 2.905 2.51l-3.94 3.94a.95.95 0 0 1-1.343 0z");
}

.bvu_bhb4w {
  stop-color: var(--svg-color--645a6a, #645A6A);
}

.c-ywsq7-x {
  stop-color: var(--svg-color--e32858, #E32858);
}

.d7r7pgzyr {
  stop-color: var(--svg-color--9c7abb, #9C7ABB);
}

.dybzzobbg {
  stop-color: var(--svg-color--a6939a, #A6939A);
}

.e911bccay {
  stop-color: var(--svg-color--a77bb9, #A77BB9);
}

.e9qvw8bxk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.89 6.265a5.6 5.6 0 0 0 1.931-1.297c.423-.423 1.946-2.625 4.194-2.625c2.247 0 3.82 2.459 4.555 3.032c.754.588 1.317.744 1.569.89");
}

.en8bykbfx {
  stop-color: var(--svg-color--d4cddc, #D4CDDC);
}

.f_a7_0lul {
  stop-color: var(--svg-color--f3edf1, #F3EDF1);
}

.fjvlpbcfk {
  stop-color: var(--svg-color--9f9f9f, #9F9F9F);
}

.fl1rvwb6v {
  stop-color: var(--svg-color--f92f60, #F92F60);
}

.ft5dv1b6b {
  fill: none;
}

.gctjexfnm {
  stop-color: var(--svg-color--c2a9d0, #C2A9D0);
  stop-opacity: 0;
}

.i-0stgbdj {
  stop-color: var(--svg-color--aa6acc, #AA6ACC);
}

.iab0nwb4s {
  stop-color: var(--svg-color--dadada, #DADADA);
}

.j3lekwgja {
  stop-color: var(--svg-color--aea0a8, #AEA0A8);
}

.jm-2apa8s {
  stop-color: var(--svg-color--7d6191, #7D6191);
  stop-opacity: 0;
}

.jprx-8bud {
  fill: var(--svg-color--907c9a, #907C9A);
  d: path("M20.034 26.313c-.25.217-.507.487-.762.753l-.093.098c-.293.305-.593.613-.92.89c-.654.554-1.376.954-2.26.954c-.886 0-1.607-.4-2.26-.954a12 12 0 0 1-.921-.89l-.094-.098a12 12 0 0 0-.761-.753c-.46-.4-1.08-.761-1.608-1.03a10 10 0 0 0-1.205-.532l-.303.953c.124.04.55.212 1.053.47c.504.256 1.04.574 1.406.893c.213.185.436.419.698.693l.091.095c.294.307.626.648.997.962c.745.631 1.69 1.19 2.906 1.19c1.218 0 2.162-.559 2.906-1.19c.372-.314.704-.655.997-.962l.092-.095c.262-.274.485-.508.697-.693c.367-.319.903-.637 1.406-.894c.505-.257.93-.43 1.054-.47l-.303-.952a10 10 0 0 0-1.205.531c-.528.27-1.149.632-1.608 1.031");
}

.js25pzkks {
  stop-color: var(--svg-color--e32858, #E32858);
  stop-opacity: 0;
}

.kgh1k9blv {
  stop-color: var(--svg-color--f9f8fb, #F9F8FB);
}

.kjv0robsl {
  d: path("M6.856 24.378a.95.95 0 0 1 0-1.344l3.742-3.742a6.36 6.36 0 0 0 2.905 2.51l-3.94 3.94a.95.95 0 0 1-1.343 0z");
}

.kvnky8b7c {
  stop-color: var(--svg-color--b9a7bf, #B9A7BF);
  stop-opacity: 0;
}

.kw0nftvqr {
  stop-color: var(--svg-color--a69aa0, #A69AA0);
  stop-opacity: 0;
}

.m1cwp94tq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M5.665 20.425c-.422-.423-2.108-2.394-2.108-4.641c0-2.248 1.296-3.404 1.87-4.139c.588-.754.743-1.317.89-1.568");
}

.mh358hkmc {
  stop-color: var(--svg-color--c4c4c4, #C4C4C4);
  stop-opacity: 0;
}

.n2nnz__ot {
  stop-color: var(--svg-color--ce2844, #CE2844);
}

.nghdesb4o {
  stop-color: var(--svg-color--69626c, #69626C);
  stop-opacity: 0;
}

.noj8anvgb {
  stop-color: var(--svg-color--ec365c, #EC365C);
  stop-opacity: 0;
}

.oylljwb0j {
  stop-color: var(--svg-color--f020a3, #F020A3);
}

.pmbhggp9y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.89 25.418c.463.192 1.155.52 1.931 1.298c.423.422 1.946 2.624 4.194 2.624c2.247 0 3.82-2.459 4.555-3.032c.754-.588 1.317-.744 1.569-.89");
}

.pn42_1m-y {
  stop-color: var(--svg-color--ad8abb, #AD8ABB);
}

.q_a7w_s2l {
  stop-color: var(--svg-color--f020a3, #F020A3);
  stop-opacity: 0;
}

.q54hwb-5v {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M25.13 7.578a.95.95 0 0 1 0 1.343l-3.742 3.743a6.36 6.36 0 0 0-2.904-2.51l3.94-3.94a.95.95 0 0 1 1.343 0z");
}

.qfg7ahp1m {
  stop-color: var(--svg-color--a794b1, #A794B1);
  stop-opacity: 0;
}

.qo3ym3_6w {
  stop-color: var(--svg-color--aa6acc, #AA6ACC);
  stop-opacity: 0;
}

.r81brwbxu {
  stop-color: var(--svg-color--cebce3, #CEBCE3);
}

.ruakdvgvi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M26.582 20.425c.422-.423 2.108-2.394 2.108-4.641c0-2.248-1.296-3.404-1.87-4.139c-.587-.754-.743-1.317-.89-1.568");
}

.sis9jbb6v {
  d: path("M4 16c0 1.918.838 3.03 1.733 4.03a21 21 0 0 1 1.668 2.169c.115.178.235.377.285.53l-.95.31q0 .005 0 0l-.042-.078a4 4 0 0 0-.133-.22a14 14 0 0 0-.441-.633a20 20 0 0 0-1.132-1.41C4.035 19.631 3 18.286 3 16s1.035-3.632 1.988-4.697c.348-.39.767-.953 1.115-1.465c.173-.254.325-.49.438-.68a5 5 0 0 0 .135-.238a1 1 0 0 0 .046-.095l.95.31a3 3 0 0 1-.273.536c-.126.21-.288.463-.469.73c-.36.528-.806 1.132-1.197 1.569C4.838 12.97 4 14.082 4 16");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t_so4ubms {
  stop-color: var(--svg-color--bc337d, #BC337D);
}

.t3-co33ny {
  fill: var(--svg-color--9d959e, #9D959E);
  d: path("M11.96 5.718c.26-.222.528-.504.792-.78l.066-.07c.294-.308.594-.619.923-.9c.655-.562 1.375-.968 2.257-.968s1.603.406 2.258.968c.328.281.629.592.923.9l.066.07c.264.276.532.558.793.78c.459.392 1.08.747 1.607 1.01a10 10 0 0 0 1.204.522l.298-.955a9 9 0 0 1-1.054-.46c-.504-.253-1.04-.565-1.406-.878c-.22-.187-.453-.431-.73-.721l-.055-.059c-.293-.307-.625-.65-.995-.968C18.164 2.572 17.219 2 15.998 2s-2.165.572-2.908 1.209a14 14 0 0 0-.995.968l-.056.059c-.277.29-.51.534-.729.721c-.367.313-.902.625-1.406.878c-.504.252-.93.422-1.055.46l.298.955c.198-.062.678-.257 1.205-.521s1.148-.62 1.607-1.011");
}

.t5fpw5byt {
  stop-color: var(--svg-color--ff769b, #FF769B);
}

.tim7irbbf {
  d: path("M20.034 26.313c-.25.217-.507.487-.762.753l-.093.098c-.293.305-.593.613-.92.89c-.654.554-1.376.954-2.26.954c-.886 0-1.607-.4-2.26-.954a12 12 0 0 1-.921-.89l-.094-.098a12 12 0 0 0-.761-.753c-.46-.4-1.08-.761-1.608-1.03a10 10 0 0 0-1.205-.532l-.303.953c.124.04.55.212 1.053.47c.504.256 1.04.574 1.406.893c.213.185.436.419.698.693l.091.095c.294.307.626.648.997.962c.745.631 1.69 1.19 2.906 1.19c1.218 0 2.162-.559 2.906-1.19c.372-.314.704-.655.997-.962l.092-.095c.262-.274.485-.508.697-.693c.367-.319.903-.637 1.406-.894c.505-.257.93-.43 1.054-.47l-.303-.952a10 10 0 0 0-1.205.531c-.528.27-1.149.632-1.608 1.031");
}

.tshs32bvi {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M25.13 23.034a.95.95 0 0 1 0 1.344l-1.363 1.363a.95.95 0 0 1-1.343 0l-3.94-3.94a6.36 6.36 0 0 0 2.904-2.51z");
}

.u5phg13rl {
  stop-color: var(--svg-color--dad4e0, #DAD4E0);
}

.uxfsibbqv {
  stop-color: var(--svg-color--bc337d, #BC337D);
  stop-opacity: 0;
}

.v2hgllb4v {
  stop-color: var(--svg-color--ec365c, #EC365C);
  stop-opacity: 0.4;
}

.v5v8qubzb {
  stop-color: var(--svg-color--a69aa0, #A69AA0);
}

.vb83fkbth {
  stop-color: var(--svg-color--ce2844, #CE2844);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vghy80bbr {
  stop-color: var(--svg-color--bcb1b5, #BCB1B5);
  stop-opacity: 0;
}

.w412h4czk {
  d: path("M25.13 23.034a.95.95 0 0 1 0 1.344l-1.363 1.363a.95.95 0 0 1-1.343 0l-3.94-3.94a6.36 6.36 0 0 0 2.904-2.51z");
}

.w4beyha1d {
  stop-color: var(--svg-color--dad1e3, #DAD1E3);
  stop-opacity: 0;
}

.wi_oohbxi {
  fill: var(--svg-color--f92f60, #F92F60);
  d: path("M15.998 26.98c6.075 0 11-4.925 11-11s-4.925-11-11-11s-11 4.924-11 11s4.925 11 11 11m0-4.715a6.3 6.3 0 0 1-2.526-.528c-.773.528-2.129.406-2.6 0s-.747-1.323-.194-2.409a6.26 6.26 0 0 1-.965-3.348c0-1.231.353-2.38.965-3.349c-.359-1.016-.076-1.858.388-2.261c.475-.413 1.605-.676 2.406-.148a6.3 6.3 0 0 1 2.526-.528c.899 0 1.753.188 2.526.528c1.037-.378 1.96-.48 2.476 0c.394.368.663 1.614.319 2.409c.611.97.965 2.118.965 3.348a6.26 6.26 0 0 1-.965 3.349c.538.837.12 2.017-.32 2.41c-.489.435-1.466.668-2.475 0a6.3 6.3 0 0 1-2.526.527");
}

.wi53wablq {
  stop-color: var(--svg-color--f9f2f8, #F9F2F8);
  stop-opacity: 0;
}

.wljkhdb6h {
  stop-color: var(--svg-color--d8cfe1, #D8CFE1);
}

.wn-p7cfol {
  stop-color: var(--svg-color--a794b1, #A794B1);
}

.x835q6b8k {
  stop-color: var(--svg-color--e3dce9, #E3DCE9);
  stop-opacity: 0;
}

.xds4qmbsk {
  fill: var(--svg-color--958c96, #958C96);
  d: path("M4 16c0 1.918.838 3.03 1.733 4.03a21 21 0 0 1 1.668 2.169c.115.178.235.377.285.53l-.95.31q0 .005 0 0l-.042-.078a4 4 0 0 0-.133-.22a14 14 0 0 0-.441-.633a20 20 0 0 0-1.132-1.41C4.035 19.631 3 18.286 3 16s1.035-3.632 1.988-4.697c.348-.39.767-.953 1.115-1.465c.173-.254.325-.49.438-.68a5 5 0 0 0 .135-.238a1 1 0 0 0 .046-.095l.95.31a3 3 0 0 1-.273.536c-.126.21-.288.463-.469.73c-.36.528-.806 1.132-1.197 1.569C4.838 12.97 4 14.082 4 16");
}

.xtlwt_l6a {
  d: path("M6.82 8.957a1 1 0 0 1 0-1.414l1.364-1.364a1 1 0 0 1 1.415 0l3.992 3.992a6.3 6.3 0 0 0-2.983 2.573z");
}

.ykmmubc9n {
  stop-color: var(--svg-color--c9c5c7, #C9C5C7);
}

.z_4m6ybwr {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.2;
}

.z7j86yzbx {
  stop-color: var(--svg-color--7d6191, #7D6191);
}

.zah51ibqd {
  d: path("M15.998 26.98c6.075 0 11-4.925 11-11s-4.925-11-11-11s-11 4.924-11 11s4.925 11 11 11m0-4.715a6.3 6.3 0 0 1-2.526-.528c-.773.528-2.129.406-2.6 0s-.747-1.323-.194-2.409a6.26 6.26 0 0 1-.965-3.348c0-1.231.353-2.38.965-3.349c-.359-1.016-.076-1.858.388-2.261c.475-.413 1.605-.676 2.406-.148a6.3 6.3 0 0 1 2.526-.528c.899 0 1.753.188 2.526.528c1.037-.378 1.96-.48 2.476 0c.394.368.663 1.614.319 2.409c.611.97.965 2.118.965 3.348a6.26 6.26 0 0 1-.965 3.349c.538.837.12 2.017-.32 2.41c-.489.435-1.466.668-2.475 0a6.3 6.3 0 0 1-2.526.527");
}

.zd7ccyysq {
  stop-color: var(--svg-color--baa9c7, #BAA9C7);
}

.zes7fnb3k {
  stop-color: var(--svg-color--b386da, #B386DA);
  stop-opacity: 0;
}

.ztadmtjet {
  stop-color: var(--svg-color--b386da, #B386DA);
}

.zzc0_kbpz {
  stop-color: var(--svg-color--a682ba, #A682BA);
}

</style>
