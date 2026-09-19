<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iHRtXuL)"><path fill="url(#iK3Vc9b)" clip-rule="evenodd" class="mbxxe4b1h"/></g><g filter="url(#iGCXbrg)"><path stroke="url(#iLyCUOb)" class="m9ewu55lh"/></g><g filter="url(#i0khcse)"><path fill="url(#ivYGybd)" class="vh2a5gbjv"/><path fill="url(#iZ796fd)" class="vh2a5gbjv"/></g><path fill="url(#itCaivC)" class="zzyi_obhs"/><path fill="url(#ibUggJc)" class="zzyi_obhs"/><g filter="url(#iGfvM6g)"><path fill="url(#iGoywjd)" class="mod_78hme"/><path fill="url(#iLBboEU)" class="mod_78hme"/><path fill="url(#i9FT5cd)" class="mod_78hme"/></g><g filter="url(#i4DBspO)"><path stroke="url(#iv0Pmtx)" class="smvvijbxa"/></g><g filter="url(#iSJkFCe)"><path stroke="url(#igWxGbc)" class="pjt08idim"/></g><g filter="url(#iV0BYub)"><path class="ke_i7tb7t"/></g><g filter="url(#iG7rYGc)" class="gprzepb-p"><path class="pr40xzbev"/><path stroke="url(#iScT5re)" class="e7q9x-xsm"/></g><g filter="url(#iGp2HFe)"><path stroke="url(#iHcmpvM)" class="bikl21bqw"/></g><defs><filter id="iHRtXuL" width="7.19" height="8.26" x="10.04" y="21.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.203922 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15449"/></filter><filter id="iGCXbrg" width="6.608" height="7.714" x="10.29" y="21.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15449" stdDeviation=".25"/></filter><filter id="i0khcse" width="2" height="19.307" x="14.98" y="3.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.12549 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15449"/></filter><filter id="iGfvM6g" width="27.93" height="14.28" x="2" y="2.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.184314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15449"/></filter><filter id="i4DBspO" width="1.2" height="12.04" x="15.206" y="3.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15449" stdDeviation=".2"/></filter><filter id="iSJkFCe" width="1.2" height="12.04" x="15.674" y="3.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15449" stdDeviation=".2"/></filter><filter id="iV0BYub" width="7.3" height="12.14" x="8.39" y="3.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.254902 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15449"/><feGaussianBlur result="effect2_foregroundBlur_18_15449" stdDeviation=".2"/></filter><filter id="iG7rYGc" width="7.03" height="11.98" x="16.49" y="3.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15449" stdDeviation=".15"/></filter><filter id="iGp2HFe" width="6.38" height="11.33" x="16.815" y="3.795" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15449" stdDeviation=".075"/></filter><linearGradient id="iK3Vc9b" x1="13.51" x2="13.51" y1="21.89" y2="29.06" gradientUnits="userSpaceOnUse"><stop class="e56cgbpvk"/><stop offset="1" class="x4cyi8b_d"/></linearGradient><linearGradient id="iLyCUOb" x1="15.225" x2="15.225" y1="28.5" y2="18.354" gradientUnits="userSpaceOnUse"><stop offset=".381" class="ccz9nhi1w"/><stop offset="1" class="s6xw76b3e"/></linearGradient><linearGradient id="ibUggJc" x1="16.062" x2="16.062" y1="2.958" y2="2.74" gradientUnits="userSpaceOnUse"><stop class="daz1w-03r"/><stop offset="1" class="bliizs2-x"/></linearGradient><linearGradient id="iv0Pmtx" x1="15.335" x2="15.335" y1="13.435" y2="3.091" gradientUnits="userSpaceOnUse"><stop class="m9g_-pvvv"/><stop offset="1" class="aw5ir2fai"/></linearGradient><linearGradient id="igWxGbc" x1="15.804" x2="15.804" y1="13.435" y2="3.091" gradientUnits="userSpaceOnUse"><stop class="s75j95bdk"/><stop offset="1" class="tkd9m1ypm"/></linearGradient><linearGradient id="iScT5re" x1="16.445" x2="18.623" y1="4.02" y2="4.906" gradientUnits="userSpaceOnUse"><stop class="kx2o18b-f"/><stop offset="1" class="t6dki3bpz"/></linearGradient><linearGradient id="iHcmpvM" x1="22.97" x2="21.406" y1="16.038" y2="6.076" gradientUnits="userSpaceOnUse"><stop class="pjjp4cb3j"/><stop offset="1" class="zvokf1xpa"/></linearGradient><radialGradient id="ivYGybd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.86833 3.00589 0 15.98 21.966)" gradientUnits="userSpaceOnUse"><stop class="l169lbbta"/><stop offset="1" class="pobsi6b8j"/></radialGradient><radialGradient id="iZ796fd" cx="0" cy="0" r="1" gradientTransform="translate(16.365 21.959)skewY(-90)" gradientUnits="userSpaceOnUse"><stop class="x2-ytnb5x"/><stop offset="1" class="crq8qkbvw"/></radialGradient><radialGradient id="itCaivC" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.67343 .80368 0 16.24 2.914)" gradientUnits="userSpaceOnUse"><stop class="ji-7wwykc"/><stop offset="1" class="ywzdmwbdu"/></radialGradient><radialGradient id="iGoywjd" cx="0" cy="0" r="1" gradientTransform="matrix(-14.00478 5.47573 -8.36133 -21.38501 22.293 8.334)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="prv2occrl"/><stop offset="1" class="oi6yy0b5v"/></radialGradient><radialGradient id="iLBboEU" cx="0" cy="0" r="1" gradientTransform="matrix(12.48287 -6.56405 13.96502 26.5573 15.965 16.91)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="o-yq0nlmb"/><stop offset="1" class="g6yhs2byd"/></radialGradient><radialGradient id="i9FT5cd" cx="0" cy="0" r="1" gradientTransform="rotate(168.528 11.201 6.135)scale(21.3383 42.6309)" gradientUnits="userSpaceOnUse"><stop offset=".885" class="vxj-axbqb"/><stop offset="1" class="waiol2bzs"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:umbrella" /></template>
<style>
.aw5ir2fai {
  stop-color: var(--svg-color--7463a2, #7463A2);
  stop-opacity: 0;
}

.bikl21bqw {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M22.97 14.9c0-5.95-2.58-10.05-5.93-10.88");
}

.bliizs2-x {
  stop-color: var(--svg-color--4a1876, #4A1876);
  stop-opacity: 0;
}

.ccz9nhi1w {
  stop-color: var(--svg-color--886b69, #886B69);
}

.crq8qkbvw {
  stop-color: var(--svg-color--504573, #504573);
  stop-opacity: 0;
}

.daz1w-03r {
  stop-color: var(--svg-color--4a1876, #4A1876);
}

.e56cgbpvk {
  stop-color: var(--svg-color--7b4f49, #7B4F49);
}

.e7q9x-xsm {
  d: path("M22.97 14.9c0-5.95-2.58-10.05-5.93-10.88");
}

.ft5dv1b6b {
  fill: none;
}

.g6yhs2byd {
  stop-color: var(--svg-color--8a63b5, #8A63B5);
}

.gprzepb-p {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.ji-7wwykc {
  stop-color: var(--svg-color--6c5983, #6C5983);
}

.ke_i7tb7t {
  stroke: var(--svg-color--7b5ea6, #7B5EA6);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.04 14.85c0-5.99 2.61-10.06 6-10.84");
}

.kx2o18b-f {
  stop-color: var(--svg-color--7d55aa, #7D55AA);
}

.l169lbbta {
  stop-color: var(--svg-color--504570, #504570);
}

.m9ewu55lh {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.04 26.13a2.553 2.553 0 0 0 2.554 2.555a2.546 2.546 0 0 0 2.554-2.554v-3.66");
}

.m9g_-pvvv {
  stop-color: var(--svg-color--7463a2, #7463A2);
}

.mbxxe4b1h {
  fill-rule: evenodd;
  d: path("M15.98 21.89a1 1 0 0 1 1 1v3.54a3.463 3.463 0 0 1-3.47 3.47a3.47 3.47 0 0 1-3.47-3.47a1 1 0 1 1 2 0c0 .81.655 1.47 1.47 1.47c.818 0 1.47-.652 1.47-1.47v-3.54a1 1 0 0 1 1-1");
}

.mod_78hme {
  d: path("M5.5 14.91c1.28 0 2.4.7 3 1.73c.1.16.27.26.46.26h.06c.19 0 .36-.1.46-.26a3.49 3.49 0 0 1 3-1.73c1.28 0 2.4.7 3 1.73c.1.16.27.26.46.26H16c.19 0 .36-.1.46-.26a3.49 3.49 0 0 1 3-1.73c1.28 0 2.4.7 3 1.73c.1.16.27.26.46.26h.06c.19 0 .36-.1.46-.26a3.49 3.49 0 0 1 3-1.73c1.34 0 2.5.76 3.08 1.88c.04.07.11.12.19.12c.12 0 .22-.1.22-.22c-.1-7.62-6.31-13.76-13.96-13.76S2.12 9.07 2 16.68c0 .12.1.22.22.22c.08 0 .16-.05.19-.12a3.5 3.5 0 0 1 3.09-1.87");
}

.o-yq0nlmb {
  stop-color: var(--svg-color--8a63b5, #8A63B5);
  stop-opacity: 0;
}

.oi6yy0b5v {
  stop-color: var(--svg-color--554a87, #554A87);
}

.pjjp4cb3j {
  stop-color: var(--svg-color--805fb2, #805FB2);
}

.pjt08idim {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.274 4.06V14.9");
}

.pobsi6b8j {
  stop-color: var(--svg-color--3e3157, #3E3157);
}

.pr40xzbev {
  stroke: var(--svg-color--7845ae, #7845AE);
  d: path("M22.97 14.9c0-5.95-2.58-10.05-5.93-10.88");
}

.prv2occrl {
  stop-color: var(--svg-color--8a60bb, #8A60BB);
}

.s6xw76b3e {
  stop-color: var(--svg-color--886b69, #886B69);
  stop-opacity: 0;
}

.s75j95bdk {
  stop-color: var(--svg-color--593e94, #593E94);
}

.smvvijbxa {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.806 4.06V14.9");
}

.t6dki3bpz {
  stop-color: var(--svg-color--7d55aa, #7D55AA);
  stop-opacity: 0;
}

.tkd9m1ypm {
  stop-color: var(--svg-color--68429f, #68429F);
  stop-opacity: 0;
}

.vh2a5gbjv {
  d: path("M16.98 4.23a1 1 0 1 0-2 0v18.155c0 .05.072.072.103.03c.215-.287.544-.524.914-.524c.353 0 .67.223.884.489c.031.038.099.017.099-.033z");
}

.vxj-axbqb {
  stop-color: var(--svg-color--625d82, #625D82);
  stop-opacity: 0;
}

.waiol2bzs {
  stop-color: var(--svg-color--625d82, #625D82);
}

.x2-ytnb5x {
  stop-color: var(--svg-color--504573, #504573);
}

.x4cyi8b_d {
  stop-color: var(--svg-color--60333e, #60333E);
}

.ywzdmwbdu {
  stop-color: var(--svg-color--563e71, #563E71);
}

.zvokf1xpa {
  stop-color: var(--svg-color--805fb2, #805FB2);
  stop-opacity: 0;
}

.zzyi_obhs {
  d: path("M16.89 2.8c.02.084-.05.158-.137.158h-1.576c-.086 0-.156-.074-.136-.159a.95.95 0 0 1 1.848 0");
}

</style>
