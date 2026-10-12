<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zsxdkeb-m"/><path class="kwhiv-93m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:retainer-teeth" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kwhiv-93m {
  d: path("M2.84 8v4.33a9.75 9.75 0 0 0 18.32 0V8");
}

.zsxdkeb-m {
  d: path("M6.5 5v4a5.5 5.5 0 0 0 1.61 3.89a1.42 1.42 0 0 0 2.47 1.42a1.42 1.42 0 0 0 2.84 0a1.42 1.42 0 0 0 2.47-1.42A5.5 5.5 0 0 0 17.5 9V5a2 2 0 0 0-2-2h-7a2 2 0 0 0-2 2");
}

</style>
