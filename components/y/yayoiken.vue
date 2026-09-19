<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="h_kzl2b9a"/><path class="y5i16mbyt"/><path class="ajcprx55j"/><path class="b0282cy1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yayoiken" /></template>
<style>
.ajcprx55j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 36.25c8.274-4.778 13.541-13.104 13.541-17.981M20 11.5c5.699 11.963 3.36 19.419-1.5 22.75C20.5 36.5 27 38 27 38c2.426-2.321 7.12-16.643 3-26.5z");
}

.b0282cy1f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.5 34.25C24.966 30.597 30 16.378 30 11.5");
}

.h_kzl2b9a {
  width: 4px;
  height: 4px;
  x: 38px;
  y: 32.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.5px;
  ry: 0.5px;
}

.y5i16mbyt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.5 11.5h10v27h-10zm-27-2h10m3.5 0h10m3.5 0h10m-37 2c7.668 12.888 2.74 22.745-2 24.75c2 2.25 9 1.75 9 1.75c2.426-2.321 7.12-16.643 3-26.5z");
}

</style>
