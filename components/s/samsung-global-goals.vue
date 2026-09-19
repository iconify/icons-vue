<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yigkyxbaa"/><circle class="cpk0fnbgt"/><circle class="xakrkvy8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-global-goals" /></template>
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

.xakrkvy8r {
  cx: 24px;
  cy: 24px;
  r: 10px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yigkyxbaa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.928 14.866L15.25 4.36m1.31 12.953L8.014 9.617m6.464 11.301L3.541 17.364m10.502 7.694L2.606 26.26m12.724 2.757l-9.96 5.75m12.745-2.656l-6.759 9.304m10.563-7.611l-2.392 11.249m6.554-11.249l2.392 11.249m1.412-12.942l6.759 9.304M32.67 29.017l9.96 5.75m-8.673-9.709l11.437 1.202m-11.872-5.342l10.937-3.554m-13.019-.051l8.546-7.696m-11.914 5.249L32.75 4.36M24 14V2.5");
}

</style>
