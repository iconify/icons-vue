<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wjql9kb9r"/><path class="aku673bye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pool-heater" /></template>
<style>
.aku673bye {
  d: path("M6 9.5q2.25-1.75 4.5 0t4.5 0m2.75 4C19.75 15.25 21 17 21 19a3 3 0 0 1-6 0q0-1.875.75-3c.25.75.75 1.25 1.25 1.5c-.25-1.5 0-2.75.75-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wjql9kb9r {
  d: path("M12.7 16H2.5V3h17v8.3");
}

</style>
