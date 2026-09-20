<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b_j89xbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-circle-4-20-regular" /></template>
<style>
.b_j89xbyu {
  fill: currentColor;
  d: path("M3 10a7 7 0 1 1 14 0a7 7 0 0 1-14 0m7-8a8 8 0 1 0 0 16a8 8 0 0 0 0-16m1.995 4.309c0-.738-.954-1.032-1.37-.423l-3.533 5.176a.6.6 0 0 0 .496.938h3.41v1.5a.5.5 0 0 0 1 0V12H13a.5.5 0 0 0 0-1h-1.003zm-1 .809L10.997 11H8.345z");
}

</style>
