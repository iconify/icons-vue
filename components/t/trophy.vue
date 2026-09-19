<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#i6MhQAc)" class="d2kvgvbvc"><path class="j4ox6eb2m"/><path fill="url(#i4JsYZm)" class="bk2pmcnfn"/><path fill="url(#i5HuPuc)" class="bk2pmcnfn"/></g><g clip-rule="evenodd" filter="url(#i79zqYm)" class="d2kvgvbvc"><path class="gt5_e2tzr"/><path fill="url(#iBD70Yb)" class="eqrep9bar"/></g><g filter="url(#ih749xb)"><path fill="url(#iZcSWvb)" class="gnr86sw9c"/><path fill="url(#iYF5Znc)" class="gnr86sw9c"/></g><path fill="url(#iavgjLE)" class="gnr86sw9c"/><path class="aq3lo47mt"/><path fill="url(#i3HhHpb)" class="e8mq-dbup"/><path fill="url(#iORLNeP)" class="e8mq-dbup"/><path fill="url(#iI6p1zd)" class="e8mq-dbup"/><g filter="url(#izrAsac)"><path fill="url(#i5OXhQc)" class="yimwu3z5b"/><path fill="url(#ioWc2ze)" class="yimwu3z5b"/><path fill="url(#iCV124f)" class="yimwu3z5b"/></g><g filter="url(#iwe6PFv)"><path class="y8ac84b8w"/></g><g filter="url(#itVN37b)"><path fill="url(#iDoPF3d)" class="n300oablz"/></g><defs><linearGradient id="i4JsYZm" x1="22.236" x2="25.868" y1="11.944" y2="8.668" gradientUnits="userSpaceOnUse"><stop class="x_7vsn9jm"/><stop offset="1" class="mxterjkms"/></linearGradient><linearGradient id="iBD70Yb" x1="9.565" x2="7.078" y1="7.957" y2="7.247" gradientUnits="userSpaceOnUse"><stop class="ehipxkbak"/><stop offset="1" class="zblxkktwl"/></linearGradient><linearGradient id="iZcSWvb" x1="16.953" x2="11.891" y1="19.76" y2="19.76" gradientUnits="userSpaceOnUse"><stop class="h07o25-sp"/><stop offset="1" class="fhn1c9bxv"/></linearGradient><linearGradient id="i5OXhQc" x1="5.706" x2="25.616" y1="25.512" y2="25.512" gradientUnits="userSpaceOnUse"><stop class="t9lbkbx5h"/><stop offset="1" class="jscn09bbv"/></linearGradient><linearGradient id="ioWc2ze" x1="15.663" x2="15.663" y1="30.379" y2="28.753" gradientUnits="userSpaceOnUse"><stop class="tynxxhb-c"/><stop offset="1" class="eezh0wjai"/></linearGradient><linearGradient id="iCV124f" x1="24.87" x2="23.932" y1="26.532" y2="26.751" gradientUnits="userSpaceOnUse"><stop class="g3akn-bfr"/><stop offset="1" class="yy0k_2boq"/></linearGradient><linearGradient id="iDoPF3d" x1="19.682" x2="12.008" y1="25.245" y2="25.245" gradientUnits="userSpaceOnUse"><stop class="yfusudv2k"/><stop offset="1" class="plemwlb5x"/></linearGradient><radialGradient id="i5HuPuc" cx="0" cy="0" r="1" gradientTransform="matrix(4.69737 -1.85526 1.70898 4.327 22.276 8.905)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="eie20gbpv"/><stop offset="1" class="vnh073b_u"/></radialGradient><radialGradient id="iYF5Znc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09 -1.90625 0 17.235 17.17)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="oy1ee1yek"/><stop offset="1" class="obve8nbsb"/></radialGradient><radialGradient id="iavgjLE" cx="0" cy="0" r="1" gradientTransform="rotate(149.162 6.89 12.85)scale(2.27493 3.45405)" gradientUnits="userSpaceOnUse"><stop class="h14szlb8i"/><stop offset="1" class="elfccabwx"/></radialGradient><radialGradient id="i3HhHpb" cx="0" cy="0" r="1" gradientTransform="matrix(1.36288 12.34872 -7.92943 .87514 18.203 3.135)" gradientUnits="userSpaceOnUse"><stop offset=".121" class="bhs6cibmx"/><stop offset="1" class="koyt3kb9b"/></radialGradient><radialGradient id="iORLNeP" cx="0" cy="0" r="1" gradientTransform="matrix(0 .70434 -7.87152 0 18.284 2.01)" gradientUnits="userSpaceOnUse"><stop class="i9if5gyfu"/><stop offset="1" class="y2q-0acbx"/></radialGradient><radialGradient id="iI6p1zd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.87504 11.18747 -10.73354 -6.59609 19.016 4.76)" gradientUnits="userSpaceOnUse"><stop offset=".787" class="y2kx52b_c"/><stop offset="1" class="x_vtdul-w"/></radialGradient><filter id="i6MhQAc" width="7.81" height="8.729" x="19.371" y="4.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1422"/></filter><filter id="i79zqYm" width="7.81" height="8.729" x="4.134" y="4.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.458824 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1422"/></filter><filter id="ih749xb" width="9.48" height="7.99" x="11.168" y="13.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.462745 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1422"/></filter><filter id="izrAsac" width="20.564" height="9.6" x="5.706" y="21.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy=".65"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.270588 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1422"/></filter><filter id="iwe6PFv" width="8.1" height="3.89" x="11.342" y="23.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_1422" stdDeviation=".2"/></filter><filter id="itVN37b" width="7.55" height="3.34" x="12.008" y="23.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.533333 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1422"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:trophy" /></template>
<style>
.aq3lo47mt {
  fill: var(--svg-color--ea873a, #EA873A);
  d: path("M15.658 16.55a6.97 6.97 0 0 1-6.97-6.97V2.72c0-.39.32-.71.71-.71h12.53c.39 0 .71.32.71.71v6.86c0 3.85-3.12 6.97-6.98 6.97");
}

.bhs6cibmx {
  stop-color: var(--svg-color--fffa73, #FFFA73);
}

.bk2pmcnfn {
  d: path("M24.555 6.834c-.9-.25-1.835.27-2.094 1.175a.866.866 0 1 1-1.666-.478a3.435 3.435 0 0 1 4.213-2.369c.034.008.102.025.164.046c2.493.831 2.691 4.214.455 5.45l-4.97 2.75a.866.866 0 1 1-.839-1.516l4.97-2.75c.982-.543.823-1.956-.159-2.288l-.006-.002z");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.e8mq-dbup {
  d: path("M15.658 16.55a6.97 6.97 0 0 1-6.97-6.97V2.72c0-.39.32-.71.71-.71h12.53c.39 0 .71.32.71.71v6.86c0 3.85-3.12 6.97-6.98 6.97");
}

.eezh0wjai {
  stop-color: var(--svg-color--8c3a79, #8C3A79);
  stop-opacity: 0;
}

.ehipxkbak {
  stop-color: var(--svg-color--d27840, #D27840);
}

.eie20gbpv {
  stop-color: var(--svg-color--ffec6a, #FFEC6A);
  stop-opacity: 0;
}

.elfccabwx {
  stop-color: var(--svg-color--ffd34d, #FFD34D);
  stop-opacity: 0;
}

.eqrep9bar {
  d: path("M6.307 5.162a3.435 3.435 0 0 1 4.214 2.37a.866.866 0 0 1-1.666.477A1.7 1.7 0 0 0 6.738 6.84l-.046.011l-.006.002c-.982.332-1.141 1.745-.159 2.288l4.97 2.75a.866.866 0 1 1-.839 1.516l-4.97-2.75c-2.235-1.236-2.037-4.619.456-5.45c.061-.02.13-.038.163-.046");
}

.fhn1c9bxv {
  stop-color: var(--svg-color--db7b3c, #DB7B3C);
}

.ft5dv1b6b {
  fill: none;
}

.g3akn-bfr {
  stop-color: var(--svg-color--b0817c, #B0817C);
}

.gnr86sw9c {
  d: path("M17.328 17.52V13.3h-3.34v4.22c0 .74-.33 1.45-.9 1.92l-1.92 1.6h8.98l-1.92-1.6a2.51 2.51 0 0 1-.9-1.92");
}

.gt5_e2tzr {
  fill: var(--svg-color--eaa73a, #EAA73A);
  d: path("M6.307 5.162a3.435 3.435 0 0 1 4.214 2.37a.866.866 0 0 1-1.666.477A1.7 1.7 0 0 0 6.738 6.84l-.046.011l-.006.002c-.982.332-1.141 1.745-.159 2.288l4.97 2.75a.866.866 0 1 1-.839 1.516l-4.97-2.75c-2.235-1.236-2.037-4.619.456-5.45c.061-.02.13-.038.163-.046");
}

.h07o25-sp {
  stop-color: var(--svg-color--fbc33a, #FBC33A);
}

.h14szlb8i {
  stop-color: var(--svg-color--ffd34d, #FFD34D);
}

.i9if5gyfu {
  stop-color: var(--svg-color--fff45b, #FFF45B);
}

.j4ox6eb2m {
  fill: var(--svg-color--ffd340, #FFD340);
  d: path("M24.555 6.834c-.9-.25-1.835.27-2.094 1.175a.866.866 0 1 1-1.666-.478a3.435 3.435 0 0 1 4.213-2.369c.034.008.102.025.164.046c2.493.831 2.691 4.214.455 5.45l-4.97 2.75a.866.866 0 1 1-.839-1.516l4.97-2.75c.982-.543.823-1.956-.159-2.288l-.006-.002z");
}

.jscn09bbv {
  stop-color: var(--svg-color--955569, #955569);
}

.koyt3kb9b {
  stop-color: var(--svg-color--fffa73, #FFFA73);
  stop-opacity: 0;
}

.mxterjkms {
  stop-color: var(--svg-color--fec551, #FEC551);
  stop-opacity: 0;
}

.n300oablz {
  d: path("M18.668 23.7h-6.02c-.35 0-.64.28-.64.64v1.81c0 .35.28.64.64.64h6.02c.35 0 .64-.28.64-.64v-1.81c0-.35-.28-.64-.64-.64");
}

.obve8nbsb {
  stop-color: var(--svg-color--ffe469, #FFE469);
  stop-opacity: 0;
}

.oy1ee1yek {
  stop-color: var(--svg-color--ffe469, #FFE469);
}

.plemwlb5x {
  stop-color: var(--svg-color--febb5b, #FEBB5B);
}

.t9lbkbx5h {
  stop-color: var(--svg-color--9d5b6c, #9D5B6C);
}

.tynxxhb-c {
  stop-color: var(--svg-color--8c3a79, #8C3A79);
}

.vnh073b_u {
  stop-color: var(--svg-color--ffec6a, #FFEC6A);
}

.x_7vsn9jm {
  stop-color: var(--svg-color--fec551, #FEC551);
}

.x_vtdul-w {
  stop-color: var(--svg-color--c55d73, #C55D73);
}

.y2kx52b_c {
  stop-color: var(--svg-color--c55d73, #C55D73);
  stop-opacity: 0;
}

.y2q-0acbx {
  stop-color: var(--svg-color--fff45b, #FFF45B);
  stop-opacity: 0;
}

.y8ac84b8w {
  fill: var(--svg-color--914556, #914556);
  d: path("M18.402 23.884h-6.02c-.35 0-.64.28-.64.64v1.81c0 .35.28.64.64.64h6.02c.35 0 .64-.28.64-.64v-1.81c0-.35-.28-.64-.64-.64");
}

.yfusudv2k {
  stop-color: var(--svg-color--ffe767, #FFE767);
}

.yimwu3z5b {
  d: path("M22.578 21.04H8.738c-.73 0-1.35.51-1.49 1.22l-1.53 7.09c-.07.33.18.64.52.64h18.85c.34 0 .59-.31.52-.64l-1.53-7.09c-.15-.71-.77-1.22-1.5-1.22");
}

.yy0k_2boq {
  stop-color: var(--svg-color--b0817c, #B0817C);
  stop-opacity: 0;
}

.zblxkktwl {
  stop-color: var(--svg-color--d27840, #D27840);
  stop-opacity: 0;
}

</style>
