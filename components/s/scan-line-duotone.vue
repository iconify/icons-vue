<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qjql2tbsq"/><path class="weddopsmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-line-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qjql2tbsq {
  stroke-opacity: 0.4;
  d: path("M3 8V6C3 4.34315 4.34315 3 6 3H8M16 3H18C19.6569 3 21 4.34315 21 6V8M21 16V18C21 19.6569 19.6569 21 18 21H16M8 21H6C4.34315 21 3 19.6569 3 18V16");
}

.weddopsmh {
  d: path("M3 12L21 12");
}

</style>
