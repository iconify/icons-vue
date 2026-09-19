<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k-s7qcc3q"/><path class="whno38bem"/><path class="u3gdtof8l"/><circle class="weyg9g97c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pixel-clock-widgets" /></template>
<style>
.k-s7qcc3q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.08 11.622c.388 4.432 6.15 4.396 3.9 10.198c-1.879 4.032 3.128 6.882-1.72 10.783c-3.644 2.552-.732 7.523-6.882 8.477c-4.432.389-4.396 6.15-10.198 3.901c-4.032-1.88-6.882 3.127-10.783-1.721c-2.552-3.644-7.523-.732-8.477-6.882c-.388-4.432-6.15-4.396-3.9-10.198c1.879-4.032-3.128-6.882 1.72-10.783c3.644-2.552.732-7.523 6.882-8.477c4.432-.388 4.396-6.15 10.198-3.9c4.032 1.879 6.882-3.128 10.783 1.72c2.552 3.644 7.523.732 8.477 6.882");
}

.u3gdtof8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.279 25.998a2.125 2.125 0 0 1-1.277-2.72l3.75-10.39a2.125 2.125 0 0 1 3.998 1.442l-3.752 10.391a2.125 2.125 0 0 1-2.72 1.277");
}

.weyg9g97c {
  cx: 7.292px;
  cy: 22.009px;
  r: 2.124px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.whno38bem {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.498 22.498c.83-.83 2.174-.83 3.004 0l6.676 6.675a2.125 2.125 0 0 1-3.005 3.005l-6.675-6.676a2.125 2.125 0 0 1 0-3.004");
}

</style>
