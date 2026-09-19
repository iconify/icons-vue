<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="j0x7qnb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sajda" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j0x7qnb4j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.616 9.866a17 17 0 0 1 2.962 9.616c0 9.442-7.654 17.096-17.096 17.096a17 17 0 0 1-9.616-2.962c3.077 4.514 8.258 7.48 14.134 7.48c9.442 0 17.096-7.654 17.096-17.096c0-5.876-2.966-11.056-7.48-14.134");
}

</style>
