<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#isnF3kc)" class="vjzo1ubqw"/><path fill="url(#iK4DwAd)" class="vjzo1ubqw"/><path fill="url(#ief1XDd)" class="vjzo1ubqw"/><path fill="url(#icXckac)" class="vjzo1ubqw"/><path fill="url(#i5iNTpg)" class="vjzo1ubqw"/><path fill="url(#iw5y23e)" class="vjzo1ubqw"/><path fill="url(#iOHVYae)" class="e88814b2x"/><g filter="url(#iK17Uae)"><path class="tnn9s-osu"/></g><g filter="url(#iH5JmRc)"><ellipse fill="url(#iPZEkEe)" transform="rotate(-44.19 18.51 16.7)" class="xomnqgudv"/></g><g filter="url(#i8I8UOe)"><ellipse fill="url(#izNWqDd)" transform="rotate(-128.955 9.75 17.078)" class="sjd570wjl"/></g><path fill="url(#iC6JoBb)" class="n-y6zh85u"/><path fill="url(#i67Fk2d)" class="n-y6zh85u"/><path fill="url(#iCcrEsd)" class="n-y6zh85u"/><path fill="url(#i2ydUBb)" class="n-y6zh85u"/><path fill="url(#i6BWjxv)" class="n-y6zh85u"/><path fill="url(#iYDc3pe)" class="n-y6zh85u"/><path fill="url(#iNrFRUd)" class="i_y3shssp"/><g filter="url(#iozgUUB)"><ellipse fill="url(#ikDvBsb)" transform="rotate(-44.19 27.605 4.958)" class="lj917xs4v"/></g><g filter="url(#iIPUVXd)"><ellipse fill="url(#iM2djXb)" transform="rotate(-128.955 21.843 5.207)" class="pnz9urkek"/></g><g filter="url(#irBGLpe)"><path class="hr9zgibkq"/></g><defs><radialGradient id="isnF3kc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -23.9627 40.7367 0 14.16 29.77)" gradientUnits="userSpaceOnUse"><stop class="ejc52zb_a"/><stop offset=".596" class="xg2pw8btp"/><stop offset="1" class="r-3kexbeb"/></radialGradient><radialGradient id="iK4DwAd" cx="0" cy="0" r="1" gradientTransform="rotate(142.986 5.77 11.28)scale(19.29 36.132)" gradientUnits="userSpaceOnUse"><stop offset=".483" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="ief1XDd" cx="0" cy="0" r="1" gradientTransform="rotate(-158.663 9.498 9.362)scale(16.7324 23.6536)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="icXckac" cx="0" cy="0" r="1" gradientTransform="rotate(90 -3.47 15.146)scale(14.5627)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></radialGradient><radialGradient id="iPZEkEe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.52034 -.2547 .17199 -3.05234 21.59 17.348)" gradientUnits="userSpaceOnUse"><stop class="pl211ybaw"/><stop offset="1" class="qnbh2pn9v"/></radialGradient><radialGradient id="izNWqDd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.30787 -.19332 .10239 -4.40002 12.055 17.647)" gradientUnits="userSpaceOnUse"><stop class="pl211ybaw"/><stop offset="1" class="qnbh2pn9v"/></radialGradient><radialGradient id="iC6JoBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -15.7644 26.7994 0 24.744 13.556)" gradientUnits="userSpaceOnUse"><stop class="ejc52zb_a"/><stop offset=".596" class="xg2pw8btp"/><stop offset="1" class="r-3kexbeb"/></radialGradient><radialGradient id="i67Fk2d" cx="0" cy="0" r="1" gradientTransform="rotate(142.986 12.519 6.988)scale(12.6903 23.7702)" gradientUnits="userSpaceOnUse"><stop offset=".483" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="iCcrEsd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.25329 -4.00522 5.66191 -14.4944 25.257 8.141)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="i2ydUBb" cx="0" cy="0" r="1" gradientTransform="rotate(90 8.446 14.664)scale(9.58038)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></radialGradient><radialGradient id="ikDvBsb" cx="0" cy="0" r="1" gradientTransform="rotate(-176.775 14.892 2.275)scale(2.97851 2.01123)" gradientUnits="userSpaceOnUse"><stop class="pl211ybaw"/><stop offset="1" class="qnbh2pn9v"/></radialGradient><radialGradient id="iM2djXb" cx="0" cy="0" r="1" gradientTransform="rotate(-178.667 11.712 2.655)scale(5.46698 2.89543)" gradientUnits="userSpaceOnUse"><stop class="pl211ybaw"/><stop offset="1" class="qnbh2pn9v"/></radialGradient><linearGradient id="i5iNTpg" x1="13.283" x2="19.177" y1="20.321" y2="27.334" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient><linearGradient id="iw5y23e" x1="12.553" x2="5.637" y1="20.613" y2="28.406" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient><linearGradient id="iOHVYae" x1="14.813" x2="12.747" y1="15.329" y2="13.058" gradientUnits="userSpaceOnUse"><stop offset=".41" class="k0jhnr2iw"/><stop offset=".834" class="yxx9jebfv"/></linearGradient><linearGradient id="i6BWjxv" x1="24.167" x2="28.044" y1="7.34" y2="11.954" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient><linearGradient id="iYDc3pe" x1="23.687" x2="19.137" y1="7.532" y2="12.659" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient><linearGradient id="iNrFRUd" x1="25.174" x2="23.814" y1="4.056" y2="2.562" gradientUnits="userSpaceOnUse"><stop offset=".41" class="k0jhnr2iw"/><stop offset=".834" class="yxx9jebfv"/></linearGradient><filter id="iK17Uae" width="7.323" height="13.945" x="10.514" y="13.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_5028" stdDeviation="1"/></filter><filter id="iH5JmRc" width="8.283" height="8.229" x="14.368" y="12.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_5028" stdDeviation=".75"/></filter><filter id="i8I8UOe" width="8.903" height="9.627" x="5.299" y="12.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_5028" stdDeviation=".75"/></filter><filter id="iozgUUB" width="6.475" height="6.44" x="24.368" y="1.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_5028" stdDeviation=".75"/></filter><filter id="iIPUVXd" width="6.884" height="7.36" x="18.401" y="1.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_5028" stdDeviation=".75"/></filter><filter id="irBGLpe" width="4.186" height="10.6" x="22.662" y="3.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_5028" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:two-hearts" /></template>
<style>
.e88814b2x {
  d: path("M11.682 14.322c.84.851 2.224.573 3.028-.313c.81-.892 1.882-1.7 3.24-1.787c-1.343-.258-2.807.026-4.097 1.04l-.35.27c-.357.273-.736.563-1.025.844c-.186.18-.514.2-.706.025z");
}

.ejc52zb_a {
  stop-color: var(--svg-color--f12e52, #F12E52);
}

.fdfp5-b0w {
  stop-color: var(--svg-color--b91d43, #B91D43);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.hr9zgibkq {
  fill: var(--svg-color--fa1c56, #FA1C56);
  d: path("M23.662 4.376v8.502c1.078-1.143 2.715-5.124 2.018-7.367c-.352-1.135-1.538-1.41-2.018-1.135");
}

.i_y3shssp {
  d: path("M23.114 3.393c.553.56 1.463.377 1.992-.206c.533-.586 1.238-1.118 2.132-1.175c-.884-.17-1.847.017-2.696.684l-.23.178c-.235.18-.344.279-.567.42c-.123.119-.611.114-.738 0c.133.124.07.1.107.1");
}

.k0jhnr2iw {
  stop-color: var(--svg-color--c12372, #C12372);
  stop-opacity: 0;
}

.lj35z3s3o {
  stop-color: var(--svg-color--b91d43, #B91D43);
}

.lj917xs4v {
  cx: 27.605px;
  cy: 4.958px;
  rx: 2.014px;
  ry: 1.386px;
}

.n-y6zh85u {
  d: path("M22.514 13.407a1.58 1.58 0 0 0 1.688-.01c1.765-1.097 4.41-3.248 5.5-5.979c1.736-3.857-2.342-6.937-5.16-4.722c-.205.161-.447.339-.661.517c-.257.213-.698.233-.955.02a14 14 0 0 0-.932-.696c-2.402-1.626-6.774.517-4.91 5.09c.635 1.906 3.488 4.554 5.43 5.78");
}

.pl211ybaw {
  stop-color: var(--svg-color--ff93ba, #FF93BA);
}

.pnz9urkek {
  cx: 21.843px;
  cy: 5.207px;
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 2.569px;
  ry: 1.386px;
}

.qnbh2pn9v {
  stop-color: var(--svg-color--ff73a6, #FF73A6);
  stop-opacity: 0;
}

.qudiit10p {
  stop-color: var(--svg-color--ff7af2, #FF7AF2);
  stop-opacity: 0;
}

.r-3kexbeb {
  stop-color: var(--svg-color--ff4ec6, #FF4EC6);
}

.sjd570wjl {
  cx: 9.75px;
  cy: 17.078px;
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 3.905px;
  ry: 2.107px;
}

.tnn9s-osu {
  fill: var(--svg-color--fa1c56, #FA1C56);
  d: path("M12.514 16.395v8.302c0 .905 1.02 1.266 1.48.487c1.275-2.155 2.352-5.189 1.589-7.644c-.428-1.376-1.661-1.92-2.514-1.871c-.358.02-.555.368-.555.726");
}

.vjzo1ubqw {
  d: path("M11.2 29.805c.528.31 1.176.294 1.704-.017c2.664-1.57 7.042-4.968 8.791-9.348c2.64-5.864-3.558-10.545-7.842-7.178c-.4.314-.892.669-1.267 1.012c-.247.226-.674.248-.925.029a20 20 0 0 0-1.681-1.284c-3.652-2.47-10.297.787-7.463 7.738c1.012 3.041 5.74 7.325 8.682 9.048");
}

.xg2pw8btp {
  stop-color: var(--svg-color--ff3b79, #FF3B79);
}

.xomnqgudv {
  cx: 18.509px;
  cy: 16.7px;
  rx: 3.062px;
  ry: 2.107px;
}

.yw57-9naf {
  stop-color: var(--svg-color--ffbce6, #FFBCE6);
}

.yxx9jebfv {
  stop-color: var(--svg-color--b5286e, #B5286E);
}

</style>
