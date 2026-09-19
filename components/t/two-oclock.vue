<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iVOQgeb)" class="f-s72rb4r"/><g filter="url(#iDsr6Sb)"><path class="ypj_kbbat"/></g><g filter="url(#iFTuRRD)"><path fill="url(#iqUPADA)" clip-rule="evenodd" class="xfz8_51as"/></g><path fill="url(#iS6Ta0d)" clip-rule="evenodd" class="meflfaczj"/><path fill="url(#it7R64d)" clip-rule="evenodd" class="meflfaczj"/><path fill="url(#iXSzXhb)" clip-rule="evenodd" class="meflfaczj"/><path fill="url(#ito5UTc)" clip-rule="evenodd" class="meflfaczj"/><g filter="url(#i1ElPGd)"><path fill="url(#i7z7V6d)" clip-rule="evenodd" class="h5kstjiuq"/></g><path fill="url(#irBiZiF)" class="m57uwqtuk"/><path fill="url(#iL8CAAe)" class="m57uwqtuk"/><defs><linearGradient id="iqUPADA" x1="16.029" x2="16.029" y1="7.217" y2="17.212" gradientUnits="userSpaceOnUse"><stop class="wdxszo23j"/><stop offset="1" class="bcrad1bcg"/></linearGradient><linearGradient id="iS6Ta0d" x1="22.034" x2="17.001" y1="12.729" y2="15.634" gradientUnits="userSpaceOnUse"><stop class="vjrcszb_p"/><stop offset="1" class="zl0yx4b_i"/></linearGradient><linearGradient id="it7R64d" x1="18.91" x2="19.41" y1="13.378" y2="14.244" gradientUnits="userSpaceOnUse"><stop class="my1z1hkvz"/><stop offset="1" class="y_kzz0mys"/></linearGradient><linearGradient id="ito5UTc" x1="22.034" x2="21.412" y1="12.729" y2="13.088" gradientUnits="userSpaceOnUse"><stop class="bqasmib2b"/><stop offset="1" class="boh6xxb-j"/></linearGradient><linearGradient id="i7z7V6d" x1="24.511" x2="4.284" y1="4.214" y2="28.735" gradientUnits="userSpaceOnUse"><stop class="mttz6pbyd"/><stop offset="1" class="olhrobbtj"/></linearGradient><radialGradient id="iVOQgeb" cx="0" cy="0" r="1" gradientTransform="rotate(-46.212 33.732 1.13)scale(25.2966)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="to7kn6bnn"/><stop offset="1" class="cvn-6ybtn"/></radialGradient><radialGradient id="iXSzXhb" cx="0" cy="0" r="1" gradientTransform="rotate(150 9.197 9.674)scale(5.73026 .81528)" gradientUnits="userSpaceOnUse"><stop class="d77sr4b-b"/><stop offset="1" class="i61yhl-1u"/></radialGradient><radialGradient id="irBiZiF" cx="0" cy="0" r="1" gradientTransform="rotate(134.039 5.215 11.505)scale(3.40442)" gradientUnits="userSpaceOnUse"><stop class="gzwdfjydy"/><stop offset="1" class="sb8wjubjk"/></radialGradient><radialGradient id="iL8CAAe" cx="0" cy="0" r="1" gradientTransform="rotate(139.399 5.392 10.922)scale(2.88111)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="yrrl0sboi"/><stop offset="1" class="lb3ip72ql"/></radialGradient><filter id="iDsr6Sb" width="11.126" height="13.984" x="11.542" y="6.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13513" stdDeviation=".75"/></filter><filter id="iFTuRRD" width="2.6" height="9.995" x="15.029" y="7.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".425"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.227451 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13513"/></filter><filter id="i1ElPGd" width="28.8" height="28.8" x="1.6" y="1.801" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.254902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13513"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13513" result="effect2_innerShadow_18_13513"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:two-oclock" /></template>
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

.d77sr4b-b {
  stop-color: var(--svg-color--50375f, #50375F);
}

.f-s72rb4r {
  d: path("M30 16.2c0 7.733-6.268 14-14 14s-14-6.267-14-14c0-7.731 6.268-14 14-14s14 6.269 14 14");
}

.ft5dv1b6b {
  fill: none;
}

.gzwdfjydy {
  stop-color: var(--svg-color--c9c6cc, #C9C6CC);
}

.h5kstjiuq {
  fill-rule: evenodd;
  d: path("M16 27.2c6.075 0 11-4.924 11-11c0-6.074-4.925-11-11-11s-11 4.926-11 11c0 6.076 4.925 11 11 11m0 3c7.732 0 14-6.267 14-14c0-7.731-6.268-14-14-14S2 8.47 2 16.2c0 7.733 6.268 14 14 14");
}

.i61yhl-1u {
  stop-color: var(--svg-color--50375f, #50375F);
  stop-opacity: 0;
}

.lb3ip72ql {
  stop-color: var(--svg-color--776f7f, #776F7F);
}

.m57uwqtuk {
  d: path("M18.02 16.212a1.989 1.989 0 1 1-3.978 0a1.989 1.989 0 0 1 3.978 0");
}

.meflfaczj {
  fill-rule: evenodd;
  d: path("M22.034 12.729a1 1 0 0 1-.366 1.366L16.5 17.078a1 1 0 1 1-1-1.732l5.168-2.983a1 1 0 0 1 1.366.366");
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

.xfz8_51as {
  fill-rule: evenodd;
  d: path("M16.029 7.217a1 1 0 0 1 1 1v7.995a1 1 0 1 1-2 0V8.217a1 1 0 0 1 1-1");
}

.y_kzz0mys {
  stop-color: var(--svg-color--2e2840, #2E2840);
  stop-opacity: 0;
}

.ypj_kbbat {
  fill: var(--svg-color--c5c1c8, #C5C1C8);
  d: path("M15.029 8.217a1 1 0 0 1 1 1v6.247l3.639-2.101a1 1 0 1 1 1 1.732L17.02 17.2v.011a1.989 1.989 0 1 1-2.991-1.718V9.217a1 1 0 0 1 1-1");
}

.yrrl0sboi {
  stop-color: var(--svg-color--776f7f, #776F7F);
  stop-opacity: 0;
}

.zl0yx4b_i {
  stop-color: var(--svg-color--2c3a65, #2C3A65);
}

</style>
