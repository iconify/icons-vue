<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zmc96rb6u"/><rect class="w_ffrezpi"/><path class="azov1abny"/><path class="ukfhkpb8f"/><path class="ct80qybvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-business-tv" /></template>
<style>
.azov1abny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.119 31.638h5.763v7.839h-5.763zm.624-18.016v8.098a3.18 3.18 0 0 1-3.182 3.182h0a3.18 3.18 0 0 1-3.182-3.182v-8.098m17.242 0v8.098a3.18 3.18 0 0 1-3.182 3.182h0a3.18 3.18 0 0 1-3.182-3.182v-8.098");
}

.ct80qybvh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 21.72a3.18 3.18 0 0 1-3.182 3.182h0a3.18 3.18 0 0 1-3.182-3.182v-8.098m-26.272 0v8.098a3.18 3.18 0 0 1-3.182 3.182h0A3.18 3.18 0 0 1 4.5 21.72");
}

.ukfhkpb8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.585 23.347a3.18 3.18 0 0 1-2.735 1.555h0a3.18 3.18 0 0 1-2.706-1.508m-5.388-.083A3.18 3.18 0 0 1 24 24.901h0a3.18 3.18 0 0 1-2.72-1.53m-5.424.024a3.18 3.18 0 0 1-2.706 1.507h0a3.18 3.18 0 0 1-2.756-1.59");
}

.w_ffrezpi {
  width: 39px;
  height: 25.855px;
  x: 4.5px;
  y: 13.621px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.zmc96rb6u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.018 13.621l5.098-5.097m-10.214 0L24 13.621");
}

</style>
