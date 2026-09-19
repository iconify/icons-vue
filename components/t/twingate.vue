<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hp9tbeb0o"/><path class="zjer7ibpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:twingate" /></template>
<style>
.hp9tbeb0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.713 43.5l11.092-7.623a10.86 10.86 0 0 0 4.709-8.95v-16.49L24.42 18.058a10.86 10.86 0 0 0-4.708 8.95z");
}

.zjer7ibpd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.286 15.402V4.5l-11.087 7.623a10.86 10.86 0 0 0-4.713 8.948v16.494l7.232-4.973");
}

</style>
