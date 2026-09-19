<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pjsnq486n"/><path class="pyz1cviyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pax-mobile" /></template>
<style>
.pjsnq486n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-1.41 21.63l-1.67-1.73m-2.71-2.8l-1.67-1.73m1.67 4.53l-1.67 1.73m6.05-6.26l-1.67 1.73");
}

.pyz1cviyn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.245 27.13v-6.26h3.206c1.174 0 1.985.69 1.985 1.864s-.811 1.798-1.985 1.798h-3.206m14.092 1.021h-4.099m-1.025 1.577l3.074-6.26l3.075 6.26");
}

</style>
