<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="krrk8-b7v"/><rect class="mb2brrx6f"/><path class="wi_6vvruu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nfctools" /></template>
<style>
.krrk8-b7v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.07 9.29za18.28 18.28 0 0 1 0 29.42m-4-24.16a11.84 11.84 0 0 1 5 9.45a11.84 11.84 0 0 1-5 9.45m-3.68-14a5.67 5.67 0 0 1 0 9.1");
}

.mb2brrx6f {
  width: 17.53px;
  height: 30.79px;
  x: 4.5px;
  y: 8.6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.58px;
}

.wi_6vvruu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 12.55h17.53M4.5 35.45h17.53");
}

</style>
