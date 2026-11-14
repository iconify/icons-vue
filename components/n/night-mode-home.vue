<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh__84v0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:night-mode-home" /></template>
<style>
.yh__84v0d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m9.201 4.953l-4.5 3.937Q3.25 10.16 3.25 12.088V16.5q0 1.76 1.245 3.005T7.5 20.75h1.25q1.76 0 3.005-1.245T13 16.5v-.75Q13 13 15.75 13h3.375q.673 0 1.149-.476t.476-1.149q0-1.216-.915-2.015l-5.036-4.407q-2.799-2.45-5.598 0m12.526 14.481q-.881 3.492-4.47 3.195q-3.59-.296-3.886-3.886q-.297-3.589 3.195-4.47q.072-.018.146-.022t.147.007t.142.035t.133.063t.119.087q.055.05.099.109t.075.126q.032.067.05.138q.024.095.023.192q-.001.098-.027.191q-.026.094-.075.178t-.118.153q-1.594 1.595 0 3.19q.798.797 1.595.797t1.595-.797q.052-.053.113-.094t.13-.069t.141-.043T21 18.5t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.069.069.118.153t.075.178t.027.191t-.023.192");
}

</style>
