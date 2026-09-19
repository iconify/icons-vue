<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iRfL7ce)" class="fu6lz2bme"/><g filter="url(#iIbnU8Z)"><path fill="url(#iZpZWAd)" class="qvwoalbnm"/></g><g filter="url(#idxEUxx)"><path clip-rule="evenodd" class="ntf7eccwr"/></g><g filter="url(#iwzRIfb)"><path fill="url(#iz3Yg3d)" clip-rule="evenodd" class="v01kspb4x"/></g><path fill="url(#ixw5r8d)" clip-rule="evenodd" class="zb6scgbxv"/><path fill="url(#i84KdJb)" clip-rule="evenodd" class="zb6scgbxv"/><path fill="url(#ivPN2Yc)" clip-rule="evenodd" class="zb6scgbxv"/><path fill="url(#irkq5He)" clip-rule="evenodd" class="zb6scgbxv"/><path fill="url(#iWc3Dvc)" class="gy6nxcbaa"/><path fill="url(#i3ismie)" class="gy6nxcbaa"/><defs><linearGradient id="iZpZWAd" x1="15" x2="15" y1="8.009" y2="19" gradientUnits="userSpaceOnUse"><stop class="fg8d8quoh"/><stop offset="1" class="t-wepab3b"/></linearGradient><linearGradient id="iz3Yg3d" x1="24.48" x2="4.253" y1="4.013" y2="28.534" gradientUnits="userSpaceOnUse"><stop class="mttz6pbyd"/><stop offset="1" class="olhrobbtj"/></linearGradient><linearGradient id="ixw5r8d" x1="15.998" x2="15.998" y1="9.037" y2="14.848" gradientUnits="userSpaceOnUse"><stop class="vjrcszb_p"/><stop offset="1" class="zl0yx4b_i"/></linearGradient><linearGradient id="i84KdJb" x1="14.998" x2="15.998" y1="12.067" y2="12.067" gradientUnits="userSpaceOnUse"><stop class="my1z1hkvz"/><stop offset="1" class="y_kzz0mys"/></linearGradient><linearGradient id="irkq5He" x1="15.998" x2="15.998" y1="9.037" y2="9.755" gradientUnits="userSpaceOnUse"><stop class="bqasmib2b"/><stop offset="1" class="boh6xxb-j"/></linearGradient><radialGradient id="iRfL7ce" cx="0" cy="0" r="1" gradientTransform="rotate(-46.212 32.62 -.436)scale(22.0719)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="to7kn6bnn"/><stop offset="1" class="cvn-6ybtn"/></radialGradient><radialGradient id="ivPN2Yc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.73026 -.81528 0 16.607 9.43)" gradientUnits="userSpaceOnUse"><stop class="d77sr4b-b"/><stop offset="1" class="i61yhl-1u"/></radialGradient><radialGradient id="iWc3Dvc" cx="0" cy="0" r="1" gradientTransform="rotate(134.039 5.242 11.398)scale(3.40442)" gradientUnits="userSpaceOnUse"><stop class="gzwdfjydy"/><stop offset="1" class="sb8wjubjk"/></radialGradient><radialGradient id="i3ismie" cx="0" cy="0" r="1" gradientTransform="rotate(139.399 5.414 10.816)scale(2.88111)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="yrrl0sboi"/><stop offset="1" class="lb3ip72ql"/></radialGradient><filter id="iIbnU8Z" width="7.978" height="14.991" x="11.011" y="6.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13489" stdDeviation="1"/></filter><filter id="idxEUxx" width="2.6" height="9.995" x="14.998" y="7.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.654902 0 0 0 0 0.188235 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13489"/></filter><filter id="iwzRIfb" width="28.8" height="28.8" x="1.569" y="1.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.254902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13489"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13489" result="effect2_innerShadow_18_13489"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:twelve-oclock" /></template>
<style>
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

.d77sr4b-b {
  stop-color: var(--svg-color--50375f, #50375F);
}

.fg8d8quoh {
  stop-color: var(--svg-color--c6bbbf, #C6BBBF);
}

.ft5dv1b6b {
  fill: none;
}

.fu6lz2bme {
  d: path("M28.184 16c0 6.746-5.469 12.215-12.215 12.215c-6.747 0-12.216-5.469-12.216-12.215S9.223 3.785 15.97 3.785S28.184 9.254 28.184 16");
}

.gy6nxcbaa {
  d: path("M17.989 16.011a1.989 1.989 0 1 1-3.978 0a1.989 1.989 0 0 1 3.978 0");
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

.ntf7eccwr {
  fill: var(--svg-color--f83f4c, #F83F4C);
  fill-rule: evenodd;
  d: path("M15.998 7.009a1 1 0 0 1 1 1v7.995a1 1 0 1 1-2 0V8.01a1 1 0 0 1 1-1");
}

.olhrobbtj {
  stop-color: var(--svg-color--706c74, #706C74);
}

.qvwoalbnm {
  d: path("M14.998 8.009a1 1 0 0 1 1 1v6.281A1.988 1.988 0 0 1 15 19a1.989 1.989 0 0 1-1.002-3.707V9.009a1 1 0 0 1 1-1");
}

.sb8wjubjk {
  stop-color: var(--svg-color--928e95, #928E95);
}

.t-wepab3b {
  stop-color: var(--svg-color--c3c0c7, #C3C0C7);
}

.to7kn6bnn {
  stop-color: var(--svg-color--dddadf, #DDDADF);
}

.v01kspb4x {
  fill-rule: evenodd;
  d: path("M15.969 27c6.075 0 11-4.925 11-11s-4.925-11-11-11s-11 4.925-11 11s4.925 11 11 11m0 3c7.732 0 14-6.268 14-14s-6.268-14-14-14s-14 6.268-14 14s6.268 14 14 14");
}

.vjrcszb_p {
  stop-color: var(--svg-color--32183d, #32183D);
}

.y_kzz0mys {
  stop-color: var(--svg-color--2e2840, #2E2840);
  stop-opacity: 0;
}

.yrrl0sboi {
  stop-color: var(--svg-color--776f7f, #776F7F);
  stop-opacity: 0;
}

.zb6scgbxv {
  fill-rule: evenodd;
  d: path("M15.998 9.037a1 1 0 0 1 1 1v5.967a1 1 0 0 1-2 0v-5.967a1 1 0 0 1 1-1");
}

.zl0yx4b_i {
  stop-color: var(--svg-color--2c3a65, #2C3A65);
}

</style>
