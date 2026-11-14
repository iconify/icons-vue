<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5z_t1d5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plan-30-60-90" /></template>
<style>
.j5z_t1d5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19.5v-1A1.5 1.5 0 0 1 4 17h3.25a1.5 1.5 0 0 0 1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5h3.25a1.5 1.5 0 0 0 1.5-1.5v-1A1.5 1.5 0 0 1 16.5 9H20a1.5 1.5 0 0 1 1.5 1.5v9A1.5 1.5 0 0 1 20 21H4a1.5 1.5 0 0 1-1.5-1.5M18.25 9V2.5m1.5 0h.742a.585.585 0 0 1 .508.875l-.075.131a1.5 1.5 0 0 0 0 1.488l.075.131a.585.585 0 0 1-.508.875h-.742a1.5 1.5 0 0 1-1.5-1.5V4a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
