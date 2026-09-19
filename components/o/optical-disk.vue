<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iRdDNnb)"><path fill="url(#i7Uzlsm)" clip-rule="evenodd" class="h3lflkbpv"/></g><g filter="url(#iz0fbDR)"><path fill="url(#i6QFdXb)" clip-rule="evenodd" class="v1s3m183f"/></g><g filter="url(#iFMYS0D)"><path fill="url(#iRzwTgd)" class="qmraj1byj"/></g><g filter="url(#iCgIhGd)"><path fill="url(#iGCzhlD)" class="zfgi5tdmr"/></g><g filter="url(#iMQ1zgd)"><path class="x2b_jk6ax"/></g><g filter="url(#iz00GBc)"><path fill="url(#i2nwDhd)" class="nvhdmuesv"/><path fill="url(#izgSXsd)" class="nvhdmuesv"/><path fill="url(#iIUdMcb)" class="nvhdmuesv"/></g><g filter="url(#iiHiWNT)"><path fill="url(#i2oj33d)" class="qj6c4_b9i"/><path fill="url(#idsUdEb)" class="qj6c4_b9i"/><path fill="url(#iRO403d)" class="qj6c4_b9i"/></g><g filter="url(#iLEmpOe)"><path fill="url(#iSQcS7e)" clip-rule="evenodd" class="lp0jo-v5k"/></g><defs><linearGradient id="i7Uzlsm" x1="16.188" x2="16.188" y1="1.983" y2="30.017" gradientUnits="userSpaceOnUse"><stop class="ediawnbdp"/><stop offset="1" class="s7p5nyv6q"/></linearGradient><linearGradient id="i6QFdXb" x1="16.188" x2="16.188" y1="8.419" y2="29.116" gradientUnits="userSpaceOnUse"><stop class="wqxnubbrq"/><stop offset="1" class="h52rn_b9d"/></linearGradient><linearGradient id="iRzwTgd" x1="25.242" x2="11.781" y1="6.918" y2="6.918" gradientUnits="userSpaceOnUse"><stop class="foteutbvm"/><stop offset="1" class="kvbhp09bi"/></linearGradient><linearGradient id="iGCzhlD" x1="11.366" x2="19.229" y1="19.941" y2="19.941" gradientUnits="userSpaceOnUse"><stop class="b30pylzju"/><stop offset="1" class="v_3308v5r"/></linearGradient><linearGradient id="i2nwDhd" x1="24.054" x2="24.054" y1="9.75" y2="22.438" gradientUnits="userSpaceOnUse"><stop class="nd__8ybfs"/><stop offset=".296" class="lfrvdic5t"/><stop offset=".656" class="yw1pyttlo"/><stop offset="1" class="dmejh4buf"/></linearGradient><linearGradient id="izgSXsd" x1="22.188" x2="23.5" y1="10.938" y2="12.75" gradientUnits="userSpaceOnUse"><stop offset=".234" class="mnwlywl6k"/><stop offset="1" class="z9ux3fhwi"/></linearGradient><linearGradient id="iIUdMcb" x1="21.719" x2="22.906" y1="21.25" y2="19.813" gradientUnits="userSpaceOnUse"><stop class="bt661pbjx"/><stop offset="1" class="xap_jbc9i"/></linearGradient><linearGradient id="i2oj33d" x1="9.75" x2="9.75" y1="22.125" y2="10.813" gradientUnits="userSpaceOnUse"><stop class="nd__8ybfs"/><stop offset=".296" class="lfrvdic5t"/><stop offset=".656" class="yw1pyttlo"/><stop offset="1" class="dmejh4buf"/></linearGradient><linearGradient id="idsUdEb" x1="10.189" x2="8.322" y1="10.938" y2="13.375" gradientUnits="userSpaceOnUse"><stop offset=".234" class="mnwlywl6k"/><stop offset="1" class="z9ux3fhwi"/></linearGradient><linearGradient id="iRO403d" x1="10.938" x2="9.5" y1="21.25" y2="18.938" gradientUnits="userSpaceOnUse"><stop class="bt661pbjx"/><stop offset="1" class="xap_jbc9i"/></linearGradient><filter id="iRdDNnb" width="28.533" height="28.533" x="1.922" y="1.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.454902 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19843"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.737255 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_19843" result="effect2_innerShadow_18_19843"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.882353 0 0 0 0 0.92549 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_19843" result="effect3_innerShadow_18_19843"/></filter><filter id="iz0fbDR" width="26.732" height="26.732" x="2.822" y="2.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19843" stdDeviation=".125"/></filter><filter id="iFMYS0D" width="19.06" height="10.791" x="6.432" y="2.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19843" stdDeviation=".125"/></filter><filter id="iCgIhGd" width="18.532" height="10.52" x="6.943" y="18.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19843" stdDeviation=".125"/></filter><filter id="iMQ1zgd" width="8.978" height="8.978" x="11.699" y="11.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19843" stdDeviation=".05"/></filter><filter id="iz00GBc" width="11.5" height="18.096" x="18.304" y="7.356" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19843" stdDeviation=".25"/></filter><filter id="iiHiWNT" width="11.5" height="18.096" x="2.572" y="7.356" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19843" stdDeviation=".25"/></filter><filter id="iLEmpOe" width="8.928" height="8.678" x="11.599" y="11.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.678431 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19843"/></filter><radialGradient id="iSQcS7e" cx="0" cy="0" r="1" gradientTransform="translate(12.754 16)scale(9.23183)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="t6--x3c9b"/><stop offset=".9" class="muhejqb1h"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:optical-disk" /></template>
<style>
.b30pylzju {
  stop-color: var(--svg-color--ebd8fe, #EBD8FE);
}

.bt661pbjx {
  stop-color: var(--svg-color--c6b6d5, #C6B6D5);
}

.dmejh4buf {
  stop-color: var(--svg-color--cdb9f2, #CDB9F2);
}

.ediawnbdp {
  stop-color: var(--svg-color--d0c9d8, #D0C9D8);
}

.foteutbvm {
  stop-color: var(--svg-color--fdebff, #FDEBFF);
}

.ft5dv1b6b {
  fill: none;
}

.h3lflkbpv {
  fill-rule: evenodd;
  d: path("M16.188 30.017c7.741 0 14.017-6.276 14.017-14.017S23.929 1.983 16.188 1.983S2.172 8.26 2.172 16s6.275 14.017 14.016 14.017m0-10.705a3.312 3.312 0 1 0 0-6.624a3.312 3.312 0 0 0 0 6.624");
}

.h52rn_b9d {
  stop-color: var(--svg-color--bfacd0, #BFACD0);
}

.kvbhp09bi {
  stop-color: var(--svg-color--fdebff, #FDEBFF);
  stop-opacity: 0;
}

.lfrvdic5t {
  stop-color: var(--svg-color--eed0de, #EED0DE);
}

.lp0jo-v5k {
  fill-rule: evenodd;
  d: path("M16.188 20.34a4.34 4.34 0 1 0 0-8.68a4.34 4.34 0 0 0 0 8.68M19.5 16a3.312 3.312 0 1 1-6.624 0a3.312 3.312 0 0 1 6.624 0");
}

.mnwlywl6k {
  stop-color: var(--svg-color--d2c8dc, #D2C8DC);
}

.muhejqb1h {
  stop-color: var(--svg-color--c7b8d4, #C7B8D4);
}

.nd__8ybfs {
  stop-color: var(--svg-color--e8c0dd, #E8C0DD);
}

.nvhdmuesv {
  d: path("m26.47 7.856l-7.252 6.025c.456.663.742 1.417.742 2.119c0 .896-.466 1.85-1.156 2.59c2.385 2.188 5.34 4.89 6.97 6.362A13.07 13.07 0 0 0 29.304 16a13.06 13.06 0 0 0-2.834-8.144");
}

.qj6c4_b9i {
  d: path("m5.907 7.856l7.251 6.025c-.456.663-.741 1.417-.741 2.119c0 .896.465 1.85 1.155 2.59c-2.385 2.188-5.34 4.89-6.97 6.362A13.07 13.07 0 0 1 3.072 16a13.06 13.06 0 0 1 2.835-8.144");
}

.qmraj1byj {
  d: path("M12.894 13.175a4.33 4.33 0 0 1 3.294-1.514c1.213 0 2.309.497 3.096 1.299l5.783-5.783a.58.58 0 0 0-.008-.838a13.07 13.07 0 0 0-8.87-3.455a13.08 13.08 0 0 0-9.507 4.08z");
}

.s7p5nyv6q {
  stop-color: var(--svg-color--b09ac4, #B09AC4);
}

.t6--x3c9b {
  stop-color: var(--svg-color--c9b9db, #C9B9DB);
}

.v_3308v5r {
  stop-color: var(--svg-color--ebd8fe, #EBD8FE);
  stop-opacity: 0;
}

.v1s3m183f {
  fill-rule: evenodd;
  d: path("M16.188 29.116c7.244 0 13.116-5.872 13.116-13.116S23.432 2.884 16.188 2.884S3.072 8.756 3.072 16s5.872 13.116 13.116 13.116M19.96 16c0 1.83-1.943 3.903-3.772 3.903S12.191 17.829 12.191 16s2.168-4.015 3.997-4.015c1.83 0 3.772 2.186 3.772 4.015");
}

.wqxnubbrq {
  stop-color: var(--svg-color--d1c7db, #D1C7DB);
}

.x2b_jk6ax {
  stroke: var(--svg-color--c6b7dc, #C6B7DC);
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M16.188 20.364a4.364 4.364 0 1 0 0-8.728a4.364 4.364 0 0 0 0 8.728Z");
}

.xap_jbc9i {
  stop-color: var(--svg-color--c6b6d5, #C6B6D5);
  stop-opacity: 0;
}

.yw1pyttlo {
  stop-color: var(--svg-color--d0cfde, #D0CFDE);
}

.z9ux3fhwi {
  stop-color: var(--svg-color--d2c8dc, #D2C8DC);
  stop-opacity: 0;
}

.zfgi5tdmr {
  d: path("M19.013 19.294a4.32 4.32 0 0 1-2.825 1.045a4.33 4.33 0 0 1-3.04-1.243l-5.78 5.78a.58.58 0 0 0 .01.841a13.07 13.07 0 0 0 8.81 3.399a13.06 13.06 0 0 0 9.037-3.61z");
}

</style>
