<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#in1Xgzc)"><path fill="url(#icp2MKd)" class="q1961dqbh"/></g><path fill="url(#iPyuhgG)" class="kl2tdo39x"/><path fill="url(#iWPkxKd)" class="kl2tdo39x"/><path fill="url(#i8fnUze)" class="kl2tdo39x"/><path fill="url(#ihKiPwe)" class="kl2tdo39x"/><path fill="url(#iwu2ARc)" class="sb_rs7b6j"/><g filter="url(#iMl4jzc)"><rect fill="url(#iue5SMe)" class="pns233bky"/><rect fill="url(#ilfjQhe)" class="pns233bky"/><rect fill="url(#iRdVmUU)" class="pns233bky"/></g><g filter="url(#i6NZegQ)"><path fill="url(#i1BS02b)" class="qahcvfblz"/><path fill="url(#iYRay3b)" class="qahcvfblz"/><path fill="url(#ip4fuCe)" class="qahcvfblz"/></g><g filter="url(#iactdid)"><path fill="url(#iWH9Ard)" class="qsss1ccwo"/></g><g filter="url(#iqi07gb)"><path stroke="url(#iXXdT7d)" class="pz0gl_b8t"/></g><defs><linearGradient id="icp2MKd" x1="11.063" x2="23.813" y1="20.75" y2="20.75" gradientUnits="userSpaceOnUse"><stop class="i526i17fp"/><stop offset="1" class="ojf-8ms5x"/></linearGradient><linearGradient id="iPyuhgG" x1="5.313" x2="25.875" y1="27.5" y2="27.5" gradientUnits="userSpaceOnUse"><stop class="mzc2ifbqd"/><stop offset=".173" class="l8wd51ter"/><stop offset="1" class="isr3znbow"/></linearGradient><linearGradient id="iWPkxKd" x1="27" x2="25.25" y1="27.5" y2="27.5" gradientUnits="userSpaceOnUse"><stop class="en_iz8btw"/><stop offset="1" class="qwcghccth"/></linearGradient><linearGradient id="i8fnUze" x1="16" x2="16" y1="30" y2="28.875" gradientUnits="userSpaceOnUse"><stop class="t9toafbnn"/><stop offset="1" class="osds2bbfe"/></linearGradient><linearGradient id="ihKiPwe" x1="16" x2="16" y1="24" y2="25.938" gradientUnits="userSpaceOnUse"><stop class="wk5c8wbec"/><stop offset="1" class="n7e28g3bj"/></linearGradient><linearGradient id="iwu2ARc" x1="18.375" x2="18.563" y1="12.313" y2="15.875" gradientUnits="userSpaceOnUse"><stop class="ls12e09pb"/><stop offset="1" class="wtr_zoshd"/></linearGradient><linearGradient id="iue5SMe" x1="15" x2="17" y1="5" y2="5" gradientUnits="userSpaceOnUse"><stop class="iqg_59b5d"/><stop offset="1" class="l3sdfhkvf"/></linearGradient><linearGradient id="ilfjQhe" x1="16" x2="16" y1="2" y2="3.069" gradientUnits="userSpaceOnUse"><stop class="srw7fgalb"/><stop offset="1" class="p_naj7jwg"/></linearGradient><linearGradient id="iRdVmUU" x1="16.624" x2="16.624" y1="8.318" y2="7.03" gradientUnits="userSpaceOnUse"><stop class="w5jnidcbc"/><stop offset="1" class="w01b-cn8t"/></linearGradient><linearGradient id="i1BS02b" x1="22.483" x2="24.156" y1="6.814" y2="8.488" gradientUnits="userSpaceOnUse"><stop class="iqg_59b5d"/><stop offset="1" class="l3sdfhkvf"/></linearGradient><linearGradient id="iYRay3b" x1="26.266" x2="25.054" y1="5.456" y2="6.669" gradientUnits="userSpaceOnUse"><stop offset=".2" class="y10eou6cc"/><stop offset="1" class="ixheuobof"/></linearGradient><linearGradient id="ip4fuCe" x1="21.378" x2="22.269" y1="10" y2="9.077" gradientUnits="userSpaceOnUse"><stop class="de_iivb7t"/><stop offset="1" class="tjefbbc2w"/></linearGradient><linearGradient id="iWH9Ard" x1="7.672" x2="8.984" y1="8.203" y2="6.891" gradientUnits="userSpaceOnUse"><stop class="iqg_59b5d"/><stop offset="1" class="l3sdfhkvf"/></linearGradient><linearGradient id="iXXdT7d" x1="12.313" x2="26.688" y1="26.125" y2="26.125" gradientUnits="userSpaceOnUse"><stop class="ujfndr2ca"/><stop offset=".803" class="df_edgtjs"/><stop offset="1" class="ujfndr2ca"/></linearGradient><filter id="in1Xgzc" width="19.5" height="16.625" x="6.875" y="10" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.27451 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11962"/></filter><filter id="iMl4jzc" width="2.25" height="6.25" x="15" y="1.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.443137 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11962"/></filter><filter id="i6NZegQ" width="5.25" height="5.25" x="21" y="4.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.443137 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11962"/></filter><filter id="iactdid" width="5.25" height="5.25" x="6" y="4.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.443137 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11962"/></filter><filter id="iqi07gb" width="15.594" height="1.5" x="11.25" y="25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11962" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:police-car-light" /></template>
<style>
.de_iivb7t {
  stop-color: var(--svg-color--f56a34, #F56A34);
}

.df_edgtjs {
  stop-color: var(--svg-color--f2e8ff, #F2E8FF);
}

.en_iz8btw {
  stop-color: var(--svg-color--dcd5e7, #DCD5E7);
}

.ft5dv1b6b {
  fill: none;
}

.i526i17fp {
  stop-color: var(--svg-color--f8312f, #F8312F);
}

.iqg_59b5d {
  stop-color: var(--svg-color--f19e41, #F19E41);
}

.isr3znbow {
  stop-color: var(--svg-color--eee0ff, #EEE0FF);
}

.ixheuobof {
  stop-color: var(--svg-color--fff45d, #FFF45D);
  stop-opacity: 0;
}

.kl2tdo39x {
  d: path("M25.865 30H6.135C5.512 30 5 29.517 5 28.93v-2.86c0-.587.512-1.07 1.135-1.07h19.73c.623 0 1.135.483 1.135 1.07v2.86c0 .587-.502 1.07-1.135 1.07");
}

.l3sdfhkvf {
  stop-color: var(--svg-color--fff657, #FFF657);
}

.l8wd51ter {
  stop-color: var(--svg-color--a88ec7, #A88EC7);
}

.ls12e09pb {
  stop-color: var(--svg-color--fff8ff, #FFF8FF);
}

.mzc2ifbqd {
  stop-color: var(--svg-color--9186a2, #9186A2);
}

.n7e28g3bj {
  stop-color: var(--svg-color--d8cfd4, #D8CFD4);
  stop-opacity: 0;
}

.ojf-8ms5x {
  stop-color: var(--svg-color--ff5ba6, #FF5BA6);
}

.osds2bbfe {
  stop-color: var(--svg-color--cc8bff, #CC8BFF);
  stop-opacity: 0;
}

.p_naj7jwg {
  stop-color: var(--svg-color--fff053, #FFF053);
  stop-opacity: 0;
}

.pns233bky {
  width: 2px;
  height: 6px;
  x: 15px;
  y: 2px;
  rx: 1px;
}

.pz0gl_b8t {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M26.344 25.75H11.75");
}

.q1961dqbh {
  d: path("M9.864 14.87L6.875 26.624h18l-2.739-11.756a6.3 6.3 0 0 0-12.272 0");
}

.qahcvfblz {
  d: path("M24.232 5.303a1.036 1.036 0 0 1 1.465 1.465l-2.93 2.929a1.036 1.036 0 0 1-1.464-1.465z");
}

.qsss1ccwo {
  d: path("M7.768 5.303a1.036 1.036 0 0 0-1.465 1.465l2.93 2.929a1.036 1.036 0 0 0 1.464-1.465z");
}

.qwcghccth {
  stop-color: var(--svg-color--dcd5e7, #DCD5E7);
  stop-opacity: 0;
}

.sb_rs7b6j {
  d: path("M19.895 15.82c.799-.46.976-1.648.396-2.652s-1.698-1.445-2.496-.984c-.798.46-.975 1.648-.395 2.653c.58 1.004 1.697 1.445 2.495.984");
}

.srw7fgalb {
  stop-color: var(--svg-color--fff053, #FFF053);
}

.t9toafbnn {
  stop-color: var(--svg-color--cc8bff, #CC8BFF);
}

.tjefbbc2w {
  stop-color: var(--svg-color--f56a34, #F56A34);
  stop-opacity: 0;
}

.ujfndr2ca {
  stop-color: var(--svg-color--f2e8ff, #F2E8FF);
  stop-opacity: 0;
}

.w01b-cn8t {
  stop-color: var(--svg-color--ee8228, #EE8228);
  stop-opacity: 0;
}

.w5jnidcbc {
  stop-color: var(--svg-color--ee8228, #EE8228);
}

.wk5c8wbec {
  stop-color: var(--svg-color--d8cfd4, #D8CFD4);
}

.wtr_zoshd {
  stop-color: var(--svg-color--fff8ff, #FFF8FF);
  stop-opacity: 0;
}

.y10eou6cc {
  stop-color: var(--svg-color--fff45d, #FFF45D);
}

</style>
