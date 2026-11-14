<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j7qjn6psg"/><path class="b-cu35ntv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vault-dial" /></template>
<style>
.b-cu35ntv {
  d: path("M11.929 4.25h.142a.654.654 0 0 1 .554 1a.737.737 0 0 1-1.25 0a.654.654 0 0 1 .554-1m3.321 2L16 5m1.75 3.75L19 8m-.5 4H20m-2.25 3.25L19 16m-3.75 1.75L16 19m-4-.5V20m-3.25-2.25L8 19m-1.75-3.75L5 16m.5-4H4m2.25-3.25L5 8m3.75-1.75L8 5m.75 7a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M12 9.75v4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j7qjn6psg {
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 1 0-18 0");
}

</style>
