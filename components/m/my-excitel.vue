<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x3oa7pb1s"/><circle class="kguly92mf"/><path class="i13l1481i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-excitel" /></template>
<style>
.i13l1481i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.25 20.75L4.64 33.36M33.36 4.64L20.75 17.25m4.7-14.7l-22.9 22.9m4-13.99l4.91-4.91l.03-.03m15.76 24.23L14.64 43.36m28.72-28.72L30.75 27.25m14.7-4.7l-22.9 22.9m14-3.99l.03-.03l4.85-4.85l.03-.03");
}

.kguly92mf {
  cx: 24px;
  cy: 24px;
  r: 7.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x3oa7pb1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.5 24h7m-9 5h11m-11-10h11M18.7 29.3l-9.9 9.9M39.2 8.8l-9.9 9.9");
}

</style>
