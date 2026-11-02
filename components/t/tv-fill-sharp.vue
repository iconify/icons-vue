<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4i9dibnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tv-fill-sharp" /></template>
<style>
.w4i9dibnj {
  fill: currentColor;
  d: path("M8.707 3.293L12 6.586l3.293-3.293a.999.999 0 1 1 1.414 1.414L14.414 7H21a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h6.586L7.293 4.707a.999.999 0 1 1 1.414-1.414");
}

</style>
