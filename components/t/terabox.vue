<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="en35j3bll"/><path class="b3o931b3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:terabox" /></template>
<style>
.b3o931b3x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.286 30.509l-4.743-4.742l-4.742 4.742");
}

.en35j3bll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.388 11.012c5.289-.285 10.791 2.763 12.617 9.736a8.16 8.16 0 0 1 7.467 8.796c-.323 3.959-3.402 7.462-7.407 7.462H13.26c-11.125 0-13.06-18.263 0-19.52a12.03 12.03 0 0 1 10.127-6.474Zm1.155 25.994V25.767");
}

</style>
