<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iWZdKZd)" class="h1l1_62rm"/><path fill="url(#iax3R5c)" class="h1l1_62rm"/><path fill="url(#iDaR65d)" class="h1l1_62rm"/><path fill="url(#iCS6bsd)" class="h1l1_62rm"/><path fill="url(#igLCMFe)" class="znkcu1bdd"/><path fill="url(#iu8Vuib)" class="znkcu1bdd"/><path fill="url(#iN5oSuc)" class="znkcu1bdd"/><path fill="url(#imtjF5d)" class="znkcu1bdd"/><g filter="url(#iunEBqw)"><path stroke="url(#il6xFvc)" class="yzgjk9g0y"/></g><path fill="url(#ix03uPd)" class="o6gzsg43i"/><g filter="url(#i1Gm8Ec)"><ellipse fill="url(#iSJDRde)" transform="rotate(-35 12.32 4.95)" class="hfeeiydva"/></g><g filter="url(#ihZ9I8n)"><path fill="url(#iNCsCWc)" class="rg06hsb3l"/></g><g filter="url(#io43WMd)"><path fill="url(#icpxeRc)" class="gw-5tq-ii"/></g><path class="p2qcls7qa"/><path fill="url(#iaPUsQb)" class="asn2ekhvw"/><path fill="url(#iipv1qe)" class="asn2ekhvw"/><path fill="url(#ibSNXce)" class="asn2ekhvw"/><path fill="url(#i7ocSle)" class="ufwvc6aiu"/><path class="j61zjcchx"/><g filter="url(#iP0ypCb)"><path fill="url(#iQJ6NFb)" class="bcnv_6j4m"/></g><path fill="url(#i6fyyVc)" class="rkax57i7a"/><path fill="url(#ilUMzKQ)" class="gdny4uboj"/><path fill="url(#iQBYC2Z)" class="gdny4uboj"/><path fill="url(#iWB6rgd)" class="hlpw6x9gt"/><path fill="url(#iDnRvRc)" class="hlpw6x9gt"/><path fill="url(#i18HJxc)" class="hlpw6x9gt"/><g filter="url(#inPpe4b)"><path fill="url(#iZd7hld)" class="i755l3bey"/><path fill="url(#ih60Wve)" class="i755l3bey"/></g><path fill="url(#irPTand)" class="ffv8br4ov"/><path fill="url(#iCRv24N)" class="ffv8br4ov"/><path fill="url(#infDfgz)" class="ffv8br4ov"/><g filter="url(#ibh2Bfb)"><path fill="url(#iPSmf5d)" class="nu36kibis"/></g><g filter="url(#isJutMb)"><path fill="url(#iNCVwJb)" class="g41gcwboo"/><path fill="url(#icq9RZl)" class="g41gcwboo"/><path fill="url(#iqWdEQe)" class="g41gcwboo"/><path fill="url(#i7N2lTN)" class="g41gcwboo"/></g><g filter="url(#iUKDEKe)"><path class="vcmmwvb_k"/></g><g filter="url(#iPDuYGb)"><path fill="url(#i2uotFb)" class="gzume6lnu"/></g><g filter="url(#iiHNjIO)"><path fill="url(#i4L8RHc)" class="wysfcsb7u"/></g><g filter="url(#i5mXfrb)"><path stroke="url(#iCE8ltL)" class="xtg3u-bwn"/></g><g filter="url(#iAl4qAc)"><path stroke="url(#ivACemO)" class="tk7gpw5ay"/></g><g filter="url(#iBixVbd)"><path stroke="url(#igATKnd)" class="d9t7qiima"/></g><g filter="url(#i1xY2Wb)"><path stroke="url(#iXzKY4b)" class="yvx1b-b_l"/></g><g filter="url(#ig0uwkd)"><path stroke="url(#iMMy4ve)" class="k_bsylboz"/></g><defs><linearGradient id="iWZdKZd" x1="12.502" x2="13.847" y1="29.457" y2="24.49" gradientUnits="userSpaceOnUse"><stop class="nv8wg8y0e"/><stop offset="1" class="lb96bubco"/></linearGradient><linearGradient id="iax3R5c" x1="13.043" x2="13.043" y1="30.373" y2="29.377" gradientUnits="userSpaceOnUse"><stop class="p_ptxbjeb"/><stop offset=".828" class="u5vkysn3x"/></linearGradient><linearGradient id="igLCMFe" x1="16.502" x2="17.847" y1="29.457" y2="24.49" gradientUnits="userSpaceOnUse"><stop class="nv8wg8y0e"/><stop offset="1" class="lb96bubco"/></linearGradient><linearGradient id="iu8Vuib" x1="19.816" x2="12.636" y1="29.362" y2="29.362" gradientUnits="userSpaceOnUse"><stop class="iwzyq_met"/><stop offset="1" class="gryo57x6u"/></linearGradient><linearGradient id="imtjF5d" x1="17.043" x2="17.043" y1="30.373" y2="29.377" gradientUnits="userSpaceOnUse"><stop class="p_ptxbjeb"/><stop offset=".828" class="u5vkysn3x"/></linearGradient><linearGradient id="il6xFvc" x1="17.414" x2="18.235" y1="27.98" y2="25.012" gradientUnits="userSpaceOnUse"><stop class="cxtlk-bre"/><stop offset="1" class="lam99wdso"/></linearGradient><linearGradient id="ix03uPd" x1="5.04" x2="13.664" y1="5.766" y2="5.766" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="icpxeRc" x1="7.44" x2="6.379" y1="3.454" y2="3.902" gradientUnits="userSpaceOnUse"><stop class="pu2q2hbxi"/><stop offset="1" class="z3wtmlbky"/></linearGradient><linearGradient id="iipv1qe" x1=".532" x2="9.352" y1="16.215" y2="16.215" gradientUnits="userSpaceOnUse"><stop class="iye40nb_c"/><stop offset="1" class="dufb_cuxp"/></linearGradient><linearGradient id="i7ocSle" x1="7.27" x2="14.003" y1="10.186" y2="8" gradientUnits="userSpaceOnUse"><stop class="bnwuodjuf"/><stop offset="1" class="lxeplpbow"/></linearGradient><linearGradient id="iQJ6NFb" x1="4.013" x2="4.615" y1="9.322" y2="7.848" gradientUnits="userSpaceOnUse"><stop class="lqpxs8bdg"/><stop offset="1" class="v5weeobdr"/></linearGradient><linearGradient id="i6fyyVc" x1="4.384" x2="6.642" y1="8.928" y2="13.921" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="i18HJxc" x1="6.445" x2="6.101" y1="7.133" y2="6.914" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="iZd7hld" x1="31.645" x2="16.457" y1="15.944" y2="15.944" gradientUnits="userSpaceOnUse"><stop class="c3bch-exu"/><stop offset="1" class="u4iqm1b9p"/></linearGradient><linearGradient id="irPTand" x1="24.048" x2="25.75" y1="17.572" y2="10.99" gradientUnits="userSpaceOnUse"><stop class="n23gc6hyt"/><stop offset="1" class="w7cog_baa"/></linearGradient><linearGradient id="iPSmf5d" x1="22.128" x2="30.59" y1="16.49" y2="1.133" gradientUnits="userSpaceOnUse"><stop class="pjkd48bhg"/><stop offset="1" class="t7qoerb9f"/></linearGradient><linearGradient id="iNCVwJb" x1="20.835" x2="7.427" y1="27.732" y2="25.845" gradientUnits="userSpaceOnUse"><stop class="z65833s6z"/><stop offset="1" class="yxjmmcc7i"/></linearGradient><linearGradient id="icq9RZl" x1="19.46" x2="19.305" y1="15.743" y2="16.796" gradientUnits="userSpaceOnUse"><stop class="ljz-3cagm"/><stop offset="1" class="wdn-cc6dw"/></linearGradient><linearGradient id="i2uotFb" x1="9.524" x2="8.664" y1="8.095" y2="8.095" gradientUnits="userSpaceOnUse"><stop class="pu2q2hbxi"/><stop offset="1" class="z3wtmlbky"/></linearGradient><linearGradient id="i4L8RHc" x1="3.873" x2="3.813" y1="10.942" y2="15.863" gradientUnits="userSpaceOnUse"><stop class="pu2q2hbxi"/><stop offset="1" class="z3wtmlbky"/></linearGradient><linearGradient id="iCE8ltL" x1="23.83" x2="13.352" y1="16.902" y2="16.902" gradientUnits="userSpaceOnUse"><stop class="ncsg-yc_t"/><stop offset="1" class="rf3wa0_1k"/></linearGradient><linearGradient id="ivACemO" x1="27.284" x2="31.723" y1="9.955" y2="12.222" gradientUnits="userSpaceOnUse"><stop class="g5g_44q1g"/><stop offset="1" class="zu_n5klec"/></linearGradient><linearGradient id="igATKnd" x1="27.284" x2="31.723" y1="7.848" y2="10.114" gradientUnits="userSpaceOnUse"><stop class="g5g_44q1g"/><stop offset="1" class="zu_n5klec"/></linearGradient><linearGradient id="iXzKY4b" x1="27.284" x2="31.723" y1="12.637" y2="14.903" gradientUnits="userSpaceOnUse"><stop class="g5g_44q1g"/><stop offset="1" class="zu_n5klec"/></linearGradient><linearGradient id="iMMy4ve" x1="26.338" x2="30.777" y1="14.682" y2="16.949" gradientUnits="userSpaceOnUse"><stop class="g5g_44q1g"/><stop offset="1" class="zu_n5klec"/></linearGradient><radialGradient id="iDaR65d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7262 0 0 -1.80125 14.584 29.412)" gradientUnits="userSpaceOnUse"><stop class="dgq40ga3c"/><stop offset="1" class="xir1dwxgq"/></radialGradient><radialGradient id="iCS6bsd" cx="0" cy="0" r="1" gradientTransform="rotate(48.373 -25.743 26.842)scale(1.48338 1.671)" gradientUnits="userSpaceOnUse"><stop class="iwzyq_met"/><stop offset="1" class="gryo57x6u"/></radialGradient><radialGradient id="iN5oSuc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21674 -1.07116 .86521 -.9828 19.649 30.256)" gradientUnits="userSpaceOnUse"><stop class="cxtlk-bre"/><stop offset="1" class="lam99wdso"/></radialGradient><radialGradient id="iSJDRde" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31867 .28918 -.27683 -2.21966 13.604 4.925)" gradientUnits="userSpaceOnUse"><stop class="pu2q2hbxi"/><stop offset="1" class="z3wtmlbky"/></radialGradient><radialGradient id="iNCsCWc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18482 -1.3665 .8579 -1.37164 11.007 3.912)" gradientUnits="userSpaceOnUse"><stop class="pu2q2hbxi"/><stop offset="1" class="z3wtmlbky"/></radialGradient><radialGradient id="iaPUsQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.36939 47.8847 0 15.94 26.592)" gradientUnits="userSpaceOnUse"><stop class="gfkjwjezj"/><stop offset="1" class="sjyaehhny"/></radialGradient><radialGradient id="ibSNXce" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.24084 -1.93213 0 4.566 11.553)" gradientUnits="userSpaceOnUse"><stop class="iye40nb_c"/><stop offset="1" class="dufb_cuxp"/></radialGradient><radialGradient id="ilUMzKQ" cx="0" cy="0" r="1" gradientTransform="rotate(32.852 -10.15 14.832)scale(5.73311)" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset="1" class="c3htxbc9y"/></radialGradient><radialGradient id="iQBYC2Z" cx="0" cy="0" r="1" gradientTransform="rotate(149.052 4.184 4.796)scale(4.20142)" gradientUnits="userSpaceOnUse"><stop class="kt-kboaov"/><stop offset="1" class="mt7e3lbgy"/></radialGradient><radialGradient id="iWB6rgd" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 6.692 7.365)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iDnRvRc" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 1.931 5.004)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="ih60Wve" cx="0" cy="0" r="1" gradientTransform="matrix(-11.519 0 0 -11.5485 31.465 14.117)" gradientUnits="userSpaceOnUse"><stop class="wmo77fbcu"/><stop offset="1" class="uicmc6bxp"/></radialGradient><radialGradient id="iCRv24N" cx="0" cy="0" r="1" gradientTransform="rotate(-107.13 19.935 .357)scale(16.0893 15.0539)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="h-alj4xay"/><stop offset="1" class="nsamxgb3t"/></radialGradient><radialGradient id="infDfgz" cx="0" cy="0" r="1" gradientTransform="matrix(3.06396 0 0 4.98645 17.761 12.619)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="epw02opzi"/><stop offset="1" class="tchutfbek"/></radialGradient><radialGradient id="iqWdEQe" cx="0" cy="0" r="1" gradientTransform="rotate(159.253 11.283 10.411)scale(4.29772 1.20949)" gradientUnits="userSpaceOnUse"><stop class="ncsg-yc_t"/><stop offset="1" class="rf3wa0_1k"/></radialGradient><radialGradient id="i7N2lTN" cx="0" cy="0" r="1" gradientTransform="rotate(87.5 -1.25 17.387)scale(6.56912 11.0094)" gradientUnits="userSpaceOnUse"><stop offset=".818" class="kewtxqoad"/><stop offset="1" class="ppk_a_5hx"/></radialGradient><filter id="iunEBqw" width="1.607" height="3.52" x="17.053" y="25.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4695" stdDeviation=".15"/></filter><filter id="i1Gm8Ec" width="2.846" height="3.159" x="10.896" y="3.37" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4695" stdDeviation=".125"/></filter><filter id="ihZ9I8n" width="3.408" height="3.251" x="7.62" y="2.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4695" stdDeviation=".125"/></filter><filter id="io43WMd" width="1.893" height="2.058" x="5.797" y="2.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4695" stdDeviation=".125"/></filter><filter id="iP0ypCb" width="2.93" height="2.588" x="2.723" y="6.947" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4695" stdDeviation=".25"/></filter><filter id="inPpe4b" width="12.011" height="12.322" x="18.043" y="4.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.167292 0 0 0 0 0.304167 0 0 0 0 0.262344 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4695"/></filter><filter id="ibh2Bfb" width="11.923" height="16.195" x="19.49" y="3.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4695" stdDeviation="1.5"/></filter><filter id="isJutMb" width="16.819" height="8" x="8.126" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.286275 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_4695"/></filter><filter id="iUKDEKe" width="8.383" height="12.918" x="7.585" y="3.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4695" stdDeviation=".75"/></filter><filter id="iPDuYGb" width="1.169" height="3.411" x="8.414" y="6.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4695" stdDeviation=".125"/></filter><filter id="iiHNjIO" width="1.039" height="2.582" x="3.925" y="11.056" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4695" stdDeviation=".125"/></filter><filter id="i5mXfrb" width="11.432" height="1.45" x="13.269" y="15.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4695" stdDeviation=".3"/></filter><filter id="iAl4qAc" width="3.774" height="2.344" x="26.269" y="9.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4695" stdDeviation=".125"/></filter><filter id="iBixVbd" width="2.965" height="1.984" x="26.74" y="7.784" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4695" stdDeviation=".125"/></filter><filter id="i1xY2Wb" width="3.774" height="2.344" x="26.269" y="12.312" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4695" stdDeviation=".125"/></filter><filter id="ig0uwkd" width="2.729" height="1.755" x="26.367" y="14.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4695" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:rooster" /></template>
<style>
.asn2ekhvw {
  d: path("m29.713 14.01l-2.72-1.57a.505.505 0 0 1-.21-.66c.13-.26.45-.36.7-.21l1.56.9c.44.25.91.06 1-.44a.67.67 0 0 0-.32-.7l-2.72-1.57a.505.505 0 0 1-.21-.66c.13-.26.45-.36.7-.21l1.85 1.07c.28.16.62-.09.54-.41c-.67-2.62-3.03-4.55-5.84-4.55c-3.31 0-6 2.69-6 6v1.9c0 .61-.49 1.1-1.1 1.1a3.13 3.13 0 0 1-2.78-1.69l-3.46-6.69A2.997 2.997 0 0 0 5.043 7v8c0 6.08 4.92 11 11 11c5.17 0 9.51-3.57 10.68-8.38c.09-.36.41-.62.78-.62h1.08c.2 0 .39-.13.44-.33s-.04-.39-.2-.49l-1.84-1.06a.505.505 0 0 1-.21-.66c.13-.26.45-.36.7-.21l1.56.9c.44.25.91.06 1-.44a.67.67 0 0 0-.32-.7");
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.bcnv_6j4m {
  d: path("m5.153 7.447l-1.93 1.588h1.93z");
}

.bnwuodjuf {
  stop-color: var(--svg-color--f97a37, #F97A37);
}

.c3bch-exu {
  stop-color: var(--svg-color--008461, #008461);
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.cxtlk-bre {
  stop-color: var(--svg-color--ffa56b, #FFA56B);
}

.d9t7qiima {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m27.065 8.11l2.315 1.334");
}

.dgq40ga3c {
  stop-color: var(--svg-color--d6551c, #D6551C);
}

.dufb_cuxp {
  stop-color: var(--svg-color--7e292a, #7E292A);
  stop-opacity: 0;
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.epw02opzi {
  stop-color: var(--svg-color--665a42, #665A42);
}

.ffv8br4ov {
  d: path("m29.713 14.01l-2.72-1.57a.505.505 0 0 1-.21-.66c.13-.26.45-.36.7-.21l1.56.9c.44.25.91.06 1-.44a.67.67 0 0 0-.32-.7l-2.72-1.57a.505.505 0 0 1-.21-.66c.13-.26.45-.36.7-.21l1.85 1.07c.28.16.62-.09.54-.41c-.67-2.62-3.03-4.55-5.84-4.55c-3.31 0-6 2.69-6 6v1.9c0 1.24.55 2.35 1.43 3.1h4.5c.53 0 .886.51.806 1.02l3.835-.022a.44.44 0 0 0 .419-.328c.05-.2-.04-.39-.2-.49l-1.84-1.06a.505.505 0 0 1-.21-.66c.13-.26.45-.36.7-.21l1.56.9c.44.25.91.06 1-.44a.7.7 0 0 0-.33-.7");
}

.ft5dv1b6b {
  fill: none;
}

.g41gcwboo {
  d: path("M22.474 16H9.755c-1.449 0-1.794 1.203-1.563 2.213c.91 3.98 3.846 5.787 8.012 5.787s7.659-2.97 8.568-6.95a.852.852 0 0 0-.821-1.05z");
}

.g5g_44q1g {
  stop-color: var(--svg-color--76a090, #76A090);
}

.gdny4uboj {
  d: path("M7.283 10.25a2.25 2.25 0 1 0 0-4.5a2.25 2.25 0 0 0 0 4.5");
}

.gfkjwjezj {
  stop-color: var(--svg-color--8b386a, #8B386A);
}

.gryo57x6u {
  stop-color: var(--svg-color--f67f41, #F67F41);
  stop-opacity: 0;
}

.gw-5tq-ii {
  d: path("m6.047 3.284l.42 1.396l.973.084a73 73 0 0 0-.217-1.011c-.145-.659-.844-.587-1.176-.47");
}

.gzume6lnu {
  d: path("M8.664 9.475c.409-.344.67-.869.67-1.456s-.261-1.111-.67-1.456z");
}

.h-alj4xay {
  stop-color: var(--svg-color--508b70, #508B70);
}

.h1l1_62rm {
  d: path("M14.853 28.5h-.92l1.11-4.25h-1.5l-1.11 4.25h-1.2c-.66 0-1.19.53-1.19 1.19c0 .17.14.31.31.31h5.38c.17 0 .31-.14.31-.31c0-.66-.54-1.19-1.19-1.19");
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.hfeeiydva {
  cx: 12.319px;
  cy: 4.949px;
  rx: 1px;
  ry: 1.464px;
}

.hlpw6x9gt {
  d: path("M6.543 8.026a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.i755l3bey {
  d: path("m29.713 14.01l-2.72-1.57a.505.505 0 0 1-.21-.66c.13-.26.45-.36.7-.21l1.56.9c.44.25.91.06 1-.44a.67.67 0 0 0-.32-.7l-2.72-1.57a.505.505 0 0 1-.21-.66c.13-.26.45-.36.7-.21l1.85 1.07c.28.16.62-.09.54-.41c-.67-2.62-3.03-4.55-5.84-4.55c-3.31 0-6 2.69-6 6v1.9c0 1.24.55 2.35 1.43 3.1h4.5c.53 0 .888.512.808 1.022l3.824-.024a.446.446 0 0 0 .428-.328c.05-.2-.04-.39-.2-.49l-1.84-1.06a.505.505 0 0 1-.21-.66c.13-.26.45-.36.7-.21l1.56.9c.44.25.91.06 1-.44a.7.7 0 0 0-.33-.7");
}

.iwzyq_met {
  stop-color: var(--svg-color--f67f41, #F67F41);
}

.iye40nb_c {
  stop-color: var(--svg-color--7e292a, #7E292A);
}

.j61zjcchx {
  fill: var(--svg-color--f07639, #F07639);
  d: path("m3.223 9.48l1.81.77l.46-.77v-2.6l-2.36 1.98c-.21.18-.16.51.09.62");
}

.k_bsylboz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m26.692 15.271l2.08 1.105");
}

.kewtxqoad {
  stop-color: var(--svg-color--b43a83, #B43A83);
  stop-opacity: 0;
}

.kmmuo7biq {
  stop-color: var(--svg-color--ed1452, #ED1452);
}

.kt-kboaov {
  stop-color: var(--svg-color--ed0c7e, #ED0C7E);
}

.lam99wdso {
  stop-color: var(--svg-color--ffa56b, #FFA56B);
  stop-opacity: 0;
}

.lb96bubco {
  stop-color: var(--svg-color--db592a, #DB592A);
}

.ljz-3cagm {
  stop-color: var(--svg-color--dd813e, #DD813E);
}

.lqpxs8bdg {
  stop-color: var(--svg-color--ffa859, #FFA859);
}

.lxeplpbow {
  stop-color: var(--svg-color--ffa661, #FFA661);
}

.mt7e3lbgy {
  stop-color: var(--svg-color--ed0c7e, #ED0C7E);
  stop-opacity: 0;
}

.n23gc6hyt {
  stop-color: var(--svg-color--6c8578, #6C8578);
}

.ncsg-yc_t {
  stop-color: var(--svg-color--f1a06d, #F1A06D);
}

.nsamxgb3t {
  stop-color: var(--svg-color--508b70, #508B70);
  stop-opacity: 0;
}

.nu36kibis {
  d: path("M24.147 6.445c1.546-.76 3.381.286 4.266 1.108c-1.997-.324-2.565.735-2.565 1.58v7.243H22.49v-6.202c0-1.286.112-2.97 1.657-3.73");
}

.nv8wg8y0e {
  stop-color: var(--svg-color--e46d33, #E46D33);
}

.o6gzsg43i {
  d: path("M13.073 4.01c-.49-.49-1.18-.67-1.82-.54c-.15.03-.29-.05-.35-.2A2.01 2.01 0 0 0 9.043 2c-.7 0-1.31.36-1.67.9c-.09.14-.26.2-.42.16Q6.728 3 6.503 3c-.82.02-1.46.72-1.46 1.54V7h2v.8h1.62l1.73 1.73l2.69-2.69c.78-.78.78-2.04-.01-2.83");
}

.p_ptxbjeb {
  stop-color: var(--svg-color--f15cc7, #F15CC7);
}

.p2qcls7qa {
  fill: var(--svg-color--8a5652, #8A5652);
  d: path("m29.713 14.01l-2.72-1.57a.505.505 0 0 1-.21-.66c.13-.26.45-.36.7-.21l1.56.9c.44.25.91.06 1-.44a.67.67 0 0 0-.32-.7l-2.72-1.57a.505.505 0 0 1-.21-.66c.13-.26.45-.36.7-.21l1.85 1.07c.28.16.62-.09.54-.41c-.67-2.62-3.03-4.55-5.84-4.55c-3.31 0-6 2.69-6 6v1.9c0 .61-.49 1.1-1.1 1.1a3.13 3.13 0 0 1-2.78-1.69l-3.46-6.69A2.997 2.997 0 0 0 5.043 7v8c0 6.08 4.92 11 11 11c5.17 0 9.51-3.57 10.68-8.38c.09-.36.41-.62.78-.62h1.08c.2 0 .39-.13.44-.33s-.04-.39-.2-.49l-1.84-1.06a.505.505 0 0 1-.21-.66c.13-.26.45-.36.7-.21l1.56.9c.44.25.91.06 1-.44a.67.67 0 0 0-.32-.7");
}

.pjkd48bhg {
  stop-color: var(--svg-color--8ea490, #8EA490);
}

.ppk_a_5hx {
  stop-color: var(--svg-color--b43a83, #B43A83);
}

.pu2q2hbxi {
  stop-color: var(--svg-color--ff7baf, #FF7BAF);
}

.rf3wa0_1k {
  stop-color: var(--svg-color--f1a06d, #F1A06D);
  stop-opacity: 0;
}

.rg06hsb3l {
  d: path("m10.566 4.154l-.707.876L7.87 2.798c.327-.29 1.182-.767 1.99-.363c.542.27.774.638.884.96c.09.261-.004.544-.178.759");
}

.rkax57i7a {
  d: path("M5.043 8.03v1.23c0 .45-.26.87-.66 1.07l-.41.2c-.57.29-.93.87-.93 1.51v.93c0 .54.41 1 .95 1.03c.57.03 1.05-.43 1.05-1v-1.84c0-.5.41-.91.91-.91h1.31V8.03z");
}

.sjyaehhny {
  stop-color: var(--svg-color--8b386a, #8B386A);
  stop-opacity: 0;
}

.t7qoerb9f {
  stop-color: var(--svg-color--8da490, #8DA490);
  stop-opacity: 0;
}

.tchutfbek {
  stop-color: var(--svg-color--5b5343, #5B5343);
  stop-opacity: 0;
}

.tk7gpw5ay {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m26.594 9.955l3.123 1.694");
}

.u4iqm1b9p {
  stop-color: var(--svg-color--008461, #008461);
  stop-opacity: 0;
}

.u5vkysn3x {
  stop-color: var(--svg-color--f15cc7, #F15CC7);
  stop-opacity: 0;
}

.ufwvc6aiu {
  d: path("m14.003 12l-3.3-6.38A2.997 2.997 0 0 0 5.043 7v5z");
}

.uicmc6bxp {
  stop-color: var(--svg-color--759787, #759787);
  stop-opacity: 0;
}

.v5weeobdr {
  stop-color: var(--svg-color--ffa859, #FFA859);
  stop-opacity: 0;
}

.vcmmwvb_k {
  fill: var(--svg-color--ffe0c1, #FFE0C1);
  fill-opacity: var(--svg-fill-opacity--0-25, 0.25);
  d: path("M14.468 15.129L9.802 5.424a.377.377 0 0 0-.7.273l2.863 9.432z");
}

.vq76pqe1z {
  stop-color: var(--svg-color--ed1c26, #ED1C26);
}

.w7cog_baa {
  stop-color: var(--svg-color--6c8578, #6C8578);
  stop-opacity: 0;
}

.wdn-cc6dw {
  stop-color: var(--svg-color--dd813e, #DD813E);
  stop-opacity: 0;
}

.wmo77fbcu {
  stop-color: var(--svg-color--759787, #759787);
}

.wysfcsb7u {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M4.175 11.576a.27.27 0 1 1 .54 0v1.542a.27.27 0 0 1-.54 0z");
}

.xir1dwxgq {
  stop-color: var(--svg-color--d6551c, #D6551C);
  stop-opacity: 0;
}

.xtg3u-bwn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.977 16.66h-9.983");
}

.yvx1b-b_l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m26.594 12.637l3.123 1.694");
}

.yxjmmcc7i {
  stop-color: var(--svg-color--885751, #885751);
}

.yzgjk9g0y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m18.235 25.524l-.757 2.67");
}

.z3wtmlbky {
  stop-color: var(--svg-color--ff7baf, #FF7BAF);
  stop-opacity: 0;
}

.z65833s6z {
  stop-color: var(--svg-color--ec7d4d, #EC7D4D);
}

.znkcu1bdd {
  d: path("M18.853 28.5h-.92l1.11-4.25h-1.5l-1.11 4.25h-1.2c-.66 0-1.19.53-1.19 1.19c0 .17.14.31.31.31h5.38c.17 0 .31-.14.31-.31c0-.66-.54-1.19-1.19-1.19");
}

.zu_n5klec {
  stop-color: var(--svg-color--76a090, #76A090);
  stop-opacity: 0;
}

</style>
