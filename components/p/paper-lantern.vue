<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zc7jwdbts"/><path class="wsyir7piu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paper-lantern" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wsyir7piu {
  d: path("M12 6.75v11.5M9 7c-1.75 3.25-1.75 7.75 0 11m6-11c1.75 3.25 1.75 7.75 0 11");
}

.zc7jwdbts {
  d: path("M12 2.75V6m0 13v2.25M4.5 12.5C4.5 8.9 7.85 6 12 6s7.5 2.9 7.5 6.5S16.15 19 12 19s-7.5-2.9-7.5-6.5");
}

</style>
