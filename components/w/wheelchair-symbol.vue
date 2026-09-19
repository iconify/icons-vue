<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iruhvMb" class="w5gk6mbep"/><path id="iCT4XCb" class="s0b27jh3p"/></defs><g class="ft5dv1b6b"><g filter="url(#i7sseJb)"><rect fill="url(#ioTq8DW)" class="tbfn38b3t"/><rect fill="url(#iVSSMfe)" class="tbfn38b3t"/></g><g filter="url(#iya7Y5F)"><path stroke="url(#iQNCP6c)" class="xrrmt9bga"/></g><g filter="url(#iWpn6Ji)"><path stroke="url(#iSsyMgd)" class="e89jjxbld"/></g><g filter="url(#i6VWgEe)" class="jyttb_bnu"><use href="#iruhvMb"/><use href="#iCT4XCb"/></g><g filter="url(#i79uPkc)" class="b-c38gb2l"><use href="#iruhvMb"/><use href="#iCT4XCb"/></g><defs><filter id="i7sseJb" width="28.875" height="28.875" x="2.487" y=".688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_392"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_392" result="effect2_innerShadow_18590_392"/></filter><filter id="iya7Y5F" width="5.5" height="28.375" x="25.924" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_392" stdDeviation="1"/></filter><filter id="iWpn6Ji" width="27.281" height="5.5" x="3.2" y=".75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_392" stdDeviation="1"/></filter><filter id="i6VWgEe" width="20.5" height="21" x="6.174" y="5.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_392" stdDeviation=".5"/></filter><filter id="i79uPkc" width="19.3" height="19.8" x="6.774" y="5.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.854902 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_392"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_392" result="effect2_innerShadow_18590_392"/></filter><linearGradient id="ioTq8DW" x1="16.424" x2="16.424" y1="5.262" y2="38.515" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iQNCP6c" x1="29.174" x2="29.174" y1="4.188" y2="27.063" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iSsyMgd" x1="28.888" x2="3.357" y1="3.75" y2="3.75" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="iVSSMfe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 28.143 3.781)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:wheelchair-symbol" /></template>
<style>
.b-c38gb2l {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
}

.e89jjxbld {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.95 3.5h21.782");
}

.ft5dv1b6b {
  fill: none;
}

.jyttb_bnu {
  fill: var(--svg-color--579fff, #579FFF);
}

.k8tg0e93k {
  stop-color: var(--svg-color--5db6ff, #5DB6FF);
}

.mqmvrj28a {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
}

.pjb-fs-ow {
  stop-color: var(--svg-color--4878dd, #4878DD);
}

.pttsnab-v {
  stop-color: var(--svg-color--7dd8ff, #7DD8FF);
}

.s0b27jh3p {
  d: path("M14.964 11.082c.863-.262 1.245-.297 1.796-.047c.097.044.256.16.453.36q.099.101.189.206a.1.1 0 0 1 .007.12l-2.145 3.216a1.5 1.5 0 0 0 .98 2.308l4.751.864c.066.012.201.065.382.348c.183.288.344.713.471 1.242c.253 1.05.314 2.255.326 2.93a1.52 1.52 0 0 0 1.513 1.496h.987a1 1 0 1 0 0-2h-.418a.1.1 0 0 1-.1-.096c-.035-.758-.126-1.812-.363-2.798c-.152-.63-.377-1.295-.729-1.847c-.354-.558-.903-1.096-1.711-1.243l-3.853-.7a.1.1 0 0 1-.065-.154l1.89-2.835a1.47 1.47 0 0 0-.035-1.69a7 7 0 0 0-.651-.77c-.261-.265-.624-.583-1.051-.777c-1.226-.558-2.199-.352-3.204-.047c-.804.244-1.436.73-1.844 1.115a6 6 0 0 0-.663.738l-.006.008a1 1 0 1 0 1.635 1.153l.08-.098c.073-.089.184-.212.325-.345c.293-.275.66-.538 1.053-.657");
}

.tbfn38b3t {
  width: 27.875px;
  height: 27.875px;
  x: 2.487px;
  y: 1.688px;
  rx: 3.6px;
}

.tcol3199r {
  stop-color: var(--svg-color--5cb7ff, #5CB7FF);
}

.tzz9ercjs {
  stop-color: var(--svg-color--639df4, #639DF4);
}

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.w5gk6mbep {
  d: path("M23.174 8.125a2 2 0 1 1-4 0a2 2 0 0 1 4 0m-6 11a4 4 0 1 1-4.15-3.997a.26.26 0 0 0 .22-.135l.8-1.483a.24.24 0 0 0-.19-.358a8 8 0 0 0-.68-.027a6 6 0 1 0 5.997 6.205a.244.244 0 0 0-.198-.245l-1.492-.299a.26.26 0 0 0-.307.263z");
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

.xrrmt9bga {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.674 4.188v22.875");
}

</style>
