<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y6m1vacym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zoysii" /></template>
<style>
.y6m1vacym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 4l18.67 14.81L24 33.62L5.33 18.81Zm12.13 20l6.54 5.19L24 44L5.33 29.19L11.87 24");
}

</style>
