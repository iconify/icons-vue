<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iKgmHKe)"><path fill="url(#iw8PEUc)" class="aewt67b4r"/><path fill="url(#iBKXcyp)" class="aewt67b4r"/><path fill="url(#iFcQt0d)" class="aewt67b4r"/></g><g filter="url(#iBF7hMd)"><path class="mt4zkebsf"/></g><g filter="url(#i68pxTb)"><path fill="url(#iIHlc3d)" class="hclieebjn"/><path fill="url(#ingCYHd)" class="hclieebjn"/></g><g filter="url(#ilhQ3Vc)"><path class="qyyadrbxc"/></g><g filter="url(#iKJyK2b)"><path class="g8b8z6_8y"/></g><g filter="url(#ia51lcd)"><path stroke="url(#ihVIpvb)" class="ie97h0bek"/></g><g filter="url(#icCLXNe)"><path stroke="url(#iRZ4p8F)" class="iij6u62xa"/></g><g filter="url(#iCQVG7b)"><path stroke="url(#i3AEnhL)" class="x_sl17yst"/></g><g filter="url(#i2icnfT)"><path stroke="url(#ifLgmkd)" class="b_az4ebnq"/></g><g filter="url(#ic5ycac)"><path stroke="url(#iiOZ1Yb)" class="gdjs5_bzn"/></g><g filter="url(#ibSFfAs)"><path stroke="url(#i6XO9rI)" class="j7ww14jhc"/></g><g filter="url(#i9KNhRc)"><path stroke="url(#iSJY5Xb)" class="oant4-b1d"/></g><g filter="url(#igMvTse)"><path stroke="url(#iooSWRa)" class="rp8n4_-jb"/></g><defs><filter id="iKgmHKe" width="26.826" height="23.063" x="2.528" y="2.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870833 0 0 0 0 0.0689409 0 0 0 0 0.37366 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7927"/></filter><filter id="iBF7hMd" width="17.331" height="12.102" x="7" y="11.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7927" stdDeviation=".5"/></filter><filter id="i68pxTb" width="15.882" height="18.494" x="8" y="11.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.0470588 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7927"/></filter><filter id="ilhQ3Vc" width="2.947" height="2.416" x="10.381" y="3.784" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7927" stdDeviation=".15"/></filter><filter id="iKJyK2b" width="2.728" height="4.088" x="15.537" y="2.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7927" stdDeviation=".15"/></filter><filter id="ia51lcd" width="2.103" height="9.603" x="19.771" y="3.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7927" stdDeviation=".15"/></filter><filter id="icCLXNe" width="2.716" height="3.204" x="24.116" y="11.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7927" stdDeviation=".15"/></filter><filter id="iCQVG7b" width="2.792" height="2.697" x="26.615" y="15.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7927" stdDeviation=".15"/></filter><filter id="i2icnfT" width="2.713" height="1.166" x="26.256" y="13.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7927" stdDeviation=".15"/></filter><filter id="ic5ycac" width="2.016" height="3.431" x="22.5" y="21.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7927" stdDeviation=".15"/></filter><filter id="ibSFfAs" width="1.4" height="18.087" x="15.4" y="11.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7927" stdDeviation=".25"/></filter><filter id="i9KNhRc" width="7.463" height="4.15" x="8.272" y="15.581" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7927" stdDeviation=".15"/></filter><filter id="igMvTse" width="8.572" height="4.947" x="15.459" y="15.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7927" stdDeviation=".25"/></filter><linearGradient id="iIHlc3d" x1="15.941" x2="15.941" y1="12.938" y2="29.938" gradientUnits="userSpaceOnUse"><stop class="y5vic3bje"/><stop offset="1" class="ct338abjm"/></linearGradient><linearGradient id="ingCYHd" x1="8" x2="8.878" y1="15.875" y2="16.313" gradientUnits="userSpaceOnUse"><stop class="f8_c0sb-t"/><stop offset=".991" class="txil1-1od"/></linearGradient><linearGradient id="ihVIpvb" x1="20.823" x2="20.823" y1="4.172" y2="12.875" gradientUnits="userSpaceOnUse"><stop class="l9zu5nh2c"/><stop offset="1" class="dl40c8bpr"/></linearGradient><linearGradient id="iRZ4p8F" x1="25.722" x2="24.878" y1="12.125" y2="13.422" gradientUnits="userSpaceOnUse"><stop class="bfz3ahbyk"/><stop offset="1" class="dl40c8bpr"/></linearGradient><linearGradient id="i3AEnhL" x1="28.268" x2="27.701" y1="16.511" y2="17.674" gradientUnits="userSpaceOnUse"><stop class="bfz3ahbyk"/><stop offset="1" class="dl40c8bpr"/></linearGradient><linearGradient id="ifLgmkd" x1="27.689" x2="27.671" y1="13.552" y2="13.801" gradientUnits="userSpaceOnUse"><stop class="bfz3ahbyk"/><stop offset="1" class="dl40c8bpr"/></linearGradient><linearGradient id="iiOZ1Yb" x1="23.508" x2="23.003" y1="22.219" y2="24.034" gradientUnits="userSpaceOnUse"><stop class="nzjvty60i"/><stop offset="1" class="h57fdybmd"/></linearGradient><linearGradient id="i6XO9rI" x1="16.6" x2="6.314" y1="12.809" y2="17.517" gradientUnits="userSpaceOnUse"><stop class="vgrdiccvz"/><stop offset=".971" class="nzjvty60i"/></linearGradient><linearGradient id="iSJY5Xb" x1="11.831" x2="11.488" y1="15.98" y2="21.2" gradientUnits="userSpaceOnUse"><stop class="vgrdiccvz"/><stop offset=".971" class="nzjvty60i"/></linearGradient><linearGradient id="iooSWRa" x1="19.745" x2="19.373" y1="16.132" y2="21.884" gradientUnits="userSpaceOnUse"><stop class="vgrdiccvz"/><stop offset=".971" class="nzjvty60i"/></linearGradient><radialGradient id="iw8PEUc" cx="0" cy="0" r="1" gradientTransform="rotate(116.714 8.603 11.984)scale(16.0928 26.3314)" gradientUnits="userSpaceOnUse"><stop class="tzgt79msc"/><stop offset="1" class="gzm4c3poo"/></radialGradient><radialGradient id="iBKXcyp" cx="0" cy="0" r="1" gradientTransform="rotate(-127.854 18.01 6.506)scale(7.63863 18.9638)" gradientUnits="userSpaceOnUse"><stop class="dqc8glbrz"/><stop offset="1" class="bgxf0xbsa"/></radialGradient><radialGradient id="iFcQt0d" cx="0" cy="0" r="1" gradientTransform="rotate(167.142 14.766 9.892)scale(11.7958 19.0302)" gradientUnits="userSpaceOnUse"><stop class="f1opweb7b"/><stop offset="1" class="ib2g4qb-c"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:maple-leaf" /></template>
<style>
.aewt67b4r {
  d: path("M15.94 2.063h.016c.176.014.341.14.422.334l1.078 2.46c.248.594.884.727 1.406.352l1.83-1.316a.7.7 0 0 1 1.096.702l-1.09 6.216c-.234 1.335 1.058 2.032 2.094 1.359l1.646-1.07c.494-.321 1.062.112.837.657l-.194.468c-.237.571.247 1.226.86 1.14l2.562-.328c.52-.073.918.474.616.903l-1.42 1.972c-.532.867-.072 1.288.593 1.406l.484.102c.72.127.75.792.18 1.117l-4.516 2.656c-.918.524-1.272 1.825-.523 2.57l.398.454c.414.412.029 1.064-.523.875l-7.827-2.655l-7.876 2.655c-.552.19-.937-.463-.524-.875l.399-.453c.75-.746.395-2.047-.524-2.57l-4.515-2.657c-.57-.325-.54-.99.18-1.117l.484-.102c.665-.118 1.125-.539.594-1.406L2.76 13.94c-.301-.43.097-.976.617-.903l2.562.328c.613.086 1.097-.569.86-1.14l-.194-.468c-.225-.545.343-.978.837-.657l1.646 1.07c1.036.673 2.328-.024 2.094-1.36l-1.09-6.215a.7.7 0 0 1 1.096-.702l1.83 1.316c.522.375 1.158.242 1.406-.352l1.078-2.46a.52.52 0 0 1 .422-.333v-.002z");
}

.b_az4ebnq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m26.706 13.734l1.813-.265");
}

.bfz3ahbyk {
  stop-color: var(--svg-color--ff7fcd, #FF7FCD);
  stop-opacity: 0;
}

.bgxf0xbsa {
  stop-color: var(--svg-color--fb4273, #FB4273);
  stop-opacity: 0;
}

.ct338abjm {
  stop-color: var(--svg-color--c81776, #C81776);
}

.dl40c8bpr {
  stop-color: var(--svg-color--ff7fb8, #FF7FB8);
}

.dqc8glbrz {
  stop-color: var(--svg-color--fb4273, #FB4273);
}

.f1opweb7b {
  stop-color: var(--svg-color--ff6fa9, #FF6FA9);
}

.f8_c0sb-t {
  stop-color: var(--svg-color--bf1a46, #BF1A46);
}

.ft5dv1b6b {
  fill: none;
}

.g8b8z6_8y {
  stroke: var(--svg-color--fb69b8, #FB69B8);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m15.987 2.625l1.172 2.64c.058.136.269.435.657.548");
}

.gdjs5_bzn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M23.081 21.922c-.125.323-.272 1.094.14 1.594s.735.833.845.937");
}

.gzm4c3poo {
  stop-color: var(--svg-color--ef2869, #EF2869);
}

.h57fdybmd {
  stop-color: var(--svg-color--ff7e8c, #FF7E8C);
}

.hclieebjn {
  d: path("M15.925 11.594a.75.75 0 0 1 .75.75v6.107a.25.25 0 0 0 .36.225l6.053-2.982a.55.55 0 0 1 .486.987l-6.62 3.261a.5.5 0 0 0-.28.449v8.797a.75.75 0 0 1-1.5 0v-8.813a.5.5 0 0 0-.278-.448l-6.59-3.246a.55.55 0 0 1 .487-.987l6.021 2.966a.25.25 0 0 0 .36-.224v-6.092a.75.75 0 0 1 .75-.75");
}

.ib2g4qb-c {
  stop-color: var(--svg-color--ff6fa9, #FF6FA9);
  stop-opacity: 0;
}

.ie97h0bek {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M21.144 4.172c.12.026.34.172.265.547s-.812 4.25-1.172 6.14c-.072.516.06 1.641 1.172 2.016");
}

.iij6u62xa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M24.933 11.51c-.241.287-.574 1.08-.196 1.654a1.38 1.38 0 0 0 1.645.566");
}

.j7ww14jhc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.1 12.263V28.95");
}

.l9zu5nh2c {
  stop-color: var(--svg-color--ff7fcd, #FF7FCD);
}

.mt4zkebsf {
  fill: var(--svg-color--d7102f, #D7102F);
  d: path("m16.374 21.908l-.051-.017l-1.397.47v-1.624a.48.48 0 0 0-.27-.433l-6.36-3.133a.531.531 0 0 1 .47-.953l5.812 2.863a.24.24 0 0 0 .348-.216v-5.881a.724.724 0 0 1 1.448 0v5.896c0 .178.188.295.348.216l5.843-2.878a.53.53 0 1 1 .47.953l-6.391 3.148a.48.48 0 0 0-.27.433z");
}

.nzjvty60i {
  stop-color: var(--svg-color--ff7e8c, #FF7E8C);
  stop-opacity: 0;
}

.oant4-b1d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m8.722 16.031l6.562 3.25");
}

.qyyadrbxc {
  stroke: var(--svg-color--fb69b8, #FB69B8);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m10.831 4.234l2.047 1.516");
}

.rp8n4_-jb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m16.16 19.563l7.171-3.547");
}

.txil1-1od {
  stop-color: var(--svg-color--bf1a46, #BF1A46);
  stop-opacity: 0;
}

.tzgt79msc {
  stop-color: var(--svg-color--fe63ba, #FE63BA);
}

.vgrdiccvz {
  stop-color: var(--svg-color--fa6e94, #FA6E94);
}

.x_sl17yst {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M27.175 16.031c-.083.1-.2.419 0 .907c.2.487.74.671.984.703l.797.187");
}

.y5vic3bje {
  stop-color: var(--svg-color--e02e6b, #E02E6B);
}

</style>
