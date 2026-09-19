<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iFq5ojT)"><path fill="url(#iDHyqsc)" class="px4rxlh_r"/><path fill="url(#il1c9tb)" class="px4rxlh_r"/></g><path fill="url(#ivIqQzt)" class="px4rxlh_r"/><path fill="url(#iuZ8uFe)" class="px4rxlh_r"/><g filter="url(#iQPsKFx)"><path fill="url(#iVMBGBk)" class="r7nxhcb1z"/><path fill="url(#iME8Yjd)" class="r7nxhcb1z"/></g><path fill="url(#iha6piT)" class="r7nxhcb1z"/><g filter="url(#ipYQ9He)"><path fill="url(#iRn9fuB)" class="mmc-z_-ch"/><path fill="url(#iEoDu1d)" class="mmc-z_-ch"/></g><path fill="url(#iYrlj9v)" class="mmc-z_-ch"/><g filter="url(#iyPBC3b)"><circle class="h3y7u-11f"/></g><g filter="url(#ieOfzrA)"><circle class="mki8jb_ml"/></g><g filter="url(#ieBkOte)"><circle class="edsmcccsk"/></g><defs><radialGradient id="iDHyqsc" cx="0" cy="0" r="1" gradientTransform="rotate(129.634 -.077 11.764)scale(8.21533 10.5736)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="wtjrjlb-k"/><stop offset="1" class="yai_z68dd"/></radialGradient><radialGradient id="il1c9tb" cx="0" cy="0" r="1" gradientTransform="matrix(.12499 16.12502 -12.17953 .0944 8.125 16.25)" gradientUnits="userSpaceOnUse"><stop offset=".349" class="vaj3f2bnr"/><stop offset=".977" class="rw1l_1bgh"/></radialGradient><radialGradient id="iuZ8uFe" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.594 12.844)scale(10.8125)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="m52-9_b9c"/><stop offset="1" class="jx0mbc4rz"/></radialGradient><radialGradient id="iVMBGBk" cx="0" cy="0" r="1" gradientTransform="matrix(-6.8125 5.875 -7.61246 -8.82722 23.938 22.875)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="wtjrjlb-k"/><stop offset="1" class="yai_z68dd"/></radialGradient><radialGradient id="iME8Yjd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.06258 15.99997 -24.78395 -7.84194 24.313 21.875)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="vaj3f2bnr"/><stop offset=".833" class="rw1l_1bgh"/><stop offset="1" class="t35s6p1er"/></radialGradient><radialGradient id="iha6piT" cx="0" cy="0" r="1" gradientTransform="rotate(101.182 2.72 20.453)scale(10.958 16.1469)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="m52-9_b9c"/><stop offset="1" class="jx0mbc4rz"/></radialGradient><radialGradient id="iRn9fuB" cx="0" cy="0" r="1" gradientTransform="matrix(-7.87495 7.00007 -9.31799 -10.48257 26.25 7.25)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="wtjrjlb-k"/><stop offset="1" class="yai_z68dd"/></radialGradient><radialGradient id="iEoDu1d" cx="0" cy="0" r="1" gradientTransform="matrix(-6.0626 13.49998 -23.54368 -10.57305 26.438 5.625)" gradientUnits="userSpaceOnUse"><stop offset=".509" class="vaj3f2bnr"/><stop offset=".946" class="rw1l_1bgh"/></radialGradient><filter id="iFq5ojT" width="10" height="14.5" x="2.25" y="12.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.501961 0 0 0 0 0.964706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_7143_6226"/></filter><filter id="iQPsKFx" width="13" height="13.5" x="15.25" y="16.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.501961 0 0 0 0 0.964706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_7143_6226"/></filter><filter id="ipYQ9He" width="19" height="13.02" x="11.25" y="1.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.02"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.501961 0 0 0 0 0.964706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_7143_6226"/></filter><filter id="iyPBC3b" width="10.5" height="10.5" x="20.75" y="1.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7143_6226" stdDeviation="1.5"/></filter><filter id="ieOfzrA" width="10.5" height="10.5" x="19.688" y="18.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7143_6226" stdDeviation="1.5"/></filter><filter id="ieBkOte" width="9.375" height="9.375" x="4.563" y="16.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7143_6226" stdDeviation="1.5"/></filter><linearGradient id="ivIqQzt" x1="6.625" x2="3.25" y1="17.75" y2="16.285" gradientUnits="userSpaceOnUse"><stop offset=".147" class="sihg3jbxw"/><stop offset=".946" class="p5uuexbwi"/></linearGradient><linearGradient id="iYrlj9v" x1="19.875" x2="17.813" y1="5.938" y2="2" gradientUnits="userSpaceOnUse"><stop offset=".147" class="sihg3jbxw"/><stop offset=".946" class="p5uuexbwi"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sweat-droplets" /></template>
<style>
.edsmcccsk {
  cx: 9.25px;
  cy: 20.875px;
  r: 1.688px;
  fill: var(--svg-color--8af6ff, #8AF6FF);
}

.ft5dv1b6b {
  fill: none;
}

.h3y7u-11f {
  cx: 26px;
  cy: 7.063px;
  r: 2.25px;
  fill: var(--svg-color--8af6ff, #8AF6FF);
}

.jx0mbc4rz {
  stop-color: var(--svg-color--a158fe, #A158FE);
}

.m52-9_b9c {
  stop-color: var(--svg-color--a158fe, #A158FE);
  stop-opacity: 0;
}

.mki8jb_ml {
  cx: 24.938px;
  cy: 23.5px;
  r: 2.25px;
  fill: var(--svg-color--8af6ff, #8AF6FF);
}

.mmc-z_-ch {
  d: path("M25.47 2.299c-1.953-.583-3.745-.263-5.233.525l-8.28 4.509a1.316 1.316 0 0 0 0 2.332l8.169 4.45c.992.545 2.126.885 3.35.885c4.13 0 7.4-3.547 6.672-7.648c-.425-2.371-2.288-4.334-4.677-5.053");
}

.p5uuexbwi {
  stop-color: var(--svg-color--74b5ca, #74B5CA);
}

.px4rxlh_r {
  d: path("M12.018 23.486c.45-1.437.206-2.765-.401-3.86L8.142 13.52a1.031 1.031 0 0 0-1.79 0l-3.427 6.018a4.95 4.95 0 0 0-.675 2.472a4.998 4.998 0 0 0 5.883 4.914c1.82-.302 3.337-1.68 3.885-3.439");
}

.r7nxhcb1z {
  d: path("M27.607 21.851c-.777-1.493-2.023-2.33-3.358-2.727l-7.544-2.08c-.857-.24-1.644.547-1.415 1.413l2.053 7.435c.25.906.698 1.762 1.415 2.479a5.575 5.575 0 0 0 8.51-.757c1.186-1.672 1.296-3.941.34-5.763");
}

.rw1l_1bgh {
  stop-color: var(--svg-color--3f80f7, #3F80F7);
}

.sihg3jbxw {
  stop-color: var(--svg-color--74b5ca, #74B5CA);
  stop-opacity: 0;
}

.t35s6p1er {
  stop-color: var(--svg-color--8437e6, #8437E6);
}

.vaj3f2bnr {
  stop-color: var(--svg-color--3f80f6, #3F80F6);
  stop-opacity: 0;
}

.wtjrjlb-k {
  stop-color: var(--svg-color--55ebff, #55EBFF);
}

.yai_z68dd {
  stop-color: var(--svg-color--01a6f0, #01A6F0);
}

</style>
