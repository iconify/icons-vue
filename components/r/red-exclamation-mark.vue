<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#ij3MlfK)" class="nxg4nmg6e"/><circle fill="url(#iS252RA)" class="nxg4nmg6e"/><circle fill="url(#iCfvh7c)" class="nxg4nmg6e"/><g filter="url(#iRE1IMc)"><path fill="url(#ioOZ5GM)" class="sqzkc_bxd"/><path fill="url(#i4yr44b)" class="sqzkc_bxd"/></g><g filter="url(#ikXOeHe)"><path stroke="url(#iAZ9xpb)" class="n9wxe7w8t"/></g><defs><radialGradient id="iS252RA" cx="0" cy="0" r="1" gradientTransform="matrix(1.53125 -1.75 1.5386 1.34627 16.938 27.123)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="dcrsbbcfe"/><stop offset="1" class="npvh19b0x"/></radialGradient><radialGradient id="iCfvh7c" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 1.21875 -3.29992 6.76908 13.47 25.56)" gradientUnits="userSpaceOnUse"><stop class="aaxt30sbu"/><stop offset="1" class="y461h2bjy"/></radialGradient><radialGradient id="i4yr44b" cx="0" cy="0" r="1" gradientTransform="rotate(148.241 8.502 4.343)scale(3.08727 2.21529)" gradientUnits="userSpaceOnUse"><stop class="pwewr5buv"/><stop offset="1" class="z0zlvqdzl"/></radialGradient><linearGradient id="ij3MlfK" x1="15.969" x2="15.969" y1="26.186" y2="29.971" gradientUnits="userSpaceOnUse"><stop class="kyy_-qs4j"/><stop offset="1" class="j8ie5mkwv"/></linearGradient><linearGradient id="ioOZ5GM" x1="15.969" x2="15.969" y1="2.505" y2="22.998" gradientUnits="userSpaceOnUse"><stop class="kqjz1wbgv"/><stop offset="1" class="i76s0ubvh"/></linearGradient><linearGradient id="iAZ9xpb" x1="17.335" x2="21.96" y1="22.526" y2="21.326" gradientUnits="userSpaceOnUse"><stop class="ycqx-0fln"/><stop offset="1" class="h0z_c4bkg"/></linearGradient><filter id="iRE1IMc" width="5.75" height="21.719" x="13.469" y="2.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.160784 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1840"/></filter><filter id="ikXOeHe" width="5" height="20.188" x="14.141" y="3.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1840" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:red-exclamation-mark" /></template>
<style>
.aaxt30sbu {
  stop-color: var(--svg-color--c8404b, #C8404B);
}

.dcrsbbcfe {
  stop-color: var(--svg-color--ff5878, #FF5878);
}

.ft5dv1b6b {
  fill: none;
}

.h0z_c4bkg {
  stop-color: var(--svg-color--ff3e59, #FF3E59);
}

.i76s0ubvh {
  stop-color: var(--svg-color--f41585, #F41585);
}

.j8ie5mkwv {
  stop-color: var(--svg-color--f62093, #F62093);
}

.kqjz1wbgv {
  stop-color: var(--svg-color--ed1f28, #ED1F28);
}

.kyy_-qs4j {
  stop-color: var(--svg-color--ff0b38, #FF0B38);
}

.n9wxe7w8t {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.641 20.936V5.748");
}

.npvh19b0x {
  stop-color: var(--svg-color--ff5878, #FF5878);
  stop-opacity: 0;
}

.nxg4nmg6e {
  cx: 15.969px;
  cy: 27.471px;
  r: 2.5px;
}

.pwewr5buv {
  stop-color: var(--svg-color--ff5960, #FF5960);
}

.sqzkc_bxd {
  d: path("M13.47 4.53a2.5 2.5 0 0 1 5 0v15.968a2.5 2.5 0 1 1-5 0z");
}

.y461h2bjy {
  stop-color: var(--svg-color--c8404b, #C8404B);
  stop-opacity: 0;
}

.ycqx-0fln {
  stop-color: var(--svg-color--ff4282, #FF4282);
}

.z0zlvqdzl {
  stop-color: var(--svg-color--ff5960, #FF5960);
  stop-opacity: 0;
}

</style>
