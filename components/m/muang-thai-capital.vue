<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mqjauu0cl"/><path class="lynn4incc"/><path class="gb_o8ib1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:muang-thai-capital" /></template>
<style>
.gb_o8ib1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.652 33.88c3.67-3.724 9.5-11.434 9.965-25.313c.542 16.16 8.357 23.957 11.567 26.835");
}

.lynn4incc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.348 33.88c-3.67-3.724-9.5-11.434-9.965-25.313c-.542 16.16-8.357 23.957-11.567 26.835");
}

.mqjauu0cl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5h0C12.126 45.5 2.5 35.874 2.5 24h0C2.5 12.126 12.126 2.5 24 2.5h0c11.874 0 21.5 9.626 21.5 21.5");
}

</style>
