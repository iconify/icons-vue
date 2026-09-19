<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i05QBNe)" class="a5awa9dpy"/><g filter="url(#inKIueb)"><path class="zv98mnbqa"/></g><g filter="url(#iJBgigc)"><path fill="url(#iixBo7b)" clip-rule="evenodd" class="m9p8-w07t"/></g><path fill="url(#iQb95Df)" clip-rule="evenodd" class="y1t11ub3k"/><path fill="url(#il3ZYOb)" clip-rule="evenodd" class="y1t11ub3k"/><path fill="url(#iWvFWnM)" clip-rule="evenodd" class="y1t11ub3k"/><path fill="url(#iaW2tyn)" clip-rule="evenodd" class="y1t11ub3k"/><g filter="url(#iWKQ2gc)"><path fill="url(#iShdZse)" clip-rule="evenodd" class="edywn_bhv"/></g><path fill="url(#i7UDhUS)" class="ain1pzbin"/><path fill="url(#iDb5Jod)" class="ain1pzbin"/><defs><linearGradient id="iixBo7b" x1="16.029" x2="16.029" y1="7.027" y2="17.023" gradientUnits="userSpaceOnUse"><stop class="wdxszo23j"/><stop offset="1" class="bcrad1bcg"/></linearGradient><linearGradient id="iQb95Df" x1="23" x2="17.189" y1="16.011" y2="16.011" gradientUnits="userSpaceOnUse"><stop class="vjrcszb_p"/><stop offset="1" class="zl0yx4b_i"/></linearGradient><linearGradient id="il3ZYOb" x1="19.97" x2="19.97" y1="15.011" y2="16.011" gradientUnits="userSpaceOnUse"><stop class="my1z1hkvz"/><stop offset="1" class="y_kzz0mys"/></linearGradient><linearGradient id="iaW2tyn" x1="23" x2="22.282" y1="16.011" y2="16.011" gradientUnits="userSpaceOnUse"><stop class="bqasmib2b"/><stop offset="1" class="boh6xxb-j"/></linearGradient><linearGradient id="iShdZse" x1="24.511" x2="4.284" y1="4.025" y2="28.545" gradientUnits="userSpaceOnUse"><stop class="mttz6pbyd"/><stop offset="1" class="olhrobbtj"/></linearGradient><radialGradient id="i05QBNe" cx="0" cy="0" r="1" gradientTransform="rotate(-46.212 33.51 1.035)scale(25.2966)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="to7kn6bnn"/><stop offset="1" class="cvn-6ybtn"/></radialGradient><radialGradient id="iWvFWnM" cx="0" cy="0" r="1" gradientTransform="matrix(-5.73026 0 0 -.81528 22.608 16.62)" gradientUnits="userSpaceOnUse"><stop class="d77sr4b-b"/><stop offset="1" class="i61yhl-1u"/></radialGradient><radialGradient id="i7UDhUS" cx="0" cy="0" r="1" gradientTransform="rotate(134.039 5.255 11.41)scale(3.40442)" gradientUnits="userSpaceOnUse"><stop class="gzwdfjydy"/><stop offset="1" class="sb8wjubjk"/></radialGradient><radialGradient id="iDb5Jod" cx="0" cy="0" r="1" gradientTransform="rotate(139.399 5.427 10.827)scale(2.88111)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="yrrl0sboi"/><stop offset="1" class="lb3ip72ql"/></radialGradient><filter id="inKIueb" width="11.958" height="13.984" x="11.542" y="6.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13525" stdDeviation=".75"/></filter><filter id="iJBgigc" width="2.6" height="9.995" x="15.029" y="7.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".425"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.227451 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13525"/></filter><filter id="iWKQ2gc" width="28.8" height="28.8" x="1.6" y="1.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.254902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13525"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13525" result="effect2_innerShadow_18_13525"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:three-oclock" /></template>
<style>
.a5awa9dpy {
  d: path("M30 16.011c0 7.732-6.268 14-14 14s-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14");
}

.ain1pzbin {
  d: path("M18.02 16.022a1.989 1.989 0 1 1-3.978 0a1.989 1.989 0 0 1 3.978 0");
}

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

.d77sr4b-b {
  stop-color: var(--svg-color--50375f, #50375F);
}

.edywn_bhv {
  fill-rule: evenodd;
  d: path("M16 27.011c6.075 0 11-4.925 11-11s-4.925-11-11-11s-11 4.925-11 11s4.925 11 11 11m0 3c7.732 0 14-6.268 14-14s-6.268-14-14-14s-14 6.268-14 14s6.268 14 14 14");
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

.m9p8-w07t {
  fill-rule: evenodd;
  d: path("M16.029 7.027a1 1 0 0 1 1 1v7.996a1 1 0 1 1-2 0V8.027a1 1 0 0 1 1-1");
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

.y1t11ub3k {
  fill-rule: evenodd;
  d: path("M23 16.011a1 1 0 0 1-1 1h-5.967a1 1 0 0 1 0-2H22a1 1 0 0 1 1 1");
}

.yrrl0sboi {
  stop-color: var(--svg-color--776f7f, #776F7F);
  stop-opacity: 0;
}

.zl0yx4b_i {
  stop-color: var(--svg-color--2c3a65, #2C3A65);
}

.zv98mnbqa {
  fill: var(--svg-color--c7c3ca, #C7C3CA);
  d: path("M15.029 8.027a1 1 0 0 1 1 1v6.275c.295.17.542.416.715.71H21a1 1 0 0 1 0 2h-4.243a1.988 1.988 0 1 1-2.728-2.708V9.027a1 1 0 0 1 1-1");
}

</style>
