<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iSOwuhd)" class="zyxx_7q9r"/><path fill="url(#iWktC4n)" class="zyxx_7q9r"/><path fill="url(#ih1um3d)" class="zyxx_7q9r"/><path fill="url(#iQ7q13b)" class="yyjzyu_pg"/><path fill="url(#ioomZZv)" class="yyjzyu_pg"/><g filter="url(#i3wKmtc)"><path fill="url(#i522xkb)" class="htrkmab-s"/></g><path class="l8baqtb9p"/><path fill="url(#iWFqGtc)" class="o7ip80c6r"/><g filter="url(#ipjsqKe)"><path fill="url(#i38CRlb)" class="e9c4cxb1o"/></g><path fill="url(#iB35Vce)" class="q6tfqhbeo"/><path fill="url(#imJA3ee)" class="q6tfqhbeo"/><g filter="url(#iiQfvFb)"><path fill="url(#iYO1dAb)" class="vdzls1fpq"/></g><defs><linearGradient id="iSOwuhd" x1="27.807" x2="26.404" y1="13.906" y2="19.969" gradientUnits="userSpaceOnUse"><stop class="mpwbs5b3u"/><stop offset="1" class="h6ow0ob8b"/></linearGradient><linearGradient id="iWktC4n" x1="25.291" x2="25.603" y1="16.564" y2="16.755" gradientUnits="userSpaceOnUse"><stop offset=".168" class="b3vrevitu"/><stop offset="1" class="uk5521bvw"/></linearGradient><linearGradient id="ih1um3d" x1="27.082" x2="25.915" y1="20.367" y2="16.544" gradientUnits="userSpaceOnUse"><stop offset=".168" class="b3vrevitu"/><stop offset="1" class="uk5521bvw"/></linearGradient><linearGradient id="iQ7q13b" x1="18.913" x2="16.96" y1="14.773" y2="18.62" gradientUnits="userSpaceOnUse"><stop class="m0vgjjb4r"/><stop offset=".531" class="sm6j6gb4q"/></linearGradient><linearGradient id="ioomZZv" x1="14.951" x2="16.139" y1="12.836" y2="13.656" gradientUnits="userSpaceOnUse"><stop offset=".199" class="vzyojdbsa"/><stop offset="1" class="cgb-a_b5m"/></linearGradient><linearGradient id="i522xkb" x1="13.107" x2="15.982" y1="16.719" y2="13.781" gradientUnits="userSpaceOnUse"><stop class="ygvhm3b_d"/><stop offset="1" class="wgtr5pm-b"/></linearGradient><linearGradient id="iWFqGtc" x1="20.17" x2="19.545" y1="16.313" y2="17.375" gradientUnits="userSpaceOnUse"><stop class="idnrekbmg"/><stop offset="1" class="air9cobqh"/></linearGradient><linearGradient id="i38CRlb" x1="30" x2="3" y1="21.406" y2="16.906" gradientUnits="userSpaceOnUse"><stop class="s4mou0b5s"/><stop offset="1" class="f8-s6pb5c"/></linearGradient><linearGradient id="iB35Vce" x1="30" x2="23.251" y1="21.406" y2="20.473" gradientUnits="userSpaceOnUse"><stop class="vd5zkrbuf"/><stop offset="1" class="d9fbl1ssf"/></linearGradient><linearGradient id="imJA3ee" x1="3.022" x2="4.148" y1="17.704" y2="17.024" gradientUnits="userSpaceOnUse"><stop class="sv-wggefa"/><stop offset="1" class="d07q6ebto"/></linearGradient><linearGradient id="iYO1dAb" x1="18.843" x2="18.843" y1="30" y2="24.216" gradientUnits="userSpaceOnUse"><stop class="mtztso4yr"/><stop offset="1" class="n8pkkpbds"/></linearGradient><filter id="i3wKmtc" width="6.385" height="4.21" x="10.46" y="13.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.027451 0 0 0 0 0.576471 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12198"/></filter><filter id="ipjsqKe" width="28.603" height="12.75" x="1.997" y="14.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.211765 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12198"/></filter><filter id="iiQfvFb" width="28.6" height="7.756" x="1.4" y="22.843" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.67451 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12198"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_12198" result="effect2_innerShadow_18_12198"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:speedboat" /></template>
<style>
.air9cobqh {
  stop-color: var(--svg-color--3ca8ce, #3CA8CE);
  stop-opacity: 0;
}

.b3vrevitu {
  stop-color: var(--svg-color--f97342, #F97342);
}

.cgb-a_b5m {
  stop-color: var(--svg-color--bcbbbe, #BCBBBE);
  stop-opacity: 0;
}

.d07q6ebto {
  stop-color: var(--svg-color--9693a9, #9693A9);
  stop-opacity: 0;
}

.d9fbl1ssf {
  stop-color: var(--svg-color--ece7f7, #ECE7F7);
}

.e9c4cxb1o {
  d: path("M30 21.04c-.15-.98-.872-1.763-1.824-1.912L3.38 15.059l-.027-.003a1 1 0 0 0-.164-.015c-.721 0-1.24.3-1.189 1c.01.25.07.48.2.7l1.51 2.514c2.89 4.876 7.617 7.786 12.658 7.786h9.423c2.061 0 3.784-1.709 4.199-4.002l.01.002z");
}

.f8-s6pb5c {
  stop-color: var(--svg-color--ff6359, #FF6359);
}

.ft5dv1b6b {
  fill: none;
}

.h6ow0ob8b {
  stop-color: var(--svg-color--ff874d, #FF874D);
}

.htrkmab-s {
  d: path("m14.46 13.455l-3.5 2.99l3.56.63l2.16-1.84c.27-.32.2-.81-.15-1.04l-.65-.42l-.94-.61h-.01c-.16.07-.33.17-.47.29");
}

.idnrekbmg {
  stop-color: var(--svg-color--3ca8ce, #3CA8CE);
}

.l8baqtb9p {
  fill: var(--svg-color--66f2ff, #66F2FF);
  d: path("m17.66 15.805l-1.77 1.51l5.84 1.03l.01-.13c.04-.39-.14-.76-.46-.97l-2.33-1.52a1 1 0 0 0-.49-.17c-.27-.03-.57.06-.8.25");
}

.m0vgjjb4r {
  stop-color: var(--svg-color--f2eff4, #F2EFF4);
}

.mpwbs5b3u {
  stop-color: var(--svg-color--ff894e, #FF894E);
}

.mtztso4yr {
  stop-color: var(--svg-color--51adff, #51ADFF);
}

.n8pkkpbds {
  stop-color: var(--svg-color--529cf8, #529CF8);
}

.o7ip80c6r {
  d: path("m17.66 15.805l-1.77 1.51l5.84 1.03l.01-.13c.04-.39-.14-.76-.46-.97l-2.33-1.52a1 1 0 0 0-.49-.17c-.27-.03-.57.06-.8.25");
}

.q6tfqhbeo {
  d: path("m2.2 16.74l1.02 1.701l26.78 4.6v-2l-28-5c.01.25.07.48.2.7");
}

.s4mou0b5s {
  stop-color: var(--svg-color--f95, #F95);
}

.sm6j6gb4q {
  stop-color: var(--svg-color--baadb5, #BAADB5);
}

.sv-wggefa {
  stop-color: var(--svg-color--9693a9, #9693A9);
}

.uk5521bvw {
  stop-color: var(--svg-color--f97342, #F97342);
  stop-opacity: 0;
}

.vd5zkrbuf {
  stop-color: var(--svg-color--dbd6e8, #DBD6E8);
}

.vdzls1fpq {
  d: path("M30 23c-1.518 0-1.776.97-3.09.97c-1.75 0-2.113-1.126-3.873-1.126c-1.749 0-2.229 1.126-3.707 1.126c-1.197 0-1.63-1.126-3.38-1.126s-2.464 1.126-3.802 1.126c-1.337 0-1.77-1.126-3.52-1.126S6.636 23.97 4.897 23.97C3.147 23.97 3.23 23 2 23v7h27.99z");
}

.vzyojdbsa {
  stop-color: var(--svg-color--bcbbbe, #BCBBBE);
}

.wgtr5pm-b {
  stop-color: var(--svg-color--4ecaff, #4ECAFF);
}

.ygvhm3b_d {
  stop-color: var(--svg-color--67f0ff, #67F0FF);
}

.yyjzyu_pg {
  d: path("m14.612 13.371l-3.582 3.12l11.994 2.17l.02-.175c.07-.796-.282-1.56-.916-1.984l-4.92-3.306a2.04 2.04 0 0 0-.976-.352a2.18 2.18 0 0 0-1.62.527");
}

.zyxx_7q9r {
  d: path("M27.28 13.909c-.2-.02-.39.08-.5.25l-3.05 5.11l3.55.7l1.77-5.25a.523.523 0 0 0-.45-.69z");
}

</style>
