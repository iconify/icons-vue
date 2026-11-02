<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qt_4xq98p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:train-track-fill" /></template>
<style>
.qt_4xq98p {
  fill: currentColor;
  d: path("M2.293 16.293L3.586 15l-1.293-1.293a.999.999 0 1 1 1.414-1.414L5 13.586L8.586 10L7.293 8.707a.999.999 0 1 1 1.414-1.414L10 8.586L13.586 5l-1.293-1.293a.999.999 0 1 1 1.414-1.414L15 3.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L16.414 5L19 7.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L20.414 9l1.293 1.293a.999.999 0 1 1-1.414 1.414L19 10.414L15.414 14l1.293 1.293a.999.999 0 1 1-1.414 1.414L14 15.414L10.414 19l1.293 1.293a.999.999 0 1 1-1.414 1.414L9 20.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L7.586 19L5 16.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414M14 12.586L17.586 9L15 6.414L11.414 10Zm-5 5L12.586 14L10 11.414L6.414 15Z");
}

</style>
