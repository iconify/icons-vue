<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-45 24 24)" class="i2-7d1bvl"/><path class="ku6vp8b-d"/><path class="dsog48ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:npo-luister" /></template>
<style>
.dsog48ban {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.958 23.987h.565a1.24 1.24 0 0 1 1.24 1.24v4.556a1.24 1.24 0 0 1-1.24 1.24h-.564a2.46 2.46 0 0 1-2.459-2.459v-2.118a2.46 2.46 0 0 1 2.458-2.458m12.05 7.034h-.565a1.24 1.24 0 0 1-1.239-1.238v-4.558a1.24 1.24 0 0 1 1.239-1.239h.565a2.46 2.46 0 0 1 2.459 2.458v2.12a2.46 2.46 0 0 1-2.459 2.458");
}

.i2-7d1bvl {
  width: 30px;
  height: 30px;
  x: 9px;
  y: 9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 3px;
}

.ku6vp8b-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.5 26.446v-2.969a8.5 8.5 0 1 0-17 0v2.969");
}

</style>
