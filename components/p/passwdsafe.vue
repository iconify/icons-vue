<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ohqzv-bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:passwdsafe" /></template>
<style>
.ohqzv-bfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.167 30.167H5.5L17.833 42.5H5.5v-37l12.333 12.333H5.5L30.167 42.5m0 0H42.5L30.167 30.167");
}

</style>
