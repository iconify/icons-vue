<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#i79SbPe)" class="wbrejxb6i"/><g filter="url(#iC2G9lk)"><path clip-rule="evenodd" class="yfdsowbnp"/></g><g clip-rule="evenodd" filter="url(#idzmkZj)" class="d2kvgvbvc"><path fill="url(#iLyQ8oc)" class="na2clzbzw"/><path fill="url(#isqyzQk)" class="na2clzbzw"/></g><path fill="url(#iSYvjxc)" clip-rule="evenodd" class="cm-a2pxor"/><path fill="url(#iAqyKvL)" clip-rule="evenodd" class="cm-a2pxor"/><path fill="url(#izZVdxe)" clip-rule="evenodd" class="cm-a2pxor"/><path fill="url(#iBUkZQc)" clip-rule="evenodd" class="cm-a2pxor"/><g filter="url(#iTcE66b)"><path fill="url(#i5jGxBb)" clip-rule="evenodd" class="qdqw6ttlb"/></g><path fill="url(#iBGlP0d)" class="rc9u_5sac"/><path fill="url(#iZrX8hb)" class="rc9u_5sac"/><defs><radialGradient id="i79SbPe" cx="0" cy="0" r="1" gradientTransform="rotate(-46.212 32.395 -.91)scale(21.1181)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="to7kn6bnn"/><stop offset="1" class="cvn-6ybtn"/></radialGradient><radialGradient id="isqyzQk" cx="0" cy="0" r="1" gradientTransform="rotate(146.437 5.42 11.306)scale(1.95012 1.33455)" gradientUnits="userSpaceOnUse"><stop offset=".293" class="h_yu15b7s"/><stop offset="1" class="e81falbog"/></radialGradient><radialGradient id="izZVdxe" cx="0" cy="0" r="1" gradientTransform="rotate(150 9.224 9.573)scale(5.73026 .81528)" gradientUnits="userSpaceOnUse"><stop class="d77sr4b-b"/><stop offset="1" class="i61yhl-1u"/></radialGradient><radialGradient id="iBGlP0d" cx="0" cy="0" r="1" gradientTransform="rotate(134.039 5.258 11.405)scale(3.40442)" gradientUnits="userSpaceOnUse"><stop class="gzwdfjydy"/><stop offset="1" class="sb8wjubjk"/></radialGradient><radialGradient id="iZrX8hb" cx="0" cy="0" r="1" gradientTransform="rotate(139.399 5.43 10.822)scale(2.88111)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="yrrl0sboi"/><stop offset="1" class="lb3ip72ql"/></radialGradient><linearGradient id="iLyQ8oc" x1="16.029" x2="16.029" y1="15.011" y2="25.007" gradientUnits="userSpaceOnUse"><stop class="wdxszo23j"/><stop offset="1" class="bcrad1bcg"/></linearGradient><linearGradient id="iSYvjxc" x1="22.034" x2="17.001" y1="12.528" y2="15.434" gradientUnits="userSpaceOnUse"><stop class="vjrcszb_p"/><stop offset="1" class="zl0yx4b_i"/></linearGradient><linearGradient id="iAqyKvL" x1="18.91" x2="19.41" y1="13.177" y2="14.043" gradientUnits="userSpaceOnUse"><stop class="my1z1hkvz"/><stop offset="1" class="y_kzz0mys"/></linearGradient><linearGradient id="iBUkZQc" x1="22.034" x2="21.412" y1="12.528" y2="12.887" gradientUnits="userSpaceOnUse"><stop class="bqasmib2b"/><stop offset="1" class="boh6xxb-j"/></linearGradient><linearGradient id="i5jGxBb" x1="24.511" x2="4.284" y1="4.013" y2="28.534" gradientUnits="userSpaceOnUse"><stop class="mttz6pbyd"/><stop offset="1" class="olhrobbtj"/></linearGradient><filter id="iC2G9lk" width="11.126" height="15.979" x="11.478" y="11.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13519" stdDeviation=".75"/></filter><filter id="idzmkZj" width="2.6" height="9.995" x="15.029" y="15.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".425"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.227451 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13519"/></filter><filter id="iTcE66b" width="28.8" height="28.8" x="1.6" y="1.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.254902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13519"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13519" result="effect2_innerShadow_18_13519"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:two-thirty" /></template>
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

.cm-a2pxor {
  fill-rule: evenodd;
  d: path("M22.034 12.528a1 1 0 0 1-.366 1.366L16.5 16.877a1 1 0 0 1-1-1.732l5.168-2.983a1 1 0 0 1 1.366.366");
}

.cvn-6ybtn {
  stop-color: var(--svg-color--bdbabf, #BDBABF);
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

.lb3ip72ql {
  stop-color: var(--svg-color--776f7f, #776F7F);
}

.mttz6pbyd {
  stop-color: var(--svg-color--6d6b70, #6D6B70);
}

.my1z1hkvz {
  stop-color: var(--svg-color--2e2840, #2E2840);
}

.na2clzbzw {
  d: path("M16.029 15.011a1 1 0 0 1 1 1v7.996a1 1 0 1 1-2 0V16.01a1 1 0 0 1 1-1");
}

.olhrobbtj {
  stop-color: var(--svg-color--706c74, #706C74);
}

.qdqw6ttlb {
  fill-rule: evenodd;
  d: path("M16 27c6.075 0 11-4.925 11-11S22.075 5 16 5S5 9.925 5 16s4.925 11 11 11m0 3c7.732 0 14-6.268 14-14S23.732 2 16 2S2 8.268 2 16s6.268 14 14 14");
}

.rc9u_5sac {
  d: path("M18.02 16.011a1.989 1.989 0 1 1-3.978 0a1.989 1.989 0 0 1 3.978 0");
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

.wbrejxb6i {
  cx: 16px;
  cy: 16.011px;
  r: 11.688px;
}

.wdxszo23j {
  stop-color: var(--svg-color--f83f4c, #F83F4C);
}

.y_kzz0mys {
  stop-color: var(--svg-color--2e2840, #2E2840);
  stop-opacity: 0;
}

.yfdsowbnp {
  fill: var(--svg-color--c4c0c7, #C4C0C7);
  fill-rule: evenodd;
  d: path("M20.97 13.278a1 1 0 0 1-.367 1.366l-3.647 2.106v.011c0 .735-.399 1.377-.992 1.721v6.275a1 1 0 1 1-2 0v-6.278a1.988 1.988 0 0 1 1.976-3.452l3.663-2.115a1 1 0 0 1 1.366.366");
}

.yrrl0sboi {
  stop-color: var(--svg-color--776f7f, #776F7F);
  stop-opacity: 0;
}

.zl0yx4b_i {
  stop-color: var(--svg-color--2c3a65, #2C3A65);
}

</style>
