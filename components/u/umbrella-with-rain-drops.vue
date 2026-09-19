<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iumU4rc)"><path fill="url(#i6g8jYb)" clip-rule="evenodd" class="qn95r5bgq"/></g><g filter="url(#iZ0Pgfd)"><path stroke="url(#iKNAkhe)" class="hag0n14px"/></g><g filter="url(#iZGM2Bq)"><path fill="url(#i0eogAb)" class="s_0pv-bey"/><path fill="url(#iuNTQZd)" class="s_0pv-bey"/></g><path fill="url(#iym2x8d)" class="awp8xqbfb"/><path fill="url(#iunfSje)" class="awp8xqbfb"/><g filter="url(#itMQW7Q)"><path fill="url(#icFrsqe)" class="sgvsxgbbu"/><path fill="url(#ii7ErJc)" class="sgvsxgbbu"/><path fill="url(#iikUDLp)" class="sgvsxgbbu"/><path fill="url(#ijxNG0b)" class="sgvsxgbbu"/></g><g filter="url(#iTZpSbc)"><path stroke="url(#i04i5dc)" class="nof_v_0ml"/></g><g filter="url(#irqzbtd)"><path stroke="url(#iyQBi3c)" class="d_hn_v_0m"/></g><g filter="url(#ihjUgsd)"><path class="vyvi1dben"/></g><g filter="url(#iBWFX2d)"><path stroke="url(#iBKlBGb)" class="wykuhxbvy"/></g><g filter="url(#i1X4ffc)"><path stroke="url(#iUMgixU)" class="nr7qdq3sy"/></g><g filter="url(#i8sx96d)"><rect transform="rotate(34.846 5.332 1.596)" class="c9mk-bc8p"/><rect fill="url(#iBfl9AN)" transform="rotate(34.846 5.332 1.596)" class="p3qgh62ox"/></g><g filter="url(#ibHwgWc)"><rect transform="rotate(34.846 21.197 1.596)" class="z5rbqabqc"/><rect fill="url(#iMxel9h)" transform="rotate(34.846 21.197 1.596)" class="a3nhmpb2c"/></g><rect fill="url(#i64iaje)" transform="rotate(34.846 21.197 1.596)" class="a3nhmpb2c"/><rect fill="url(#ipj9WlG)" transform="rotate(34.846 21.197 1.596)" class="a3nhmpb2c"/><g filter="url(#iTlzFvb)"><rect transform="rotate(34.846 12.18 5.578)" class="c_9_2mblr"/><rect fill="url(#iXZJEJe)" transform="rotate(34.846 12.18 5.578)" class="jhzs1rbkz"/></g><rect fill="url(#ijUZ7gb)" transform="rotate(34.846 12.18 5.578)" class="jhzs1rbkz"/><g filter="url(#iGRQRhe)"><rect transform="rotate(34.846 28.045 5.578)" class="fndaytbrh"/><rect fill="url(#iQxFCKc)" transform="rotate(34.846 28.045 5.578)" class="zzzxynt1k"/></g><rect fill="url(#iAlPIWq)" transform="rotate(34.846 28.045 5.578)" class="zzzxynt1k"/><g filter="url(#iYtZgOe)"><path class="sm8vetd_i"/></g><g filter="url(#iesdStc)"><path class="g_ulmobtf"/></g><g filter="url(#ivEl8ux)"><path class="beh4ly13j"/></g><defs><filter id="iumU4rc" width="7.19" height="8.26" x="10.168" y="21.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.203922 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15467"/></filter><filter id="iZ0Pgfd" width="6.608" height="7.714" x="10.418" y="21.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15467" stdDeviation=".25"/></filter><filter id="iZGM2Bq" width="2" height="19.307" x="15.108" y="3.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.12549 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15467"/></filter><filter id="itMQW7Q" width="27.93" height="14.28" x="2.128" y="2.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.184314 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15467"/></filter><filter id="iTZpSbc" width="1.2" height="12.04" x="15.334" y="3.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15467" stdDeviation=".2"/></filter><filter id="irqzbtd" width="1.2" height="12.04" x="15.803" y="3.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15467" stdDeviation=".2"/></filter><filter id="ihjUgsd" width="7.3" height="12.14" x="8.518" y="3.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.254902 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15467"/><feGaussianBlur result="effect2_foregroundBlur_18_15467" stdDeviation=".2"/></filter><filter id="iBWFX2d" width="7.03" height="11.98" x="16.618" y="3.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15467" stdDeviation=".15"/></filter><filter id="i1X4ffc" width="6.38" height="11.33" x="16.943" y="3.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15467" stdDeviation=".075"/></filter><filter id="i8sx96d" width="4.985" height="5.042" x="2.802" y="1.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.305882 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15467"/></filter><filter id="ibHwgWc" width="4.385" height="4.992" x="18.667" y="2.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.463958 0 0 0 0 0.552704 0 0 0 0 0.85 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15467"/></filter><filter id="iTlzFvb" width="4.385" height="4.992" x="9.65" y="6.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.463958 0 0 0 0 0.552704 0 0 0 0 0.85 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15467"/></filter><filter id="iGRQRhe" width="4.485" height="4.992" x="25.515" y="6.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15467"/></filter><filter id="iYtZgOe" width="4.007" height="4.7" x="19.041" y="2.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15467" stdDeviation=".5"/></filter><filter id="iesdStc" width="4.007" height="4.7" x="25.941" y="6.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15467" stdDeviation=".5"/></filter><filter id="ivEl8ux" width="4.007" height="4.7" x="9.959" y="6.372" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15467" stdDeviation=".5"/></filter><radialGradient id="i0eogAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.86833 3.00589 0 16.108 21.982)" gradientUnits="userSpaceOnUse"><stop class="l169lbbta"/><stop offset="1" class="pobsi6b8j"/></radialGradient><radialGradient id="iuNTQZd" cx="0" cy="0" r="1" gradientTransform="translate(16.494 21.974)skewY(-90)" gradientUnits="userSpaceOnUse"><stop class="x2-ytnb5x"/><stop offset="1" class="crq8qkbvw"/></radialGradient><radialGradient id="iym2x8d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.67343 .80368 0 16.368 2.929)" gradientUnits="userSpaceOnUse"><stop class="ji-7wwykc"/><stop offset="1" class="ywzdmwbdu"/></radialGradient><radialGradient id="icFrsqe" cx="0" cy="0" r="1" gradientTransform="matrix(-14.00478 5.47573 -8.36133 -21.38501 22.421 8.35)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="prv2occrl"/><stop offset="1" class="oi6yy0b5v"/></radialGradient><radialGradient id="ii7ErJc" cx="0" cy="0" r="1" gradientTransform="matrix(12.48287 -6.56405 13.96502 26.5573 16.093 16.925)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="o-yq0nlmb"/><stop offset="1" class="g6yhs2byd"/></radialGradient><radialGradient id="iikUDLp" cx="0" cy="0" r="1" gradientTransform="rotate(168.528 11.265 6.15)scale(21.3383 42.6309)" gradientUnits="userSpaceOnUse"><stop offset=".885" class="vxj-axbqb"/><stop offset="1" class="waiol2bzs"/></radialGradient><radialGradient id="ijxNG0b" cx="0" cy="0" r="1" gradientTransform="rotate(139.582 6.85 6.214)scale(11.5278 5.15191)" gradientUnits="userSpaceOnUse"><stop class="n-aktib6i"/><stop offset="1" class="qmvylqx8h"/></radialGradient><radialGradient id="iBfl9AN" cx="0" cy="0" r="1" gradientTransform="matrix(.97195 -1.34789 1.24277 .89615 7.406 1.547)" gradientUnits="userSpaceOnUse"><stop class="hsu10dbqc"/><stop offset="1" class="e-22sgb9u"/></radialGradient><radialGradient id="iMxel9h" cx="0" cy="0" r="1" gradientTransform="matrix(.97195 -1.34788 1.24276 .89615 23.271 1.546)" gradientUnits="userSpaceOnUse"><stop class="hwpaekb3k"/><stop offset="1" class="ryj63cvik"/></radialGradient><radialGradient id="iXZJEJe" cx="0" cy="0" r="1" gradientTransform="matrix(.97195 -1.34788 1.24276 .89615 14.254 5.529)" gradientUnits="userSpaceOnUse"><stop class="ob0pxzb-v"/><stop offset="1" class="g66jqqbiz"/></radialGradient><radialGradient id="iQxFCKc" cx="0" cy="0" r="1" gradientTransform="matrix(.97195 -1.34788 1.24276 .89615 30.12 5.529)" gradientUnits="userSpaceOnUse"><stop class="hwpaekb3k"/><stop offset="1" class="ryj63cvik"/></radialGradient><linearGradient id="i6g8jYb" x1="13.638" x2="13.638" y1="21.905" y2="29.075" gradientUnits="userSpaceOnUse"><stop class="e56cgbpvk"/><stop offset="1" class="x4cyi8b_d"/></linearGradient><linearGradient id="iKNAkhe" x1="15.353" x2="15.353" y1="28.515" y2="18.369" gradientUnits="userSpaceOnUse"><stop offset=".381" class="ccz9nhi1w"/><stop offset="1" class="s6xw76b3e"/></linearGradient><linearGradient id="iunfSje" x1="16.19" x2="16.19" y1="2.973" y2="2.755" gradientUnits="userSpaceOnUse"><stop class="daz1w-03r"/><stop offset="1" class="bliizs2-x"/></linearGradient><linearGradient id="i04i5dc" x1="15.463" x2="15.463" y1="13.45" y2="3.106" gradientUnits="userSpaceOnUse"><stop class="m9g_-pvvv"/><stop offset="1" class="aw5ir2fai"/></linearGradient><linearGradient id="iyQBi3c" x1="15.932" x2="15.932" y1="13.45" y2="3.106" gradientUnits="userSpaceOnUse"><stop class="s75j95bdk"/><stop offset="1" class="tkd9m1ypm"/></linearGradient><linearGradient id="iBKlBGb" x1="21.881" x2="15.649" y1="13.25" y2="3.235" gradientUnits="userSpaceOnUse"><stop class="q5rmd4b5j"/><stop offset="1" class="gjmfc-d0p"/></linearGradient><linearGradient id="iUMgixU" x1="23.098" x2="21.534" y1="16.053" y2="6.091" gradientUnits="userSpaceOnUse"><stop class="pjjp4cb3j"/><stop offset="1" class="zvokf1xpa"/></linearGradient><linearGradient id="i64iaje" x1="22.941" x2="22.788" y1="8.047" y2="5.641" gradientUnits="userSpaceOnUse"><stop class="l584yh-ge"/><stop offset="1" class="m9xdtpbik"/></linearGradient><linearGradient id="ipj9WlG" x1="20.647" x2="22.499" y1="3.307" y2="3.304" gradientUnits="userSpaceOnUse"><stop class="g5n3vvbje"/><stop offset="1" class="antjufb8f"/></linearGradient><linearGradient id="ijUZ7gb" x1="13.923" x2="13.771" y1="12.03" y2="9.623" gradientUnits="userSpaceOnUse"><stop class="l584yh-ge"/><stop offset="1" class="m9xdtpbik"/></linearGradient><linearGradient id="iAlPIWq" x1="29.789" x2="29.636" y1="12.03" y2="9.623" gradientUnits="userSpaceOnUse"><stop class="cm2ki_bky"/><stop offset="1" class="ddhfngahy"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:umbrella-with-rain-drops" /></template>
<style>
.a3nhmpb2c {
  width: 2.729px;
  height: 5.364px;
  x: 21.197px;
  y: 1.596px;
  rx: 1.364px;
}

.antjufb8f {
  stop-color: var(--svg-color--6487cc, #6487CC);
  stop-opacity: 0;
}

.aw5ir2fai {
  stop-color: var(--svg-color--7463a2, #7463A2);
  stop-opacity: 0;
}

.awp8xqbfb {
  d: path("M17.017 2.814c.02.085-.05.159-.136.159h-1.576c-.086 0-.156-.074-.136-.159a.95.95 0 0 1 1.848 0");
}

.beh4ly13j {
  stroke: var(--svg-color--5d8bff, #5D8BFF);
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m12.757 7.51l-1.589 2.425");
}

.bliizs2-x {
  stop-color: var(--svg-color--4a1876, #4A1876);
  stop-opacity: 0;
}

.c_9_2mblr {
  width: 2.729px;
  height: 5.364px;
  x: 12.18px;
  y: 5.578px;
  fill: var(--svg-color--4c7af7, #4C7AF7);
  rx: 1.364px;
}

.c9mk-bc8p {
  width: 2.729px;
  height: 5.364px;
  x: 5.332px;
  y: 1.596px;
  fill: var(--svg-color--4c7cfd, #4C7CFD);
  rx: 1.364px;
}

.ccz9nhi1w {
  stop-color: var(--svg-color--886b69, #886B69);
}

.cm2ki_bky {
  stop-color: var(--svg-color--4d53cc, #4D53CC);
}

.crq8qkbvw {
  stop-color: var(--svg-color--504573, #504573);
  stop-opacity: 0;
}

.d_hn_v_0m {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.403 4.075v10.84");
}

.daz1w-03r {
  stop-color: var(--svg-color--4a1876, #4A1876);
}

.ddhfngahy {
  stop-color: var(--svg-color--4d53cc, #4D53CC);
  stop-opacity: 0;
}

.e-22sgb9u {
  stop-color: var(--svg-color--72a7ff, #72A7FF);
  stop-opacity: 0;
}

.e56cgbpvk {
  stop-color: var(--svg-color--7b4f49, #7B4F49);
}

.fndaytbrh {
  width: 2.729px;
  height: 5.364px;
  x: 28.045px;
  y: 5.578px;
  fill: var(--svg-color--5794fc, #5794FC);
  rx: 1.364px;
}

.ft5dv1b6b {
  fill: none;
}

.g_ulmobtf {
  stroke: var(--svg-color--7dbfff, #7DBFFF);
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m28.739 7.346l-1.59 2.426");
}

.g5n3vvbje {
  stop-color: var(--svg-color--6487cc, #6487CC);
}

.g66jqqbiz {
  stop-color: var(--svg-color--6ea6ff, #6EA6FF);
  stop-opacity: 0;
}

.g6yhs2byd {
  stop-color: var(--svg-color--8a63b5, #8A63B5);
}

.gjmfc-d0p {
  stop-color: var(--svg-color--7147a3, #7147A3);
}

.hag0n14px {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.168 26.146a2.553 2.553 0 0 0 2.554 2.554a2.546 2.546 0 0 0 2.554-2.554v-3.66");
}

.hsu10dbqc {
  stop-color: var(--svg-color--72a7ff, #72A7FF);
}

.hwpaekb3k {
  stop-color: var(--svg-color--7dbfff, #7DBFFF);
}

.jhzs1rbkz {
  width: 2.729px;
  height: 5.364px;
  x: 12.18px;
  y: 5.578px;
  rx: 1.364px;
}

.ji-7wwykc {
  stop-color: var(--svg-color--6c5983, #6C5983);
}

.l169lbbta {
  stop-color: var(--svg-color--504570, #504570);
}

.l584yh-ge {
  stop-color: var(--svg-color--414bb6, #414BB6);
}

.m9g_-pvvv {
  stop-color: var(--svg-color--7463a2, #7463A2);
}

.m9xdtpbik {
  stop-color: var(--svg-color--414bb6, #414BB6);
  stop-opacity: 0;
}

.n-aktib6i {
  stop-color: var(--svg-color--604695, #604695);
}

.nof_v_0ml {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.934 4.075v10.84");
}

.nr7qdq3sy {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M23.098 14.915c0-5.95-2.58-10.05-5.93-10.88");
}

.o-yq0nlmb {
  stop-color: var(--svg-color--8a63b5, #8A63B5);
  stop-opacity: 0;
}

.ob0pxzb-v {
  stop-color: var(--svg-color--6ea6ff, #6EA6FF);
}

.oi6yy0b5v {
  stop-color: var(--svg-color--554a87, #554A87);
}

.p3qgh62ox {
  width: 2.729px;
  height: 5.364px;
  x: 5.332px;
  y: 1.596px;
  rx: 1.364px;
}

.pjjp4cb3j {
  stop-color: var(--svg-color--805fb2, #805FB2);
}

.pobsi6b8j {
  stop-color: var(--svg-color--3e3157, #3E3157);
}

.prv2occrl {
  stop-color: var(--svg-color--8a60bb, #8A60BB);
}

.q5rmd4b5j {
  stop-color: var(--svg-color--7845ae, #7845AE);
}

.qmvylqx8h {
  stop-color: var(--svg-color--604695, #604695);
  stop-opacity: 0;
}

.qn95r5bgq {
  fill-rule: evenodd;
  d: path("M16.108 21.905a1 1 0 0 1 1 1v3.54a3.463 3.463 0 0 1-3.47 3.47a3.47 3.47 0 0 1-3.47-3.47a1 1 0 1 1 2 0c0 .81.655 1.47 1.47 1.47c.818 0 1.47-.652 1.47-1.47v-3.54a1 1 0 0 1 1-1");
}

.ryj63cvik {
  stop-color: var(--svg-color--7dbfff, #7DBFFF);
  stop-opacity: 0;
}

.s_0pv-bey {
  d: path("M17.108 4.245a1 1 0 1 0-2 0V22.4c0 .05.073.072.103.03c.215-.287.545-.524.914-.524c.353 0 .67.223.884.489c.031.038.1.017.1-.033z");
}

.s6xw76b3e {
  stop-color: var(--svg-color--886b69, #886B69);
  stop-opacity: 0;
}

.s75j95bdk {
  stop-color: var(--svg-color--593e94, #593E94);
}

.sgvsxgbbu {
  d: path("M5.628 14.925c1.28 0 2.4.7 3 1.73c.1.16.27.26.46.26h.06c.19 0 .36-.1.46-.26a3.49 3.49 0 0 1 3-1.73c1.28 0 2.4.7 3 1.73c.1.16.27.26.46.26h.06c.19 0 .36-.1.46-.26a3.49 3.49 0 0 1 3-1.73c1.28 0 2.4.7 3 1.73c.1.16.27.26.46.26h.06c.19 0 .36-.1.46-.26a3.49 3.49 0 0 1 3-1.73c1.34 0 2.5.76 3.08 1.88c.04.07.11.12.19.12c.12 0 .22-.1.22-.22c-.1-7.62-6.31-13.76-13.96-13.76s-13.85 6.14-13.97 13.75c0 .12.1.22.22.22c.08 0 .16-.05.19-.12a3.5 3.5 0 0 1 3.09-1.87");
}

.sm8vetd_i {
  stroke: var(--svg-color--7dbfff, #7DBFFF);
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m21.839 3.245l-1.59 2.426");
}

.tkd9m1ypm {
  stop-color: var(--svg-color--68429f, #68429F);
  stop-opacity: 0;
}

.vxj-axbqb {
  stop-color: var(--svg-color--625d82, #625D82);
  stop-opacity: 0;
}

.vyvi1dben {
  stroke: var(--svg-color--7b5ea6, #7B5EA6);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.168 14.865c0-5.99 2.61-10.06 6-10.84");
}

.waiol2bzs {
  stop-color: var(--svg-color--625d82, #625D82);
}

.wykuhxbvy {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M23.098 14.915c0-5.95-2.58-10.05-5.93-10.88");
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

.z5rbqabqc {
  width: 2.729px;
  height: 5.364px;
  x: 21.197px;
  y: 1.596px;
  fill: var(--svg-color--5994fd, #5994FD);
  rx: 1.364px;
}

.zvokf1xpa {
  stop-color: var(--svg-color--805fb2, #805FB2);
  stop-opacity: 0;
}

.zzzxynt1k {
  width: 2.729px;
  height: 5.364px;
  x: 28.045px;
  y: 5.578px;
  rx: 1.364px;
}

</style>
