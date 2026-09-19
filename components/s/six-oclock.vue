<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#itxdPJc)" class="com508a7q"/><g filter="url(#iamlbem)"><path clip-rule="evenodd" class="efqn7lbxu"/></g><g filter="url(#ifgNkNb)"><path fill="url(#ivLkWsc)" clip-rule="evenodd" class="fd529_bip"/></g><path fill="url(#iLtZcRb)" clip-rule="evenodd" class="cr9yxzb9y"/><path fill="url(#ixCZ8Ed)" clip-rule="evenodd" class="cr9yxzb9y"/><path fill="url(#iQRfLvb)" clip-rule="evenodd" class="cr9yxzb9y"/><path fill="url(#iIQ2Fwd)" clip-rule="evenodd" class="cr9yxzb9y"/><g filter="url(#iKrtMsb)"><path fill="url(#iBoBa2b)" clip-rule="evenodd" class="nsc4v9emx"/></g><path fill="url(#iWkCPSb)" class="qxxkglluf"/><path fill="url(#iCUvHUN)" class="qxxkglluf"/><defs><linearGradient id="ivLkWsc" x1="16.192" x2="16.192" y1="7.083" y2="17.078" gradientUnits="userSpaceOnUse"><stop class="wdxszo23j"/><stop offset="1" class="bcrad1bcg"/></linearGradient><linearGradient id="iLtZcRb" x1="16.192" x2="16.192" y1="23.034" y2="17.223" gradientUnits="userSpaceOnUse"><stop class="vjrcszb_p"/><stop offset="1" class="zl0yx4b_i"/></linearGradient><linearGradient id="ixCZ8Ed" x1="17.192" x2="16.192" y1="20.004" y2="20.004" gradientUnits="userSpaceOnUse"><stop class="my1z1hkvz"/><stop offset="1" class="y_kzz0mys"/></linearGradient><linearGradient id="iIQ2Fwd" x1="16.192" x2="16.192" y1="23.034" y2="22.317" gradientUnits="userSpaceOnUse"><stop class="bqasmib2b"/><stop offset="1" class="boh6xxb-j"/></linearGradient><linearGradient id="iBoBa2b" x1="24.674" x2="4.447" y1="4.081" y2="28.601" gradientUnits="userSpaceOnUse"><stop class="mttz6pbyd"/><stop offset="1" class="olhrobbtj"/></linearGradient><radialGradient id="itxdPJc" cx="0" cy="0" r="1" gradientTransform="rotate(-46.212 33.656 .872)scale(25.2966)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="to7kn6bnn"/><stop offset="1" class="cvn-6ybtn"/></radialGradient><radialGradient id="iQRfLvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.73026 .81528 0 15.582 22.642)" gradientUnits="userSpaceOnUse"><stop class="d77sr4b-b"/><stop offset="1" class="i61yhl-1u"/></radialGradient><radialGradient id="iWkCPSb" cx="0" cy="0" r="1" gradientTransform="rotate(134.039 5.325 11.473)scale(3.40442)" gradientUnits="userSpaceOnUse"><stop class="gzwdfjydy"/><stop offset="1" class="sb8wjubjk"/></radialGradient><radialGradient id="iCUvHUN" cx="0" cy="0" r="1" gradientTransform="rotate(139.399 5.498 10.885)scale(2.88111)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="yrrl0sboi"/><stop offset="1" class="lb3ip72ql"/></radialGradient><filter id="iamlbem" width="6.978" height="18.951" x="11.705" y="6.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13561" stdDeviation=".75"/></filter><filter id="ifgNkNb" width="2.6" height="9.995" x="15.192" y="7.083" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".425"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.227451 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13561"/></filter><filter id="iKrtMsb" width="28.8" height="28.8" x="1.763" y="1.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.254902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13561"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13561" result="effect2_innerShadow_18_13561"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:six-oclock" /></template>
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

.com508a7q {
  d: path("M30.163 16.067c0 7.732-6.268 14-14 14s-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14");
}

.cr9yxzb9y {
  fill-rule: evenodd;
  d: path("M16.192 23.034a1 1 0 0 1-1-1v-5.967a1 1 0 1 1 2 0v5.967a1 1 0 0 1-1 1");
}

.cvn-6ybtn {
  stop-color: var(--svg-color--bdbabf, #BDBABF);
}

.d77sr4b-b {
  stop-color: var(--svg-color--50375f, #50375F);
}

.efqn7lbxu {
  fill: var(--svg-color--c3c0c6, #C3C0C6);
  fill-rule: evenodd;
  d: path("M15.192 8.083a1 1 0 0 1 1 1v6.274a1.988 1.988 0 0 1 0 3.442v4.235a1 1 0 1 1-2 0v-4.238a1.988 1.988 0 0 1 0-3.436V9.083a1 1 0 0 1 1-1");
}

.fd529_bip {
  fill-rule: evenodd;
  d: path("M16.192 7.083a1 1 0 0 1 1 1v7.995a1 1 0 1 1-2 0V8.083a1 1 0 0 1 1-1");
}

.ft5dv1b6b {
  fill: none;
}

.gzwdfjydy {
  stop-color: var(--svg-color--c9c6cc, #C9C6CC);
}

.i61yhl-1u {
  stop-color: var(--svg-color--50375f, #50375F);
  stop-opacity: 0;
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

.nsc4v9emx {
  fill-rule: evenodd;
  d: path("M16.163 27.067c6.075 0 11-4.925 11-11s-4.925-11-11-11s-11 4.925-11 11s4.925 11 11 11m0 3c7.732 0 14-6.268 14-14s-6.268-14-14-14s-14 6.268-14 14s6.268 14 14 14");
}

.olhrobbtj {
  stop-color: var(--svg-color--706c74, #706C74);
}

.qxxkglluf {
  d: path("M18.183 16.078a1.989 1.989 0 1 1-3.978 0a1.989 1.989 0 0 1 3.978 0");
}

.sb8wjubjk {
  stop-color: var(--svg-color--928e95, #928E95);
}

.to7kn6bnn {
  stop-color: var(--svg-color--dddadf, #DDDADF);
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

.yrrl0sboi {
  stop-color: var(--svg-color--776f7f, #776F7F);
  stop-opacity: 0;
}

.zl0yx4b_i {
  stop-color: var(--svg-color--2c3a65, #2C3A65);
}

</style>
