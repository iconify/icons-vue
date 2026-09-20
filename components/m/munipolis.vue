<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uiiu8wutw"/><path class="wnz5g-4hx"/><circle class="j_evs0bva"/><path class="n2qujj8gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:munipolis" /></template>
<style>
.j_evs0bva {
  cx: 24px;
  cy: 24px;
  r: 3.071px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n2qujj8gi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 27.071V45.5");
}

.uiiu8wutw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.997 45.289C10.388 43.793 2.5 34.714 2.5 24C2.5 12.126 12.126 2.5 24 2.5S45.5 12.126 45.5 24c0 10.714-7.888 19.793-18.497 21.289");
}

.wnz5g-4hx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.994 35.912A12.286 12.286 0 0 1 11.714 24c0-6.785 5.5-12.286 12.286-12.286S36.286 17.214 36.286 24a12.286 12.286 0 0 1-9.28 11.912");
}

</style>
