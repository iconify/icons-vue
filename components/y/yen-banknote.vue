<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iiJ3iMc)" class="v12x-rb6e"/><rect fill="url(#iz4mN0t)" class="v12x-rb6e"/><rect fill="url(#i35P12b)" class="v12x-rb6e"/><rect fill="url(#ijIIpCd)" class="zvg2jmbxz"/><g filter="url(#i529YLb)"><path fill="url(#iEoSM3k)" clip-rule="evenodd" class="lyqt40b3w"/></g><ellipse class="duhx5sozc"/><ellipse fill="url(#iQEAExe)" class="q_n0jxbcg"/><ellipse fill="url(#iuC2RfZ)" class="q_n0jxbcg"/><g filter="url(#i8Mgf7b)"><path fill="url(#i1ffYOd)" class="mu0pakbht"/></g><g filter="url(#ithV29d)"><path class="f2m9yib1p"/></g><g filter="url(#ig7ykme)"><path class="ox3uvhlov"/></g><path fill="url(#ijTCtmc)" class="rxhnf_m0o"/><path fill="url(#itOYGEd)" class="rxhnf_m0o"/><defs><linearGradient id="iiJ3iMc" x1="28.109" x2="3.047" y1="28.75" y2="28.75" gradientUnits="userSpaceOnUse"><stop class="ppph20b4e"/><stop offset="1" class="gihibmbtk"/></linearGradient><linearGradient id="iz4mN0t" x1="29.922" x2="27.266" y1="27.875" y2="27.875" gradientUnits="userSpaceOnUse"><stop class="av72r6bxv"/><stop offset="1" class="l7ka6vypz"/></linearGradient><linearGradient id="i35P12b" x1="2.078" x2="4.828" y1="27.75" y2="27.75" gradientUnits="userSpaceOnUse"><stop offset=".557" class="awvzwtd4l"/><stop offset="1" class="na2il_b7s"/></linearGradient><linearGradient id="iEoSM3k" x1="25.625" x2="7.875" y1="9.813" y2="24.5" gradientUnits="userSpaceOnUse"><stop class="e8h3xkvoe"/><stop offset="1" class="shis-4bob"/></linearGradient><linearGradient id="iQEAExe" x1="19.313" x2="21.094" y1="17.75" y2="17.75" gradientUnits="userSpaceOnUse"><stop offset=".228" class="h9z8j9_wp"/><stop offset="1" class="noaee5b-j"/></linearGradient><linearGradient id="i1ffYOd" x1="9.498" x2="9.498" y1="12.265" y2="21.75" gradientUnits="userSpaceOnUse"><stop class="ajz_v4uxp"/><stop offset="1" class="mfrnh_cso"/></linearGradient><linearGradient id="ijTCtmc" x1="17.25" x2="17.25" y1="9.75" y2="27.063" gradientUnits="userSpaceOnUse"><stop class="aa1s23ikb"/><stop offset="1" class="qgx211bpe"/></linearGradient><linearGradient id="itOYGEd" x1="18.313" x2="18.313" y1="29.969" y2="26.125" gradientUnits="userSpaceOnUse"><stop offset=".894" class="lok4kt4na"/><stop offset="1" class="r4fju6bru"/></linearGradient><filter id="i529YLb" width="25.525" height="15.731" x="3.237" y="9.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.427451 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21354"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.580392 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21354" result="effect2_innerShadow_18_21354"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.427451 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_21354" result="effect3_innerShadow_18_21354"/></filter><filter id="i8Mgf7b" width="6.797" height="9.784" x="6" y="12.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.462745 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_21354"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_21354" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.768627 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_21354"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.996078 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_21354" result="effect3_innerShadow_18_21354"/></filter><filter id="ithV29d" width="5.112" height="18.753" x="14.412" y="8.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21354" stdDeviation=".2"/></filter><filter id="ig7ykme" width="4.813" height="3.906" x="14.563" y="26.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21354" stdDeviation=".125"/></filter><radialGradient id="ijIIpCd" cx="0" cy="0" r="1" gradientTransform="matrix(12.93753 14.5 -19.01468 16.96571 2.688 8.813)" gradientUnits="userSpaceOnUse"><stop class="xru6-w0mn"/><stop offset="1" class="t7q5fyb2q"/></radialGradient><radialGradient id="iuC2RfZ" cx="0" cy="0" r="1" gradientTransform="rotate(-40.802 34.495 -19.069)scale(4.83012 4.74756)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="z3z539b8z"/><stop offset=".987" class="rtrttvbdo"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:yen-banknote" /></template>
<style>
.aa1s23ikb {
  stop-color: var(--svg-color--ffd425, #FFD425);
}

.ajz_v4uxp {
  stop-color: var(--svg-color--efeaea, #EFEAEA);
}

.av72r6bxv {
  stop-color: var(--svg-color--df9d4b, #DF9D4B);
}

.awvzwtd4l {
  stop-color: var(--svg-color--a04e1f, #A04E1F);
}

.duhx5sozc {
  cx: 20.844px;
  cy: 17.234px;
  fill: var(--svg-color--cc8642, #CC8642);
  rx: 4.625px;
  ry: 4.266px;
}

.e8h3xkvoe {
  stop-color: var(--svg-color--cc833f, #CC833F);
}

.f2m9yib1p {
  fill: var(--svg-color--8f491d, #8F491D);
  d: path("M14.969 8.422h4.156v17.953h-4.312z");
}

.ft5dv1b6b {
  fill: none;
}

.gihibmbtk {
  stop-color: var(--svg-color--ae5a20, #AE5A20);
}

.h9z8j9_wp {
  stop-color: var(--svg-color--d2813e, #D2813E);
}

.l7ka6vypz {
  stop-color: var(--svg-color--df9d4b, #DF9D4B);
  stop-opacity: 0;
}

.lok4kt4na {
  stop-color: var(--svg-color--cc8139, #CC8139);
}

.lyqt40b3w {
  fill-rule: evenodd;
  d: path("M27.063 10.219H4.938a.75.75 0 0 0-.75.75V23.5c0 .414.335.75.75.75h22.125a.75.75 0 0 0 .75-.75V10.969a.75.75 0 0 0-.75-.75m-22.125-.75a1.5 1.5 0 0 0-1.5 1.5V23.5a1.5 1.5 0 0 0 1.5 1.5h22.125a1.5 1.5 0 0 0 1.5-1.5V10.969a1.5 1.5 0 0 0-1.5-1.5z");
}

.mfrnh_cso {
  stop-color: var(--svg-color--eae3e3, #EAE3E3);
}

.mu0pakbht {
  d: path("M7.41 12.569a.625.625 0 0 0-1.07.643l2.098 3.494H6.922a.575.575 0 0 0 0 1.15h1.89v.71h-1.89a.575.575 0 1 0 0 1.15h1.89v1.409a.625.625 0 0 0 1.25 0v-1.41h2.11a.575.575 0 0 0 0-1.15h-2.11v-.709h2.11a.575.575 0 0 0 0-1.15h-1.72l2.158-3.486a.625.625 0 1 0-1.063-.658l-2.102 3.394z");
}

.na2il_b7s {
  stop-color: var(--svg-color--a04e1f, #A04E1F);
  stop-opacity: 0;
}

.noaee5b-j {
  stop-color: var(--svg-color--d2813e, #D2813E);
  stop-opacity: 0;
}

.ox3uvhlov {
  fill: var(--svg-color--9e5020, #9E5020);
  d: path("M14.984 29.781h4.141v-3.406h-4.312z");
}

.ppph20b4e {
  stop-color: var(--svg-color--b67732, #B67732);
}

.q_n0jxbcg {
  cx: 20.844px;
  cy: 17.234px;
  rx: 4.625px;
  ry: 4.266px;
}

.qgx211bpe {
  stop-color: var(--svg-color--ffad24, #FFAD24);
}

.r4fju6bru {
  stop-color: var(--svg-color--cc8139, #CC8139);
  stop-opacity: 0;
}

.rtrttvbdo {
  stop-color: var(--svg-color--af6328, #AF6328);
}

.rxhnf_m0o {
  d: path("M15.063 8.094h4.375v21.875h-4.375z");
}

.shis-4bob {
  stop-color: var(--svg-color--d48840, #D48840);
}

.t7q5fyb2q {
  stop-color: var(--svg-color--e5ac6a, #E5AC6A);
}

.v12x-rb6e {
  width: 27.844px;
  height: 18.281px;
  x: 2.078px;
  y: 11.688px;
  rx: 2.2px;
}

.xru6-w0mn {
  stop-color: var(--svg-color--f5bf80, #F5BF80);
}

.z3z539b8z {
  stop-color: var(--svg-color--c68240, #C68240);
  stop-opacity: 0;
}

.zvg2jmbxz {
  width: 27.844px;
  height: 18.281px;
  x: 2.078px;
  y: 8.094px;
  rx: 2.2px;
}

</style>
