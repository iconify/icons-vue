<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bef9-wbqz"/><path class="hso2os5js"/><circle class="qy74rb42j"/><circle class="lv6x61bpm"/><circle class="o3eakwb8x"/><circle class="q_-9cebhc"/><path class="f387h2b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rumble" /></template>
<style>
.bef9-wbqz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.957 31.709a11.8 11.8 0 0 0 5.53 3.594c.36.101.719.193 1.087.267q1.12.221 2.295.221c6.515 0 11.796-5.28 11.796-11.786c0-2.01-.498-3.89-1.383-5.539v-.009M32.6 15.112a11.72 11.72 0 0 0-7.731-2.894c-6.506 0-11.787 5.271-11.787 11.787c0 .755.074 1.474.212 2.193v.01");
}

.f387h2b5v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.712 12.57l1.576 7.197l17.14-10.912l-20.66 27.804l-1.512-7.428l-16.588 9.575z");
}

.hso2os5js {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.95 10.836l3.382 5.879l-3.299 2.691v9.188l3.299 2.7l-3.41 5.917l-3.99-1.512l-7.962 4.599l-.682 4.202h-6.829l-.682-4.202l-7.962-4.599l-3.99 1.512l-.599-1.042m28.881-23.933l-.018.01l-.157.064l-7.962-4.598l-.682-4.212h-6.829l-.682 4.212l-7.962 4.598l-3.99-1.52l-3.419 5.925l3.308 2.691v9.188l-3.308 2.7l1.723 2.977");
}

.lv6x61bpm {
  cx: 24.873px;
  cy: 40.336px;
  r: 1.843px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o3eakwb8x {
  cx: 10.719px;
  cy: 15.821px;
  r: 1.843px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q_-9cebhc {
  cx: 39.027px;
  cy: 32.164px;
  r: 1.843px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qy74rb42j {
  cx: 24.873px;
  cy: 7.649px;
  r: 1.843px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
