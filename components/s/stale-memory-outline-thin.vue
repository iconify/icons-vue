<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n0n63pb2v"/><path class="shd7-wbsb"/><path class="gkpqkuwgc"/><path class="suyrhnabh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stale-memory-outline-thin" /></template>
<style>
.gkpqkuwgc {
  d: path("M12 5.5v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0n63pb2v {
  d: path("M4 15v4h16v-4");
}

.shd7-wbsb {
  d: path("M9 8.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.suyrhnabh {
  d: path("M12 8.5h2.5");
}

</style>
