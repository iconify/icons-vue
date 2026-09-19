<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wd_-7k5sy"/><path class="fbp6fpjjf"/><ellipse class="dr9jo6mnd"/><path class="wb-kk_bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:meituan" /></template>
<style>
.dr9jo6mnd {
  cx: 22.233px;
  cy: 26.999px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.198px;
  ry: 3.115px;
}

.fbp6fpjjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.507 23.71c-3.888.793-4.96 11.298.388 11.74");
}

.wb-kk_bcz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.804 33.746c1.358 1.977 3.407 3.335 5.598 2.073");
}

.wd_-7k5sy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.246 42.487a93 93 0 0 1-.015-1.904c17.531-5.599 12.944-15.146 5.586-20.007c.628-3.142 1.407-6.017 2.333-8.604a5.589 5.589 0 0 0-10.522-3.766c-1.01 2.826-1.863 5.92-2.566 9.243c-.642-3.034-1.458-6.093-2.499-9.035c-.976-2.761-3.907-4.48-6.74-3.735a5.59 5.59 0 0 0-3.856 7.293c4.215 11.779 4.258 26.557 4.185 30.513a.994.994 0 0 0 1 1.012l12.094.003a.996.996 0 0 0 1-1.013");
}

</style>
