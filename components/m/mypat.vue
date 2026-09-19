<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c2n0i0b4n"/><path class="eiizv3-3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mypat" /></template>
<style>
.c2n0i0b4n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.62 25.186a15.341 15.341 0 1 1 8.213 8.703");
}

.eiizv3-3c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.42 43.5s-.8-18.337 10.85-28.263");
}

</style>
