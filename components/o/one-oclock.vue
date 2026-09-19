<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iAaZvYd)" class="buvc57-1l"/><g filter="url(#irRnX3b)"><path class="s28x9cb3z"/></g><g clip-rule="evenodd" filter="url(#iMabDJc)" class="d2kvgvbvc"><path fill="url(#imx2S2p)" class="dtrkbie2b"/><path fill="url(#icNTMLc)" class="dtrkbie2b"/></g><path fill="url(#iGj4vUI)" clip-rule="evenodd" class="kq4yfabxc"/><path fill="url(#ikYL0Fc)" clip-rule="evenodd" class="kq4yfabxc"/><path fill="url(#i1lw9Mg)" clip-rule="evenodd" class="kq4yfabxc"/><path fill="url(#iz29ltb)" clip-rule="evenodd" class="kq4yfabxc"/><g filter="url(#iKJJxcd)"><path fill="url(#iwS5Cvg)" clip-rule="evenodd" class="awg103b5o"/></g><path fill="url(#i0IjIue)" class="uq26t3x8p"/><path fill="url(#icEXOCb)" class="uq26t3x8p"/><defs><radialGradient id="iAaZvYd" cx="0" cy="0" r="1" gradientTransform="rotate(-46.212 33.56 1.1)scale(25.2966)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="to7kn6bnn"/><stop offset="1" class="cvn-6ybtn"/></radialGradient><radialGradient id="icNTMLc" cx="0" cy="0" r="1" gradientTransform="rotate(-63.8 19.85 -5.473)scale(4.04007 1.32805)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="h_yu15b7s"/><stop offset="1" class="e81falbog"/></radialGradient><radialGradient id="i1lw9Mg" cx="0" cy="0" r="1" gradientTransform="rotate(120 6.806 11.056)scale(5.73026 .81528)" gradientUnits="userSpaceOnUse"><stop class="d77sr4b-b"/><stop offset="1" class="i61yhl-1u"/></radialGradient><radialGradient id="i0IjIue" cx="0" cy="0" r="1" gradientTransform="rotate(134.039 5.228 11.431)scale(3.40442)" gradientUnits="userSpaceOnUse"><stop class="gzwdfjydy"/><stop offset="1" class="sb8wjubjk"/></radialGradient><radialGradient id="icEXOCb" cx="0" cy="0" r="1" gradientTransform="rotate(139.399 5.401 10.85)scale(2.88111)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="yrrl0sboi"/><stop offset="1" class="lb3ip72ql"/></radialGradient><linearGradient id="imx2S2p" x1="15.998" x2="15.998" y1="7.076" y2="17.071" gradientUnits="userSpaceOnUse"><stop class="wdxszo23j"/><stop offset="1" class="bcrad1bcg"/></linearGradient><linearGradient id="iGj4vUI" x1="19.452" x2="16.547" y1="10.045" y2="15.077" gradientUnits="userSpaceOnUse"><stop class="vjrcszb_p"/><stop offset="1" class="zl0yx4b_i"/></linearGradient><linearGradient id="ikYL0Fc" x1="17.071" x2="17.937" y1="12.169" y2="12.669" gradientUnits="userSpaceOnUse"><stop class="my1z1hkvz"/><stop offset="1" class="y_kzz0mys"/></linearGradient><linearGradient id="iz29ltb" x1="19.452" x2="19.094" y1="10.045" y2="10.666" gradientUnits="userSpaceOnUse"><stop class="bqasmib2b"/><stop offset="1" class="boh6xxb-j"/></linearGradient><linearGradient id="iwS5Cvg" x1="24.48" x2="4.253" y1="4.081" y2="28.601" gradientUnits="userSpaceOnUse"><stop class="mttz6pbyd"/><stop offset="1" class="olhrobbtj"/></linearGradient><filter id="irRnX3b" width="8.941" height="13.991" x="11.092" y="6.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13501" stdDeviation=".75"/></filter><filter id="iMabDJc" width="2.6" height="9.995" x="14.998" y="7.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".425"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.227451 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13501"/></filter><filter id="iKJJxcd" width="28.8" height="28.8" x="1.569" y="1.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.254902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13501"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13501" result="effect2_innerShadow_18_13501"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:one-oclock" /></template>
<style>
.awg103b5o {
  fill-rule: evenodd;
  d: path("M15.969 27.067c6.075 0 11-4.925 11-11s-4.925-11-11-11s-11 4.925-11 11s4.925 11 11 11m0 3c7.732 0 14-6.268 14-14s-6.268-14-14-14s-14 6.268-14 14s6.268 14 14 14");
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

.buvc57-1l {
  d: path("M29.969 16.067c0 7.732-6.268 14-14 14s-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14");
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

.dtrkbie2b {
  d: path("M15.998 7.076a1 1 0 0 1 1 1v7.995a1 1 0 1 1-2 0V8.076a1 1 0 0 1 1-1");
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

.kq4yfabxc {
  fill-rule: evenodd;
  d: path("M19.452 10.045a1 1 0 0 1 .366 1.366l-2.983 5.167a1 1 0 1 1-1.732-1l2.983-5.167a1 1 0 0 1 1.366-.366");
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

.s28x9cb3z {
  fill: var(--svg-color--c4c1c8, #C4C1C8);
  d: path("M14.578 7.999a1 1 0 0 1 1 1v4.22l1.089-1.885a1 1 0 1 1 1.732 1l-2.108 3.651a1.989 1.989 0 1 1-2.713-.702V8.999a1 1 0 0 1 1-1");
}

.sb8wjubjk {
  stop-color: var(--svg-color--928e95, #928E95);
}

.to7kn6bnn {
  stop-color: var(--svg-color--dddadf, #DDDADF);
}

.uq26t3x8p {
  d: path("M17.989 16.078a1.989 1.989 0 1 1-3.978 0a1.989 1.989 0 0 1 3.978 0");
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
