<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iSdxuOt)" class="j57_k-bar"/><circle fill="url(#iL0YE9d)" class="j57_k-bar"/><circle fill="url(#iLSQ0Bc)" class="j57_k-bar"/><g filter="url(#iSPPyLb)"><path fill="url(#iEI9Dtd)" clip-rule="evenodd" class="sb5rhixqr"/></g><g filter="url(#iuT1nur)" class="e3fsewyjy"><path stroke="url(#ipuUmvc)" class="rd4e0eb9q"/><path stroke="url(#i9didrb)" class="rd4e0eb9q"/></g><defs><linearGradient id="iSdxuOt" x1="15.688" x2="15.688" y1="26.161" y2="29.947" gradientUnits="userSpaceOnUse"><stop class="kyy_-qs4j"/><stop offset="1" class="j8ie5mkwv"/></linearGradient><linearGradient id="iEI9Dtd" x1="16.18" x2="16.18" y1="2.537" y2="23.365" gradientUnits="userSpaceOnUse"><stop class="kqjz1wbgv"/><stop offset="1" class="i76s0ubvh"/></linearGradient><linearGradient id="ipuUmvc" x1="22.547" x2="17.86" y1="7.224" y2="11.099" gradientUnits="userSpaceOnUse"><stop offset=".103" class="bsa6cxs1i"/><stop offset="1" class="yjqpvi6jt"/></linearGradient><linearGradient id="i9didrb" x1="18.86" x2="22.204" y1="21.474" y2="13.724" gradientUnits="userSpaceOnUse"><stop class="qdbbpp3-r"/><stop offset="1" class="vr4ufs7kt"/></linearGradient><radialGradient id="iL0YE9d" cx="0" cy="0" r="1" gradientTransform="matrix(1.53125 -1.75 1.5386 1.34627 16.657 27.099)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="dcrsbbcfe"/><stop offset="1" class="npvh19b0x"/></radialGradient><radialGradient id="iLSQ0Bc" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 1.21874 -3.2999 6.7691 13.188 25.536)" gradientUnits="userSpaceOnUse"><stop class="aaxt30sbu"/><stop offset="1" class="y461h2bjy"/></radialGradient><filter id="iSPPyLb" width="16.672" height="22.061" x="8.219" y="2.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.180392 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1806"/></filter><filter id="iuT1nur" width="15.922" height="20.515" x="8.782" y="1.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1806" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:red-question-mark" /></template>
<style>
.aaxt30sbu {
  stop-color: var(--svg-color--c8404b, #C8404B);
}

.bsa6cxs1i {
  stop-color: var(--svg-color--ff5867, #FF5867);
}

.dcrsbbcfe {
  stop-color: var(--svg-color--ff5878, #FF5878);
}

.e3fsewyjy {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ft5dv1b6b {
  fill: none;
}

.i76s0ubvh {
  stop-color: var(--svg-color--f41585, #F41585);
}

.j57_k-bar {
  cx: 15.688px;
  cy: 27.447px;
  r: 2.5px;
}

.j8ie5mkwv {
  stop-color: var(--svg-color--f62093, #F62093);
}

.kqjz1wbgv {
  stop-color: var(--svg-color--ed1f28, #ED1F28);
}

.kyy_-qs4j {
  stop-color: var(--svg-color--ff0b38, #FF0B38);
}

.npvh19b0x {
  stop-color: var(--svg-color--ff5878, #FF5878);
  stop-opacity: 0;
}

.qdbbpp3-r {
  stop-color: var(--svg-color--ff3c80, #FF3C80);
}

.rd4e0eb9q {
  d: path("M11.282 9.364c0-1.828 1.094-4.203 4.187-4.906c4.297-.797 6.735 2.375 6.735 5.781s-1.844 4.797-5.969 6.906v2.704");
}

.sb5rhixqr {
  fill-rule: evenodd;
  d: path("M15.413 7.126c-.946.225-1.45.655-1.736 1.05c-.32.44-.458.965-.458 1.407a2.5 2.5 0 1 1-5 0c0-2.793 1.716-6.34 6.134-7.344l.098-.02c2.888-.535 5.41.255 7.18 1.984c1.703 1.661 2.51 3.989 2.51 6.255c0 2.253-.647 4.093-2.117 5.654c-1.012 1.074-2.355 1.942-3.852 2.762v1.99a2.5 2.5 0 1 1-5 0v-3.5a2.5 2.5 0 0 1 1.362-2.225c2.088-1.068 3.207-1.773 3.85-2.455c.483-.513.757-1.072.757-2.226c0-1.14-.41-2.1-1.002-2.677c-.516-.504-1.347-.898-2.726-.655");
}

.vr4ufs7kt {
  stop-color: var(--svg-color--ff3c80, #FF3C80);
  stop-opacity: 0;
}

.y461h2bjy {
  stop-color: var(--svg-color--c8404b, #C8404B);
  stop-opacity: 0;
}

.yjqpvi6jt {
  stop-color: var(--svg-color--ff5867, #FF5867);
  stop-opacity: 0;
}

</style>
