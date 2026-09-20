<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cd3krbc6p"/><path class="r1wce7vla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:session" /></template>
<style>
.cd3krbc6p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.51 4.5h-19a9 9 0 0 0-9 9a9.05 9.05 0 0 0 4.3 7.7L24 29.41V18.59h10.28a7.19 7.19 0 0 0 7.1-5.43a7.07 7.07 0 0 0-6.87-8.66");
}

.r1wce7vla {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.49 43.5h19a9 9 0 0 0 9-9a9.05 9.05 0 0 0-4.3-7.7L24 18.59v10.82H13.72a7.19 7.19 0 0 0-7.1 5.43a7.07 7.07 0 0 0 6.87 8.66");
}

</style>
