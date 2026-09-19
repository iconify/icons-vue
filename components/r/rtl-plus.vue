<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vs_-sk_ph"/><path class="sr4jse75r"/><path class="d3k4dlqtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rtl-plus" /></template>
<style>
.d3k4dlqtm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.334 22.203v3.315h4.974m-16.302-3.176h4.973m-2.486 3.316v-3.316m21.52.199v3.316m-2.487-1.658H44.5");
}

.sr4jse75r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.5 20.27h11.328v7.46H3.5zm11.328 0h11.328v7.46H14.828zm11.329 0h11.328v7.46H26.157z");
}

.vs_-sk_ph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.678 25.658v-3.316h3.862c.614 0 1.11.499 1.11 1.114s-.497 1.113-1.11 1.113H6.678m3.862 0l1.085 1.088");
}

</style>
