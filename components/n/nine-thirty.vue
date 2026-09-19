<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ivo7YDc)" class="jl81vn0ac"/><g filter="url(#iF11MLJ)"><path class="cpepkcb8h"/></g><g clip-rule="evenodd" filter="url(#i0YCOle)" class="d2kvgvbvc"><path fill="url(#iLyQ8oc)" class="na2clzbzw"/><path fill="url(#isqyzQk)" class="na2clzbzw"/></g><path fill="url(#ihES51h)" clip-rule="evenodd" class="ym-8u4p6t"/><path fill="url(#inCA6eW)" clip-rule="evenodd" class="ym-8u4p6t"/><path fill="url(#iQS3nMb)" clip-rule="evenodd" class="ym-8u4p6t"/><path fill="url(#iZU8O5b)" clip-rule="evenodd" class="ym-8u4p6t"/><g filter="url(#i5aGtkg)"><path fill="url(#i5jGxBb)" clip-rule="evenodd" class="qdqw6ttlb"/></g><path fill="url(#iBGlP0d)" class="rc9u_5sac"/><path fill="url(#iZrX8hb)" class="rc9u_5sac"/><defs><radialGradient id="ivo7YDc" cx="0" cy="0" r="1" gradientTransform="rotate(-46.212 33.496 1.03)scale(25.2966)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="to7kn6bnn"/><stop offset="1" class="cvn-6ybtn"/></radialGradient><radialGradient id="isqyzQk" cx="0" cy="0" r="1" gradientTransform="rotate(146.437 5.42 11.306)scale(1.95012 1.33455)" gradientUnits="userSpaceOnUse"><stop offset=".293" class="h_yu15b7s"/><stop offset="1" class="e81falbog"/></radialGradient><radialGradient id="iQS3nMb" cx="0" cy="0" r="1" gradientTransform="matrix(5.73026 0 0 .81528 9.425 15.39)" gradientUnits="userSpaceOnUse"><stop class="d77sr4b-b"/><stop offset="1" class="i61yhl-1u"/></radialGradient><radialGradient id="iBGlP0d" cx="0" cy="0" r="1" gradientTransform="rotate(134.039 5.258 11.405)scale(3.40442)" gradientUnits="userSpaceOnUse"><stop class="gzwdfjydy"/><stop offset="1" class="sb8wjubjk"/></radialGradient><radialGradient id="iZrX8hb" cx="0" cy="0" r="1" gradientTransform="rotate(139.399 5.43 10.822)scale(2.88111)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="yrrl0sboi"/><stop offset="1" class="lb3ip72ql"/></radialGradient><linearGradient id="iLyQ8oc" x1="16.029" x2="16.029" y1="15.011" y2="25.007" gradientUnits="userSpaceOnUse"><stop class="wdxszo23j"/><stop offset="1" class="bcrad1bcg"/></linearGradient><linearGradient id="ihES51h" x1="9.033" x2="14.844" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop class="vjrcszb_p"/><stop offset="1" class="zl0yx4b_i"/></linearGradient><linearGradient id="inCA6eW" x1="12.063" x2="12.063" y1="17" y2="16" gradientUnits="userSpaceOnUse"><stop class="my1z1hkvz"/><stop offset="1" class="y_kzz0mys"/></linearGradient><linearGradient id="iZU8O5b" x1="9.033" x2="9.751" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop class="bqasmib2b"/><stop offset="1" class="boh6xxb-j"/></linearGradient><linearGradient id="i5jGxBb" x1="24.511" x2="4.284" y1="4.013" y2="28.534" gradientUnits="userSpaceOnUse"><stop class="mttz6pbyd"/><stop offset="1" class="olhrobbtj"/></linearGradient><filter id="iF11MLJ" width="11.987" height="13.984" x="6.533" y="13.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13603" stdDeviation=".75"/></filter><filter id="i0YCOle" width="2.6" height="9.995" x="15.029" y="15.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".425"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.227451 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13603"/></filter><filter id="i5aGtkg" width="28.8" height="28.8" x="1.6" y="1.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.254902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13603"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13603" result="effect2_innerShadow_18_13603"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:nine-thirty" /></template>
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

.cpepkcb8h {
  fill: var(--svg-color--c0bcc3, #C0BCC3);
  d: path("M16.029 18.732A1.988 1.988 0 1 0 13.319 16H9.032a1 1 0 1 0 0 2h4.272c.174.302.424.554.724.73v6.277a1 1 0 1 0 2 0z");
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

.jl81vn0ac {
  d: path("M30 16c0 7.732-6.268 14-14 14S2 23.732 2 16S8.268 2 16 2s14 6.268 14 14");
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

.wdxszo23j {
  stop-color: var(--svg-color--f83f4c, #F83F4C);
}

.y_kzz0mys {
  stop-color: var(--svg-color--2e2840, #2E2840);
  stop-opacity: 0;
}

.ym-8u4p6t {
  fill-rule: evenodd;
  d: path("M9.033 16a1 1 0 0 1 1-1H16a1 1 0 1 1 0 2h-5.967a1 1 0 0 1-1-1");
}

.yrrl0sboi {
  stop-color: var(--svg-color--776f7f, #776F7F);
  stop-opacity: 0;
}

.zl0yx4b_i {
  stop-color: var(--svg-color--2c3a65, #2C3A65);
}

</style>
