<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iopcqwd)"><path class="q1aab4b_h"/><path fill="url(#ikQ0iCd)" class="vtudzmb2m"/></g><path fill="url(#iFHXjOe)" class="vtudzmb2m"/><path fill="url(#isHeLud)" class="vtudzmb2m"/><path fill="url(#iTe1oDx)" class="vtudzmb2m"/><path fill="url(#iBSNiTc)" class="vtudzmb2m"/><path fill="url(#iDKYNXS)" class="vtudzmb2m"/><path fill="url(#i9Lzk9b)" class="vtudzmb2m"/><g filter="url(#i2zPINc)" class="zkg1ohbml"><path class="fqqb6yb8p"/><path class="tvnatgb6q"/><path class="c5kj6ifzd"/></g><path class="qkvgkxbna"/><path fill="url(#iV5uzAc)" class="cauchjb2x"/><path fill="url(#iAwi36d)" class="cauchjb2x"/><path fill="url(#iEnucAb)" class="cauchjb2x"/><path fill="url(#iurEtwy)" class="cauchjb2x"/><g filter="url(#ifj2sbb)"><rect class="dki-6b40m"/></g><path class="tquskdjak"/><path fill="url(#i2WKVoc)" class="ul8ir3bey"/><path fill="url(#iOtHjkg)" class="ul8ir3bey"/><path fill="url(#iSZoE1B)" class="ul8ir3bey"/><g filter="url(#ieEZEpd)"><rect class="dvxej4bqk"/></g><path class="kk4u6x1cc"/><path fill="url(#id5ScFe)" class="gsdgegf-i"/><path fill="url(#ieErD3d)" class="gsdgegf-i"/><path fill="url(#iIcT1uc)" class="gsdgegf-i"/><path fill="url(#ifkAMqc)" class="zfw4f3b1v"/><path fill="url(#iUlg4Ne)" class="zfw4f3b1v"/><path fill="url(#iuVekkb)" class="zfw4f3b1v"/><defs><radialGradient id="ikQ0iCd" cx="0" cy="0" r="1" gradientTransform="rotate(138.108 7.87 13)scale(14.0119 10.4377)" gradientUnits="userSpaceOnUse"><stop class="a7b5rx4hj"/><stop offset="1" class="dfnes2bcq"/></radialGradient><radialGradient id="iFHXjOe" cx="0" cy="0" r="1" gradientTransform="rotate(-123.041 14.95 -1.841)scale(2.55392 2.71595)" gradientUnits="userSpaceOnUse"><stop class="t_h6y93xq"/><stop offset="1" class="go7pnzbmu"/></radialGradient><radialGradient id="isHeLud" cx="0" cy="0" r="1" gradientTransform="rotate(70.346 9.566 16.832)scale(5.07426 17.3147)" gradientUnits="userSpaceOnUse"><stop class="uspel7bnu"/><stop offset="1" class="i6sr6ypje"/></radialGradient><radialGradient id="iTe1oDx" cx="0" cy="0" r="1" gradientTransform="rotate(153.85 12.672 6.153)scale(2.56455 2.04967)" gradientUnits="userSpaceOnUse"><stop class="q4cc3mx-x"/><stop offset="1" class="azsexxb8y"/></radialGradient><radialGradient id="iBSNiTc" cx="0" cy="0" r="1" gradientTransform="matrix(1.61753 1.77534 -9.13543 8.3234 18.598 4.912)" gradientUnits="userSpaceOnUse"><stop class="imredum9e"/><stop offset="1" class="hkiqiobnq"/></radialGradient><radialGradient id="iDKYNXS" cx="0" cy="0" r="1" gradientTransform="matrix(1.14411 0 0 3.35343 17.611 7.99)" gradientUnits="userSpaceOnUse"><stop class="qw8npu9lr"/><stop offset="1" class="eeqmv0bsu"/></radialGradient><radialGradient id="i9Lzk9b" cx="0" cy="0" r="1" gradientTransform="matrix(-23.07864 10.46505 -10.22957 -22.55934 27.226 12.987)" gradientUnits="userSpaceOnUse"><stop offset=".927" class="lt3qtcapj"/><stop offset="1" class="rsxfn_k5r"/></radialGradient><radialGradient id="iAwi36d" cx="0" cy="0" r="1" gradientTransform="matrix(4.61755 5.37902 -4.6731 4.01156 3.133 8.621)" gradientUnits="userSpaceOnUse"><stop offset=".552" class="sh8skvhrj"/><stop offset="1" class="qhue76bjg"/></radialGradient><radialGradient id="iEnucAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.74306 -1.49874 0 6.484 11.043)" gradientUnits="userSpaceOnUse"><stop class="bvxf3272v"/><stop offset="1" class="c8navzydj"/></radialGradient><radialGradient id="iOtHjkg" cx="0" cy="0" r="1" gradientTransform="matrix(4.49973 6.05545 -5.09585 3.78666 7.922 7.967)" gradientUnits="userSpaceOnUse"><stop offset=".552" class="sh8skvhrj"/><stop offset="1" class="qhue76bjg"/></radialGradient><radialGradient id="iSZoE1B" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.21375 -1.4605 0 11.188 10.693)" gradientUnits="userSpaceOnUse"><stop class="bvxf3272v"/><stop offset="1" class="c8navzydj"/></radialGradient><radialGradient id="ieErD3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.91432 -6.68636 0 15.69 7.684)" gradientUnits="userSpaceOnUse"><stop offset=".662" class="sh8skvhrj"/><stop offset="1" class="qhue76bjg"/></radialGradient><radialGradient id="iIcT1uc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.07727 -2.31463 0 16.754 9.526)" gradientUnits="userSpaceOnUse"><stop class="pr8asrb6m"/><stop offset="1" class="iury1fgsr"/></radialGradient><radialGradient id="ifkAMqc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.45056 7.51928 -4.3011 -1.40174 23.97 11.777)" gradientUnits="userSpaceOnUse"><stop class="uxwrv0rcj"/><stop offset="1" class="zvkfssboi"/></radialGradient><radialGradient id="iUlg4Ne" cx="0" cy="0" r="1" gradientTransform="matrix(-2.7342 1.76829 -1.38594 -2.14299 28.75 14.165)" gradientUnits="userSpaceOnUse"><stop class="msz2nkx7f"/><stop offset="1" class="sb7dl_nwc"/></radialGradient><radialGradient id="iuVekkb" cx="0" cy="0" r="1" gradientTransform="matrix(1.1188 .37926 -2.2621 6.67318 22.105 15.873)" gradientUnits="userSpaceOnUse"><stop offset=".521" class="mfes0jfhi"/><stop offset="1" class="daazlyncz"/></radialGradient><linearGradient id="iV5uzAc" x1="3.103" x2="5.926" y1="12.014" y2="12.014" gradientUnits="userSpaceOnUse"><stop class="pn3502byk"/><stop offset="1" class="tegmsxbpg"/></linearGradient><linearGradient id="iurEtwy" x1="2.43" x2="3.039" y1="11.043" y2="11.043" gradientUnits="userSpaceOnUse"><stop class="sl6h9922k"/><stop offset="1" class="l8wm-5b2g"/></linearGradient><linearGradient id="i2WKVoc" x1="7.893" x2="10.645" y1="11.787" y2="11.787" gradientUnits="userSpaceOnUse"><stop class="pn3502byk"/><stop offset="1" class="tegmsxbpg"/></linearGradient><linearGradient id="id5ScFe" x1="12.792" x2="15.587" y1="11.657" y2="11.657" gradientUnits="userSpaceOnUse"><stop class="pn3502byk"/><stop offset="1" class="tegmsxbpg"/></linearGradient><filter id="iopcqwd" width="27.675" height="25.549" x="2.538" y="2.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.368627 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1993"/></filter><filter id="i2zPINc" width="16.091" height="12.26" x="1.909" y="6.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1993" stdDeviation="1"/></filter><filter id="ifj2sbb" width="2.266" height="8.313" x="6.249" y="6.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1993" stdDeviation=".375"/></filter><filter id="ieEZEpd" width="2.266" height="8.719" x="11.186" y="6.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1993" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pinching-hand-medium" /></template>
<style>
.a7b5rx4hj {
  stop-color: var(--svg-color--cca189, #CCA189);
}

.azsexxb8y {
  stop-color: var(--svg-color--cea68e, #CEA68E);
  stop-opacity: 0;
}

.bvxf3272v {
  stop-color: var(--svg-color--b28c7d, #B28C7D);
}

.c5kj6ifzd {
  d: path("M6.192 9.051a2.28 2.28 0 0 0-2.283 2.266v2.55a2.28 2.28 0 0 0 2.283 2.267a2.28 2.28 0 0 0 2.282-2.267v-2.55a2.273 2.273 0 0 0-2.282-2.266");
}

.c8navzydj {
  stop-color: var(--svg-color--b28c7d, #B28C7D);
  stop-opacity: 0;
}

.cauchjb2x {
  d: path("M5.45 6.577c-1.606 0-2.912 1.19-2.912 2.655v3.622c0 1.464 1.306 2.655 2.912 2.655s2.912-1.19 2.912-2.655V9.232c0-1.464-1.306-2.655-2.912-2.655");
}

.daazlyncz {
  stop-color: var(--svg-color--c29a85, #C29A85);
  stop-opacity: 0;
}

.dfnes2bcq {
  stop-color: var(--svg-color--cca189, #CCA189);
  stop-opacity: 0;
}

.dki-6b40m {
  width: 0.766px;
  height: 6.813px;
  x: 6.999px;
  y: 7.54px;
  fill: var(--svg-color--714e38, #714E38);
  rx: 0.383px;
}

.dvxej4bqk {
  width: 0.766px;
  height: 7.219px;
  x: 11.936px;
  y: 7.134px;
  fill: var(--svg-color--714e38, #714E38);
  rx: 0.383px;
}

.eeqmv0bsu {
  stop-color: var(--svg-color--7a523c, #7A523C);
  stop-opacity: 0;
}

.fqqb6yb8p {
  d: path("M13.338 8.462a2.656 2.656 0 0 0-2.662 2.643v2.974c0 1.457 1.194 2.644 2.662 2.644S16 15.536 16 14.079v-2.974a2.65 2.65 0 0 0-2.662-2.643");
}

.ft5dv1b6b {
  fill: none;
}

.go7pnzbmu {
  stop-color: var(--svg-color--895266, #895266);
  stop-opacity: 0;
}

.gsdgegf-i {
  d: path("M15.116 5.525c-1.59 0-2.883 1.284-2.883 2.862v4.349c0 1.578 1.294 2.862 2.883 2.862s2.883-1.284 2.883-2.862v-4.35a2.87 2.87 0 0 0-2.883-2.861");
}

.hkiqiobnq {
  stop-color: var(--svg-color--8e7462, #8E7462);
  stop-opacity: 0;
}

.i6sr6ypje {
  stop-color: var(--svg-color--a68169, #A68169);
  stop-opacity: 0;
}

.imredum9e {
  stop-color: var(--svg-color--8e7462, #8E7462);
}

.iury1fgsr {
  stop-color: var(--svg-color--cfa689, #CFA689);
  stop-opacity: 0;
}

.kk4u6x1cc {
  fill: var(--svg-color--af8471, #AF8471);
  d: path("M15.116 5.525c-1.59 0-2.883 1.284-2.883 2.862v4.349c0 1.578 1.294 2.862 2.883 2.862s2.883-1.284 2.883-2.862v-4.35a2.87 2.87 0 0 0-2.883-2.861");
}

.l8wm-5b2g {
  stop-color: var(--svg-color--9c7766, #9C7766);
  stop-opacity: 0;
}

.lt3qtcapj {
  stop-color: var(--svg-color--9e736a, #9E736A);
  stop-opacity: 0;
}

.mfes0jfhi {
  stop-color: var(--svg-color--c29a85, #C29A85);
}

.msz2nkx7f {
  stop-color: var(--svg-color--cea58f, #CEA58F);
}

.pn3502byk {
  stop-color: var(--svg-color--91715c, #91715C);
}

.pr8asrb6m {
  stop-color: var(--svg-color--cfa689, #CFA689);
}

.q1aab4b_h {
  fill: var(--svg-color--ae7f78, #AE7F78);
  d: path("M28.92 13.697c-.962-1.437-2.828-1.782-4.375-.438c-.76.661-1.648 1.618-1.648.464v-3.097c.07-1.28.828-1.625 2.063-1.203c1.756.446 3.168-.964 3.43-2.164c.203-.938-.008-2.441-1.61-3.203c-3.297-1.422-7.36-.203-8.9 3.333l-3.302 2.334H2.538v6.583c0 7.719 3.982 12.219 10.456 12.219c3.26 0 5.55-1.252 8.003-3.451c1.31-1.175 2.412-2.398 4.22-4.08c2.032-2.22 5.61-4.454 3.704-7.297");
}

.q4cc3mx-x {
  stop-color: var(--svg-color--cea68e, #CEA68E);
}

.qhue76bjg {
  stop-color: var(--svg-color--90596a, #90596A);
}

.qkvgkxbna {
  fill: var(--svg-color--a47c6b, #A47C6B);
  d: path("M5.45 6.577c-1.606 0-2.912 1.19-2.912 2.655v3.622c0 1.464 1.306 2.655 2.912 2.655s2.912-1.19 2.912-2.655V9.232c0-1.464-1.306-2.655-2.912-2.655");
}

.qw8npu9lr {
  stop-color: var(--svg-color--7a523c, #7A523C);
}

.rsxfn_k5r {
  stop-color: var(--svg-color--9e736a, #9E736A);
}

.sb7dl_nwc {
  stop-color: var(--svg-color--cea58f, #CEA58F);
  stop-opacity: 0;
}

.sh8skvhrj {
  stop-color: var(--svg-color--90596a, #90596A);
  stop-opacity: 0;
}

.sl6h9922k {
  stop-color: var(--svg-color--9c7766, #9C7766);
}

.t_h6y93xq {
  stop-color: var(--svg-color--895266, #895266);
}

.tegmsxbpg {
  stop-color: var(--svg-color--91715c, #91715C);
  stop-opacity: 0;
}

.tquskdjak {
  fill: var(--svg-color--a47c6b, #A47C6B);
  d: path("M10.18 5.665c-1.565 0-2.838 1.23-2.838 2.744v4.569c0 1.513 1.273 2.743 2.838 2.743s2.838-1.23 2.838-2.743v-4.58c0-1.512-1.273-2.733-2.838-2.733");
}

.tvnatgb6q {
  d: path("M9.53 8.866A2.527 2.527 0 0 0 7 11.38v2.829a2.527 2.527 0 0 0 2.532 2.514a2.527 2.527 0 0 0 2.532-2.514v-2.83A2.52 2.52 0 0 0 9.53 8.867");
}

.ul8ir3bey {
  d: path("M10.18 5.665c-1.565 0-2.838 1.23-2.838 2.744v4.569c0 1.513 1.273 2.743 2.838 2.743s2.838-1.23 2.838-2.743v-4.58c0-1.512-1.273-2.733-2.838-2.733");
}

.uspel7bnu {
  stop-color: var(--svg-color--a68169, #A68169);
}

.uxwrv0rcj {
  stop-color: var(--svg-color--876351, #876351);
}

.vtudzmb2m {
  d: path("M28.92 13.697c-.962-1.437-2.828-1.782-4.375-.438c-.76.661-1.648 1.618-1.648.464v-3.097c.07-1.28.828-1.625 2.063-1.203c1.756.446 3.168-.964 3.43-2.164c.203-.938-.008-2.441-1.61-3.203c-3.297-1.422-7.36-.203-8.9 3.333l-3.302 2.334H2.538v6.583c0 7.719 3.982 12.219 10.456 12.219c3.26 0 5.55-1.252 8.003-3.451c1.31-1.175 2.412-2.398 4.22-4.08c2.032-2.22 5.61-4.454 3.704-7.297");
}

.zfw4f3b1v {
  d: path("M24.546 13.26c1.546-1.345 3.412-1 4.375.437c1.525 2.275-.461 4.16-2.356 5.96a28 28 0 0 0-1.348 1.336c-.884.823-1.6 1.536-2.253 2.187a52 52 0 0 1-1.967 1.893c-.446.4-.886.769-1.328 1.104l3.427-11.924c.252.078.71-.333 1.167-.743q.143-.129.282-.25");
}

.zkg1ohbml {
  fill: var(--svg-color--633740, #633740);
}

.zvkfssboi {
  stop-color: var(--svg-color--876351, #876351);
  stop-opacity: 0;
}

</style>
