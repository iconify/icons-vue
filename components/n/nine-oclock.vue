<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#irUTLAd)" class="vs2pi1dju"/><g filter="url(#iuEDUPd)"><path class="e2gs_ys-i"/></g><g filter="url(#iTyVoVd)"><path fill="url(#iQeaxBb)" clip-rule="evenodd" class="qjq54lbqm"/></g><path fill="url(#i8zqYbd)" clip-rule="evenodd" class="nnpa1i6xx"/><path fill="url(#iFbPYcd)" clip-rule="evenodd" class="nnpa1i6xx"/><path fill="url(#iI9bDQb)" clip-rule="evenodd" class="nnpa1i6xx"/><path fill="url(#isBCp1b)" clip-rule="evenodd" class="nnpa1i6xx"/><g filter="url(#inUBrac)"><path fill="url(#ik9OWUd)" clip-rule="evenodd" class="kd5oq-b2e"/></g><path fill="url(#iQwzr4c)" class="x2-4v00lt"/><path fill="url(#iowFzBP)" class="x2-4v00lt"/><defs><linearGradient id="iQeaxBb" x1="16.06" x2="16.06" y1="7.016" y2="17.011" gradientUnits="userSpaceOnUse"><stop class="wdxszo23j"/><stop offset="1" class="bcrad1bcg"/></linearGradient><linearGradient id="i8zqYbd" x1="9.064" x2="14.875" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop class="vjrcszb_p"/><stop offset="1" class="zl0yx4b_i"/></linearGradient><linearGradient id="iFbPYcd" x1="12.094" x2="12.094" y1="17" y2="16" gradientUnits="userSpaceOnUse"><stop class="my1z1hkvz"/><stop offset="1" class="y_kzz0mys"/></linearGradient><linearGradient id="isBCp1b" x1="9.064" x2="9.782" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop class="bqasmib2b"/><stop offset="1" class="boh6xxb-j"/></linearGradient><linearGradient id="ik9OWUd" x1="24.542" x2="4.315" y1="4.013" y2="28.534" gradientUnits="userSpaceOnUse"><stop class="mttz6pbyd"/><stop offset="1" class="olhrobbtj"/></linearGradient><radialGradient id="irUTLAd" cx="0" cy="0" r="1" gradientTransform="rotate(-46.212 33.512 .993)scale(25.2966)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="to7kn6bnn"/><stop offset="1" class="cvn-6ybtn"/></radialGradient><radialGradient id="iI9bDQb" cx="0" cy="0" r="1" gradientTransform="matrix(5.73026 0 0 .81528 9.456 15.39)" gradientUnits="userSpaceOnUse"><stop class="d77sr4b-b"/><stop offset="1" class="i61yhl-1u"/></radialGradient><radialGradient id="iQwzr4c" cx="0" cy="0" r="1" gradientTransform="rotate(134.039 5.273 11.411)scale(3.40442)" gradientUnits="userSpaceOnUse"><stop class="gzwdfjydy"/><stop offset="1" class="sb8wjubjk"/></radialGradient><radialGradient id="iowFzBP" cx="0" cy="0" r="1" gradientTransform="rotate(139.399 5.445 10.827)scale(2.88111)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="yrrl0sboi"/><stop offset="1" class="lb3ip72ql"/></radialGradient><filter id="iuEDUPd" width="11.987" height="13.984" x="6.564" y="6.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13597" stdDeviation=".75"/></filter><filter id="iTyVoVd" width="2.6" height="9.995" x="15.06" y="7.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".425"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.227451 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13597"/></filter><filter id="inUBrac" width="28.8" height="28.8" x="1.631" y="1.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.254902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13597"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13597" result="effect2_innerShadow_18_13597"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:nine-oclock" /></template>
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

.e2gs_ys-i {
  fill: var(--svg-color--c1bec5, #C1BEC5);
  d: path("M15.06 8.016a1 1 0 0 1 1 1v6.274A1.988 1.988 0 1 1 13.336 18H9.064a1 1 0 1 1 0-2h4.285a2 2 0 0 1 .711-.707V9.016a1 1 0 0 1 1-1");
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

.kd5oq-b2e {
  fill-rule: evenodd;
  d: path("M16.031 27c6.075 0 11-4.925 11-11s-4.925-11-11-11s-11 4.925-11 11s4.925 11 11 11m0 3c7.732 0 14-6.268 14-14s-6.268-14-14-14s-14 6.268-14 14s6.268 14 14 14");
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

.nnpa1i6xx {
  fill-rule: evenodd;
  d: path("M9.064 16a1 1 0 0 1 1-1h5.967a1 1 0 1 1 0 2h-5.967a1 1 0 0 1-1-1");
}

.olhrobbtj {
  stop-color: var(--svg-color--706c74, #706C74);
}

.qjq54lbqm {
  fill-rule: evenodd;
  d: path("M16.06 7.016a1 1 0 0 1 1 1v7.995a1 1 0 0 1-2 0V8.016a1 1 0 0 1 1-1");
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

.vs2pi1dju {
  d: path("M30.031 16c0 7.732-6.268 14-14 14s-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14");
}

.wdxszo23j {
  stop-color: var(--svg-color--f83f4c, #F83F4C);
}

.x2-4v00lt {
  d: path("M18.051 16.011a1.989 1.989 0 1 1-3.977 0a1.989 1.989 0 0 1 3.977 0");
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
