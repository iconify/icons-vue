<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g-elf4bvk"/><path class="qfv7tzb7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mooncake-box" /></template>
<style>
.g-elf4bvk {
  d: path("M12 4.25a4 4 0 0 1 5.5 2.25a4 4 0 0 1 2.25 5.5a4 4 0 0 1-2.25 5.5a4 4 0 0 1-5.5 2.25a4 4 0 0 1-5.5-2.25A4 4 0 0 1 4.25 12A4 4 0 0 1 6.5 6.5A4 4 0 0 1 12 4.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qfv7tzb7w {
  d: path("M9.5 9.5a2.5 2.5 0 0 1 5 0a2.5 2.5 0 0 1 0 5a2.5 2.5 0 0 1-5 0a2.5 2.5 0 0 1 0-5");
}

</style>
