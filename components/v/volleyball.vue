<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="gnx5avbcu"/><g filter="url(#iutbTwe)"><path fill="url(#ikgB4zP)" class="knegg8ffc"/></g><path fill="url(#iPTVijb)" class="knegg8ffc"/><path fill="url(#iWA1Uhd)" class="knegg8ffc"/><g filter="url(#iGoiHMb)"><path fill="url(#iu2OcCd)" class="vgf--cugi"/></g><path fill="url(#icL06sc)" class="vgf--cugi"/><g filter="url(#i1V3fke)"><path fill="url(#ignFDsc)" class="vyr-3obyy"/><path fill="url(#iDM2bbe)" class="vyr-3obyy"/></g><g filter="url(#iAJNPpd)"><path fill="url(#iKCDzld)" class="qkjb-6bym"/></g><g filter="url(#id3JoMc)"><path fill="url(#icmHsZc)" class="nl7buibqr"/></g><g filter="url(#iCdUWdV)"><path fill="url(#i5LuB1v)" class="spuj8xbff"/><path fill="url(#idrZZ6d)" class="spuj8xbff"/></g><path fill="url(#iQhwHKd)" class="spuj8xbff"/><g filter="url(#iLGAaPc)"><path fill="url(#iwApfpd)" class="afzvchm4b"/><path fill="url(#ijK7Rcc)" class="afzvchm4b"/></g><g filter="url(#iPrpzFe)"><path fill="url(#i3aNTde)" class="x4keqlbie"/></g><path fill="url(#is7v1Fx)" class="x4keqlbie"/><g filter="url(#iG1nbyc)"><path fill="url(#i8eks1c)" class="dbmpjcbtq"/></g><g filter="url(#ihw5Lae)"><path class="x3b19mbll"/></g><defs><radialGradient id="ikgB4zP" cx="0" cy="0" r="1" gradientTransform="matrix(3.84815 9.59144 -18.46398 7.40788 25.467 10.583)" gradientUnits="userSpaceOnUse"><stop class="sri0wodum"/><stop offset="1" class="azmo-7b2m"/></radialGradient><radialGradient id="iWA1Uhd" cx="0" cy="0" r="1" gradientTransform="matrix(-.26688 5.56627 -1.42477 -.06831 25.808 21.796)" gradientUnits="userSpaceOnUse"><stop offset=".577" class="v59aybbxx"/><stop offset="1" class="wqw9u5b0p"/></radialGradient><radialGradient id="iu2OcCd" cx="0" cy="0" r="1" gradientTransform="rotate(139.6 9.022 6.699)scale(11.572 12.9492)" gradientUnits="userSpaceOnUse"><stop class="sncitsoap"/><stop offset="1" class="jpa10hq6s"/></radialGradient><radialGradient id="icL06sc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.99034 9.73353 -11.08019 -10.23418 18.143 3.777)" gradientUnits="userSpaceOnUse"><stop offset=".952" class="fwxferbll"/><stop offset="1" class="v8tgwvbcc"/></radialGradient><radialGradient id="ignFDsc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.34847 -2.59928 12.4874 -11.28244 11.044 6.464)" gradientUnits="userSpaceOnUse"><stop class="kd75xnbir"/><stop offset="1" class="hppvytcqu"/></radialGradient><radialGradient id="iDM2bbe" cx="0" cy="0" r="1" gradientTransform="rotate(-142.254 7.765 2.194)scale(8.5546 21.5465)" gradientUnits="userSpaceOnUse"><stop offset=".628" class="p5ny_kyck"/><stop offset=".956" class="vnn0_v2do"/></radialGradient><radialGradient id="iKCDzld" cx="0" cy="0" r="1" gradientTransform="matrix(-10.55212 6.72814 -4.07556 -6.39192 23.877 8.91)" gradientUnits="userSpaceOnUse"><stop class="mxq3m0b9j"/><stop offset="1" class="yijfb6b1k"/></radialGradient><radialGradient id="icmHsZc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.62575 18.69317 -9.655 -2.38919 20.766 12.115)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="dsj9cbb0t"/><stop offset=".378" class="t_qgzojwl"/><stop offset="1" class="p2o96rz4h"/></radialGradient><radialGradient id="i5LuB1v" cx="0" cy="0" r="1" gradientTransform="rotate(101.525 8.176 16.45)scale(15.8582 14.6548)" gradientUnits="userSpaceOnUse"><stop class="wnobtbbst"/><stop offset=".713" class="v8ur9jjuc"/></radialGradient><radialGradient id="idrZZ6d" cx="0" cy="0" r="1" gradientTransform="matrix(-4.56341 14.76299 -12.88974 -3.98437 25.975 14.104)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="hz5gwxbtj"/><stop offset="1" class="nfkk9sbul"/></radialGradient><radialGradient id="iQhwHKd" cx="0" cy="0" r="1" gradientTransform="rotate(103.021 -.53 19.253)scale(7.97367 3.46975)" gradientUnits="userSpaceOnUse"><stop offset=".677" class="d4wakaczv"/><stop offset="1" class="bvqu0q_ni"/></radialGradient><radialGradient id="iwApfpd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.69249 5.4114 -22.0823 -10.98722 10.235 19.227)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="rfseqkbjx"/><stop offset="1" class="pxm1ix-rw"/></radialGradient><radialGradient id="ijK7Rcc" cx="0" cy="0" r="1" gradientTransform="rotate(-160.924 9.21 9.16)scale(13.7692 15.4373)" gradientUnits="userSpaceOnUse"><stop offset=".734" class="os71cub1u"/><stop offset="1" class="aby244bzc"/></radialGradient><radialGradient id="i3aNTde" cx="0" cy="0" r="1" gradientTransform="matrix(10.91188 -2.82125 5.18896 20.06955 2.39 15.696)" gradientUnits="userSpaceOnUse"><stop class="s02i3mbvr"/><stop offset="1" class="eja_m081n"/></radialGradient><radialGradient id="is7v1Fx" cx="0" cy="0" r="1" gradientTransform="rotate(-145.679 9.8 5.738)scale(13.6782 13.627)" gradientUnits="userSpaceOnUse"><stop offset=".736" class="jmysrtbyq"/><stop offset="1" class="jjgl51yny"/></radialGradient><filter id="iutbTwe" width="5.615" height="14.044" x="24.497" y="10.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.768627 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2245"/></filter><filter id="iGoiHMb" width="17.737" height="12.813" x="7.222" y="1.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.741176 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2245"/></filter><filter id="i1V3fke" width="11.018" height="8.963" x="5.563" y="1.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.635294 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2245"/></filter><filter id="iAJNPpd" width="18.089" height="10.613" x="11.005" y="5.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.709804 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2245"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.752941 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2245" result="effect2_innerShadow_18_2245"/></filter><filter id="id3JoMc" width="9.982" height="17.575" x="12.006" y="12.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 0.607843 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2245"/></filter><filter id="iCdUWdV" width="8.261" height="19.279" x="18.857" y="10.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.756863 0 0 0 0 0.792157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2245"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.721569 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2245" result="effect2_innerShadow_18_2245"/></filter><filter id="iLGAaPc" width="15.07" height="13.089" x="1.709" y="12.967" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.623529 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2245"/></filter><filter id="iPrpzFe" width="14.72" height="14.678" x="2.205" y="6.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.666667 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2245"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 0.576471 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2245" result="effect2_innerShadow_18_2245"/></filter><filter id="iG1nbyc" width="11.668" height="8.104" x="3.259" y="21.716" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.568627 0 0 0 0 0.870588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2245"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.490196 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2245" result="effect2_innerShadow_18_2245"/></filter><filter id="ihw5Lae" width="13.759" height="9.189" x="10.801" y="5.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_2245" stdDeviation=".1"/></filter><linearGradient id="iPTVijb" x1="27.813" x2="29.712" y1="24.176" y2="18.057" gradientUnits="userSpaceOnUse"><stop class="vze3-jy9t"/><stop offset="1" class="bu80pd31j"/></linearGradient><linearGradient id="i8eks1c" x1="10.849" x2="9.117" y1="23.671" y2="29.172" gradientUnits="userSpaceOnUse"><stop class="ybyy3g4su"/><stop offset="1" class="s5mpy60sk"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:volleyball" /></template>
<style>
.aby244bzc {
  stop-color: var(--svg-color--c3a1a2, #C3A1A2);
}

.afzvchm4b {
  d: path("M2.74 20.574c-1.008-3.018-.95-5.884-.604-7.402c.055-.242.357-.277.49-.068c1 1.569 2.733 4.056 5.984 5.943c2.681 1.556 5.83 1.829 7.904 1.712a.25.25 0 0 1 .265.252c-.066 2.684-1.102 4.237-1.66 4.781a.23.23 0 0 1-.172.064c-5.458-.2-9.443-2.454-11.275-3.92a2.9 2.9 0 0 1-.932-1.362");
}

.azmo-7b2m {
  stop-color: var(--svg-color--d7cfe1, #D7CFE1);
}

.bu80pd31j {
  stop-color: var(--svg-color--cebede, #CEBEDE);
  stop-opacity: 0;
}

.bvqu0q_ni {
  stop-color: var(--svg-color--915ab7, #915AB7);
  stop-opacity: 0;
}

.d4wakaczv {
  stop-color: var(--svg-color--915ab7, #915AB7);
}

.dbmpjcbtq {
  d: path("M11.097 29.007c-4.121-1.189-6.94-4.88-7.827-7.1c-.054-.137.103-.248.22-.16c3.856 2.902 8.256 3.961 11.192 4.058c.195.006.313.22.204.382c-.837 1.248-1.854 2.151-2.56 2.64c-.358.249-.81.301-1.23.18");
}

.dsj9cbb0t {
  stop-color: var(--svg-color--eee6f6, #EEE6F6);
}

.eja_m081n {
  stop-color: var(--svg-color--d5c3e5, #D5C3E5);
}

.ft5dv1b6b {
  fill: none;
}

.fwxferbll {
  stop-color: var(--svg-color--a997ac, #A997AC);
  stop-opacity: 0;
}

.gnx5avbcu {
  cx: 16.094px;
  cy: 16.18px;
  r: 12.797px;
  fill: var(--svg-color--3c3740, #3C3740);
}

.hppvytcqu {
  stop-color: var(--svg-color--c4bbb9, #C4BBB9);
}

.hz5gwxbtj {
  stop-color: var(--svg-color--c292e7, #C292E7);
  stop-opacity: 0;
}

.jjgl51yny {
  stop-color: var(--svg-color--c8a8a2, #C8A8A2);
}

.jmysrtbyq {
  stop-color: var(--svg-color--c8a8a2, #C8A8A2);
  stop-opacity: 0;
}

.jpa10hq6s {
  stop-color: var(--svg-color--cec1cd, #CEC1CD);
}

.kd75xnbir {
  stop-color: var(--svg-color--cfcac9, #CFCAC9);
}

.knegg8ffc {
  d: path("M26.471 24.512c.895-6.07-.861-11.43-1.953-13.632a.2.2 0 0 1 .173-.291c2.379-.071 3.785.484 4.122.723c.625.54 1.031 3.329.86 5.579c-.297 3.88-2.08 6.6-3.037 7.702c-.064.074-.18.016-.165-.081");
}

.mxq3m0b9j {
  stop-color: var(--svg-color--f4f3f5, #F4F3F5);
}

.nfkk9sbul {
  stop-color: var(--svg-color--c292e7, #C292E7);
}

.nl7buibqr {
  d: path("M15.987 16.299a1.04 1.04 0 0 1 .1-.956c.722-1.052 1.491-1.989 3.087-3.085a.24.24 0 0 1 .346.074c.864 1.453 2.306 4.683 2.215 8.527c-.093 3.92-1.897 7.121-2.98 8.495a.9.9 0 0 1-.61.33c-1.391.145-3.764.211-5.914-.282c-.26-.06-.304-.41-.082-.56c1.577-1.062 3.354-3.012 4.148-5.139c.862-2.613.435-5.425-.31-7.404");
}

.os71cub1u {
  stop-color: var(--svg-color--c3a1a2, #C3A1A2);
  stop-opacity: 0;
}

.p2o96rz4h {
  stop-color: var(--svg-color--bf83e7, #BF83E7);
}

.p5ny_kyck {
  stop-color: var(--svg-color--c4aca6, #C4ACA6);
  stop-opacity: 0;
}

.pxm1ix-rw {
  stop-color: var(--svg-color--b78ed5, #B78ED5);
}

.qkjb-6bym {
  d: path("M16.172 8.297c-2.585 1.798-4.486 4.59-5.127 5.987a.45.45 0 0 0 .22.59c1.892.936 2.875.966 4.077 1.088a.54.54 0 0 0 .514-.264c.727-1.228 2.542-3.411 5.55-4.651c2.614-.842 6.003-.428 7.283.174c.08.037.172-.032.152-.117c-.531-2.218-2.025-4.118-2.972-5.049a1.48 1.48 0 0 0-.9-.422c-2.111-.194-5.696.508-8.797 2.664");
}

.rfseqkbjx {
  stop-color: var(--svg-color--ceb4e5, #CEB4E5);
}

.s02i3mbvr {
  stop-color: var(--svg-color--c6abb4, #C6ABB4);
}

.s5mpy60sk {
  stop-color: var(--svg-color--b67fdd, #B67FDD);
}

.sncitsoap {
  stop-color: var(--svg-color--e5e4e5, #E5E4E5);
}

.spuj8xbff {
  d: path("M24.085 10.575c-2.147.03-3.544.802-4.283 1.271a.505.505 0 0 0-.176.653c.841 1.685 2.208 4.787 2.016 9.07c-.139 3.09-1.781 6.256-2.755 7.587c-.081.11.011.27.146.246c3.502-.602 6.042-2.836 7.08-4.118c.196-.243.33-.53.393-.835c.355-1.686.53-4.992.14-7.558c-.38-2.513-1.355-4.816-1.943-5.947a.69.69 0 0 0-.619-.37");
}

.sri0wodum {
  stop-color: var(--svg-color--f9f6fb, #F9F6FB);
}

.t_qgzojwl {
  stop-color: var(--svg-color--e2cff4, #E2CFF4);
}

.v59aybbxx {
  stop-color: var(--svg-color--a482c0, #A482C0);
}

.v8tgwvbcc {
  stop-color: var(--svg-color--a997ac, #A997AC);
}

.v8ur9jjuc {
  stop-color: var(--svg-color--dfccf1, #DFCCF1);
}

.vgf--cugi {
  d: path("M16.723 2.216C11.907 4.05 8.7 8.063 7.35 10.349a.9.9 0 0 0 .047.993c.972 1.33 2.316 2.556 3.226 3.152c.12.079.279.03.346-.096c3.918-7.294 10.043-8.727 13.64-8.778c.224-.003.337-.272.173-.424c-2.185-2.012-5.002-2.887-6.625-3.145a2.8 2.8 0 0 0-1.433.165");
}

.vnn0_v2do {
  stop-color: var(--svg-color--c4aca6, #C4ACA6);
}

.vyr-3obyy {
  d: path("M16.489 2.107C11.013 1.6 7.416 4.382 6.017 6.037a.87.87 0 0 0-.202.629c.119 1.682.682 3.31 1.152 4.032c.06.09.189.077.239-.02c2.049-3.924 6.384-7.264 9.309-8.372c.1-.038.08-.19-.026-.2");
}

.vze3-jy9t {
  stop-color: var(--svg-color--cebede, #CEBEDE);
}

.wnobtbbst {
  stop-color: var(--svg-color--faf6fe, #FAF6FE);
}

.wqw9u5b0p {
  stop-color: var(--svg-color--a482c0, #A482C0);
  stop-opacity: 0;
}

.x3b19mbll {
  stroke: var(--svg-color--a69aac, #A69AAC);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.047 14.297c1.36-3.078 6.078-8.578 13.313-8.719");
}

.x4keqlbie {
  d: path("M5.414 6.68c-1.856 1.676-2.766 4.3-3.004 5.874a.44.44 0 0 0 .036.256c.518 1.101 2.435 3.897 5.054 5.58c3.735 2.401 6.443 2.409 9.026 2.407a.245.245 0 0 0 .247-.24c.031-1.823-.47-3.519-.79-4.362a.49.49 0 0 0-.452-.307c-2.04-.039-4.167-.472-6.406-2.622C6.79 11.022 5.997 8.31 5.832 6.857c-.023-.205-.265-.314-.418-.176");
}

.ybyy3g4su {
  stop-color: var(--svg-color--bf90e2, #BF90E2);
}

.yijfb6b1k {
  stop-color: var(--svg-color--d2c7d1, #D2C7D1);
}

</style>
