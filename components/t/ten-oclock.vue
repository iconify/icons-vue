<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ivo7YDc)" class="jl81vn0ac"/><g filter="url(#ibnEbme)"><path class="s34ztf2qh"/></g><g filter="url(#iL8jcve)"><path fill="url(#icla2vd)" clip-rule="evenodd" class="a_e0mdb7b"/></g><path fill="url(#iMzkCQe)" clip-rule="evenodd" class="px2x7q1uq"/><path fill="url(#iA6aBQe)" clip-rule="evenodd" class="px2x7q1uq"/><path fill="url(#icPriQb)" clip-rule="evenodd" class="px2x7q1uq"/><path fill="url(#iSFyLEd)" clip-rule="evenodd" class="px2x7q1uq"/><g filter="url(#ib6L5lb)"><path fill="url(#i5jGxBb)" clip-rule="evenodd" class="qdqw6ttlb"/></g><path fill="url(#iBGlP0d)" class="rc9u_5sac"/><path fill="url(#iZrX8hb)" class="rc9u_5sac"/><defs><linearGradient id="icla2vd" x1="16.029" x2="16.029" y1="7.016" y2="17.011" gradientUnits="userSpaceOnUse"><stop class="wdxszo23j"/><stop offset="1" class="bcrad1bcg"/></linearGradient><linearGradient id="iMzkCQe" x1="9.966" x2="14.999" y1="12.528" y2="15.433" gradientUnits="userSpaceOnUse"><stop class="vjrcszb_p"/><stop offset="1" class="zl0yx4b_i"/></linearGradient><linearGradient id="iA6aBQe" x1="12.09" x2="12.59" y1="14.909" y2="14.043" gradientUnits="userSpaceOnUse"><stop class="my1z1hkvz"/><stop offset="1" class="y_kzz0mys"/></linearGradient><linearGradient id="iSFyLEd" x1="9.966" x2="10.588" y1="12.528" y2="12.886" gradientUnits="userSpaceOnUse"><stop class="bqasmib2b"/><stop offset="1" class="boh6xxb-j"/></linearGradient><linearGradient id="i5jGxBb" x1="24.511" x2="4.284" y1="4.013" y2="28.534" gradientUnits="userSpaceOnUse"><stop class="mttz6pbyd"/><stop offset="1" class="olhrobbtj"/></linearGradient><radialGradient id="ivo7YDc" cx="0" cy="0" r="1" gradientTransform="rotate(-46.212 33.496 1.03)scale(25.2966)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="to7kn6bnn"/><stop offset="1" class="cvn-6ybtn"/></radialGradient><radialGradient id="icPriQb" cx="0" cy="0" r="1" gradientTransform="rotate(30 -17.453 25.898)scale(5.73026 .81528)" gradientUnits="userSpaceOnUse"><stop class="d77sr4b-b"/><stop offset="1" class="i61yhl-1u"/></radialGradient><radialGradient id="iBGlP0d" cx="0" cy="0" r="1" gradientTransform="rotate(134.039 5.258 11.405)scale(3.40442)" gradientUnits="userSpaceOnUse"><stop class="gzwdfjydy"/><stop offset="1" class="sb8wjubjk"/></radialGradient><radialGradient id="iZrX8hb" cx="0" cy="0" r="1" gradientTransform="rotate(139.399 5.43 10.822)scale(2.88111)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="yrrl0sboi"/><stop offset="1" class="lb3ip72ql"/></radialGradient><filter id="ibnEbme" width="11.188" height="13.984" x="7.341" y="6.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13609" stdDeviation=".75"/></filter><filter id="iL8jcve" width="2.6" height="9.995" x="15.029" y="7.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".425"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.227451 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13609"/></filter><filter id="ib6L5lb" width="28.8" height="28.8" x="1.6" y="1.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.254902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13609"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13609" result="effect2_innerShadow_18_13609"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ten-oclock" /></template>
<style>
.a_e0mdb7b {
  fill-rule: evenodd;
  d: path("M16.029 7.016a1 1 0 0 1 1 1v7.995a1 1 0 0 1-2 0V8.016a1 1 0 0 1 1-1");
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

.olhrobbtj {
  stop-color: var(--svg-color--706c74, #706C74);
}

.px2x7q1uq {
  fill-rule: evenodd;
  d: path("M9.966 12.528a1 1 0 0 1 1.366-.366l5.168 2.983a1 1 0 1 1-1 1.732l-5.168-2.983a1 1 0 0 1-.366-1.366");
}

.qdqw6ttlb {
  fill-rule: evenodd;
  d: path("M16 27c6.075 0 11-4.925 11-11S22.075 5 16 5S5 9.925 5 16s4.925 11 11 11m0 3c7.732 0 14-6.268 14-14S23.732 2 16 2S2 8.268 2 16s6.268 14 14 14");
}

.rc9u_5sac {
  d: path("M18.02 16.011a1.989 1.989 0 1 1-3.978 0a1.989 1.989 0 0 1 3.978 0");
}

.s34ztf2qh {
  fill: var(--svg-color--c2bfc6, #C2BFC6);
  d: path("M15.038 7.531a1 1 0 0 1 1 1v6.275a1.988 1.988 0 1 1-2.987 1.745l-3.71-2.142a1 1 0 1 1 1-1.732l3.694 2.133l.003-.001V8.53a1 1 0 0 1 1-1");
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
