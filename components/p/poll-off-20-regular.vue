<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nmm07ubik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:poll-off-20-regular" /></template>
<style>
.nmm07ubik {
  fill: currentColor;
  d: path("M8 8.707L2.146 2.854a.5.5 0 1 1 .708-.708l15 15a.5.5 0 0 1-.708.708l-.13-.13A2 2 0 0 1 14 16v-1.294l-2-2V16a2 2 0 1 1-4 0zm3 3l-2-2V16a1 1 0 1 0 2 0zm4 4V16a1 1 0 0 0 1.259.966zM11 4v4.879l1 1V4a2 2 0 1 0-4 0v1.879l1 1V4a1 1 0 0 1 2 0m3 7.879l1 1V8a1 1 0 1 1 2 0v6.879l1 1V8a2 2 0 1 0-4 0zM2 12a2 2 0 1 1 4 0v4a2 2 0 1 1-4 0zm2-1a1 1 0 0 0-1 1v4a1 1 0 1 0 2 0v-4a1 1 0 0 0-1-1");
}

</style>
