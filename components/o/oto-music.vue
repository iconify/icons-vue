<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="il8ghy5zn"/><circle class="y45wx2xdn"/><path class="j0bt1xb-e"/><path class="cknvqtncw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oto-music" /></template>
<style>
.cknvqtncw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.135 4.5H13.169v8.751h9.051");
}

.il8ghy5zn {
  cx: 20.057px;
  cy: 32.586px;
  r: 2.164px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j0bt1xb-e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.22 32.586V15.414m.002 6.472a11.2 11.2 0 0 0-4.096-.05a10.918 10.918 0 0 0 2.508 21.65a11.174 11.174 0 0 0 10.337-11.29v-14a4.946 4.946 0 0 1 4.946-4.945h2.94V4.5h-5.722A10.914 10.914 0 0 0 22.22 15.414");
}

.y45wx2xdn {
  cx: 36.613px;
  cy: 18.736px;
  r: 2.164px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
