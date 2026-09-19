<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iv5YS3b)"><path class="zmwy5m-lr"/><path fill="url(#iEzP7Db)" class="vtudzmb2m"/></g><path fill="url(#iFPuAad)" class="vtudzmb2m"/><path fill="url(#iHjlzpb)" class="vtudzmb2m"/><path fill="url(#ir838gb)" class="vtudzmb2m"/><path fill="url(#iHsMmJc)" class="vtudzmb2m"/><path fill="url(#igpzFEb)" class="vtudzmb2m"/><g filter="url(#iSOiV7c)" class="gt662abla"><path class="fqqb6yb8p"/><path class="tvnatgb6q"/><path class="c5kj6ifzd"/></g><path class="ibt64tbsa"/><path fill="url(#ir0M36b)" class="cauchjb2x"/><path fill="url(#iFKvSad)" class="cauchjb2x"/><path fill="url(#iWUywQc)" class="cauchjb2x"/><g filter="url(#ii5eNEh)"><rect class="xbzshgfum"/></g><path class="ukadjvyso"/><path fill="url(#i79vkzd)" class="ul8ir3bey"/><path fill="url(#izb12Oc)" class="ul8ir3bey"/><path fill="url(#iTZg0nb)" class="ul8ir3bey"/><g filter="url(#ijEZ99b)"><rect class="m3ki82bcn"/></g><path class="l7fxtw3ve"/><path fill="url(#iwktFdj)" class="gsdgegf-i"/><path fill="url(#iVB5Eae)" class="gsdgegf-i"/><path fill="url(#ikllsre)" class="gsdgegf-i"/><path fill="url(#ify6LFc)" class="zfw4f3b1v"/><path fill="url(#i41XNKL)" class="zfw4f3b1v"/><path fill="url(#ivzSY6d)" class="zfw4f3b1v"/><defs><radialGradient id="iEzP7Db" cx="0" cy="0" r="1" gradientTransform="rotate(138.108 7.87 13)scale(14.0119 10.4377)" gradientUnits="userSpaceOnUse"><stop class="qtu4cvboo"/><stop offset="1" class="xgbsqqbww"/></radialGradient><radialGradient id="iFPuAad" cx="0" cy="0" r="1" gradientTransform="matrix(-2.56813 -3.0232 2.6919 -2.28669 25.821 10.57)" gradientUnits="userSpaceOnUse"><stop class="x8yrve0lu"/><stop offset="1" class="el0l438lp"/></radialGradient><radialGradient id="iHjlzpb" cx="0" cy="0" r="1" gradientTransform="rotate(153.85 12.672 6.153)scale(2.56455 2.04967)" gradientUnits="userSpaceOnUse"><stop class="xm34y9b_d"/><stop offset="1" class="iv6sy1bym"/></radialGradient><radialGradient id="ir838gb" cx="0" cy="0" r="1" gradientTransform="matrix(1.61753 1.77534 -9.13543 8.3234 18.598 4.912)" gradientUnits="userSpaceOnUse"><stop class="gepjqcb-e"/><stop offset="1" class="dgepvabeh"/></radialGradient><radialGradient id="iHsMmJc" cx="0" cy="0" r="1" gradientTransform="matrix(1.14411 0 0 3.35343 17.611 7.99)" gradientUnits="userSpaceOnUse"><stop class="es6vmmb9b"/><stop offset="1" class="pwmb7xbsq"/></radialGradient><radialGradient id="igpzFEb" cx="0" cy="0" r="1" gradientTransform="matrix(-23.07864 10.46505 -10.22957 -22.55934 27.226 12.987)" gradientUnits="userSpaceOnUse"><stop offset=".927" class="hledypm0h"/><stop offset="1" class="z538ckbol"/></radialGradient><radialGradient id="iFKvSad" cx="0" cy="0" r="1" gradientTransform="rotate(50.042 -7.669 7.666)scale(7.61743 6.61775)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="tm79y4buv"/><stop offset="1" class="gxhnzfbyk"/></radialGradient><radialGradient id="iWUywQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.74306 -1.49874 0 6.484 11.043)" gradientUnits="userSpaceOnUse"><stop class="x_1xlacav"/><stop offset="1" class="yyaeehggs"/></radialGradient><radialGradient id="izb12Oc" cx="0" cy="0" r="1" gradientTransform="matrix(4.76725 6.57316 -5.51324 3.99854 7.922 7.967)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="tm79y4buv"/><stop offset="1" class="gxhnzfbyk"/></radialGradient><radialGradient id="iTZg0nb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.21375 -1.4605 0 11.188 10.693)" gradientUnits="userSpaceOnUse"><stop class="x_1xlacav"/><stop offset="1" class="yyaeehggs"/></radialGradient><radialGradient id="iVB5Eae" cx="0" cy="0" r="1" gradientTransform="matrix(4.84256 6.58468 -5.54635 4.07894 12.822 7.83)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="tm79y4buv"/><stop offset="1" class="gxhnzfbyk"/></radialGradient><radialGradient id="ikllsre" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.24202 -2.21875 0 16.658 10.561)" gradientUnits="userSpaceOnUse"><stop class="x_1xlacav"/><stop offset="1" class="yyaeehggs"/></radialGradient><radialGradient id="i41XNKL" cx="0" cy="0" r="1" gradientTransform="matrix(-2.7342 1.76829 -1.38594 -2.14299 28.75 14.165)" gradientUnits="userSpaceOnUse"><stop class="p6wb4qngy"/><stop offset="1" class="iv9_edb6r"/></radialGradient><radialGradient id="ivzSY6d" cx="0" cy="0" r="1" gradientTransform="matrix(1.46286 .58513 -2.0674 5.16858 22.082 15.868)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="rfc_0qb7j"/><stop offset="1" class="wxt_mybxq"/></radialGradient><linearGradient id="ir0M36b" x1="3.103" x2="5.926" y1="12.014" y2="12.014" gradientUnits="userSpaceOnUse"><stop class="uu5o3cekc"/><stop offset="1" class="hmitd-bry"/></linearGradient><linearGradient id="i79vkzd" x1="7.893" x2="10.645" y1="11.787" y2="11.787" gradientUnits="userSpaceOnUse"><stop class="uu5o3cekc"/><stop offset="1" class="hmitd-bry"/></linearGradient><linearGradient id="iwktFdj" x1="12.792" x2="15.587" y1="11.657" y2="11.657" gradientUnits="userSpaceOnUse"><stop class="uu5o3cekc"/><stop offset="1" class="hmitd-bry"/></linearGradient><linearGradient id="ify6LFc" x1="24.566" x2="26.532" y1="13.091" y2="16.764" gradientUnits="userSpaceOnUse"><stop class="ti-d9_bga"/><stop offset="1" class="inp-zn7gz"/></linearGradient><filter id="iv5YS3b" width="27.675" height="25.549" x="2.538" y="2.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.308333 0 0 0 0 0.173438 0 0 0 0 0.298341 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1973"/></filter><filter id="iSOiV7c" width="16.091" height="12.26" x="1.909" y="6.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1973" stdDeviation="1"/></filter><filter id="ii5eNEh" width="2.266" height="8.313" x="6.249" y="6.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1973" stdDeviation=".375"/></filter><filter id="ijEZ99b" width="2.266" height="8.719" x="11.186" y="6.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1973" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pinching-hand-dark" /></template>
<style>
.c5kj6ifzd {
  d: path("M6.192 9.051a2.28 2.28 0 0 0-2.283 2.266v2.55a2.28 2.28 0 0 0 2.283 2.267a2.28 2.28 0 0 0 2.282-2.267v-2.55a2.273 2.273 0 0 0-2.282-2.266");
}

.cauchjb2x {
  d: path("M5.45 6.577c-1.606 0-2.912 1.19-2.912 2.655v3.622c0 1.464 1.306 2.655 2.912 2.655s2.912-1.19 2.912-2.655V9.232c0-1.464-1.306-2.655-2.912-2.655");
}

.dgepvabeh {
  stop-color: var(--svg-color--4c403f, #4C403F);
  stop-opacity: 0;
}

.el0l438lp {
  stop-color: var(--svg-color--331d2e, #331D2E);
  stop-opacity: 0;
}

.es6vmmb9b {
  stop-color: var(--svg-color--241210, #241210);
}

.fqqb6yb8p {
  d: path("M13.338 8.462a2.656 2.656 0 0 0-2.662 2.643v2.974c0 1.457 1.194 2.644 2.662 2.644S16 15.536 16 14.079v-2.974a2.65 2.65 0 0 0-2.662-2.643");
}

.ft5dv1b6b {
  fill: none;
}

.gepjqcb-e {
  stop-color: var(--svg-color--4c403f, #4C403F);
}

.gsdgegf-i {
  d: path("M15.116 5.525c-1.59 0-2.883 1.284-2.883 2.862v4.349c0 1.578 1.294 2.862 2.883 2.862s2.883-1.284 2.883-2.862v-4.35a2.87 2.87 0 0 0-2.883-2.861");
}

.gt662abla {
  fill: var(--svg-color--1f0d12, #1F0D12);
}

.gxhnzfbyk {
  stop-color: var(--svg-color--3d1c2d, #3D1C2D);
}

.hledypm0h {
  stop-color: var(--svg-color--4e3b39, #4E3B39);
  stop-opacity: 0;
}

.hmitd-bry {
  stop-color: var(--svg-color--3e2a29, #3E2A29);
  stop-opacity: 0;
}

.ibt64tbsa {
  fill: var(--svg-color--462f2d, #462F2D);
  d: path("M5.45 6.577c-1.606 0-2.912 1.19-2.912 2.655v3.622c0 1.464 1.306 2.655 2.912 2.655s2.912-1.19 2.912-2.655V9.232c0-1.464-1.306-2.655-2.912-2.655");
}

.inp-zn7gz {
  stop-color: var(--svg-color--311d1b, #311D1B);
  stop-opacity: 0;
}

.iv6sy1bym {
  stop-color: var(--svg-color--65514f, #65514F);
  stop-opacity: 0;
}

.iv9_edb6r {
  stop-color: var(--svg-color--634f4d, #634F4D);
  stop-opacity: 0;
}

.l7fxtw3ve {
  fill: var(--svg-color--462f2d, #462F2D);
  d: path("M15.116 5.525c-1.59 0-2.883 1.284-2.883 2.862v4.349c0 1.578 1.294 2.862 2.883 2.862s2.883-1.284 2.883-2.862v-4.35a2.87 2.87 0 0 0-2.883-2.861");
}

.m3ki82bcn {
  width: 0.766px;
  height: 7.219px;
  x: 11.936px;
  y: 7.134px;
  fill: var(--svg-color--240f0e, #240F0E);
  rx: 0.383px;
}

.p6wb4qngy {
  stop-color: var(--svg-color--634f4d, #634F4D);
}

.pwmb7xbsq {
  stop-color: var(--svg-color--241210, #241210);
  stop-opacity: 0;
}

.qtu4cvboo {
  stop-color: var(--svg-color--614c4a, #614C4A);
}

.rfc_0qb7j {
  stop-color: var(--svg-color--5d4b49, #5D4B49);
}

.ti-d9_bga {
  stop-color: var(--svg-color--311d1b, #311D1B);
}

.tm79y4buv {
  stop-color: var(--svg-color--3d1c2d, #3D1C2D);
  stop-opacity: 0;
}

.tvnatgb6q {
  d: path("M9.53 8.866A2.527 2.527 0 0 0 7 11.38v2.829a2.527 2.527 0 0 0 2.532 2.514a2.527 2.527 0 0 0 2.532-2.514v-2.83A2.52 2.52 0 0 0 9.53 8.867");
}

.ukadjvyso {
  fill: var(--svg-color--462f2d, #462F2D);
  d: path("M10.18 5.665c-1.565 0-2.838 1.23-2.838 2.744v4.569c0 1.513 1.273 2.743 2.838 2.743s2.838-1.23 2.838-2.743v-4.58c0-1.512-1.273-2.733-2.838-2.733");
}

.ul8ir3bey {
  d: path("M10.18 5.665c-1.565 0-2.838 1.23-2.838 2.744v4.569c0 1.513 1.273 2.743 2.838 2.743s2.838-1.23 2.838-2.743v-4.58c0-1.512-1.273-2.733-2.838-2.733");
}

.uu5o3cekc {
  stop-color: var(--svg-color--3e2a29, #3E2A29);
}

.vtudzmb2m {
  d: path("M28.92 13.697c-.962-1.437-2.828-1.782-4.375-.438c-.76.661-1.648 1.618-1.648.464v-3.097c.07-1.28.828-1.625 2.063-1.203c1.756.446 3.168-.964 3.43-2.164c.203-.938-.008-2.441-1.61-3.203c-3.297-1.422-7.36-.203-8.9 3.333l-3.302 2.334H2.538v6.583c0 7.719 3.982 12.219 10.456 12.219c3.26 0 5.55-1.252 8.003-3.451c1.31-1.175 2.412-2.398 4.22-4.08c2.032-2.22 5.61-4.454 3.704-7.297");
}

.wxt_mybxq {
  stop-color: var(--svg-color--5d4b49, #5D4B49);
  stop-opacity: 0;
}

.x_1xlacav {
  stop-color: var(--svg-color--554342, #554342);
}

.x8yrve0lu {
  stop-color: var(--svg-color--331d2e, #331D2E);
}

.xbzshgfum {
  width: 0.766px;
  height: 6.813px;
  x: 6.999px;
  y: 7.54px;
  fill: var(--svg-color--240f0e, #240F0E);
  rx: 0.383px;
}

.xgbsqqbww {
  stop-color: var(--svg-color--614c4a, #614C4A);
  stop-opacity: 0;
}

.xm34y9b_d {
  stop-color: var(--svg-color--65514f, #65514F);
}

.yyaeehggs {
  stop-color: var(--svg-color--554342, #554342);
  stop-opacity: 0;
}

.z538ckbol {
  stop-color: var(--svg-color--4e3b39, #4E3B39);
}

.zfw4f3b1v {
  d: path("M24.546 13.26c1.546-1.345 3.412-1 4.375.437c1.525 2.275-.461 4.16-2.356 5.96a28 28 0 0 0-1.348 1.336c-.884.823-1.6 1.536-2.253 2.187a52 52 0 0 1-1.967 1.893c-.446.4-.886.769-1.328 1.104l3.427-11.924c.252.078.71-.333 1.167-.743q.143-.129.282-.25");
}

.zmwy5m-lr {
  fill: var(--svg-color--472c33, #472C33);
  d: path("M28.92 13.697c-.962-1.437-2.828-1.782-4.375-.438c-.76.661-1.648 1.618-1.648.464v-3.097c.07-1.28.828-1.625 2.063-1.203c1.756.446 3.168-.964 3.43-2.164c.203-.938-.008-2.441-1.61-3.203c-3.297-1.422-7.36-.203-8.9 3.333l-3.302 2.334H2.538v6.583c0 7.719 3.982 12.219 10.456 12.219c3.26 0 5.55-1.252 8.003-3.451c1.31-1.175 2.412-2.398 4.22-4.08c2.032-2.22 5.61-4.454 3.704-7.297");
}

</style>
