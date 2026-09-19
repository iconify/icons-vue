<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oktsvqb-a"/><path class="hc7jfgb6j"/><path class="jrvzk0p9j"/><path class="sym5vh8uz"/><path class="m3t0nuzyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:spotiflyer" /></template>
<style>
.hc7jfgb6j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.269 32.627c2.896.944 3.99 3.232 3.848 8.343");
}

.jrvzk0p9j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.529 37.725l-3.426 3.255l-3.425-3.255");
}

.m3t0nuzyr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.567 24.28c7.808-2.369 17.515-1.22 24.152 2.857M10.35 17.32c7.595-2.305 20.22-1.86 28.198 2.876M12.33 30.67c6.86-1.57 12.91-1.26 18.02.92");
}

.oktsvqb-a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.554 28.607a7.947 7.947 0 1 0 7.946 7.947h0v-.01a7.937 7.937 0 0 0-7.937-7.937z");
}

.sym5vh8uz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.59 32.86c1.23-2.7 1.91-5.7 1.91-8.86c0-11.87-9.63-21.5-21.5-21.5S2.5 12.13 2.5 24S12.13 45.5 24 45.5c3.16 0 6.16-.68 8.86-1.91");
}

</style>
