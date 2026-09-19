<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hyj2i9bak"/><path class="a43agccdh"/><path class="o6e4etbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minecraft-compass" /></template>
<style>
.a43agccdh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.144 24v2.643h2.642v2.643h5.286v2.643h15.857v-2.643h5.285v-2.643h2.643V24m-10.32-8.075v2.391h-2.643v2.392h-2.643v2.391h5.286v-2.391h2.643v-2.392h2.643v-2.391z");
}

.hyj2i9bak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.857 16.072v-2.643h-2.643v-2.643H31.93V8.143H16.07v2.643h-5.285v2.643H8.143v2.643H5.5v15.857h2.643v2.643h2.643v2.642h5.285v2.643H31.93v-2.643h5.285v-2.642h2.643v-2.643H42.5V16.072z");
}

.o6e4etbee {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.861 25.993v-5.286h2.391v5.286z");
}

</style>
