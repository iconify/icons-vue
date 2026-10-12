<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oou6i8omd"/><path class="ah4vbsbty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oil-pressure-light" /></template>
<style>
.ah4vbsbty {
  d: path("M5 16.25a2.5 2.5 0 0 1 5 0m-2.5 0L9 14.5m11-1.25c.85 1.1 1.25 1.85 1.25 2.5a1.25 1.25 0 0 1-2.5 0c0-.65.4-1.4 1.25-2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oou6i8omd {
  d: path("M4.25 11h5.5q1.25 0 2.18.83l.39.34q.93.83 1.89.03l3.83-3.15q.96-.8.52.37l-3.12 8.16q-.44 1.17-1.69 1.17h-9.5Q3 18.75 3 17.5v-5.25Q3 11 4.25 11M7 11V8.75m-2 0h4");
}

</style>
