<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i8wgIhe)"><path fill="url(#iqYKK3b)" class="exdeh_f4u"/></g><g filter="url(#iCF84QX)"><rect fill="url(#iqiMwPd)" class="mrq-rkb1d"/></g><path fill="url(#iQU29ne)" clip-rule="evenodd" class="rn78lob1c"/><path fill="url(#i175eqn)" clip-rule="evenodd" class="rn78lob1c"/><g filter="url(#iZHcQTc)"><path fill="url(#iKuBXhc)" clip-rule="evenodd" class="ogvmi_nmw"/></g><path fill="url(#iulNSud)" class="iyrdytxdh"/><path fill="url(#iqH1OSb)" class="exdeh_f4u"/><defs><linearGradient id="iqYKK3b" x1="8.423" x2="29.234" y1="26.418" y2="14.512" gradientUnits="userSpaceOnUse"><stop class="zq68emb2g"/><stop offset="1" class="s15yyd-nu"/></linearGradient><linearGradient id="iQU29ne" x1="16.298" x2="31.578" y1="25.855" y2="25.855" gradientUnits="userSpaceOnUse"><stop class="luw47v2fo"/><stop offset="1" class="gc1pfplfe"/></linearGradient><linearGradient id="i175eqn" x1="20.716" x2="20.716" y1="27.889" y2="25.867" gradientUnits="userSpaceOnUse"><stop class="s7pnydbec"/><stop offset="1" class="vsvwidnic"/></linearGradient><linearGradient id="iulNSud" x1="7.5" x2="27.692" y1="29.297" y2="29.297" gradientUnits="userSpaceOnUse"><stop class="u6vxc1urh"/><stop offset="1" class="lt38d1btv"/></linearGradient><linearGradient id="iqH1OSb" x1="15.967" x2="15.967" y1="27.096" y2="26.349" gradientUnits="userSpaceOnUse"><stop offset=".077" class="bq9xj9byf"/><stop offset="1" class="d754bdczv"/></linearGradient><filter id="i8wgIhe" width="29.433" height="19.935" x="2" y="7.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.309804 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9605"/></filter><filter id="iCF84QX" width="4.005" height="2.011" x="5.975" y="23.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.180392 0 0 0 0 0.0666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9605"/></filter><filter id="iZHcQTc" width="16.861" height="9.889" x="7.562" y="8.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.65098 0 0 0 0 0.890196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_9605"/></filter><radialGradient id="iqiMwPd" cx="0" cy="0" r="1" gradientTransform="matrix(3.76074 0 0 1.6587 6.499 24.017)" gradientUnits="userSpaceOnUse"><stop class="q3m2_ybli"/><stop offset="1" class="vmpcc9dpd"/></radialGradient><radialGradient id="iKuBXhc" cx="0" cy="0" r="1" gradientTransform="matrix(14.88716 -10.13517 3.27117 4.8049 9.536 18.401)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="plxiymbgn"/><stop offset="1" class="rdyfaxbjx"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:monorail" /></template>
<style>
.bq9xj9byf {
  stop-color: var(--svg-color--0f1a41, #0F1A41);
}

.d754bdczv {
  stop-color: var(--svg-color--0f1a41, #0F1A41);
  stop-opacity: 0;
}

.exdeh_f4u {
  d: path("M4.457 26.97h25.476V7.535c-6.97 1.045-13.748 3.934-19.63 8.76l-7.444 6.352a2.457 2.457 0 0 0 1.598 4.323");
}

.ft5dv1b6b {
  fill: none;
}

.gc1pfplfe {
  stop-color: var(--svg-color--ede0f5, #EDE0F5);
}

.iyrdytxdh {
  d: path("M2 26.97h27.933V30H2z");
}

.lt38d1btv {
  stop-color: var(--svg-color--d4c7dc, #D4C7DC);
}

.luw47v2fo {
  stop-color: var(--svg-color--c5bbcd, #C5BBCD);
}

.mrq-rkb1d {
  width: 4.005px;
  height: 2.011px;
  x: 5.975px;
  y: 23.008px;
  rx: 1.006px;
}

.ogvmi_nmw {
  fill-rule: evenodd;
  d: path("M7.962 18.292c2.33.285 6.373.134 9.881-1.945c3.171-1.88 5.365-4.724 6.58-7.585c-5.004 1.492-9.803 3.99-14.12 7.532z");
}

.plxiymbgn {
  stop-color: var(--svg-color--5af1ff, #5AF1FF);
}

.q3m2_ybli {
  stop-color: var(--svg-color--ff7853, #FF7853);
}

.rdyfaxbjx {
  stop-color: var(--svg-color--2599d8, #2599D8);
}

.rn78lob1c {
  fill-rule: evenodd;
  d: path("M29.933 20.039h-6.267c-3.091 0-6.154 1.654-7.902 3.872L13.39 26.97h16.542z");
}

.s15yyd-nu {
  stop-color: var(--svg-color--73b3ff, #73B3FF);
}

.s7pnydbec {
  stop-color: var(--svg-color--817a87, #817A87);
}

.u6vxc1urh {
  stop-color: var(--svg-color--aea4b4, #AEA4B4);
}

.vmpcc9dpd {
  stop-color: var(--svg-color--f43a21, #F43A21);
}

.vsvwidnic {
  stop-color: var(--svg-color--817a87, #817A87);
  stop-opacity: 0;
}

.zq68emb2g {
  stop-color: var(--svg-color--5775ff, #5775FF);
}

</style>
