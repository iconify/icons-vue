<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k1d4u8bxa"/><path class="esa94b30c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myride-link" /></template>
<style>
.esa94b30c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.053 22.38l.729.872a5.414 5.414 0 0 1-.684 7.642l-9.96 8.323a5.413 5.413 0 0 1-7.642-.685l-.729-.872a5.414 5.414 0 0 1 .685-7.643l9.959-8.322a5.413 5.413 0 0 1 7.642.684");
}

.k1d4u8bxa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.504 9.468l.729.873a5.414 5.414 0 0 1-.684 7.642l-9.96 8.322a5.413 5.413 0 0 1-7.642-.684l-.729-.873a5.414 5.414 0 0 1 .685-7.642l9.959-8.323a5.413 5.413 0 0 1 7.642.685");
}

</style>
