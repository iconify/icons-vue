<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="j1us9qb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:regexcrossword" /></template>
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

.j1us9qb0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15 30.23V17.48h4.18a4.29 4.29 0 0 1 0 8.57H15m4.17 0l4.17 4.18m9.65-8.45l-6.38 8.45m6.38 0l-6.38-8.45M14.6 10.18L7.87 26m32.26-4L33.4 37.82");
}

</style>
