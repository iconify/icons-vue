<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="f0z08q67z"/><path class="cj8dxil5j"/><path class="ry-df4p8n"/><path class="zy74fob0o"/><path class="i17z_-bev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tunnelbear-alt" /></template>
<style>
.cj8dxil5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.706 10.894c0 3.531-7.48 6.394-16.706 6.394S7.294 14.425 7.294 10.894m0 0C7.294 7.363 14.774 4.5 24 4.5s16.706 2.863 16.706 6.394v6.351c0 3.532-7.48 6.394-16.706 6.394S7.294 20.777 7.294 17.246z");
}

.f0z08q67z {
  cx: 24px;
  cy: 10.934px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 13.143px;
  ry: 3.772px;
}

.i17z_-bev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.813 27.154H20.97c-6.638 0-7.677 4.3-6.038 6.311c2.99 3.668 8.105.777 6.782-2.184c-.744-1.665-2.892-1.922-3.863-.751");
}

.ry-df4p8n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.196 20.157v17.487c0 3.234-6.803 5.856-15.196 5.856S8.804 40.878 8.804 37.644V20.157");
}

.zy74fob0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.665 39.329c1.231-1.361 4.722-.27 6.97-.27c1.014 0 2.128-.317 2.805-2.226c1.034-2.914 2.598-7.446 3.276-9.68");
}

</style>
