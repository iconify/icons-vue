<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o2y50xp_j"/><path class="omxmfacgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mumbai-1-1" /></template>
<style>
.o2y50xp_j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.783 20.68l-2.83-1.66L4.5 30.25l6.287 3.63v6.714l12.873-7.433l13.098 7.563v-7.033L43.5 29.8l-13.654-7.884V7.808l-5.82 3.36l-6.741-3.893V22.89");
}

.omxmfacgq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.846 21.916v8.255l-2.72 1.57m-3.466 1.421l-6.348-3.665v-3.33");
}

</style>
