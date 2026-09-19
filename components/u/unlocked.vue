<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#inhhfWb)"><path class="jzf9a2bwe"/></g><path stroke="url(#iydnP2d)" class="acw7tzbos"/><path stroke="url(#i0oEmzB)" class="acw7tzbos"/><g filter="url(#iIW17ac)" class="atjk8mbde"><path stroke="url(#iQ6K2nc)" class="ofkfa_bwz"/><path stroke="url(#iHurTQd)" class="ofkfa_bwz"/></g><g filter="url(#i1wB2td)"><rect fill="url(#ixJPqKd)" class="stev3h_cy"/></g><rect fill="url(#iQLDfWc)" class="stev3h_cy"/><rect fill="url(#i0K0eDb)" class="stev3h_cy"/><rect fill="url(#i7kLc5d)" class="stev3h_cy"/><g filter="url(#i1yqcJd)" class="c7knmzboe"><path stroke="url(#iXA9Yzc)" class="fj5fyuq-p"/><path stroke="url(#iRtf03c)" class="fj5fyuq-p"/></g><path fill="url(#iMI1Dqb)" class="fj5fyuq-p"/><defs><radialGradient id="iydnP2d" cx="0" cy="0" r="1" gradientTransform="matrix(-.15625 -5.414 5.80992 -.16767 24.531 8.156)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="ic4s5xbvn"/><stop offset="1" class="zw343dbjx"/></radialGradient><radialGradient id="i0oEmzB" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.21875 8.81238 0 29.305 11.406)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="ho4l9nbiv"/><stop offset="1" class="nb2cfktpd"/></radialGradient><radialGradient id="iQ6K2nc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.67338 3.47071 -4.76862 -5.04709 30.036 4.538)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="f_yy7pxnt"/><stop offset="1" class="bdorqcccj"/></radialGradient><radialGradient id="iHurTQd" cx="0" cy="0" r="1" gradientTransform="rotate(-80.102 19.36 -2.728)scale(9.45321 6.82288)" gradientUnits="userSpaceOnUse"><stop class="f_yy7pxnt"/><stop offset="1" class="bdorqcccj"/></radialGradient><radialGradient id="iQLDfWc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18751 -2.40624 5.60574 -5.09619 23.813 29.898)" gradientUnits="userSpaceOnUse"><stop class="ol_x1zd0x"/><stop offset="1" class="wyhbviwvc"/></radialGradient><radialGradient id="i7kLc5d" cx="0" cy="0" r="1" gradientTransform="rotate(126.254 9.23 11.624)scale(2.32513 5.25171)" gradientUnits="userSpaceOnUse"><stop class="otx6b2qss"/><stop offset="1" class="kp53krb3m"/></radialGradient><radialGradient id="iMI1Dqb" cx="0" cy="0" r="1" gradientTransform="rotate(34.061 -24.997 26.914)scale(5.69121 7.82719)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="p0s2a-btm"/><stop offset="1" class="vzphlmk8b"/></radialGradient><linearGradient id="ixJPqKd" x1="7.563" x2="14.5" y1="14.117" y2="29.898" gradientUnits="userSpaceOnUse"><stop class="gkbwn2d_k"/><stop offset="1" class="ltuow0bom"/></linearGradient><linearGradient id="i0K0eDb" x1="13.406" x2="13.406" y1="10.742" y2="12.242" gradientUnits="userSpaceOnUse"><stop class="oy1zi6b-t"/><stop offset="1" class="r8k5v-b5l"/></linearGradient><linearGradient id="iXA9Yzc" x1="16.531" x2="12.656" y1="21.68" y2="21.68" gradientUnits="userSpaceOnUse"><stop offset=".331" class="z0qt9gb0h"/><stop offset="1" class="ew96f-mrq"/></linearGradient><linearGradient id="iRtf03c" x1="10.281" x2="13" y1="20.742" y2="20.742" gradientUnits="userSpaceOnUse"><stop class="h80w1obxx"/><stop offset="1" class="k_9_8y67b"/></linearGradient><filter id="inhhfWb" width="13.609" height="13.328" x="18.07" y="2.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.556863 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23558"/></filter><filter id="iIW17ac" width="12.359" height="13.078" x="18.633" y="1.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23558" stdDeviation=".375"/></filter><filter id="i1wB2td" width="23.438" height="20.344" x="1.688" y="10.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.364706 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23558"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.772549 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23558" result="effect2_innerShadow_18_23558"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_23558" result="effect3_innerShadow_18_23558"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.478431 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_23558" result="effect4_innerShadow_18_23558"/></filter><filter id="i1yqcJd" width="7.965" height="12.26" x="9.41" y="14.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23558" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:unlocked" /></template>
<style>
.acw7tzbos {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2-75px, 2.75px);
  d: path("M19.445 14.07V8.508c0-2.77 2.207-5.016 4.93-5.016s4.93 2.246 4.93 5.016v1.086");
}

.atjk8mbde {
  stroke-linecap: round;
}

.bdorqcccj {
  stop-color: var(--svg-color--edecf3, #EDECF3);
  stop-opacity: 0;
}

.c7knmzboe {
  stroke-width: var(--svg-stroke-width--1-75px, 1.75px);
}

.ew96f-mrq {
  stop-color: var(--svg-color--d98a40, #D98A40);
  stop-opacity: 0;
}

.f_yy7pxnt {
  stop-color: var(--svg-color--edecf3, #EDECF3);
}

.fj5fyuq-p {
  d: path("M14.805 20.392a2.607 2.607 0 1 0-2.797.017v3.294a1.398 1.398 0 0 0 2.797 0z");
}

.ft5dv1b6b {
  fill: none;
}

.gkbwn2d_k {
  stop-color: var(--svg-color--ffc74e, #FFC74E);
}

.h80w1obxx {
  stop-color: var(--svg-color--ffcd63, #FFCD63);
}

.ho4l9nbiv {
  stop-color: var(--svg-color--b57fd6, #B57FD6);
}

.ic4s5xbvn {
  stop-color: var(--svg-color--ab83c0, #AB83C0);
}

.jzf9a2bwe {
  stroke: var(--svg-color--c2c2c6, #C2C2C6);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2-75px, 2.75px);
  d: path("M19.445 14.07V8.508c0-2.77 2.207-5.016 4.93-5.016s4.93 2.246 4.93 5.016v1.086");
}

.k_9_8y67b {
  stop-color: var(--svg-color--ffcd63, #FFCD63);
  stop-opacity: 0;
}

.kp53krb3m {
  stop-color: var(--svg-color--fff760, #FFF760);
  stop-opacity: 0;
}

.ltuow0bom {
  stop-color: var(--svg-color--f7864e, #F7864E);
}

.nb2cfktpd {
  stop-color: var(--svg-color--b57fd6, #B57FD6);
  stop-opacity: 0;
}

.ofkfa_bwz {
  d: path("M19.883 13.758V8.195c0-2.77 2.207-5.015 4.93-5.015s4.93 2.245 4.93 5.015v1.086");
}

.ol_x1zd0x {
  stop-color: var(--svg-color--ff8650, #FF8650);
}

.otx6b2qss {
  stop-color: var(--svg-color--fff760, #FFF760);
}

.oy1zi6b-t {
  stop-color: var(--svg-color--f3d04e, #F3D04E);
}

.p0s2a-btm {
  stop-color: var(--svg-color--564f80, #564F80);
}

.r8k5v-b5l {
  stop-color: var(--svg-color--f3d04e, #F3D04E);
  stop-opacity: 0;
}

.stev3h_cy {
  width: 21.938px;
  height: 18.844px;
  x: 2.438px;
  y: 11.055px;
  rx: 3px;
}

.vzphlmk8b {
  stop-color: var(--svg-color--473154, #473154);
}

.wyhbviwvc {
  stop-color: var(--svg-color--ff8650, #FF8650);
  stop-opacity: 0;
}

.z0qt9gb0h {
  stop-color: var(--svg-color--d98a40, #D98A40);
}

.zw343dbjx {
  stop-color: var(--svg-color--cbbbdc, #CBBBDC);
  stop-opacity: 0;
}

</style>
