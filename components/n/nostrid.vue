<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jn9muouap"/><path class="bp-xh3biy"/><path class="s803c7bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nostrid" /></template>
<style>
.bp-xh3biy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.513 39.436l-4.273 2.468l-26.754-15.46l22.555-13.021v16.28");
}

.jn9muouap {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.487 26.445v-4.898l26.777-15.45V32.14l-14.112-8.148");
}

.s803c7bjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.264 6.096l4.223 2.439l.027 30.9l-22.555-13.021l14.083-8.13");
}

</style>
