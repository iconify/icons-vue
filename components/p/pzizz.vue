<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ohb54_bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pzizz" /></template>
<style>
.ohb54_bha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 32.535c12.602.088 19.573-8.015 19.5-17.07h-7.686C34.785 17.934 33.092 23.86 24 24c-9.092-.14-10.785-6.065-11.814-8.536H4.501C4.427 24.52 11.399 32.623 24 32.535");
}

</style>
