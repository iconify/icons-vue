<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="bi9aflbjx"/><circle class="abwmgkeay"/><circle class="x86j-ydem"/><circle class="wx7mi5qqx"/><path class="n5x6lgpdv"/><path class="v2tm8dbeu"/><path class="q9f8i039j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:warpinator" /></template>
<style>
.abwmgkeay {
  cx: 9.37px;
  cy: 8.049px;
  r: 3.049px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.bi9aflbjx {
  cx: 21.443px;
  cy: 23.011px;
  r: 6.358px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n5x6lgpdv {
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 1 2;
  stroke-linecap: round;
  d: path("m11.476 10.802l5.772 7.299");
}

.q9f8i039j {
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 1 2;
  stroke-linecap: round;
  d: path("m14.03 34.38l3.393-5.708");
}

.v2tm8dbeu {
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 1 2;
  stroke-dashoffset: 4.5;
  stroke-linecap: round;
  d: path("m27.67 22.586l6.096-.435");
}

.wx7mi5qqx {
  cx: 38.318px;
  cy: 21.688px;
  r: 3.36px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x86j-ydem {
  cx: 11.114px;
  cy: 39.182px;
  r: 3.818px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
