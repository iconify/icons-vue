<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iwUcNTd)" class="sych83haw"/><g filter="url(#iv2rGHe)"><path clip-rule="evenodd" class="mcvqpwe9b"/></g><g clip-rule="evenodd" filter="url(#i4XfhAM)" class="d2kvgvbvc"><path fill="url(#iUmVEsn)" class="ic6_i2u6i"/><path fill="url(#iW3WMdc)" class="ic6_i2u6i"/></g><path fill="url(#ivTQF3c)" clip-rule="evenodd" class="ahknxbhqy"/><path fill="url(#irTtyCd)" clip-rule="evenodd" class="ahknxbhqy"/><path fill="url(#iQLqw6b)" clip-rule="evenodd" class="ahknxbhqy"/><path fill="url(#iQiGdLe)" clip-rule="evenodd" class="ahknxbhqy"/><g filter="url(#is3PZKb)"><path fill="url(#i9kn7Xc)" clip-rule="evenodd" class="u6qixrbpx"/></g><path fill="url(#i7L1bxc)" class="m2ojg1cse"/><path fill="url(#i0GtlhX)" class="m2ojg1cse"/><defs><radialGradient id="iwUcNTd" cx="0" cy="0" r="1" gradientTransform="rotate(-46.212 33.64 1.09)scale(25.2966)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="to7kn6bnn"/><stop offset="1" class="cvn-6ybtn"/></radialGradient><radialGradient id="iW3WMdc" cx="0" cy="0" r="1" gradientTransform="rotate(146.437 5.402 11.367)scale(1.95012 1.33455)" gradientUnits="userSpaceOnUse"><stop offset=".293" class="h_yu15b7s"/><stop offset="1" class="e81falbog"/></radialGradient><radialGradient id="iQLqw6b" cx="0" cy="0" r="1" gradientTransform="rotate(120 6.806 11.093)scale(5.73026 .81528)" gradientUnits="userSpaceOnUse"><stop class="d77sr4b-b"/><stop offset="1" class="i61yhl-1u"/></radialGradient><radialGradient id="i7L1bxc" cx="0" cy="0" r="1" gradientTransform="rotate(134.039 5.232 11.466)scale(3.40442)" gradientUnits="userSpaceOnUse"><stop class="gzwdfjydy"/><stop offset="1" class="sb8wjubjk"/></radialGradient><radialGradient id="i0GtlhX" cx="0" cy="0" r="1" gradientTransform="rotate(139.399 5.406 10.883)scale(2.88111)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="yrrl0sboi"/><stop offset="1" class="lb3ip72ql"/></radialGradient><linearGradient id="iUmVEsn" x1="16.029" x2="16.029" y1="15.134" y2="25.129" gradientUnits="userSpaceOnUse"><stop class="wdxszo23j"/><stop offset="1" class="bcrad1bcg"/></linearGradient><linearGradient id="ivTQF3c" x1="19.484" x2="16.578" y1="10.1" y2="15.133" gradientUnits="userSpaceOnUse"><stop class="vjrcszb_p"/><stop offset="1" class="zl0yx4b_i"/></linearGradient><linearGradient id="irTtyCd" x1="17.102" x2="17.968" y1="12.225" y2="12.725" gradientUnits="userSpaceOnUse"><stop class="my1z1hkvz"/><stop offset="1" class="y_kzz0mys"/></linearGradient><linearGradient id="iQiGdLe" x1="19.484" x2="19.125" y1="10.1" y2="10.722" gradientUnits="userSpaceOnUse"><stop class="bqasmib2b"/><stop offset="1" class="boh6xxb-j"/></linearGradient><linearGradient id="i9kn7Xc" x1="24.511" x2="4.284" y1="4.136" y2="28.656" gradientUnits="userSpaceOnUse"><stop class="mttz6pbyd"/><stop offset="1" class="olhrobbtj"/></linearGradient><filter id="iv2rGHe" width="8.941" height="18.163" x="11.542" y="8.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13507" stdDeviation=".75"/></filter><filter id="i4XfhAM" width="2.6" height="9.995" x="15.029" y="15.134" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".425"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.227451 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13507"/></filter><filter id="is3PZKb" width="28.8" height="28.8" x="1.6" y="1.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.254902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13507"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13507" result="effect2_innerShadow_18_13507"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:one-thirty" /></template>
<style>
.ahknxbhqy {
  fill-rule: evenodd;
  d: path("M19.484 10.1a1 1 0 0 1 .366 1.366l-2.984 5.168a1 1 0 0 1-1.732-1l2.984-5.168a1 1 0 0 1 1.366-.366");
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

.ic6_i2u6i {
  d: path("M16.029 15.134a1 1 0 0 1 1 1v7.995a1 1 0 1 1-2 0v-7.995a1 1 0 0 1 1-1");
}

.lb3ip72ql {
  stop-color: var(--svg-color--776f7f, #776F7F);
}

.m2ojg1cse {
  d: path("M18.02 16.134a1.989 1.989 0 1 1-3.978 0a1.989 1.989 0 0 1 3.978 0");
}

.mcvqpwe9b {
  fill: var(--svg-color--c3c0c7, #C3C0C7);
  fill-rule: evenodd;
  d: path("M18.484 10.1a1 1 0 0 1 .366 1.366l-2.109 3.652a1.99 1.99 0 0 1-.712 2.737v6.274a1 1 0 1 1-2 0v-6.277a1.988 1.988 0 0 1 .964-3.706l2.125-3.68a1 1 0 0 1 1.366-.366");
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

.sych83haw {
  d: path("M30 16.123c0 7.732-6.268 14-14 14s-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14");
}

.to7kn6bnn {
  stop-color: var(--svg-color--dddadf, #DDDADF);
}

.u6qixrbpx {
  fill-rule: evenodd;
  d: path("M16 27.123c6.075 0 11-4.925 11-11s-4.925-11-11-11s-11 4.925-11 11s4.925 11 11 11m0 3c7.732 0 14-6.268 14-14s-6.268-14-14-14s-14 6.268-14 14s6.268 14 14 14");
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
