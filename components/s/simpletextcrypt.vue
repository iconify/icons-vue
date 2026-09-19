<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="pnz4lsb4r"/><path class="ksr48ccqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:simpletextcrypt" /></template>
<style>
.ksr48ccqw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 33.6l6.52 6.45h.01l16.72-16.53m-16.2 8.58l3.76 3.72");
}

.pnz4lsb4r {
  cx: 34.27px;
  cy: 17.07px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 9.23px;
  ry: 9.12px;
}

</style>
