<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#ig0iKob)" class="c0bglzbgx"/><rect fill="url(#iw1xVOe)" class="c0bglzbgx"/><rect fill="url(#iAGrIev)" class="c0bglzbgx"/><rect fill="url(#if98Jdd)" class="kla-nsx9y"/><g filter="url(#iiGn7cb)"><path fill="url(#i0lOjBb)" clip-rule="evenodd" class="i88ky9vqt"/></g><ellipse class="pwifw-m-z"/><ellipse fill="url(#iTTKmMd)" class="sousm-bga"/><ellipse fill="url(#i4fBPuq)" class="sousm-bga"/><g filter="url(#iU0cJRc)"><path class="a_nzfsl_h"/></g><g filter="url(#iIS5V6q)"><path class="z9vw1iamv"/></g><path fill="url(#ij2dOid)" class="n91vrkbzi"/><path fill="url(#ic9Rcke)" class="n91vrkbzi"/><g filter="url(#ibzg3le)"><path fill="url(#iEhJRAc)" class="p8d66pbnu"/></g><defs><linearGradient id="ig0iKob" x1="28.109" x2="3.047" y1="28.688" y2="28.688" gradientUnits="userSpaceOnUse"><stop class="bsczq7ber"/><stop offset="1" class="zxf7n-tas"/></linearGradient><linearGradient id="iw1xVOe" x1="29.922" x2="27.266" y1="27.813" y2="27.813" gradientUnits="userSpaceOnUse"><stop class="l3qwkyb-o"/><stop offset="1" class="rew3e5t0l"/></linearGradient><linearGradient id="iAGrIev" x1="2.078" x2="4.828" y1="27.688" y2="27.688" gradientUnits="userSpaceOnUse"><stop offset=".557" class="cgyggbbxl"/><stop offset="1" class="t5cgv1bsk"/></linearGradient><linearGradient id="i0lOjBb" x1="25.625" x2="7.875" y1="9.75" y2="24.438" gradientUnits="userSpaceOnUse"><stop class="ufz-86bnt"/><stop offset="1" class="lsibcpg6v"/></linearGradient><linearGradient id="iTTKmMd" x1="19.313" x2="21.094" y1="17.688" y2="17.688" gradientUnits="userSpaceOnUse"><stop offset=".228" class="kwu7e_zje"/><stop offset="1" class="uo4xi6k3e"/></linearGradient><linearGradient id="ij2dOid" x1="17.25" x2="17.25" y1="9.688" y2="27" gradientUnits="userSpaceOnUse"><stop class="aa1s23ikb"/><stop offset="1" class="qgx211bpe"/></linearGradient><linearGradient id="ic9Rcke" x1="18.313" x2="18.313" y1="29.906" y2="26.063" gradientUnits="userSpaceOnUse"><stop offset=".894" class="lok4kt4na"/><stop offset="1" class="r4fju6bru"/></linearGradient><linearGradient id="iEhJRAc" x1="9.734" x2="9.734" y1="12.306" y2="21.397" gradientUnits="userSpaceOnUse"><stop class="ajz_v4uxp"/><stop offset="1" class="mfrnh_cso"/></linearGradient><filter id="iiGn7cb" width="25.325" height="15.731" x="3.237" y="9.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.266667 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21488"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.25098 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21488" result="effect2_innerShadow_18_21488"/></filter><filter id="iU0cJRc" width="5.112" height="18.8" x="14.412" y="7.912" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21488" stdDeviation=".2"/></filter><filter id="iIS5V6q" width="4.813" height="3.906" x="14.563" y="26.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21488" stdDeviation=".125"/></filter><filter id="ibzg3le" width="8.231" height="9.591" x="5.469" y="12.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.298039 0 0 0 0 0.568627 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_21488"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_21488" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.760784 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_21488"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.996078 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_21488" result="effect3_innerShadow_18_21488"/></filter><radialGradient id="if98Jdd" cx="0" cy="0" r="1" gradientTransform="matrix(22.02347 17.07558 -22.39218 28.88063 2.688 8.75)" gradientUnits="userSpaceOnUse"><stop class="t4i9tc31m"/><stop offset="1" class="snquhyb0g"/></radialGradient><radialGradient id="i4fBPuq" cx="0" cy="0" r="1" gradientTransform="rotate(-40.802 34.41 -19.1)scale(4.83012 4.74756)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="ln8v20h7t"/><stop offset="1" class="wag5wlbyq"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pound-banknote" /></template>
<style>
.a_nzfsl_h {
  fill: var(--svg-color--5e3d72, #5E3D72);
  d: path("M14.969 8.313h4.156v18h-4.312z");
}

.aa1s23ikb {
  stop-color: var(--svg-color--ffd425, #FFD425);
}

.ajz_v4uxp {
  stop-color: var(--svg-color--efeaea, #EFEAEA);
}

.bsczq7ber {
  stop-color: var(--svg-color--614a81, #614A81);
}

.c0bglzbgx {
  width: 27.844px;
  height: 18.281px;
  x: 2.078px;
  y: 11.625px;
  rx: 2.2px;
}

.cgyggbbxl {
  stop-color: var(--svg-color--49345c, #49345C);
}

.ft5dv1b6b {
  fill: none;
}

.i88ky9vqt {
  fill-rule: evenodd;
  d: path("M27.063 10.156H4.938a.75.75 0 0 0-.75.75v12.532c0 .414.335.75.75.75h22.125a.75.75 0 0 0 .75-.75V10.906a.75.75 0 0 0-.75-.75m-22.125-.75a1.5 1.5 0 0 0-1.5 1.5v12.532a1.5 1.5 0 0 0 1.5 1.5h22.125a1.5 1.5 0 0 0 1.5-1.5V10.906a1.5 1.5 0 0 0-1.5-1.5z");
}

.kla-nsx9y {
  width: 27.844px;
  height: 18.281px;
  x: 2.078px;
  y: 8.031px;
  rx: 2.2px;
}

.kwu7e_zje {
  stop-color: var(--svg-color--5a507f, #5A507F);
}

.l3qwkyb-o {
  stop-color: var(--svg-color--7b63ad, #7B63AD);
}

.ln8v20h7t {
  stop-color: var(--svg-color--514675, #514675);
  stop-opacity: 0;
}

.lok4kt4na {
  stop-color: var(--svg-color--cc8139, #CC8139);
}

.lsibcpg6v {
  stop-color: var(--svg-color--63568f, #63568F);
}

.mfrnh_cso {
  stop-color: var(--svg-color--eae3e3, #EAE3E3);
}

.n91vrkbzi {
  d: path("M15.063 8.031h4.375v21.875h-4.375z");
}

.p8d66pbnu {
  d: path("M8.704 12.669c.425-.235.956-.363 1.608-.363c1.029 0 1.754.382 2.204.928c.429.52.573 1.15.535 1.612a.6.6 0 1 1-1.196-.098a1.13 1.13 0 0 0-.265-.751c-.2-.242-.572-.49-1.277-.49c-.497 0-.819.096-1.028.212a1.03 1.03 0 0 0-.423.425c-.184.342-.184.738-.184.978v1.528h1.666a.6.6 0 0 1 0 1.2H8.678v1.865c.002.133-.012.302-.054.482H13a.6.6 0 1 1 0 1.2H6.469a.6.6 0 1 1 0-1.2h.749c.067 0 .095-.015.107-.023a.2.2 0 0 0 .067-.078a.8.8 0 0 0 .086-.369V17.85h-1.01a.6.6 0 1 1 0-1.2h1.01v-1.548c-.002-.24-.006-.908.328-1.527c.184-.342.47-.67.898-.906");
}

.pwifw-m-z {
  cx: 20.844px;
  cy: 17.172px;
  fill: var(--svg-color--605689, #605689);
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

.rew3e5t0l {
  stop-color: var(--svg-color--7b63ad, #7B63AD);
  stop-opacity: 0;
}

.snquhyb0g {
  stop-color: var(--svg-color--9f74d3, #9F74D3);
}

.sousm-bga {
  cx: 20.844px;
  cy: 17.172px;
  rx: 4.625px;
  ry: 4.266px;
}

.t4i9tc31m {
  stop-color: var(--svg-color--bd89e6, #BD89E6);
}

.t5cgv1bsk {
  stop-color: var(--svg-color--49345c, #49345C);
  stop-opacity: 0;
}

.ufz-86bnt {
  stop-color: var(--svg-color--5e5388, #5E5388);
}

.uo4xi6k3e {
  stop-color: var(--svg-color--5a507f, #5A507F);
  stop-opacity: 0;
}

.wag5wlbyq {
  stop-color: var(--svg-color--463762, #463762);
}

.z9vw1iamv {
  fill: var(--svg-color--462b56, #462B56);
  d: path("M14.984 29.719h4.141v-3.407h-4.312z");
}

.zxf7n-tas {
  stop-color: var(--svg-color--513b6c, #513B6C);
}

</style>
