<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v6p8jvb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pliability" /></template>
<style>
.v6p8jvb-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.6 24H24v3.605c0 5.022-4.077 9.099-9.1 9.099H4.5v-3.605C4.5 28.077 8.577 24 13.6 24M24 11.296h13.148a6.355 6.355 0 0 1 6.352 6.352A6.355 6.355 0 0 1 37.148 24H24z");
}

</style>
