<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ivo7YDc)" class="jl81vn0ac"/><g filter="url(#iHmLeQc)"><path class="pt6c83l5b"/></g><g filter="url(#ilzbNke)"><path fill="url(#icla2vd)" clip-rule="evenodd" class="a_e0mdb7b"/></g><path fill="url(#iEcaAbP)" clip-rule="evenodd" class="egl2wtejy"/><path fill="url(#iM2prQe)" clip-rule="evenodd" class="egl2wtejy"/><path fill="url(#iqxLlPd)" clip-rule="evenodd" class="egl2wtejy"/><path fill="url(#iFO0zwb)" clip-rule="evenodd" class="egl2wtejy"/><g filter="url(#iGMg2Wb)"><path fill="url(#i5jGxBb)" clip-rule="evenodd" class="qdqw6ttlb"/></g><path fill="url(#iBGlP0d)" class="rc9u_5sac"/><path fill="url(#iZrX8hb)" class="rc9u_5sac"/><defs><linearGradient id="icla2vd" x1="16.029" x2="16.029" y1="7.016" y2="17.011" gradientUnits="userSpaceOnUse"><stop class="wdxszo23j"/><stop offset="1" class="bcrad1bcg"/></linearGradient><linearGradient id="iEcaAbP" x1="12.516" x2="15.422" y1="22.045" y2="17.012" gradientUnits="userSpaceOnUse"><stop class="vjrcszb_p"/><stop offset="1" class="zl0yx4b_i"/></linearGradient><linearGradient id="iM2prQe" x1="14.898" x2="14.031" y1="19.921" y2="19.421" gradientUnits="userSpaceOnUse"><stop class="my1z1hkvz"/><stop offset="1" class="y_kzz0mys"/></linearGradient><linearGradient id="iFO0zwb" x1="12.516" x2="12.875" y1="22.045" y2="21.424" gradientUnits="userSpaceOnUse"><stop class="bqasmib2b"/><stop offset="1" class="boh6xxb-j"/></linearGradient><linearGradient id="i5jGxBb" x1="24.511" x2="4.284" y1="4.013" y2="28.534" gradientUnits="userSpaceOnUse"><stop class="mttz6pbyd"/><stop offset="1" class="olhrobbtj"/></linearGradient><radialGradient id="ivo7YDc" cx="0" cy="0" r="1" gradientTransform="rotate(-46.212 33.496 1.03)scale(25.2966)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="to7kn6bnn"/><stop offset="1" class="cvn-6ybtn"/></radialGradient><radialGradient id="iqxLlPd" cx="0" cy="0" r="1" gradientTransform="matrix(2.86513 -4.96255 .70605 .40764 12.185 21.4)" gradientUnits="userSpaceOnUse"><stop class="d77sr4b-b"/><stop offset="1" class="i61yhl-1u"/></radialGradient><radialGradient id="iBGlP0d" cx="0" cy="0" r="1" gradientTransform="rotate(134.039 5.258 11.405)scale(3.40442)" gradientUnits="userSpaceOnUse"><stop class="gzwdfjydy"/><stop offset="1" class="sb8wjubjk"/></radialGradient><radialGradient id="iZrX8hb" cx="0" cy="0" r="1" gradientTransform="rotate(139.399 5.43 10.822)scale(2.88111)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="yrrl0sboi"/><stop offset="1" class="lb3ip72ql"/></radialGradient><filter id="iHmLeQc" width="9.004" height="18.163" x="9.525" y="5.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13573" stdDeviation=".75"/></filter><filter id="ilzbNke" width="2.6" height="9.995" x="15.029" y="7.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".425"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.227451 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13573"/></filter><filter id="iGMg2Wb" width="28.8" height="28.8" x="1.6" y="1.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.254902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13573"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13573" result="effect2_innerShadow_18_13573"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:seven-oclock" /></template>
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

.egl2wtejy {
  fill-rule: evenodd;
  d: path("M12.516 22.045a1 1 0 0 1-.366-1.366l2.984-5.168a1 1 0 1 1 1.732 1l-2.984 5.168a1 1 0 0 1-1.366.366");
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

.pt6c83l5b {
  fill: var(--svg-color--c6bcc0, #C6BCC0);
  d: path("M15.038 7.382a1 1 0 0 1 1 1v6.274a1.988 1.988 0 0 1-.998 3.71h-.025l-2.124 3.679a1 1 0 1 1-1.732-1l2.14-3.706a1.99 1.99 0 0 1 .739-2.68V8.382a1 1 0 0 1 1-1");
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

.yrrl0sboi {
  stop-color: var(--svg-color--776f7f, #776F7F);
  stop-opacity: 0;
}

.zl0yx4b_i {
  stop-color: var(--svg-color--2c3a65, #2C3A65);
}

</style>
