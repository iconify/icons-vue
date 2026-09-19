<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pdwy3zblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:skiddle" /></template>
<style>
.pdwy3zblx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.5 12.509l-14.25 8.227m6.334 4.352l7.916-4.57V4.5l-19 10.97v2.002l19 13.056v2.002l-19 10.97V27.484l7.916-4.57m6.334 4.35L14.5 35.491");
}

</style>
