<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yhy910zdf"/><rect class="y_f2bbm3f"/><path class="p13p70suy"/><path class="vvtf29b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:melolo" /></template>
<style>
.p13p70suy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.499 24.919v12.478h1.611m4.714-2.725v-6.888a2.863 2.863 0 0 1 2.866-2.865a2.86 2.86 0 0 1 2.865 2.865v3.59");
}

.vvtf29b4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.653 18.416L17.795 6.373c-4.299-2.481-9.672.62-9.672 5.584v24.086c0 4.963 5.373 8.065 9.672 5.584l20.858-12.043c4.299-2.482 4.299-8.686 0-11.168");
}

.y_f2bbm3f {
  width: 5.731px;
  height: 12.476px;
  x: 14.818px;
  y: 24.916px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.865px;
  ry: 2.865px;
}

.yhy910zdf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.448 37.397H8.263m-.14-1.352V24.919m.173-14.446l3.654 11.916l3.828-12.457v12.457m-7.655-.011V11.954m11.679 4.195h2.82m1.298-6.238h-4.119v12.478h4.325");
}

</style>
