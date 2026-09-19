<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fjeawrbbu"/><ellipse class="hlnp7wpbr"/><circle class="t9r385-0o"/><path class="jka38fbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:unlockmaster" /></template>
<style>
.fjeawrbbu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.132 14.889C31.069 2.688 13.825 2.46 13.877 13.728l-.052 4.232m14.542 23.073H8.834a2.34 2.34 0 0 1-2.345-2.342V20.955a2.34 2.34 0 0 1 2.345-2.343h27.289a2.34 2.34 0 0 1 2.344 2.343v7.283");
}

.hlnp7wpbr {
  cx: 34.477px;
  cy: 35.472px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8.266px;
  ry: 8.259px;
}

.jka38fbdj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.561 27.213l-.024 2.33m8.206 5.929h-2.18m-6.026 6.172l.02 2.087m-6.106-8.259h-2.24m13.132-4.663l-1.784 3.125c-.12-.624-.735-1.183-1.173-1.417zm-16.245.778l.284 2.452h-2.066l.362-2.452s-1.328-.732-1.344-1.764c-.015-1.033 1.008-2.072 2.028-2.063c1.02.01 2.03 1.027 2.028 2.063c-.003 1.035-1.292 1.764-1.292 1.764");
}

.t9r385-0o {
  cx: 34.537px;
  cy: 35.335px;
  r: 1.837px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
