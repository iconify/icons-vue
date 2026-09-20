<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xb02-7biy"/><path class="lvugp06qn"/><path class="ew59ewb9n"/><path class="evpct9bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:singapore-airlines" /></template>
<style>
.evpct9bdp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.36 40.73h3.178c.716 0 1.384-.362 1.774-.963l4.094-6.315a2.25 2.25 0 0 1 1.884-1.024");
}

.ew59ewb9n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.685 33.658l1.352-2.119a3.31 3.31 0 0 1 2.79-1.528h3.638a3.31 3.31 0 0 1 2.815 1.569l1.695 2.742h-2.17c-.999 0-1.923.529-2.429 1.39l-3.758 6.398a2.82 2.82 0 0 1-2.428 1.39H9.762l6.836-10.814l-7.067-11.028a3.2 3.2 0 0 1-.024-3.42l2.176-3.502l9.157 14.289c.349.544.351 1.24.006 1.787l-6.27 9.919h10.13c.604 0 1.165-.31 1.486-.822l4.074-6.491a2.11 2.11 0 0 1 1.79-.99h3.234");
}

.lvugp06qn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.43 38.758l6.037-9.458a7.35 7.35 0 0 0-.054-7.996L18.367 4.5l-1.94 3.103a3.2 3.2 0 0 0 .039 3.459l.021.033");
}

.xb02-7biy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.512 40.73l6.8-10.654a5.16 5.16 0 0 0-.038-5.614L15.337 9.345l-2.468 3.642a3.2 3.2 0 0 0-.046 3.527l.058.09");
}

</style>
