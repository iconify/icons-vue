<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tg7swab8w"/><path class="p0r6sib6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:refreezer" /></template>
<style>
.p0r6sib6b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.563 33.956l6.627 6.626l6.626-6.626m-6.626-12.02v18.646");
}

.tg7swab8w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.635 41.136h2.65v1.021a1.31 1.31 0 0 0 1.306 1.314h2.608a1.31 1.31 0 0 0 1.314-1.306v-1.037a2.617 2.617 0 0 0 2.499-2.618V7.156a2.62 2.62 0 0 0-2.613-2.627H12.615a2.62 2.62 0 0 0-2.627 2.613V38.51a2.617 2.617 0 0 0 2.499 2.619v1.029a1.31 1.31 0 0 0 1.308 1.312h2.606a1.31 1.31 0 0 0 1.314-1.306v-1.029h3.03M10.51 19.29h26.98m-22.073-9.283v5.506m0 7.555v5.506");
}

</style>
