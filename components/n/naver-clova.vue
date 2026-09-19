<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c0zubbcta"/><path class="nkqnq4b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:naver-clova" /></template>
<style>
.c0zubbcta {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 39.326c-4.232 4.232-11.094 4.232-15.326 0S4.442 28.232 8.674 24c-4.232-4.232-4.232-11.094 0-15.326s11.094-4.232 15.326 0c4.232-4.232 11.094-4.232 15.326 0s4.232 11.094 0 15.326h0c4.232 4.232 4.232 11.094 0 15.326s-11.094 4.232-15.326 0");
}

.nkqnq4b0h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 35.304A8.28 8.28 0 1 1 12.696 24A8.28 8.28 0 1 1 24 12.696A8.28 8.28 0 1 1 35.304 24A8.28 8.28 0 1 1 24 35.304");
}

</style>
