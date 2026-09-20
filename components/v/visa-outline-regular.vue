<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d3xn50bni"/><path class="oy7fa3gbk"/><path class="dafu-cchc"/><path class="wskxlyzso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:visa-outline-regular" /></template>
<style>
.d3xn50bni {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.dafu-cchc {
  d: path("M10 8h7v8h-7Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oy7fa3gbk {
  d: path("M8 2v20");
}

.wskxlyzso {
  d: path("M12 12h3");
}

</style>
