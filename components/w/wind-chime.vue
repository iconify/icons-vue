<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iFwoBHA)"><path fill="url(#iA2cUUb)" class="wrsxa1-lt"/><path fill="url(#iLNpXFe)" class="wrsxa1-lt"/><path fill="url(#iNBsuTb)" class="wrsxa1-lt"/></g><path clip-rule="evenodd" class="aq3kpw7xf"/><path fill="url(#i6p4v0b)" clip-rule="evenodd" class="qae7fybta"/><path fill="url(#isTTohd)" clip-rule="evenodd" class="qae7fybta"/><path fill="url(#i88dm9q)" clip-rule="evenodd" class="qae7fybta"/><g filter="url(#i3Tt1zd)" class="nctb2ac4r"><path fill="url(#i7nUxqc)" class="bca4abb6z"/><path fill="url(#iwZA4Mb)" class="bca4abb6z"/><path fill="url(#irQuueZ)" class="bca4abb6z"/></g><g filter="url(#iQZiVyq)"><path fill="url(#i7Ge5NC)" class="n9gyjf4gk"/><path fill="url(#iv1NMAb)" class="n9gyjf4gk"/></g><path class="un0_haclx"/><path class="hoyfjjbgt"/><defs><radialGradient id="iA2cUUb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.21875 0 0 -5.81876 19.812 23.5)" gradientUnits="userSpaceOnUse"><stop class="gn-eyhc7q"/><stop offset="1" class="afag147hp"/></radialGradient><radialGradient id="iNBsuTb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.21875 -.03127 .06954 -18.27657 20.969 23.406)" gradientUnits="userSpaceOnUse"><stop offset=".84" class="d9quf14eb"/><stop offset="1" class="mlh455b2t"/></radialGradient><radialGradient id="isTTohd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9 -.6775 0 16.99 1.781)" gradientUnits="userSpaceOnUse"><stop class="dp61g2bol"/><stop offset="1" class="kqbrhlmzd"/></radialGradient><radialGradient id="i88dm9q" cx="0" cy="0" r="1" gradientTransform="matrix(-.72874 0 0 -3.65625 17.219 19.875)" gradientUnits="userSpaceOnUse"><stop class="y0kt-zb2f"/><stop offset="1" class="cz9ru29br"/></radialGradient><radialGradient id="iwZA4Mb" cx="0" cy="0" r="1" gradientTransform="rotate(150.255 10.277 6.777)scale(3.52724 3.27187)" gradientUnits="userSpaceOnUse"><stop class="dubb3bc5f"/><stop offset="1" class="m92k-fbhe"/></radialGradient><radialGradient id="irQuueZ" cx="0" cy="0" r="1" gradientTransform="matrix(6.375 -4.125 2.5689 3.97013 7.688 13.625)" gradientUnits="userSpaceOnUse"><stop class="dubb3bc5f"/><stop offset="1" class="m92k-fbhe"/></radialGradient><radialGradient id="i7Ge5NC" cx="0" cy="0" r="1" gradientTransform="matrix(-2.125 1.4375 -1.57911 -2.33436 17.781 16.313)" gradientUnits="userSpaceOnUse"><stop class="we-16-o2z"/><stop offset="1" class="oayjv192q"/></radialGradient><radialGradient id="iv1NMAb" cx="0" cy="0" r="1" gradientTransform="matrix(.23999 1.17626 -1.12478 .22949 15.01 16.98)" gradientUnits="userSpaceOnUse"><stop class="t3mpidbyt"/><stop offset="1" class="vmpo1qb-s"/></radialGradient><linearGradient id="iLNpXFe" x1="17.415" x2="17.415" y1="20.46" y2="20.906" gradientUnits="userSpaceOnUse"><stop class="hpy5ptqfm"/><stop offset="1" class="ceru9acrs"/></linearGradient><linearGradient id="i6p4v0b" x1="17.813" x2="17.813" y1="22.5" y2="10" gradientUnits="userSpaceOnUse"><stop class="x7fnu5blu"/><stop offset="1" class="e7usbsb4s"/></linearGradient><linearGradient id="i7nUxqc" x1="23.688" x2="8.313" y1="7.625" y2="7.625" gradientUnits="userSpaceOnUse"><stop class="f2bbbev7d"/><stop offset="1" class="lnicg2b6c"/></linearGradient><filter id="iFwoBHA" width="8.68" height="9.26" x="13.2" y="20.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.807843 0 0 0 0 0.917647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1041"/></filter><filter id="i3Tt1zd" width="16.99" height="10.88" x="8" y="3.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.481771 0 0 0 0 0.630317 0 0 0 0 0.770833 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1041"/></filter><filter id="iQZiVyq" width="2.96" height="2.96" x="15.01" y="15.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.721569 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1041"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:wind-chime" /></template>
<style>
.afag147hp {
  stop-color: var(--svg-color--e8e0f2, #E8E0F2);
}

.aq3kpw7xf {
  fill: var(--svg-color--4999df, #4999DF);
  fill-rule: evenodd;
  d: path("M16.49 1.5a.5.5 0 0 1 .5.5v18.9a.5.5 0 0 1-1 0V2a.5.5 0 0 1 .5-.5");
}

.bca4abb6z {
  d: path("M19.55 3.54h-6.11c-3 0-5.44 2.44-5.44 5.44s2.44 5.44 5.44 5.44h6.11a5.44 5.44 0 1 0 0-10.88");
}

.ceru9acrs {
  stop-color: var(--svg-color--d3d2e1, #D3D2E1);
  stop-opacity: 0;
}

.cz9ru29br {
  stop-color: var(--svg-color--70e6ff, #70E6FF);
  stop-opacity: 0;
}

.d9quf14eb {
  stop-color: var(--svg-color--d4d0dc, #D4D0DC);
  stop-opacity: 0;
}

.dp61g2bol {
  stop-color: var(--svg-color--60c5ff, #60C5FF);
}

.dubb3bc5f {
  stop-color: var(--svg-color--cef8ff, #CEF8FF);
}

.e7usbsb4s {
  stop-color: var(--svg-color--52d6ff, #52D6FF);
  stop-opacity: 0;
}

.f2bbbev7d {
  stop-color: var(--svg-color--94cbff, #94CBFF);
}

.ft5dv1b6b {
  fill: none;
}

.gn-eyhc7q {
  stop-color: var(--svg-color--f4effc, #F4EFFC);
}

.hoyfjjbgt {
  fill: var(--svg-color--ff7578, #FF7578);
  d: path("M16.58 23.68a.67.67 0 1 0 0-1.34a.67.67 0 0 0 0 1.34m.57 2.3a.67.67 0 1 0 0-1.34a.67.67 0 0 0 0 1.34m.77 2.28a.67.67 0 1 0 0-1.34a.67.67 0 0 0 0 1.34");
}

.hpy5ptqfm {
  stop-color: var(--svg-color--d3d2e1, #D3D2E1);
}

.kqbrhlmzd {
  stop-color: var(--svg-color--60c5ff, #60C5FF);
  stop-opacity: 0;
}

.lnicg2b6c {
  stop-color: var(--svg-color--8cc5fd, #8CC5FD);
}

.m92k-fbhe {
  stop-color: var(--svg-color--cef8ff, #CEF8FF);
  stop-opacity: 0;
}

.mlh455b2t {
  stop-color: var(--svg-color--d4d0dc, #D4D0DC);
}

.n9gyjf4gk {
  d: path("M16.49 18.46a1.48 1.48 0 1 0 0-2.96a1.48 1.48 0 0 0 0 2.96");
}

.nctb2ac4r {
  opacity: var(--svg-opacity--0-8, 0.8);
}

.oayjv192q {
  stop-color: var(--svg-color--efbe44, #EFBE44);
}

.qae7fybta {
  fill-rule: evenodd;
  d: path("M16.49 1.5a.5.5 0 0 1 .5.5v18.9a.5.5 0 0 1-1 0V2a.5.5 0 0 1 .5-.5");
}

.t3mpidbyt {
  stop-color: var(--svg-color--ffd561, #FFD561);
}

.un0_haclx {
  fill: var(--svg-color--ff8585, #FF8585);
  d: path("M21.26 6.19c-.24 0-.43-.19-.43-.43v-.01a.28.28 0 1 0-.56 0v.01c0 .24-.19.43-.43.43c-.15 0-.28.12-.29.27c0 .16.12.28.28.28h.01c.24 0 .43.19.43.43v.01a.28.28 0 1 0 .56 0v-.01c0-.24.19-.43.43-.43h.01c.15 0 .28-.13.28-.28a.293.293 0 0 0-.29-.27m.01 4c-.24 0-.43-.19-.43-.43v-.01a.28.28 0 1 0-.56 0v.01c0 .24-.19.43-.43.43c-.15 0-.28.12-.29.27c0 .16.12.28.28.28h.01c.24 0 .43.19.43.43v.01a.28.28 0 1 0 .56 0v-.01c0-.24.19-.43.43-.43h.01c.15 0 .28-.13.28-.28a.294.294 0 0 0-.29-.27m2.42-1.99c-.24 0-.43-.19-.43-.43v-.01a.28.28 0 1 0-.56 0v.01c0 .24-.19.43-.43.43c-.15 0-.28.12-.29.27c0 .16.12.28.28.28h.01c.24 0 .43.19.43.43v.01a.28.28 0 1 0 .56 0v-.01c0-.24.19-.43.43-.43h.01c.15 0 .28-.13.28-.28a.294.294 0 0 0-.29-.27");
}

.vmpo1qb-s {
  stop-color: var(--svg-color--ffd561, #FFD561);
  stop-opacity: 0;
}

.we-16-o2z {
  stop-color: var(--svg-color--fff366, #FFF366);
}

.wrsxa1-lt {
  d: path("M13.2 21.05v.9c0 2 .42 3.97 1.23 5.79l.62 1.39c.09.21.3.34.53.34h5.47c.42 0 .7-.43.53-.81l-.41-.93c-.81-1.82-1.23-3.8-1.23-5.79v-.9a.58.58 0 0 0-.58-.58h-5.57c-.33.02-.59.28-.59.59");
}

.x7fnu5blu {
  stop-color: var(--svg-color--52d6ff, #52D6FF);
}

.y0kt-zb2f {
  stop-color: var(--svg-color--70e6ff, #70E6FF);
}

</style>
