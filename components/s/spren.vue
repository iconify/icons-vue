<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pmo1cubef"/><path class="azxqz4wcr"/><circle class="ofk75-xbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:spren" /></template>
<style>
.azxqz4wcr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.295 7.49a3.08 3.08 0 0 1 1.344-2.6a2.395 2.395 0 0 1 2.667.03a3.09 3.09 0 0 1 1.293 2.63M9.797 36.647l28.403-.033m-14.354.016v4.302m9.823-26.769c-2.202 18.492 5.89 14.164 4.531 22.45M14.487 14.54c2.202 18.492-6.048 13.82-4.69 22.107");
}

.ofk75-xbl {
  cx: 23.846px;
  cy: 42.216px;
  r: 1.284px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pmo1cubef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.487 14.54c-.012-2.463 1.828-4.742 4.82-5.97a12.98 12.98 0 0 1 9.643.036c2.97 1.248 4.773 3.54 4.72 6.003");
}

</style>
