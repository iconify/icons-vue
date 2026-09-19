<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x7t7dwhtp"/><path class="zjzcmsazl"/><path class="csawrw22u"/><circle class="rwdd0xb4a"/><circle class="mqhw4vbox"/><path class="esdckw8yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trifa" /></template>
<style>
.csawrw22u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.016 33.022a6.985 6.985 0 1 1 13.97 0v6.636h-13.97Z");
}

.esdckw8yw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.926 27.202l-1.165-1.747m9.314 1.747l1.164-1.747");
}

.mqhw4vbox {
  cx: 27.201px;
  cy: 30.403px;
  r: 0.75px;
  fill: currentColor;
}

.rwdd0xb4a {
  cx: 20.799px;
  cy: 30.403px;
  r: 0.75px;
  fill: currentColor;
}

.x7t7dwhtp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.939 18.753c2.12-2.646 2.727-6.17.783-8.946a6.985 6.985 0 1 0-5.113 10.965a10.6 10.6 0 0 1-.597 2.699a29 29 0 0 0 4.927-4.718");
}

.zjzcmsazl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.687 13.813a9.313 9.313 0 1 1 18.626 0v5.821h6.403V43.5H8.284V19.634h6.403Z");
}

</style>
