<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="oqchuwnil"/><path class="qfjxy2bhk"/><path class="unxwndbob"/><path class="wxvxnjdoh"/><path class="aew6nbc0v"/><path class="ozj6hcbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sipnetic" /></template>
<style>
.aew6nbc0v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.007 21.029a17.082 17.082 0 0 1 27.986 0");
}

.oqchuwnil {
  cx: 24px;
  cy: 23.78px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.989px;
  ry: 2.135px;
}

.ozj6hcbbb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.53 14.96c9.525-6.46 23.415-6.46 32.94 0m-32.94 0c-2.7 1.693-4.907 5.42-.612 7.218a2.596 2.596 0 0 0 3.09-1.15M40.47 14.96c2.7 1.693 4.907 5.42.612 7.218a2.596 2.596 0 0 1-3.09-1.15M9.05 30.833c.115 4.638 4.448 6.97 14.962 7.05s14.876-2.334 14.932-7.059");
}

.qfjxy2bhk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.147 28.36a10.15 10.15 0 0 1-10.426-.085c-2.972-1.945-3.597-5.219-1.474-7.707s6.36-3.449 9.978-2.26s5.532 4.17 4.51 7.02");
}

.unxwndbob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.147 28.36l-1.482-2.743l4.07-.29");
}

.wxvxnjdoh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.054 30.826a14.947 14.947 0 1 1 29.893 0");
}

</style>
