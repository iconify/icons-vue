<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i2igyac)"><path class="l0dl69ovb"/></g><path stroke="url(#iax6Ued)" class="tuuuhpb-w"/><g filter="url(#iq2fype)"><path stroke="url(#ilr8Exb)" class="t7cy22bgn"/></g><g filter="url(#iH0dOgb)"><path fill="url(#iC9ruHb)" class="lvp7sdbvk"/><path fill="url(#iPYK3ec)" class="lvp7sdbvk"/></g><g filter="url(#iqijHhr)"><path fill="url(#i6i5uwd)" class="d-5720bml"/></g><g filter="url(#iHObaXJ)"><path fill="url(#iMFgUod)" class="ly94tlbtw"/><path fill="url(#ixQLptb)" class="ly94tlbtw"/><path fill="url(#iyIE0rd)" class="ly94tlbtw"/></g><path fill="url(#igZcY7h)" class="ly94tlbtw"/><path fill="url(#im5oC7G)" class="ly94tlbtw"/><path fill="url(#iyG2Tjd)" class="vik643b9n"/><path fill="url(#ihtVBFZ)" class="vik643b9n"/><path fill="url(#ijYjTpb)" class="vik643b9n"/><g filter="url(#i3mvwSd)"><path fill="url(#ifIHoJh)" class="z9_nal4ca"/></g><path fill="url(#icMqSMe)" class="eebsajypd"/><path fill="url(#iCGlB2k)" class="eebsajypd"/><path fill="url(#iBvhzLc)" class="eebsajypd"/><defs><linearGradient id="iC9ruHb" x1="10.365" x2="13.051" y1="15.536" y2="17.666" gradientUnits="userSpaceOnUse"><stop class="c2rp26eeh"/><stop offset="1" class="zs_uykj5i"/></linearGradient><linearGradient id="i6i5uwd" x1="5.228" x2="18.227" y1="18.625" y2="27.5" gradientUnits="userSpaceOnUse"><stop class="r9iha0bnv"/><stop offset="1" class="ab2pw6l5o"/></linearGradient><linearGradient id="iMFgUod" x1="19.54" x2="14.009" y1="5.219" y2="12.688" gradientUnits="userSpaceOnUse"><stop class="l5dzsbcmz"/><stop offset="1" class="a3ra2_u5q"/></linearGradient><linearGradient id="igZcY7h" x1="19.758" x2="19.193" y1="4.867" y2="5.771" gradientUnits="userSpaceOnUse"><stop class="o-4z4tbfb"/><stop offset="1" class="ps0a30bgj"/></linearGradient><linearGradient id="iyG2Tjd" x1="19.645" x2="22.243" y1="3.568" y2="5.206" gradientUnits="userSpaceOnUse"><stop class="c7r012s9s"/><stop offset="1" class="a47qzkr4t"/></linearGradient><linearGradient id="ihtVBFZ" x1="18.634" x2="19.54" y1="3.5" y2="4" gradientUnits="userSpaceOnUse"><stop class="q590akbfi"/><stop offset="1" class="zheaq1xyz"/></linearGradient><linearGradient id="ifIHoJh" x1="3.728" x2="29.29" y1="29.188" y2="29.188" gradientUnits="userSpaceOnUse"><stop class="wpg65xr7s"/><stop offset="1" class="bdn7kzbkp"/></linearGradient><linearGradient id="icMqSMe" x1="12.133" x2="17.245" y1="10.995" y2="14.638" gradientUnits="userSpaceOnUse"><stop class="xbbbkxb3z"/><stop offset="1" class="ad-628bkt"/></linearGradient><linearGradient id="iCGlB2k" x1="18.177" x2="15.437" y1="15.626" y2="13.565" gradientUnits="userSpaceOnUse"><stop offset=".088" class="uwpipdi-h"/><stop offset="1" class="sz428bbhz"/></linearGradient><linearGradient id="iBvhzLc" x1="10.891" x2="11.936" y1="10.261" y2="11.052" gradientUnits="userSpaceOnUse"><stop class="okzohmbto"/><stop offset="1" class="as-7wxdfw"/></linearGradient><radialGradient id="iax6Ued" cx="0" cy="0" r="1" gradientTransform="matrix(2.91552 -3.47241 6.05948 5.08768 19.865 15.176)" gradientUnits="userSpaceOnUse"><stop offset=".339" class="bmi7uwb0q"/><stop offset="1" class="lthtirvxg"/></radialGradient><radialGradient id="ilr8Exb" cx="0" cy="0" r="1" gradientTransform="matrix(-11.1052 2.2275 -2.88252 -14.37076 27.563 16.552)" gradientUnits="userSpaceOnUse"><stop class="re5wblbnn"/><stop offset="1" class="mikez6ahl"/></radialGradient><radialGradient id="iPYK3ec" cx="0" cy="0" r="1" gradientTransform="rotate(127.117 2.23 11.104)scale(1.52001 1.49024)" gradientUnits="userSpaceOnUse"><stop class="lo6p9snyn"/><stop offset="1" class="dshj7nbsh"/></radialGradient><radialGradient id="ixQLptb" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 -4.68572 3.93023 .78634 14.54 15.25)" gradientUnits="userSpaceOnUse"><stop class="gbqt9ebka"/><stop offset="1" class="zhm0nvb0t"/></radialGradient><radialGradient id="iyIE0rd" cx="0" cy="0" r="1" gradientTransform="rotate(130.374 8.188 8.432)scale(3.81715 4.39177)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="iykszg4py"/><stop offset="1" class="b6zkafbbw"/></radialGradient><radialGradient id="im5oC7G" cx="0" cy="0" r="1" gradientTransform="matrix(-.08472 -1.88639 4.57273 -.20536 15.24 17.06)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="yx9fa1bzt"/><stop offset="1" class="l-vw7zbeq"/></radialGradient><radialGradient id="ijYjTpb" cx="0" cy="0" r="1" gradientTransform="rotate(126.573 9.76 7.271)scale(.60313 1.72845)" gradientUnits="userSpaceOnUse"><stop class="vbqb2_i_e"/><stop offset="1" class="ggdz-gb3i"/></radialGradient><filter id="i2igyac" width="8.895" height="19.065" x="18.555" y="10.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.541176 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25115"/></filter><filter id="iq2fype" width="9.094" height="18.251" x="18.309" y="10.395" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25115" stdDeviation=".375"/></filter><filter id="iH0dOgb" width="5.186" height="5.713" x="10.089" y="12.272" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25115"/></filter><filter id="iqijHhr" width="15.833" height="11.884" x="4.719" y="17.294" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.396078 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25115"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.741176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_25115" result="effect2_innerShadow_18_25115"/></filter><filter id="iHObaXJ" width="12.394" height="13.243" x="9.953" y="4.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.545098 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25115"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.639216 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_25115" result="effect2_innerShadow_18_25115"/></filter><filter id="i3mvwSd" width="28.962" height="5.4" x="1.484" y="25.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.65" dy=".8"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.627451 0 0 0 0 0.596078 0 0 0 0 0.662745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25115"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.501961 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_25115" result="effect2_innerShadow_18_25115"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.286275 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_25115" result="effect3_innerShadow_18_25115"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:microscope" /></template>
<style>
.a3ra2_u5q {
  stop-color: var(--svg-color--b3abbd, #B3ABBD);
}

.a47qzkr4t {
  stop-color: var(--svg-color--61596a, #61596A);
}

.ab2pw6l5o {
  stop-color: var(--svg-color--4184d5, #4184D5);
}

.ad-628bkt {
  stop-color: var(--svg-color--f7e0ff, #F7E0FF);
}

.as-7wxdfw {
  stop-color: var(--svg-color--b6b5b7, #B6B5B7);
  stop-opacity: 0;
}

.b6zkafbbw {
  stop-color: var(--svg-color--c4c1c7, #C4C1C7);
  stop-opacity: 0;
}

.bdn7kzbkp {
  stop-color: var(--svg-color--9688a5, #9688A5);
}

.bmi7uwb0q {
  stop-color: var(--svg-color--765398, #765398);
}

.c2rp26eeh {
  stop-color: var(--svg-color--6c6c73, #6C6C73);
}

.c7r012s9s {
  stop-color: var(--svg-color--6e6b71, #6E6B71);
}

.d-5720bml {
  d: path("M5 17.888a1.275 1.275 0 0 1 1.775-.313L19.96 26.81a1.274 1.274 0 1 1-1.463 2.088L5.313 19.663A1.275 1.275 0 0 1 5 17.888");
}

.dshj7nbsh {
  stop-color: var(--svg-color--554170, #554170);
  stop-opacity: 0;
}

.eebsajypd {
  d: path("M10.502 11.13q.174-.403.438-.774l.805-1.133l6.916 4.922l-.805 1.132a4.3 4.3 0 0 1-.588.667z");
}

.ft5dv1b6b {
  fill: none;
}

.gbqt9ebka {
  stop-color: var(--svg-color--b699d4, #B699D4);
}

.ggdz-gb3i {
  stop-color: var(--svg-color--8c8990, #8C8990);
  stop-opacity: 0;
}

.iykszg4py {
  stop-color: var(--svg-color--ded8e5, #DED8E5);
}

.l-vw7zbeq {
  stop-color: var(--svg-color--b29dc8, #B29DC8);
  stop-opacity: 0;
}

.l0dl69ovb {
  stroke: var(--svg-color--b5b2bc, #B5B2BC);
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M18.79 11.516c3.25.515 7.024 2.963 7.156 7.89c.125 4.64-3.172 6.86-5.265 8.172");
}

.l5dzsbcmz {
  stop-color: var(--svg-color--c4c2c7, #C4C2C7);
}

.lo6p9snyn {
  stop-color: var(--svg-color--554170, #554170);
}

.lthtirvxg {
  stop-color: var(--svg-color--a892c0, #A892C0);
  stop-opacity: 0;
}

.lvp7sdbvk {
  d: path("M11.749 13.089a1.943 1.943 0 0 1 3.165 2.252l-1.3 1.827a1.943 1.943 0 1 1-3.165-2.253z");
}

.ly94tlbtw {
  d: path("M18.096 4.096a4.24 4.24 0 0 0-3.952 1.756l-3.204 4.504a4.244 4.244 0 1 0 6.916 4.92l3.204-4.503a4.24 4.24 0 0 0 .364-4.309z");
}

.mikez6ahl {
  stop-color: var(--svg-color--d5cddd, #D5CDDD);
  stop-opacity: 0;
}

.o-4z4tbfb {
  stop-color: var(--svg-color--c5c3c7, #C5C3C7);
}

.okzohmbto {
  stop-color: var(--svg-color--b6b5b7, #B6B5B7);
}

.ps0a30bgj {
  stop-color: var(--svg-color--c5c3c7, #C5C3C7);
  stop-opacity: 0;
}

.q590akbfi {
  stop-color: var(--svg-color--585758, #585758);
}

.r9iha0bnv {
  stop-color: var(--svg-color--43b6ff, #43B6FF);
}

.re5wblbnn {
  stop-color: var(--svg-color--d5cddd, #D5CDDD);
}

.sz428bbhz {
  stop-color: var(--svg-color--dfc9f7, #DFC9F7);
  stop-opacity: 0;
}

.t7cy22bgn {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M19.118 11.516c3.25.515 7.023 2.963 7.156 7.89c.125 4.64-3.172 6.86-5.266 8.172");
}

.tuuuhpb-w {
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M18.79 11.516c3.25.515 7.024 2.963 7.156 7.89c.125 4.64-3.172 6.86-5.265 8.172");
}

.uwpipdi-h {
  stop-color: var(--svg-color--b5a1cb, #B5A1CB);
}

.vbqb2_i_e {
  stop-color: var(--svg-color--8c8990, #8C8990);
}

.vik643b9n {
  d: path("M19.078 2.714a1 1 0 0 1 1.395-.235l1.702 1.208a1 1 0 0 1 .235 1.394l-.987 1.388l-3.332-2.367z");
}

.wpg65xr7s {
  stop-color: var(--svg-color--9a8da8, #9A8DA8);
}

.xbbbkxb3z {
  stop-color: var(--svg-color--e5dcef, #E5DCEF);
}

.yx9fa1bzt {
  stop-color: var(--svg-color--8167ae, #8167AE);
}

.z9_nal4ca {
  d: path("M2.134 28.516a3 3 0 0 1 3-3h21.812a3 3 0 0 1 3 3v.05a1.2 1.2 0 0 1-1.2 1.2H3.334a1.2 1.2 0 0 1-1.2-1.2z");
}

.zheaq1xyz {
  stop-color: var(--svg-color--585758, #585758);
  stop-opacity: 0;
}

.zhm0nvb0t {
  stop-color: var(--svg-color--b699d4, #B699D4);
  stop-opacity: 0;
}

.zs_uykj5i {
  stop-color: var(--svg-color--444060, #444060);
}

</style>
