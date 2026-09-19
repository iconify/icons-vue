<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iF8hr1Y)" class="lmh4whbrs"/><g filter="url(#iRjbTLH)"><circle fill="url(#ineFjxe)" class="lmh4whbrs"/></g><circle fill="url(#iDfclyq)" class="x5_7l-bbi"/><circle fill="url(#i5SxOXv)" class="g4k3q7cmw"/><circle fill="url(#iDQjjDb)" class="g4k3q7cmw"/><g filter="url(#iJuHvoe)"><circle stroke="url(#iVWrhkh)" class="c-vn58bav"/></g><path fill="url(#i1sbmye)" class="lf_xyqbww"/><path fill="url(#iWMCDRb)" class="lf_xyqbww"/><g filter="url(#ijVOq8d)"><path stroke="url(#i5tgigb)" class="beej6_jjo"/></g><path fill="url(#iJIDgkc)" class="cmiujyb_i"/><path fill="url(#iSzvL0d)" class="cmiujyb_i"/><circle fill="url(#isY3BBc)" class="h2-o4in6u"/><path fill="url(#iI5hnOe)" class="kk0mxrbeg"/><path fill="url(#izQPxtP)" class="kk0mxrbeg"/><path fill="url(#i41vW0b)" class="kk0mxrbeg"/><path fill="url(#it1b0rc)" class="kk0mxrbeg"/><path fill="url(#ijm1mxb)" class="kk0mxrbeg"/><circle fill="url(#isN18QL)" class="h2-o4in6u"/><g filter="url(#ibzqadb)"><circle fill="url(#iVqbCsc)" class="h2-o4in6u"/><circle fill="url(#i6I1WIc)" class="h2-o4in6u"/><circle stroke="url(#i85kn2d)" class="c6dds4bjf"/></g><circle fill="url(#iqfJvtw)" class="az0fwjbyp"/><circle fill="url(#iOoj4yQ)" class="az0fwjbyp"/><g filter="url(#iVvakfG)"><circle stroke="url(#iWmCMLb)" transform="rotate(-90 9.5 12.5)" class="aif3dxb6p"/></g><circle fill="url(#i00DHBC)" transform="rotate(-90 9.5 12.5)" class="az0fwjbyp"/><circle fill="url(#iLSfHyb)" transform="rotate(-90 9.5 12.5)" class="az0fwjbyp"/><circle fill="url(#iENAIVc)" transform="rotate(-90 9.5 12.5)" class="az0fwjbyp"/><g filter="url(#iG2xhHc)"><ellipse fill="url(#iXmj3me)" class="ubkox1pdz"/><ellipse fill="url(#i284jQd)" class="ubkox1pdz"/><path stroke="url(#i13YuGe)" class="of-m-4ton"/></g><g filter="url(#ijI30Gd)"><path class="b9n006w2d"/></g><g filter="url(#iVymCCe)"><path stroke="url(#iQvapiM)" class="fc5mtu2so"/></g><path fill="url(#iodMIJb)" class="tir0dnb0c"/><path fill="url(#iDSx0Vz)" class="lf_xyqbww"/><path fill="url(#iK72nye)" class="lf_xyqbww"/><defs><radialGradient id="iF8hr1Y" cx="0" cy="0" r="1" gradientTransform="rotate(133.363 8.703 9.384)scale(24.7588)" gradientUnits="userSpaceOnUse"><stop class="ifsoepbvs"/><stop offset="1" class="gap-yf33v"/></radialGradient><radialGradient id="ineFjxe" cx="0" cy="0" r="1" gradientTransform="rotate(111.357 9.906 13.64)scale(20.9378)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="aebf02t-y"/><stop offset="1" class="t9qmhi0ed"/></radialGradient><radialGradient id="i5SxOXv" cx="0" cy="0" r="1" gradientTransform="matrix(2.23466 -2.21485 1.49233 1.50568 22.5 11.927)" gradientUnits="userSpaceOnUse"><stop class="kfr8f4sfk"/><stop offset="1" class="zorq6pbpy"/></radialGradient><radialGradient id="iDQjjDb" cx="0" cy="0" r="1" gradientTransform="rotate(90 5.5 17)scale(2.5)" gradientUnits="userSpaceOnUse"><stop offset=".921" class="tkongac3i"/><stop offset=".977" class="plnlp5b6m"/></radialGradient><radialGradient id="iSzvL0d" cx="0" cy="0" r="1" gradientTransform="matrix(-.0625 -4.28125 5.84388 -.08531 27.279 25.1)" gradientUnits="userSpaceOnUse"><stop offset=".777" class="hyszpbcik"/><stop offset=".992" class="a6o3g7zqv"/></radialGradient><radialGradient id="iI5hnOe" cx="0" cy="0" r="1" gradientTransform="rotate(114.236 6.943 11.718)scale(18.217 15.6028)" gradientUnits="userSpaceOnUse"><stop class="q_61rmcfh"/><stop offset="1" class="y8da_t9hl"/></radialGradient><radialGradient id="izQPxtP" cx="0" cy="0" r="1" gradientTransform="matrix(-10.50884 18.30203 -30.75377 -17.6585 17.714 11.698)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="akqj6kdgb"/><stop offset=".802" class="spn12mu7s"/></radialGradient><radialGradient id="i41vW0b" cx="0" cy="0" r="1" gradientTransform="matrix(-21.55488 -10.83437 11.03328 -21.9506 24.688 19.823)" gradientUnits="userSpaceOnUse"><stop offset=".679" class="d_4llxbcl"/><stop offset="1" class="arhawk_an"/></radialGradient><radialGradient id="it1b0rc" cx="0" cy="0" r="1" gradientTransform="rotate(108.645 8.712 10.94)scale(27.7204 27.9176)" gradientUnits="userSpaceOnUse"><stop offset=".821" class="hka5o5b2o"/><stop offset="1" class="h7b_ie_gi"/></radialGradient><radialGradient id="ijm1mxb" cx="0" cy="0" r="1" gradientTransform="matrix(3.63292 1.68134 -6.88693 14.8808 2.912 9.97)" gradientUnits="userSpaceOnUse"><stop class="dnqv24y1t"/><stop offset="1" class="e483yhb6b"/></radialGradient><radialGradient id="iVqbCsc" cx="0" cy="0" r="1" gradientTransform="rotate(135 4.38 13.926)scale(3.93533 4.69999)" gradientUnits="userSpaceOnUse"><stop offset=".252" class="kj-88vbdi"/><stop offset="1" class="hqgudgt7g"/></radialGradient><radialGradient id="i6I1WIc" cx="0" cy="0" r="1" gradientTransform="matrix(3.28124 -3.12501 2.54646 2.67376 15.094 23.01)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="ey0lgwv1v"/><stop offset="1" class="rz7k2sb_t"/></radialGradient><radialGradient id="i00DHBC" cx="0" cy="0" r="1" gradientTransform="rotate(-47.175 20.864 -.52)scale(6.98771)" gradientUnits="userSpaceOnUse"><stop class="t8mzg_bgw"/><stop offset="1" class="asif75bjf"/></radialGradient><radialGradient id="iLSfHyb" cx="0" cy="0" r="1" gradientTransform="matrix(5.375 -5.4375 4.05278 4.0062 6.813 15.136)" gradientUnits="userSpaceOnUse"><stop offset=".636" class="y2dt9rtuc"/><stop offset="1" class="tzxv8fgey"/></radialGradient><radialGradient id="iENAIVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.81038 4.96523 0 9.5 13.511)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="gn6-v4b1b"/><stop offset="1" class="legwfrc_m"/></radialGradient><radialGradient id="iXmj3me" cx="0" cy="0" r="1" gradientTransform="matrix(-3.00536 0 0 -3.27072 17.005 5.5)" gradientUnits="userSpaceOnUse"><stop offset=".437" class="piy3tic3g"/><stop offset="1" class="r38asee8x"/></radialGradient><radialGradient id="i284jQd" cx="0" cy="0" r="1" gradientTransform="matrix(2.75536 0 0 2.97042 14.693 5.5)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="od4hrnb8k"/><stop offset="1" class="um7ihac7p"/></radialGradient><radialGradient id="iodMIJb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.39148 .9118 -.55587 -2.0676 22.278 11.5)" gradientUnits="userSpaceOnUse"><stop class="iyv9pnbxm"/><stop offset="1" class="g26sm3b5a"/></radialGradient><radialGradient id="iK72nye" cx="0" cy="0" r="1" gradientTransform="rotate(-142.952 9.324 11.92)scale(5.57176 3.36972)" gradientUnits="userSpaceOnUse"><stop offset=".888" class="te8heeq8v"/><stop offset="1" class="uu4-6olre"/></radialGradient><linearGradient id="iDfclyq" x1="16.5" x2="14.5" y1="4.5" y2="6.5" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="nec_isxbo"/></linearGradient><linearGradient id="iVWrhkh" x1="23.435" x2="22.5" y1="8.819" y2="14" gradientUnits="userSpaceOnUse"><stop class="quyb0sbxe"/><stop offset="1" class="n0wdc0bol"/></linearGradient><linearGradient id="i1sbmye" x1="11" x2="4" y1="24.5" y2="26" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="uyvx2tbpp"/></linearGradient><linearGradient id="iWMCDRb" x1="9.958" x2="6.145" y1="23.957" y2="28.108" gradientUnits="userSpaceOnUse"><stop class="odmjt405d"/><stop offset="1" class="qf2998b3n"/></linearGradient><linearGradient id="i5tgigb" x1="27.279" x2="24.138" y1="20.881" y2="26.35" gradientUnits="userSpaceOnUse"><stop class="z2mp41bxm"/><stop offset=".999" class="ot4-jgt4j"/></linearGradient><linearGradient id="iJIDgkc" x1="25.873" x2="27.06" y1="25.975" y2="19.787" gradientUnits="userSpaceOnUse"><stop class="g4rfypbmn"/><stop offset="1" class="o-kypwb8c"/></linearGradient><linearGradient id="isY3BBc" x1="18.167" x2="14.833" y1="19.833" y2="23.167" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="nec_isxbo"/></linearGradient><linearGradient id="isN18QL" x1="18.167" x2="14.833" y1="19.833" y2="23.167" gradientUnits="userSpaceOnUse"><stop class="odmjt405d"/><stop offset="1" class="qf2998b3n"/></linearGradient><linearGradient id="i85kn2d" x1="18.25" x2="14.369" y1="19.32" y2="23.257" gradientUnits="userSpaceOnUse"><stop class="qkzvsmbnh"/><stop offset="1" class="mj21lz_nw"/></linearGradient><linearGradient id="iqfJvtw" x1="11.833" x2="7.167" y1="10.167" y2="14.833" gradientUnits="userSpaceOnUse"><stop class="s334l8uyu"/><stop offset="1" class="nec_isxbo"/></linearGradient><linearGradient id="iOoj4yQ" x1="11.833" x2="7.167" y1="10.167" y2="14.833" gradientUnits="userSpaceOnUse"><stop class="odmjt405d"/><stop offset="1" class="qf2998b3n"/></linearGradient><linearGradient id="iWmCMLb" x1="11.325" x2="6.934" y1="9.361" y2="15.057" gradientUnits="userSpaceOnUse"><stop class="xe1h3_e7t"/><stop offset="1" class="nt99fmbml"/></linearGradient><linearGradient id="i13YuGe" x1="17.448" x2="16.268" y1="5.17" y2="5.17" gradientUnits="userSpaceOnUse"><stop class="tneowg16w"/><stop offset="1" class="btjyt1bqw"/></linearGradient><linearGradient id="iQvapiM" x1="10.35" x2="5.287" y1="27.948" y2="23.479" gradientUnits="userSpaceOnUse"><stop class="t4vxokb_x"/><stop offset="1" class="n2qdeeb3x"/></linearGradient><linearGradient id="iDSx0Vz" x1="10.307" x2="5.964" y1="24.331" y2="26.993" gradientUnits="userSpaceOnUse"><stop class="zt28h012e"/><stop offset="1" class="bslbvcb-m"/></linearGradient><filter id="iRjbTLH" width="28.3" height="28.3" x="1.7" y="1.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.568627 0 0 0 0 0.454902 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13993"/></filter><filter id="iJuHvoe" width="6" height="6" x="19.5" y="8.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13993" stdDeviation=".2"/></filter><filter id="ijVOq8d" width="5.697" height="6.589" x="23.522" y="20.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13993" stdDeviation=".15"/></filter><filter id="ibzqadb" width="5.7" height="5.7" x="13.65" y="18.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13993" stdDeviation=".1"/></filter><filter id="iVvakfG" width="7.8" height="7.8" x="5.6" y="8.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13993" stdDeviation=".15"/></filter><filter id="iG2xhHc" width="4.148" height="3.7" x="13.65" y="3.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13993" stdDeviation=".1"/></filter><filter id="ijI30Gd" width="4.473" height="6.01" x="19.475" y="8.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13993" stdDeviation=".2"/></filter><filter id="iVymCCe" width="6.717" height="6.285" x="4.583" y="22.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13993" stdDeviation=".1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:waning-gibbous-moon" /></template>
<style>
.a6o3g7zqv {
  stop-color: var(--svg-color--663f8e, #663F8E);
}

.aebf02t-y {
  stop-color: var(--svg-color--a37bd0, #A37BD0);
}

.aif3dxb6p {
  cx: 9.5px;
  cy: 12.5px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.akqj6kdgb {
  stop-color: var(--svg-color--d97850, #D97850);
  stop-opacity: 0;
}

.arhawk_an {
  stop-color: var(--svg-color--b69262, #B69262);
}

.asif75bjf {
  stop-color: var(--svg-color--d5a04b, #D5A04B);
}

.az0fwjbyp {
  cx: 9.5px;
  cy: 12.5px;
  r: 3.5px;
}

.b9n006w2d {
  stroke: var(--svg-color--fffbaf, #FFFBAF);
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.14 9.038C21.083 9.228 20 10.119 20 11.5a2.5 2.5 0 0 0 2.5 2.5c.43 0 .635-.047.989-.239");
}

.beej6_jjo {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M28.877 21.316a3.5 3.5 0 0 0-4.074 5.507");
}

.bslbvcb-m {
  stop-color: var(--svg-color--ae6b71, #AE6B71);
}

.btjyt1bqw {
  stop-color: var(--svg-color--ffdd7b, #FFDD7B);
}

.c-vn58bav {
  cx: 22.5px;
  cy: 11.5px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.c6dds4bjf {
  cx: 16.5px;
  cy: 21.5px;
  r: 2.575px;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
}

.cmiujyb_i {
  d: path("M28.955 21.316a14.04 14.04 0 0 1-4.073 5.507a3.5 3.5 0 0 1 4.074-5.507");
}

.d_4llxbcl {
  stop-color: var(--svg-color--b69262, #B69262);
  stop-opacity: 0;
}

.dnqv24y1t {
  stop-color: var(--svg-color--b48c4f, #B48C4F);
}

.e483yhb6b {
  stop-color: var(--svg-color--b48c4f, #B48C4F);
  stop-opacity: 0;
}

.ey0lgwv1v {
  stop-color: var(--svg-color--e3915b, #E3915B);
  stop-opacity: 0;
}

.fc5mtu2so {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M10.348 28.636a14.05 14.05 0 0 1-5.44-4.406c.642-.813 1.561-1.256 2.677-1.256c1.933 0 3.327 1.724 3.415 3.424c0 .852-.146 1.63-.652 2.238Z");
}

.ft5dv1b6b {
  fill: none;
}

.g26sm3b5a {
  stop-color: var(--svg-color--ffe07d, #FFE07D);
}

.g4k3q7cmw {
  cx: 22.5px;
  cy: 11.5px;
  r: 2.5px;
}

.g4rfypbmn {
  stop-color: var(--svg-color--8a60b5, #8A60B5);
}

.gap-yf33v {
  stop-color: var(--svg-color--f7ca32, #F7CA32);
}

.gn6-v4b1b {
  stop-color: var(--svg-color--ffca62, #FFCA62);
  stop-opacity: 0;
}

.h2-o4in6u {
  cx: 16.5px;
  cy: 21.5px;
  r: 2.5px;
}

.h7b_ie_gi {
  stop-color: var(--svg-color--c3747f, #C3747F);
}

.hka5o5b2o {
  stop-color: var(--svg-color--c3747f, #C3747F);
  stop-opacity: 0;
}

.hqgudgt7g {
  stop-color: var(--svg-color--ffd87e, #FFD87E);
}

.hyszpbcik {
  stop-color: var(--svg-color--663f8e, #663F8E);
  stop-opacity: 0;
}

.ifsoepbvs {
  stop-color: var(--svg-color--feed6e, #FEED6E);
}

.iyv9pnbxm {
  stop-color: var(--svg-color--fff6ae, #FFF6AE);
}

.kfr8f4sfk {
  stop-color: var(--svg-color--b287d7, #B287D7);
}

.kj-88vbdi {
  stop-color: var(--svg-color--f29e64, #F29E64);
}

.kk0mxrbeg {
  d: path("M17.4 2.07Q16.709 2 16 2C8.268 2 2 8.268 2 16s6.268 14 14 14q.709 0 1.4-.07C21.428 26.63 24 21.616 24 16c0-.753-.061-1.624-.208-2.351c-1.094-.448-1.792-1.394-1.792-2.65c0-.702.184-1.502.589-2.013c-1.144-2.773-2.903-5.044-5.19-6.917");
}

.legwfrc_m {
  stop-color: var(--svg-color--ffca62, #FFCA62);
}

.lf_xyqbww {
  d: path("M10.189 28.74a14.05 14.05 0 0 1-5.439-4.405a3.5 3.5 0 1 1 5.439 4.406");
}

.lmh4whbrs {
  cx: 16px;
  cy: 16px;
  r: 14px;
}

.mj21lz_nw {
  stop-color: var(--svg-color--ffb053, #FFB053);
}

.n0wdc0bol {
  stop-color: var(--svg-color--a27ace, #A27ACE);
}

.n2qdeeb3x {
  stop-color: var(--svg-color--b96779, #B96779);
}

.nec_isxbo {
  stop-color: var(--svg-color--ffef71, #FFEF71);
}

.nt99fmbml {
  stop-color: var(--svg-color--d79c38, #D79C38);
}

.o-kypwb8c {
  stop-color: var(--svg-color--885bb3, #885BB3);
}

.od4hrnb8k {
  stop-color: var(--svg-color--cd9e56, #CD9E56);
  stop-opacity: 0;
}

.odmjt405d {
  stop-color: var(--svg-color--0f0f0f, #0F0F0F);
}

.of-m-4ton {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M15.724 7.075c.984 0 1.8-.696 1.8-1.575c0-.88-.816-1.575-1.8-1.575c-.983 0-1.799.696-1.799 1.575c0 .88.816 1.575 1.8 1.575Z");
}

.ot4-jgt4j {
  stop-color: var(--svg-color--7e55ac, #7E55AC);
}

.piy3tic3g {
  stop-color: var(--svg-color--f3bb63, #F3BB63);
}

.plnlp5b6m {
  stop-color: var(--svg-color--a47acb, #A47ACB);
}

.q_61rmcfh {
  stop-color: var(--svg-color--ffed90, #FFED90);
}

.qf2998b3n {
  stop-color: var(--svg-color--704e8d, #704E8D);
}

.qkzvsmbnh {
  stop-color: var(--svg-color--fbac52, #FBAC52);
}

.quyb0sbxe {
  stop-color: var(--svg-color--a076cf, #A076CF);
}

.r38asee8x {
  stop-color: var(--svg-color--fff3a5, #FFF3A5);
}

.rz7k2sb_t {
  stop-color: var(--svg-color--e3915b, #E3915B);
}

.s334l8uyu {
  stop-color: var(--svg-color--f5c224, #F5C224);
}

.spn12mu7s {
  stop-color: var(--svg-color--d97850, #D97850);
}

.t4vxokb_x {
  stop-color: var(--svg-color--b36558, #B36558);
}

.t8mzg_bgw {
  stop-color: var(--svg-color--f6b953, #F6B953);
}

.t9qmhi0ed {
  stop-color: var(--svg-color--6d3e9e, #6D3E9E);
}

.te8heeq8v {
  stop-color: var(--svg-color--af4c46, #AF4C46);
  stop-opacity: 0;
}

.tir0dnb0c {
  d: path("M22.589 9.002L22.5 9a2.5 2.5 0 0 0 0 5c.43 0 .93-.185 1.283-.377C22.783 13.137 22 12.187 22 11c0-.639.087-1.166.589-1.998");
}

.tkongac3i {
  stop-color: var(--svg-color--a47acb, #A47ACB);
  stop-opacity: 0;
}

.tneowg16w {
  stop-color: var(--svg-color--fdc36b, #FDC36B);
}

.tzxv8fgey {
  stop-color: var(--svg-color--bd8d44, #BD8D44);
}

.ubkox1pdz {
  cx: 15.724px;
  cy: 5.5px;
  rx: 1.724px;
  ry: 1.5px;
}

.um7ihac7p {
  stop-color: var(--svg-color--cd9e56, #CD9E56);
}

.uu4-6olre {
  stop-color: var(--svg-color--af4c46, #AF4C46);
}

.uyvx2tbpp {
  stop-color: var(--svg-color--fce35d, #FCE35D);
}

.x5_7l-bbi {
  cx: 15.5px;
  cy: 5.5px;
  r: 1.5px;
}

.xe1h3_e7t {
  stop-color: var(--svg-color--e4ac50, #E4AC50);
}

.y2dt9rtuc {
  stop-color: var(--svg-color--bd8d44, #BD8D44);
  stop-opacity: 0;
}

.y8da_t9hl {
  stop-color: var(--svg-color--ffb64a, #FFB64A);
}

.z2mp41bxm {
  stop-color: var(--svg-color--7246a2, #7246A2);
}

.zorq6pbpy {
  stop-color: var(--svg-color--9b6ac1, #9B6AC1);
}

.zt28h012e {
  stop-color: var(--svg-color--bd6152, #BD6152);
}

</style>
