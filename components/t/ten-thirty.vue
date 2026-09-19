<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iaIwitb)" class="ttzscwblc"/><g filter="url(#i0wffQb)"><path clip-rule="evenodd" class="zb1geh3hc"/></g><g clip-rule="evenodd" filter="url(#i0mjYre)" class="d2kvgvbvc"><path fill="url(#i41vjTo)" class="egycrkblg"/><path fill="url(#iFg8n8S)" class="egycrkblg"/></g><path fill="url(#i7GkA0c)" clip-rule="evenodd" class="cvrdn6bqq"/><path fill="url(#idCb7nc)" clip-rule="evenodd" class="cvrdn6bqq"/><path fill="url(#ioeX5Qb)" clip-rule="evenodd" class="cvrdn6bqq"/><path fill="url(#ifvNMMc)" clip-rule="evenodd" class="cvrdn6bqq"/><g filter="url(#icodlzb)"><path fill="url(#iCRrf4c)" clip-rule="evenodd" class="y1kv_jb7s"/></g><path fill="url(#ig9qCrd)" class="l29470b7a"/><path fill="url(#i5LbbLb)" class="l29470b7a"/><defs><radialGradient id="iaIwitb" cx="0" cy="0" r="1" gradientTransform="rotate(-46.212 33.525 .999)scale(25.2966)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="to7kn6bnn"/><stop offset="1" class="cvn-6ybtn"/></radialGradient><radialGradient id="iFg8n8S" cx="0" cy="0" r="1" gradientTransform="rotate(150.018 6.083 10.711)scale(3.75208 1.82648)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="h_yu15b7s"/><stop offset="1" class="e81falbog"/></radialGradient><radialGradient id="ioeX5Qb" cx="0" cy="0" r="1" gradientTransform="rotate(30 -17.437 25.956)scale(5.73026 .81528)" gradientUnits="userSpaceOnUse"><stop class="d77sr4b-b"/><stop offset="1" class="i61yhl-1u"/></radialGradient><radialGradient id="ig9qCrd" cx="0" cy="0" r="1" gradientTransform="rotate(134.039 5.271 11.417)scale(3.40442)" gradientUnits="userSpaceOnUse"><stop class="gzwdfjydy"/><stop offset="1" class="sb8wjubjk"/></radialGradient><radialGradient id="i5LbbLb" cx="0" cy="0" r="1" gradientTransform="rotate(139.399 5.443 10.833)scale(2.88111)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="yrrl0sboi"/><stop offset="1" class="lb3ip72ql"/></radialGradient><linearGradient id="i41vjTo" x1="16.06" x2="16.06" y1="15.022" y2="25.018" gradientUnits="userSpaceOnUse"><stop class="bcrad1bcg"/><stop offset="1" class="wdxszo23j"/></linearGradient><linearGradient id="i7GkA0c" x1="9.997" x2="15.03" y1="12.528" y2="15.433" gradientUnits="userSpaceOnUse"><stop class="vjrcszb_p"/><stop offset="1" class="zl0yx4b_i"/></linearGradient><linearGradient id="idCb7nc" x1="12.122" x2="12.622" y1="14.909" y2="14.043" gradientUnits="userSpaceOnUse"><stop class="my1z1hkvz"/><stop offset="1" class="y_kzz0mys"/></linearGradient><linearGradient id="ifvNMMc" x1="9.997" x2="10.619" y1="12.528" y2="12.886" gradientUnits="userSpaceOnUse"><stop class="bqasmib2b"/><stop offset="1" class="boh6xxb-j"/></linearGradient><linearGradient id="iCRrf4c" x1="24.542" x2="4.315" y1="4.025" y2="28.545" gradientUnits="userSpaceOnUse"><stop class="mttz6pbyd"/><stop offset="1" class="olhrobbtj"/></linearGradient><filter id="i0wffQb" width="11.188" height="15.99" x="7.997" y="11.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13615" stdDeviation=".75"/></filter><filter id="i0mjYre" width="2.6" height="9.995" x="15.06" y="15.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".425"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.227451 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13615"/></filter><filter id="icodlzb" width="28.8" height="28.8" x="1.631" y="1.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.254902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13615"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13615" result="effect2_innerShadow_18_13615"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ten-thirty" /></template>
<style>
.bcrad1bcg {
  stop-color: var(--svg-color--f74093, #F74093);
}

.boh6xxb-j {
  stop-color: var(--svg-color--3e1846, #3E1846);
  stop-opacity: 0;
}

.bqasmib2b {
  stop-color: var(--svg-color--3e1846, #3E1846);
}

.cvn-6ybtn {
  stop-color: var(--svg-color--bdbabf, #BDBABF);
}

.cvrdn6bqq {
  fill-rule: evenodd;
  d: path("M9.997 12.528a1 1 0 0 1 1.367-.366l5.167 2.983a1 1 0 0 1-1 1.732l-5.167-2.983a1 1 0 0 1-.367-1.366");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d77sr4b-b {
  stop-color: var(--svg-color--50375f, #50375F);
}

.e81falbog {
  stop-color: var(--svg-color--911a57, #911A57);
  stop-opacity: 0;
}

.egycrkblg {
  d: path("M16.06 15.022a1 1 0 0 1 1 1v7.996a1 1 0 1 1-2 0v-7.996a1 1 0 0 1 1-1");
}

.ft5dv1b6b {
  fill: none;
}

.gzwdfjydy {
  stop-color: var(--svg-color--c9c6cc, #C9C6CC);
}

.h_yu15b7s {
  stop-color: var(--svg-color--911a57, #911A57);
}

.i61yhl-1u {
  stop-color: var(--svg-color--50375f, #50375F);
  stop-opacity: 0;
}

.l29470b7a {
  d: path("M18.051 16.022a1.989 1.989 0 1 1-3.978 0a1.989 1.989 0 0 1 3.978 0");
}

.lb3ip72ql {
  stop-color: var(--svg-color--776f7f, #776F7F);
}

.mttz6pbyd {
  stop-color: var(--svg-color--6d6b70, #6D6B70);
}

.my1z1hkvz {
  stop-color: var(--svg-color--2e2840, #2E2840);
}

.olhrobbtj {
  stop-color: var(--svg-color--706c74, #706C74);
}

.sb8wjubjk {
  stop-color: var(--svg-color--928e95, #928E95);
}

.to7kn6bnn {
  stop-color: var(--svg-color--dddadf, #DDDADF);
}

.ttzscwblc {
  d: path("M30.031 16.011c0 7.732-6.268 14-14 14s-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14");
}

.vjrcszb_p {
  stop-color: var(--svg-color--32183d, #32183D);
}

.wdxszo23j {
  stop-color: var(--svg-color--f83f4c, #F83F4C);
}

.y_kzz0mys {
  stop-color: var(--svg-color--2e2840, #2E2840);
  stop-opacity: 0;
}

.y1kv_jb7s {
  fill-rule: evenodd;
  d: path("M16.031 27.011c6.075 0 11-4.925 11-11s-4.925-11-11-11s-11 4.925-11 11s4.925 11 11 11m0 3c7.732 0 14-6.268 14-14s-6.268-14-14-14s-14 6.268-14 14s6.268 14 14 14");
}

.yrrl0sboi {
  stop-color: var(--svg-color--776f7f, #776F7F);
  stop-opacity: 0;
}

.zb1geh3hc {
  fill: var(--svg-color--c3bec5, #C3BEC5);
  fill-rule: evenodd;
  d: path("M9.632 13.52a1 1 0 0 1 1.366-.365l3.703 2.138a1.989 1.989 0 0 1 1.993 3.443v6.275a1 1 0 1 1-2 0v-6.278a1.99 1.99 0 0 1-.986-1.704l-3.71-2.142a1 1 0 0 1-.366-1.367");
}

.zl0yx4b_i {
  stop-color: var(--svg-color--2c3a65, #2C3A65);
}

</style>
