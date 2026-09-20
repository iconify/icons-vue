<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b638um2po"/><path class="boo92bs_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:materialislands" /></template>
<style>
.b638um2po {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.45 30.24L24 28.18l-13.45 2.06L24 4.5z");
}

.boo92bs_p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.55 30.24L24 28.18l13.45 2.06L24 43.5zM24 4.5v39");
}

</style>
