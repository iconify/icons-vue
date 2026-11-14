<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yawagqi_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pebble-tray" /></template>
<style>
.yawagqi_f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.192 8.623q.592-.373 1.558-.373q2.092 0 2.433 1.75h.317q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .117-.036.229l-2 6.25q-.018.056-.044.109q-.027.053-.062.101q-.034.048-.076.09t-.09.077t-.1.062t-.109.045t-.115.028t-.118.009h-15q-.059 0-.118-.009q-.058-.01-.115-.028q-.056-.018-.109-.045q-.052-.027-.1-.062t-.09-.077t-.076-.09t-.062-.101q-.026-.053-.044-.109l-2-6.25q-.046-.143-.033-.291q.012-.149.08-.281q.069-.133.182-.229q.114-.097.256-.142Q2.383 10 2.5 10h.792Q3.646 7 7 7q2.151 0 3.068 1.234q.191-.254.427-.489Q11.74 6.5 13.5 6.5t3.005 1.245q.411.411.687.878M18 10h1.5q-.25-.25-.75-.25T18 10m-4.5-2q2.345 0 2.69 2h-5.38q.345-2 2.69-2M7 8.5q-1.837 0-2.174 1.5h4.348Q8.837 8.5 7 8.5");
}

</style>
