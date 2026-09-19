<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y710xcb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openweather" /></template>
<style>
.y710xcb7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.673 30.636a17.694 17.694 0 1 0-33.345 0M4.5 30.635h39M8.791 35.817h15.706m4.393 0h2.982m4.392 0h2.982m-24.64 5.181h19.757");
}

</style>
