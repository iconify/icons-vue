<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="v8rgnlbmc"/><path class="qtiiljbpv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pixel-search" /></template>
<style>
.qtiiljbpv {
  d: path("m28.903 32.01l3.225-3.226l9.755 9.755l-3.226 3.225zm1.483-4.963l-3.222 3.223");
}

.v8rgnlbmc {
  cx: 17.808px;
  cy: 17.804px;
  r: 13.041px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
