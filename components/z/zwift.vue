<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y7sm4im4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zwift" /></template>
<style>
.y7sm4im4j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.952 6.776a5.452 5.452 0 0 0 0 10.905h4.258L6.245 33.019a5.452 5.452 0 0 0 4.707 8.204h22.524a5.452 5.452 0 1 0 0-10.905H28.74L42.5 6.776Z");
}

</style>
