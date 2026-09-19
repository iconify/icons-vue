<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i72SNkd)"><path fill="url(#iMGDYIc)" class="j7rhm6bms"/><path fill="url(#i7RZAtd)" class="j7rhm6bms"/></g><g filter="url(#iNOHxPd)"><path fill="url(#iDwvqye)" class="a8j66jbwz"/><path fill="url(#ipDxo5P)" class="a8j66jbwz"/><path fill="url(#isn3pMc)" class="a8j66jbwz"/></g><g filter="url(#iqWSxre)"><path fill="url(#iCSmvov)" class="vbsj3vrgx"/><path fill="url(#i9d9Ohf)" class="vbsj3vrgx"/></g><g filter="url(#iCeWsAe)"><path fill="url(#iqA1kDe)" class="xyokq8xzu"/></g><path fill="url(#iWhCPud)" class="xyokq8xzu"/><g filter="url(#iOVl1Nd)"><path fill="url(#itMU4se)" class="idzufbb0m"/></g><defs><radialGradient id="iMGDYIc" cx="0" cy="0" r="1" gradientTransform="matrix(1.28127 3.34374 -2.19036 .83931 16.188 16.14)" gradientUnits="userSpaceOnUse"><stop class="uqhl3z1qr"/><stop offset="1" class="lcdxabc3l"/></radialGradient><radialGradient id="i7RZAtd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.1875 -2.46874 1.58642 -2.0483 19.594 17.515)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="btfegqcop"/><stop offset="1" class="u7ozbpb3k"/></radialGradient><radialGradient id="iDwvqye" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 7.375 -2.08313 .30894 19.625 13.578)" gradientUnits="userSpaceOnUse"><stop class="znyn2wb9y"/><stop offset="1" class="vqm1q7nqi"/></radialGradient><radialGradient id="ipDxo5P" cx="0" cy="0" r="1" gradientTransform="rotate(87.785 2.507 17.275)scale(1.41512 1.2626)" gradientUnits="userSpaceOnUse"><stop class="pi6vuobte"/><stop offset=".99" class="nqidp2b7x"/></radialGradient><radialGradient id="iCSmvov" cx="0" cy="0" r="1" gradientTransform="rotate(101.967 6.956 16.094)scale(7.33679 1.03879)" gradientUnits="userSpaceOnUse"><stop class="t8hh4lgpi"/><stop offset="1" class="x2jzt5xbj"/></radialGradient><radialGradient id="i9d9Ohf" cx="0" cy="0" r="1" gradientTransform="matrix(-.1502 1.05142 -1.09912 -.15702 24.099 13.203)" gradientUnits="userSpaceOnUse"><stop class="d8rm47bcu"/><stop offset="1" class="chtsw1bas"/></radialGradient><radialGradient id="iqA1kDe" cx="0" cy="0" r="1" gradientTransform="matrix(-18.51782 11.00907 -16.0961 -27.07447 22.393 13.131)" gradientUnits="userSpaceOnUse"><stop class="pakg5cbjz"/><stop offset="1" class="fmhkqrb5m"/></radialGradient><radialGradient id="iWhCPud" cx="0" cy="0" r="1" gradientTransform="matrix(4.20776 -3.2772 7.0537 9.0566 2.48 22.57)" gradientUnits="userSpaceOnUse"><stop class="h673f0b8e"/><stop offset="1" class="hwqn56bsj"/></radialGradient><radialGradient id="itMU4se" cx="0" cy="0" r="1" gradientTransform="rotate(-17.266 63.201 -1.622)scale(12.541 9.77596)" gradientUnits="userSpaceOnUse"><stop class="ejfg4jbun"/><stop offset=".79" class="p35klubgi"/></radialGradient><filter id="i72SNkd" width="5.726" height="7.719" x="14.151" y="14.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.223529 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6669"/></filter><filter id="iNOHxPd" width="4.609" height="7.162" x="17.57" y="12.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.254902 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6669"/></filter><filter id="iqWSxre" width="5.64" height="7.217" x="20.125" y="12.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.176471 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6669"/></filter><filter id="iCeWsAe" width="29.181" height="19.207" x="2.047" y="6.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.129412 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6669"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.188235 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_6669" result="effect2_innerShadow_20020_6669"/></filter><filter id="iOVl1Nd" width="26.184" height="17.765" x="3.339" y="7.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6669" stdDeviation=".75"/></filter><linearGradient id="isn3pMc" x1="17.57" x2="19.219" y1="17.609" y2="17.25" gradientUnits="userSpaceOnUse"><stop class="yohxxxbcm"/><stop offset="1" class="my1j5j-gr"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:palm-up-hand-dark" /></template>
<style>
.a8j66jbwz {
  d: path("M19.43 12.931a2.07 2.07 0 0 0-1.85 2.262l.491 4.89l4.109-.412l-.488-4.893a2.064 2.064 0 0 0-2.262-1.847");
}

.btfegqcop {
  stop-color: var(--svg-color--1f100e, #1F100E);
}

.chtsw1bas {
  stop-color: var(--svg-color--5f4a47, #5F4A47);
  stop-opacity: 0;
}

.d8rm47bcu {
  stop-color: var(--svg-color--5f4a47, #5F4A47);
}

.ejfg4jbun {
  stop-color: var(--svg-color--5f4949, #5F4949);
  stop-opacity: 0;
}

.fmhkqrb5m {
  stop-color: var(--svg-color--442b2c, #442B2C);
}

.ft5dv1b6b {
  fill: none;
}

.h673f0b8e {
  stop-color: var(--svg-color--523f3e, #523F3E);
}

.hwqn56bsj {
  stop-color: var(--svg-color--523f3e, #523F3E);
  stop-opacity: 0;
}

.idzufbb0m {
  d: path("m21.04 22.533l6.74-5.94a.718.718 0 0 0-.947-1.08l-4.854 4.238a2 2 0 0 1-1.497.485l-6.272-.572a4 4 0 0 1-3.637-3.983v-.187a4 4 0 0 1 .949-2.586l.188-.221a3 3 0 0 1 1.952-1.041l1.906-.215a3 3 0 0 0 1.734-.81l.95-.905a.55.55 0 0 0-.715-.834l-.277.213a2.86 2.86 0 0 1-1.992.585l-2.297-.197A4 4 0 0 0 9.78 10.66l-3.79 3.844a4 4 0 0 0-1.048 3.707l.276 1.198a5 5 0 0 0 4.724 3.875l8.334.247a4 4 0 0 0 2.764-.998");
}

.j7rhm6bms {
  d: path("M15.5 14.867c-1.097.392-1.61 1.624-1.219 2.765l1.969 4.836l3.627-1.316l-1.683-4.922c-.389-1.146-1.596-1.753-2.693-1.363");
}

.lcdxabc3l {
  stop-color: var(--svg-color--2c1916, #2C1916);
}

.my1j5j-gr {
  stop-color: var(--svg-color--392724, #392724);
  stop-opacity: 0;
}

.nqidp2b7x {
  stop-color: var(--svg-color--574544, #574544);
  stop-opacity: 0;
}

.p35klubgi {
  stop-color: var(--svg-color--5f4949, #5F4949);
}

.pakg5cbjz {
  stop-color: var(--svg-color--4b2e36, #4B2E36);
}

.pi6vuobte {
  stop-color: var(--svg-color--574544, #574544);
}

.t8hh4lgpi {
  stop-color: var(--svg-color--554140, #554140);
}

.u7ozbpb3k {
  stop-color: var(--svg-color--1f100e, #1F100E);
  stop-opacity: 0;
}

.uqhl3z1qr {
  stop-color: var(--svg-color--4a3938, #4A3938);
}

.vbsj3vrgx {
  d: path("M24.09 12.045a2.05 2.05 0 0 0-2.388 1.64l-.62 4.098a2 2 0 0 1-.738 1.271l-.219.172h4.717l.89-4.792a2.05 2.05 0 0 0-1.641-2.39");
}

.vqm1q7nqi {
  stop-color: var(--svg-color--392421, #392421);
}

.x2jzt5xbj {
  stop-color: var(--svg-color--412a27, #412A27);
}

.xyokq8xzu {
  d: path("M12.625 15.954c0 1.702 1.672 2.881 3.484 2.881h3.657c.8 0 1.174-.137 1.656-.62l4.03-3.455c1.062-.986 2.602-1.354 3.772-.25c1.243 1.173.813 2.76-.311 3.772l-5.867 5.1c-1.406 1.315-2.26 1.815-4.01 1.815l-8.715.029c-4.825.029-8.274-2.46-8.274-6.851c0-2.125 1.594-4.368 3-5.782l2.062-2c1.493-1.398 2.664-2.039 4.094-2.414s3.305-.14 3.305-.14c.59 0 1.055-.078 1.562-.383c.906-.546 2.197-.545 2.946.203c.64.555 1 1.5.718 2.476c-.247.616-.51.904-1.039 1.329c-1.077.866-2.66 1.216-3.966 1.32c-1.448.25-2.104 1.285-2.104 2.97");
}

.yohxxxbcm {
  stop-color: var(--svg-color--392724, #392724);
}

.znyn2wb9y {
  stop-color: var(--svg-color--574543, #574543);
}

</style>
