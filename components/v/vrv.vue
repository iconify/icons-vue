<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ig5xlubfw"/><path class="ls99_u76q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vrv" /></template>
<style>
.ig5xlubfw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.818 44.633L5.84 34.308l.088-20.5L23.994 3.633L41.973 13.96l-.088 20.5Z");
}

.ls99_u76q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.883 28.072l14.273 8.24L39.1 27.685");
}

</style>
