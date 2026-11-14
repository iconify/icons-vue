<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="piqge88pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:soil-moisture-sensor" /></template>
<style>
.piqge88pq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.812 20H2.5c1.339-3.682 6.711-4.899 10.866-3.651M9.25 2.5h2.5a1.75 1.75 0 0 1 1.75 1.75v1.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 7.5 5.75v-1.5A1.75 1.75 0 0 1 9.25 2.5M9 7.5V17m3-9.5V17m6.5-3.5c1.75 2.25 3 3.75 3 5.5a3 3 0 0 1-6 0c0-1.75 1.25-3.25 3-5.5");
}

</style>
