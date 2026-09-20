<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="antg9pb8w"/><circle class="ddpzdj9ts"/><path class="of4ce3bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:silence-2" /></template>
<style>
.antg9pb8w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.706 30.274a62 62 0 0 1-6.298-1.11a3.11 3.11 0 0 0-2.999.58c-.53.54-2.059 2.05-3.648 3.609a28.68 28.68 0 0 1-13.096-13.105c1.55-1.59 3-3.11 3.589-3.639a3.11 3.11 0 0 0 .58-2.999a62 62 0 0 1-1.11-6.308A2 2 0 0 0 15.53 5.52l-.105.014H6.908a1.5 1.5 0 0 0-1.36 1.37c-.55 7.687 3.739 15.914 4.608 17.494v.06l.12.23a35.4 35.4 0 0 0 12.996 12.995l.44.25c2 1.06 9.947 5.058 17.374 4.508a1.5 1.5 0 0 0 1.39-1.36v-8.507a2 2 0 0 0-1.665-2.286z");
}

.ddpzdj9ts {
  cx: 34.503px;
  cy: 13.506px;
  r: 7.997px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.of4ce3bqj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.214 13.506h10.578");
}

</style>
