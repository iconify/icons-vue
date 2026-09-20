<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c5x0ilhdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-footer-arrow-down-20-regular" /></template>
<style>
.c5x0ilhdj {
  fill: currentColor;
  d: path("M7 15.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5M5 4a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2zm2-1a1 1 0 0 0-1 1v12a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1V4a1 1 0 0 0-1-1zm5.354 8.854l-2 2l-.003.002a.5.5 0 0 1-.348.144h-.006a.5.5 0 0 1-.35-.146l-2-2a.5.5 0 0 1 .707-.708L9.5 12.293V9.5a.5.5 0 0 1 1 0v2.793l1.146-1.147a.5.5 0 0 1 .708.708");
}

</style>
