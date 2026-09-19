<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="pu-0m6bji"/><path class="wurzehbsp"/><path class="iohq_73lr"/><circle class="piuq-bcef"/><path class="w4qj8m78u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trufi" /></template>
<style>
.iohq_73lr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.572 5.298c9.942-1.753 12.674 2.685 13.339 6.456l2.901 16.453a6.54 6.54 0 0 1-5.305 7.577l-17.39 3.066a6.54 6.54 0 0 1-7.577-5.305L7.639 17.09c-.665-3.77.384-8.875 10.326-10.628Z");
}

.piuq-bcef {
  cx: 34.412px;
  cy: 29.985px;
  r: 2.808px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pu-0m6bji {
  cx: 17.162px;
  cy: 33.027px;
  r: 2.808px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.w4qj8m78u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.666 35.932l.442 2.503a2.115 2.115 0 0 0 2.45 1.716l1.225-.216a2.115 2.115 0 0 0 1.716-2.45l-.774-4.388");
}

.wurzehbsp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.957 38.702l.442 2.503a2.115 2.115 0 0 1-1.716 2.45l-1.225.216a2.115 2.115 0 0 1-2.45-1.716l-.774-4.387");
}

</style>
