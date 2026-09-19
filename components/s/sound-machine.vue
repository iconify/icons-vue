<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="umooh9bzp"/><ellipse class="umooh9bzp"/><path class="q40bf0bjw"/><ellipse class="yq6r3r84u"/><ellipse class="ddddjhvqf"/><path class="r7_hq-xpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sound-machine" /></template>
<style>
.ddddjhvqf {
  cx: 24.038px;
  cy: 14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.828px;
  ry: 1.502px;
}

.q40bf0bjw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.646 14S5.108 28.357 4.518 32.912C4.038 36.624 13.24 39.69 24 39.69s19.966-3.066 19.482-6.778C42.862 28.17 40.354 14 40.354 14m-4.614 7.651l3.328 11.84M9.729 21.651l3.328 11.84");
}

.r7_hq-xpo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.592 14h.882m-18.872 0h.882m8.554 3.25v.335m0-7.171v.336");
}

.umooh9bzp {
  cx: 24px;
  cy: 14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 16.354px;
  ry: 5.69px;
}

.yq6r3r84u {
  cx: 24px;
  cy: 35.219px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.036px;
  ry: 2.112px;
}

</style>
