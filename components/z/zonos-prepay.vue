<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="gh9tvsntj"/><path class="leie8bb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zonos-prepay" /></template>
<style>
.gh9tvsntj {
  cx: 24px;
  cy: 25.216px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.leie8bb-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 20.216v-4a9 9 0 1 1-4.156 16.983l-2.078 3.992a13.5 13.5 0 1 1 15.355-21.93l2.702-2.948a17.5 17.5 0 1 1-27.99 19.599l-3.695 1.53C-.313 22.697 4.588 10.36 15.198 5.6C25.81.838 38.285 5.378 43.353 15.846s.892 23.07-9.424 28.44l-1.847-3.549");
}

</style>
