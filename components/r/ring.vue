<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iGpYXZc)"><path clip-rule="evenodd" class="w3o0xsb_q"/></g><path fill="url(#ipQBykd)" clip-rule="evenodd" class="t8sqf8bnl"/><path fill="url(#iCTnuNb)" class="y-wztinzu"/><path fill="url(#iKVjdAe)" class="y-wztinzu"/><path fill="url(#iWB48ob)" class="y-wztinzu"/><path fill="url(#iqX3XWb)" class="a40k7cbft"/><path fill="url(#iako4Me)" class="a40k7cbft"/><path fill="url(#igu4zte)" class="a40k7cbft"/><g filter="url(#i6AKPFX)"><circle stroke="url(#iVDZqKb)" class="q-ss3sbrk"/><circle stroke="url(#igVw7Cf)" class="q-ss3sbrk"/></g><defs><linearGradient id="iCTnuNb" x1="13.797" x2="19.891" y1="4.281" y2="4.281" gradientUnits="userSpaceOnUse"><stop class="lzbhr9zxc"/><stop offset=".641" class="ie_fb-28e"/><stop offset="1" class="priojnbzc"/></linearGradient><linearGradient id="iKVjdAe" x1="15.555" x2="15.555" y1="4.969" y2="4.672" gradientUnits="userSpaceOnUse"><stop offset=".368" class="df0o1tb0l"/><stop offset="1" class="ail4yviak"/></linearGradient><linearGradient id="iWB48ob" x1="15.555" x2="15.555" y1="1.938" y2="2.313" gradientUnits="userSpaceOnUse"><stop class="nujh6fb8u"/><stop offset="1" class="u99_io_wd"/></linearGradient><linearGradient id="iqX3XWb" x1="11.547" x2="16.953" y1="7.844" y2="6.586" gradientUnits="userSpaceOnUse"><stop class="yk5k7rt_n"/><stop offset="1" class="t3tybq5xy"/></linearGradient><linearGradient id="iako4Me" x1="15.555" x2="15.555" y1="4.859" y2="5.016" gradientUnits="userSpaceOnUse"><stop class="df0o1tb0l"/><stop offset="1" class="ail4yviak"/></linearGradient><linearGradient id="igVw7Cf" x1="7.609" x2="10.359" y1="25.688" y2="23.25" gradientUnits="userSpaceOnUse"><stop offset=".207" class="srb1eub7d"/><stop offset="1" class="izd9mbntc"/></linearGradient><radialGradient id="ipQBykd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.25 -4.125 0 15.547 7.688)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="qsgwxxb-i"/><stop offset="1" class="adox_uesu"/></radialGradient><radialGradient id="igu4zte" cx="0" cy="0" r="1" gradientTransform="matrix(-3.21875 0 0 -.25 18.594 4.953)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="c8normbks"/><stop offset="1" class="dg4plfn8a"/></radialGradient><radialGradient id="iVDZqKb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.73434 4.64849 -5.05575 -7.32435 24.36 13.625)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="srb1eub7d"/><stop offset="1" class="izd9mbntc"/></radialGradient><filter id="iGpYXZc" width="23.125" height="22.634" x="3.984" y="7.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.858824 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17726"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".15"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.603922 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17726" result="effect2_innerShadow_18_17726"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.611765 0 0 0 0 0.878431 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_17726" result="effect3_innerShadow_18_17726"/></filter><filter id="i6AKPFX" width="20.781" height="20.781" x="5.609" y="8.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17726" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ring" /></template>
<style>
.a40k7cbft {
  d: path("m10.454 5.159l1.405 3.154h7.391l1.406-3.154a.4.4 0 0 0 .01-.3H10.443a.4.4 0 0 0 .01.3");
}

.adox_uesu {
  stop-color: var(--svg-color--c0a4d9, #C0A4D9);
  stop-opacity: 0;
}

.ail4yviak {
  stop-color: var(--svg-color--32a5f6, #32A5F6);
  stop-opacity: 0;
}

.c8normbks {
  stop-color: var(--svg-color--51bbfd, #51BBFD);
}

.df0o1tb0l {
  stop-color: var(--svg-color--32a5f6, #32A5F6);
}

.dg4plfn8a {
  stop-color: var(--svg-color--52b9fc, #52B9FC);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ie_fb-28e {
  stop-color: var(--svg-color--2695dd, #2695DD);
}

.izd9mbntc {
  stop-color: var(--svg-color--e3dfe9, #E3DFE9);
  stop-opacity: 0;
}

.lzbhr9zxc {
  stop-color: var(--svg-color--47ccff, #47CCFF);
}

.nujh6fb8u {
  stop-color: var(--svg-color--2b9fd9, #2B9FD9);
}

.priojnbzc {
  stop-color: var(--svg-color--3576a8, #3576A8);
}

.q-ss3sbrk {
  cx: 16px;
  cy: 19.102px;
  r: 8.891px;
}

.qsgwxxb-i {
  stop-color: var(--svg-color--c0a4d9, #C0A4D9);
}

.srb1eub7d {
  stop-color: var(--svg-color--e3dfe9, #E3DFE9);
}

.t3tybq5xy {
  stop-color: var(--svg-color--2cb2ff, #2CB2FF);
}

.t8sqf8bnl {
  fill-rule: evenodd;
  d: path("M11.844 8.234c.101.877-.235 1.368-.66 1.547h.006a10.56 10.56 0 0 0-6.206 9.625c0 5.834 4.73 10.563 10.563 10.563s10.562-4.73 10.562-10.563c0-4.298-2.567-7.997-6.253-9.646c-.381-.17-.723-.685-.626-1.526zm10.915 11.172a7.213 7.213 0 1 1-14.425 0a7.213 7.213 0 0 1 14.425 0");
}

.u99_io_wd {
  stop-color: var(--svg-color--2b9fd9, #2B9FD9);
  stop-opacity: 0;
}

.w3o0xsb_q {
  fill: var(--svg-color--c4afd9, #C4AFD9);
  fill-rule: evenodd;
  d: path("M11.844 8.234c.101.877-.235 1.368-.66 1.547h.006a10.56 10.56 0 0 0-6.206 9.625c0 5.834 4.73 10.563 10.563 10.563s10.562-4.73 10.562-10.563c0-4.298-2.567-7.997-6.253-9.646c-.381-.17-.723-.685-.626-1.526zm10.915 11.172a7.213 7.213 0 1 1-14.425 0a7.213 7.213 0 0 1 14.425 0");
}

.y-wztinzu {
  d: path("m11.86 8.313l-1.406-3.154a.4.4 0 0 1 .06-.421l2.106-2.5a.25.25 0 0 1 .192-.09h5.486a.25.25 0 0 1 .191.09l2.107 2.5a.4.4 0 0 1 .06.42L19.25 8.313z");
}

.yk5k7rt_n {
  stop-color: var(--svg-color--2c67ca, #2C67CA);
}

</style>
