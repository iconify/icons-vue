<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ihKbHXc)" class="cat3xdbmy"/><path fill="url(#iNPAmbc)" class="cat3xdbmy"/><path fill="url(#iC3Mh2T)" class="zme-lob6v"/><g filter="url(#i7DbNne)"><path class="iwv1mmbsh"/><path stroke="url(#iVcgwvA)" class="at-w0_lai"/></g><path fill="url(#iDJCdnb)" class="z5it0bo3i"/><path fill="url(#iycj4Vc)" class="z5it0bo3i"/><circle class="p4efsbbcd"/><g filter="url(#i8c7wsc)"><circle class="qv1uhacyx"/><circle stroke="url(#iEUoLue)" class="uchf32gie"/></g><g filter="url(#iagJYRc)"><circle stroke="url(#i5OKvld)" class="iwyjgibyi"/></g><circle fill="url(#i8hCSuc)" class="fuv_lwb4l"/><circle fill="url(#iLOkZtc)" class="fuv_lwb4l"/><circle fill="url(#iTnLMye)" class="fuv_lwb4l"/><g filter="url(#i7m4Ene)"><path clip-rule="evenodd" class="qbkmp7bgt"/></g><g filter="url(#iMgTiwe)"><circle class="jjs2m3b9s"/></g><g filter="url(#inaFejc)"><path class="f9_uoq6us"/></g><g filter="url(#i4JZstb)"><path class="wj-1hvb3o"/></g><defs><radialGradient id="ihKbHXc" cx="0" cy="0" r="1" gradientTransform="rotate(145.355 10.726 12.308)scale(13.0404 13.1312)" gradientUnits="userSpaceOnUse"><stop class="env2z8b8m"/><stop offset="1" class="to7bwdbwk"/></radialGradient><radialGradient id="iNPAmbc" cx="0" cy="0" r="1" gradientTransform="matrix(7.93732 .09067 -.10344 9.05502 17.875 20.7)" gradientUnits="userSpaceOnUse"><stop offset=".957" class="xmm1gxbbq"/><stop offset=".988" class="gbkn_lbcr"/></radialGradient><radialGradient id="iC3Mh2T" cx="0" cy="0" r="1" gradientTransform="matrix(7.94324 -8.94917 30.58233 27.14472 18.659 27.739)" gradientUnits="userSpaceOnUse"><stop class="ys4s8obgk"/><stop offset="1" class="sga_h1tko"/></radialGradient><radialGradient id="iVcgwvA" cx="0" cy="0" r="1" gradientTransform="matrix(3.26418 -2.26687 3.55398 5.11754 20.614 9.366)" gradientUnits="userSpaceOnUse"><stop offset=".782" class="urtapza_s"/><stop offset="1" class="fcs3-jb1d"/></radialGradient><radialGradient id="iDJCdnb" cx="0" cy="0" r="1" gradientTransform="matrix(-12.31257 8.68749 -7.9191 -11.22355 23.672 16.337)" gradientUnits="userSpaceOnUse"><stop class="kifmdm1ft"/><stop offset="1" class="y4y1r5b3t"/></radialGradient><radialGradient id="iycj4Vc" cx="0" cy="0" r="1" gradientTransform="matrix(8.34375 0 0 8.92433 14.36 20.493)" gradientUnits="userSpaceOnUse"><stop offset=".897" class="osto1vxmr"/><stop offset=".976" class="yzy0m75dy"/></radialGradient><radialGradient id="iEUoLue" cx="0" cy="0" r="1" gradientTransform="matrix(4.46042 -1.8199 2.0919 5.12705 12.68 7.013)" gradientUnits="userSpaceOnUse"><stop class="ox0zzlbmu"/><stop offset="1" class="u8ou5u3yb"/></radialGradient><radialGradient id="i8hCSuc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.714 30.123 5.264)scale(20.3152)" gradientUnits="userSpaceOnUse"><stop class="h2xvz19xq"/><stop offset="1" class="sgmnawb6s"/></radialGradient><radialGradient id="iLOkZtc" cx="0" cy="0" r="1" gradientTransform="translate(12.764 20.493)scale(9.61084)" gradientUnits="userSpaceOnUse"><stop offset=".967" class="i-oyl1n7d"/><stop offset="1" class="igpo4fb5t"/></radialGradient><radialGradient id="iTnLMye" cx="0" cy="0" r="1" gradientTransform="rotate(90 -3.512 16.637)scale(9.59375)" gradientUnits="userSpaceOnUse"><stop offset=".965" class="ps7jgabce"/><stop offset="1" class="ols-0s5sb"/></radialGradient><filter id="i7DbNne" width="5.88" height="9.561" x="18.647" y="4.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.631373 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3277"/></filter><filter id="i8c7wsc" width="6.18" height="6.18" x="13.453" y="1.649" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.631373 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3277"/></filter><filter id="iagJYRc" width="5.68" height="5.68" x="13.739" y="1.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3277" stdDeviation=".125"/></filter><filter id="i7m4Ene" width="14.159" height="13.359" x="5.787" y="13.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.509804 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3277"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.619608 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_3277" result="effect2_innerShadow_18_3277"/></filter><filter id="iMgTiwe" width="10.917" height="10.917" x="7.533" y="14.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.388235 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3277"/></filter><filter id="inaFejc" width="8.865" height="8.615" x="8.434" y="15.968" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3277" stdDeviation=".5"/></filter><filter id="i4JZstb" width="7.665" height="7.415" x="8.934" y="16.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.631373 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3277"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.47451 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_3277" result="effect2_innerShadow_18_3277"/></filter><linearGradient id="i5OKvld" x1="18.674" x2="15.248" y1="2.981" y2="7.187" gradientUnits="userSpaceOnUse"><stop class="alqj_3bcx"/><stop offset=".186" class="d7vj7udxd"/><stop offset=".86" class="d7vj7udxd"/><stop offset="1" class="alqj_3bcx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:yo-yo" /></template>
<style>
.alqj_3bcx {
  stop-color: var(--svg-color--fdcd63, #FDCD63);
}

.at-w0_lai {
  d: path("M18.719 5.267c.937-.136 3.13.03 4.43 1.804c1.624 2.219.46 5.297-2.758 6.766");
}

.cat3xdbmy {
  d: path("M17.875 29.743a9.25 9.25 0 0 0 0-18.5h-4.75v1.311a9.24 9.24 0 0 0-4.5 7.94a9.24 9.24 0 0 0 4.5 7.938v1.311z");
}

.d7vj7udxd {
  stop-color: var(--svg-color--fdcd63, #FDCD63);
  stop-opacity: 0;
}

.env2z8b8m {
  stop-color: var(--svg-color--a28acf, #A28ACF);
}

.f9_uoq6us {
  fill: var(--svg-color--8b60d0, #8B60D0);
  d: path("M11.279 18.725a.47.47 0 0 0 .334-.23c.206-.347.504-.831.79-1.27a.55.55 0 0 1 .93 0c.28.433.575.91.78 1.255a.49.49 0 0 0 .36.24c.425.054.925.097 1.37.192c.43.092.6.577.318.919c-.241.292-.512.605-.746.876l-.294.342a.5.5 0 0 0-.097.459c.162.567.276 1.07.347 1.464c.082.45-.292.729-.713.562a32 32 0 0 1-1.578-.686a.5.5 0 0 0-.426 0c-.379.176-.98.449-1.578.686c-.42.167-.795-.112-.713-.562c.072-.394.186-.897.347-1.465a.5.5 0 0 0-.096-.458l-.295-.342c-.234-.27-.505-.584-.746-.876a.559.559 0 0 1 .318-.92c.446-.094.978-.127 1.388-.186");
}

.fcs3-jb1d {
  stop-color: var(--svg-color--fcca60, #FCCA60);
}

.ft5dv1b6b {
  fill: none;
}

.fuv_lwb4l {
  cx: 13.125px;
  cy: 20.493px;
  r: 9.25px;
}

.gbkn_lbcr {
  stop-color: var(--svg-color--734bad, #734BAD);
  stop-opacity: 0;
}

.h2xvz19xq {
  stop-color: var(--svg-color--9268d7, #9268D7);
}

.i-oyl1n7d {
  stop-color: var(--svg-color--ab87e5, #AB87E5);
  stop-opacity: 0;
}

.igpo4fb5t {
  stop-color: var(--svg-color--ab87e5, #AB87E5);
}

.iwv1mmbsh {
  stroke: var(--svg-color--ebb240, #EBB240);
  d: path("M18.719 5.267c.937-.136 3.13.03 4.43 1.804c1.624 2.219.46 5.297-2.758 6.766");
}

.iwyjgibyi {
  cx: 16.579px;
  cy: 4.722px;
  r: 2.465px;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
}

.jjs2m3b9s {
  cx: 12.867px;
  cy: 20.493px;
  r: 5.334px;
  fill: var(--svg-color--9369d3, #9369D3);
}

.kifmdm1ft {
  stop-color: var(--svg-color--b090e1, #B090E1);
}

.ols-0s5sb {
  stop-color: var(--svg-color--8653d0, #8653D0);
}

.osto1vxmr {
  stop-color: var(--svg-color--af8ce6, #AF8CE6);
}

.ox0zzlbmu {
  stop-color: var(--svg-color--e9b443, #E9B443);
}

.p4efsbbcd {
  cx: 13.125px;
  cy: 20.493px;
  r: 9.156px;
  fill: var(--svg-color--ff8a8a, #FF8A8A);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
}

.ps7jgabce {
  stop-color: var(--svg-color--8653d0, #8653D0);
  stop-opacity: 0;
}

.qbkmp7bgt {
  fill: var(--svg-color--c78eff, #C78EFF);
  fill-rule: evenodd;
  d: path("M12.867 27.173a6.68 6.68 0 1 0 0-13.36a6.68 6.68 0 0 0 0 13.36m0-1.344a5.336 5.336 0 1 0 0-10.672a5.336 5.336 0 0 0 0 10.672");
}

.qv1uhacyx {
  cx: 16.418px;
  cy: 4.864px;
  r: 2.465px;
  stroke: var(--svg-color--ebb240, #EBB240);
}

.sga_h1tko {
  stop-color: var(--svg-color--442662, #442662);
}

.sgmnawb6s {
  stop-color: var(--svg-color--9469d5, #9469D5);
}

.to7bwdbwk {
  stop-color: var(--svg-color--744eb1, #744EB1);
}

.u8ou5u3yb {
  stop-color: var(--svg-color--e9b443, #E9B443);
  stop-opacity: 0;
}

.uchf32gie {
  cx: 16.418px;
  cy: 4.864px;
  r: 2.465px;
}

.urtapza_s {
  stop-color: var(--svg-color--fcca60, #FCCA60);
  stop-opacity: 0;
}

.wj-1hvb3o {
  fill: var(--svg-color--c08bf9, #C08BF9);
  d: path("M11.279 18.725a.47.47 0 0 0 .334-.23c.206-.347.504-.831.79-1.27a.55.55 0 0 1 .93 0c.28.433.575.91.78 1.255a.49.49 0 0 0 .36.24c.425.054.925.097 1.37.192c.43.092.6.577.318.919c-.241.292-.512.605-.746.876l-.294.342a.5.5 0 0 0-.097.459c.162.567.276 1.07.347 1.464c.082.45-.292.729-.713.562a32 32 0 0 1-1.578-.686a.5.5 0 0 0-.426 0c-.379.176-.98.449-1.578.686c-.42.167-.795-.112-.713-.562c.072-.394.186-.897.347-1.465a.5.5 0 0 0-.096-.458l-.295-.342c-.234-.27-.505-.584-.746-.876a.559.559 0 0 1 .318-.92c.446-.094.978-.127 1.388-.186");
}

.xmm1gxbbq {
  stop-color: var(--svg-color--734bad, #734BAD);
}

.y4y1r5b3t {
  stop-color: var(--svg-color--8357c5, #8357C5);
}

.ys4s8obgk {
  stop-color: var(--svg-color--543a6e, #543A6E);
}

.yzy0m75dy {
  stop-color: var(--svg-color--af8ce6, #AF8CE6);
  stop-opacity: 0;
}

.z5it0bo3i {
  d: path("M15 29.743a9.25 9.25 0 0 0 0-18.5h-1.875v.19c-4.21.867-7.375 4.594-7.375 9.06s3.165 8.193 7.375 9.06v.19z");
}

.zme-lob6v {
  d: path("M16.203 29.462c5.109 0 9.25-4.016 9.25-8.969s-4.141-8.968-9.25-8.968h-3.078v1.271c-2.696 1.567-4.5 4.428-4.5 7.697s1.804 6.13 4.5 7.698v1.27z");
}

</style>
