<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q0pfjzyyh"/><circle class="t19f0lfak"/><path class="ekgvmpbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minhaoi" /></template>
<style>
.ekgvmpbzi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.05 21.522v8.881M5.365 22.277c.045-5.664 3.073-10.126 6.908-13.335s8.666-4.484 14.31-4.44s14.17 4.577 15.79 9.868s-4.715 8.902-5.922 13.323s.786 9.987-1.48 12.83s-5.424 3.056-8.388 2.96c-13.823-.445-21.246-9.38-21.218-21.206");
}

.q0pfjzyyh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.648 30.403a3.397 3.397 0 0 1-3.454-3.355v-2.171a3.456 3.456 0 0 1 6.908 0v2.178a3.414 3.414 0 0 1-3.454 3.352Z");
}

.t19f0lfak {
  cx: 29.05px;
  cy: 18.81px;
  r: 0.75px;
  fill: currentColor;
}

</style>
