<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fag840bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:uae4arm" /></template>
<style>
.fag840bun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.25 28l8.16 11.89l21.26-31.8M18.68 35.82l2.81 4.09L42.75 8.09M13.33 28l2.74 4");
}

</style>
