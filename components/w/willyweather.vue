<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-11.238 24 15.526)" class="tvp9fgb5u"/><path class="ikapzgb-u"/><path class="bkh-gq4sg"/><path class="l53emxbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:willyweather" /></template>
<style>
.bkh-gq4sg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.836 29.416a5 5 0 0 0 .047.589c.515 3.712 4.983 6.16 9.98 5.468a11.8 11.8 0 0 0 3.63-1.105");
}

.ikapzgb-u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.02 22.778a3.67 3.67 0 0 0-.358 2.09c.515 3.712 7.247 5.846 15.037 4.767s13.688-4.965 13.173-8.678a3.9 3.9 0 0 0-1.331-2.34");
}

.l53emxbdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.624 33.258a4.9 4.9 0 0 0-.07 1.712c.398 2.869 3.315 4.932 6.95 5.203");
}

.tvp9fgb5u {
  cx: 24px;
  cy: 15.526px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 19.835px;
  ry: 6.786px;
}

</style>
