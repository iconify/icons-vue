<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ur6kzh9-x"/><path class="syl8negkl"/><path class="um8ov264a"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:privacyshade" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.syl8negkl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.9 21.6c.7-6.1-5-11.1-11-11.1s-11.8 5-11 11.1c.7 6.2 6.8 15.1 11 15c4.2.1 10.3-8.8 11-15");
}

.um8ov264a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.3 30.5h6.2v6.9h-27v-6.9h5.9M35 20.6h2.5v6.9H33m-18.3 0h-4.2v-6.9h2.3m12.9-10h11.8v6.9h-3.1m-21.1 0h-2.8v-6.9H22");
}

.ur6kzh9-x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.6 21.3c0 4.8-3.8 8.7-8.6 8.8c-4.8 0-8.7-3.8-8.8-8.6v-.2c0-4.8 3.8-8.7 8.6-8.8s8.7 3.8 8.8 8.6z");
}

</style>
