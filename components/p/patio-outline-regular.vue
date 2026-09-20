<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ifmxbfbzl"/><path class="eo0o7bbpy"/><path class="j7cy7sb_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:patio-outline-regular" /></template>
<style>
.eo0o7bbpy {
  d: path("M14 6h7v5h-7Z");
}

.ifmxbfbzl {
  d: path("M3 6h8v5H3Z");
}

.j7cy7sb_r {
  d: path("M3 14h18v5H3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
