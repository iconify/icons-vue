<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d887occ3b"/><path class="bjoc-1b1x"/><path class="do75_ubrw"/><path class="sx26elboz"/><path class="z3c0asb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:reinstead" /></template>
<style>
.bjoc-1b1x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m45.5 24l-17.997-3.503L24 24l3.503 3.503zM24 24h21.5");
}

.d887occ3b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 2.5l-3.503 17.997L24 24l3.503-3.503zM24 24V2.5");
}

.do75_ubrw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 45.5l3.503-17.997L24 24l-3.503 3.503zM24 24v21.5");
}

.sx26elboz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m2.5 24l17.997 3.503L24 24l-3.503-3.503zM24 24H2.5m38.983-.782a17.5 17.5 0 0 0-16.7-16.7m-.001 34.965a17.5 17.5 0 0 0 16.7-16.701m-34.965 0a17.5 17.5 0 0 0 16.7 16.7");
}

.z3c0asb2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.218 6.517a17.5 17.5 0 0 0-16.7 16.701m20.985 4.285l5.629 5.629m-12.635-5.629l-5.629 5.629m5.629-12.635l-5.629-5.629m12.635 5.629l5.629-5.629");
}

</style>
