<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o2th2-7fb"/><ellipse class="h3uns0b8n"/><path class="djojoquct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:postparty" /></template>
<style>
.djojoquct {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.526 21.74h5.41");
}

.h3uns0b8n {
  cx: 17.447px;
  cy: 21.74px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.575px;
  ry: 2.581px;
}

.o2th2-7fb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.149 33.135h9.853c4.04 0 10.482-3.863 10.498-11.104s-5.038-11.655-11.721-12.04H16.127c-5.837 0-10.696 5.411-10.626 12.04s3.986 9.788 9.724 11.104l-1.9 4.874");
}

</style>
